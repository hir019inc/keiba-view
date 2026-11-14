# Keiba View

競馬予想リポジトリ（private）の成果物をスマホで閲覧するビューア。

- ここにあるのは器（HTML/JS）だけ。**データ・トークンは一切含まない**。
- データは閲覧者の端末がGitHub APIから読み取り専用トークンで直接取得する
  （fine-grained PAT・対象リポ限定・Contents: Read-only）。
- 正本は private リポの `07_viewer/index.html`。更新はそちらを直してからここへ写す。
