# pub_proto_games

`ryo-yam-64/proto_games` で生成・検証されたカジュアルゲームのプロトタイプを公開するためのリポジトリ。

このリポジトリは**公開成果物専用**です。
ゲームの生成ルール、AI向け指示、制作途中のファイルはここでは管理しません。

## 構成

- `index.html` — プロトタイプ一覧
- `games/` — 公開済みゲーム
- `.github/workflows/pages.yml` — GitHub Pages deploy

`main` が更新されると GitHub Pages へ自動デプロイされます。
公開ファイルは制作リポジトリ側の workflow から同期されるため、原則として `index.html` / `games/` を手動編集しません。
