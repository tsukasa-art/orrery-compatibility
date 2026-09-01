# Schema and update rules

`data/compatibility.json` is generated. Do not edit it or the title table in `README.md` directly.

Each record represents one tested combination of title, edition/distribution, and execution route. `engine` and `protectionLayer` are separate because a protection wrapper such as iarsys is not the rendering engine.

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
