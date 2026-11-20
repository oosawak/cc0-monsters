# CC0モンスター・動物 3Dモデル集

CC0の3Dモンスター・動物モデルを集めたカタログ＆保管庫です。全件、出典ページでライセンスが **CC0** であることを確認してから収録しています（複製・改変・再配布・商用利用可、クレジット表記不要）。

公開ページ: https://oosawak.github.io/cc0-monsters/

## 収録（全115件）

- **OpenGameArt「CC0 - 3D Animals / Creatures」71件** — 全71件ともライセンス表示はCC0単独。実ファイル76点中74点を収録（残り2点はGitHubのファイル上限のため元サイトへのリンク: 3D Gum Bot 110MB、Dromaeosaur 62MB）。
- **Grab3D creatures 35件** — 全件CC0。リグ付きは4件（Werewolf / Yeti / Stone Golem / Stylized Zombie、各walk・runアニメ入り。GLBの中身を解析してスキンとアニメの実在を検証済み）。全件にプレビュー用GLB（3D表示用）を収録し、高精細版・Light版は元サイトへのリンクも併記。
- **Quaternius 9パック** — CC0のアニメ付きパック（Animated Monster、Cute Monsters、Easy Enemy 等）。入手がGoogle Driveフォルダ形式のためリンク収録。

## 検証メモ

- Grab3Dのファイルは通常のダウンロードでは途中で切れることがあったため、全ファイルについてサーバ申告サイズ（Content-Length）と実サイズの一致を確認し、不一致はレジューム再取得で解消済み。GLBはヘッダ申告長と実長の一致も全件確認。
- OpenGameArt分は全76ファイルで申告サイズと実サイズが一致。

## 使い方

ゲーム制作時は、まず公開ページで検索し（「リグ付きのみ」「アニメ付きのみ」の絞り込みあり）、Grab3D分はその場で3Dプレビューできます。使った素材はゲーム側のREADME等に「素材: ○○（CC0、出典: OpenGameArt/Grab3D/Quaternius）」と記録しておくと後で追えます。

`catalog.json` が全件の索引（出典・ライセンス・リグ/アニメ有無・ファイル一覧）です。AIエージェントはこのJSONを入口にしてください。
