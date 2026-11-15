# Schema and update rules

`data/compatibility.json` is generated. Do not edit it or the title table in `README.md` directly.

Each record represents one tested combination of title, edition/distribution, and execution route. `engine` and `protectionLayer` are separate because a protection wrapper such as iarsys is not the rendering engine.

## Title metadata

- `brand`: the brand name printed on the package or the brand's site (not the company name).
- `titleKana`: reading of the title in hiragana, without edition words such as 体験版 or 製品版. Symbols are omitted.
- `brandKana`: reading of the brand in hiragana.

These are for search and kana ordering (e.g. kasane.tsukasa-art.com). They are optional, but a record that has one has all three. Readings were checked against the publisher, sales pages, ErogameScape, and VNDB (2026-11-13).

## Japanese text and version

- `constraintsJa`, `evidenceSummaryJa`: Japanese translations of `constraints` and `evidenceSummary`, with the same content and the same number of constraints.
- `verifiedWith`: the released KASANE version used for the latest check, such as `1.0.12 (21)`. Omitted when the latest check used a development build or no version was recorded.

## Axes

- `launch`: process reaches the expected game entry point
- `rendering`: normal game rendering is visible
- `audio`: BGM, voice, or other title audio was observed
- `saveLoad`: save and load were observed
- `movie`: an opening, ending, logo, or other movie path was observed
- `thumbnail`: save thumbnail capture was observed
- `installerAuth`: installation or legitimate authentication path was observed

Allowed values are `verified`, `partial`, `blocked`, `unverified`, and `not-applicable`.

`unverified` means the current canon has no evidence for that axis. It must not be promoted from a general statement such as “the title works.”

## Publication boundary

The public export uses an explicit field allowlist. Private library IDs, local paths, binary hashes, raw logs, credentials, and private evidence paths are excluded. A public update must be generated from the private canon, reviewed as a diff, and published independently from Zenn articles.
