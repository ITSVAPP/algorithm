# 開発者用

GitHubとGitBookを利用して公開している。
GitHubにpushすれば自動でGitBookにも公開される。

## 前提条件
- gitをインストールしてあること

## gitからのクローン
```bash
git clone https://github.com/ITSVAPP/algorithm.git
```

## 推奨拡張機能の追加
`@recommended`で検索し、該当拡張機能をインストールする

### 作成のチップス

- 画像のサイズを指定するときは、width="500"のように指定する
- `<div style="page-break-before:always"></div>`を入れると、印刷時に改ページができる

### 拡張機能の使い方

- 拡張機能「Paste Image」を使うと、画像の貼り付けが楽になる
  - ショートカットキー「Ctrl+Alt+V」で貼り付け可
- 拡張機能「Markdown All in One」を使うと、Markdown の記法を便利に使える
  - [使い方](https://zenn.dev/ctrlkeykoyubi/articles/vscode-markdown-all-in-one)を参照すること


### `gitbook-cli`のインストール

### node.jsのバージョン指定
`nvm use 12.22.12`

#### インストール
`npm install --global gitbook-cli`
