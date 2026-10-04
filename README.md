# Orrery Compatibility Status

Windows向けビジュアルノベルをMac上のWine互換環境で検証した、タイトル別の動作状況です。

この一覧は、非公開で開発している **KASANE（カサネ）**（Windows向けノベルゲームをMacで遊ぶためのランチャー。[紹介ページ](https://tsukasa-art.com/projects/orrery/kasane/)。データ内の `Melammu` は開発名）と **swingby-wine**、タイトル別profile、prefix、runtime overlayを組み合わせた検証結果です。公開リポジトリ [melammu-vn](https://github.com/tsukasa-art/melammu-vn) のsource-only参照実装だけで同じ結果が得られることを意味しません。

タイトル名には成人向け作品が含まれます。ゲームデータ、画像、認証情報、DRM回避手段は掲載しません。正規に入手したソフトウェアの互換性調査記録です。

## 読み方

- 一行は「タイトル × 版・配布形態 × 検証経路」です。
- engine名だけでは互換性を判断できません。同じengineでも版、arch、描画backend、動画・認証経路が異なります。
- 「起動・描画確認済み」は全機能の保証ではありません。軸別の結果は [data/compatibility.json](data/compatibility.json) を参照してください。
- 未確認は失敗を意味しません。現在の正典に、その軸を確認した記録が無いという意味です。
- 確認日は各レコードの最後の根拠日です。データセット更新日: **2026-08-23**。

## タイトル別一覧

| タイトル | 版 | engine / protection | 概要 | 最終確認 |
|---|---|---|---|---|
| アマツツミ体験版v2 | 体験版v2 | CMVS | 起動・描画確認済み | 2026-06-29 |
| 青春フラジャイル体験版v2 | 体験版v2 | CMVS | 起動・描画確認済み | 2026-06-29 |
| 妹のセイイキ | 製品版 | KiriKiri | 起動・描画確認済み | 2026-06-14 |
| 放課後シンデレラ | 製品版 | BGI / Ethornell | 起動・描画確認済み | 2026-07-01 |
| 放課後シンデレラ 体験版 | 体験版 | BGI / Ethornell | 起動・描画確認済み | 2026-07-01 |
| 放課後シンデレラ ミニファンディスク | ミニファンディスク | BGI / Ethornell | 起動・描画確認済み | 2026-06-14 |
| 放課後シンデレラ2 | 製品版 | BGI / Ethornell | 起動・描画確認済み | 2026-06-14 |
| ナツユメナギサ体験版 | 体験版 | RealLive | 起動・描画確認済み | 2026-07-01 |
| HOMESTAY a la mode 体験版 | 体験版 | Yaneurao GameSDK | 起動・描画確認済み | 2026-06-14 |
| Making Lovers | 製品版 | BGI / Ethornell | 起動・描画確認済み | 2026-06-15 |
| ゆびさきコネクション | 製品版 | BGI / Ethornell | 起動・描画確認済み | 2026-06-14 |
| 抜きゲーみたいな島に住んでる貧乳はどうすりゃいいですか？Remaster 体験版 | 体験版 | Artemis / iarsys | 起動・描画確認済み | 2026-06-23 |
| ギャルズフィクション体験版 | 体験版 | Artemis / iarsys | 起動・描画確認済み | 2026-07-02 |
| ライムライト・レモネードジャム 体験版 | 体験版 | KiriKiri2 / TVP | 起動・描画確認済み | 2026-07-19 |
| スタディ§ステディ体験版 | 体験版 | marmalade / Emote | 一部成立 | 2026-06-29 |
| フルキスS | 製品版 | GIGA / PAC | 起動・描画確認済み | 2026-07-02 |
| ハミダシクリエイティブ | 製品版 | Artemis | 起動・描画確認済み | 2026-07-23 |
| アイベヤ2 | 製品版 | CatSystem2 | 起動・描画確認済み | 2026-08-23 |
| 家庭教師のおねえさん | 製品版 | Yaneurao GameSDK | 起動・描画確認済み | 2026-06-14 |
| バブルdeハウスde〇〇〇 | 製品版 | Yaneurao GameSDK | 起動・描画確認済み | 2026-06-15 |
| 夏汁100% | 製品版 | Yaneurao GameSDK / SoftDenchi | 起動・描画確認済み | 2026-07-04 |
| なまイキ | 製品版 | Yaneurao GameSDK / SoftDenchi | 起動・描画確認済み | 2026-07-04 |
| SugarStyle | 製品版 | BGI / Ethornell / SoftDenchi | 起動・描画確認済み | 2026-07-05 |
| えろまんが Hもマンガもステップアップ♪ HDリマスター | HDリマスター製品版 | YU-RIS / SoftDenchi | 起動・描画確認済み | 2026-07-17 |
| お姉さん×SHUFFLE！ | 製品版 | Yaneurao GameSDK / SoftDenchi | 起動・描画確認済み | 2026-07-17 |
| SugarStyle 恋人以上夫婦未満アフターストーリー | 特典アフターストーリー | BGI / Ethornell / SoftDenchi | 起動・描画確認済み | 2026-07-17 |
| あまたらすリドルスター体験版 | 体験版 | KiriKiri / XP3 | 未成立の軸あり | 2026-07-02 |
| D.C.III R X-rated | 製品版 | CIRCUS ADV / CIRCUS online activation | 起動・描画確認済み | 2026-07-06 |
| 水平線まで何マイル？ | DMM版 | KiriKiri2 / DMM GAME PLAYER | 起動・描画確認済み | 2026-07-15 |
| 失われた未来を求めて | DMM版 | KiriKiri family / DMM GAME PLAYER | 起動・描画確認済み | 2026-07-15 |

## 状態値

| 値 | 意味 |
|---|---|
| `verified` | 確認済み |
| `partial` | 一部成立 |
| `blocked` | 未成立 |
| `unverified` | 未確認 |
| `not-applicable` | 対象外 |

## 公開データ

- [軸別データ](data/compatibility.json)
- [schemaと更新規則](docs/schema.md)
- 技術的な原因・修正の記録は[Orrery Case Notes](https://tsukasa-art.com/projects/orrery/)および[Zenn](https://zenn.dev/tsukasa_art)に分離しています。

このREADMEと公開JSONは、private canonのpublic-safe projectionから生成します。READMEだけを直接更新しません。
