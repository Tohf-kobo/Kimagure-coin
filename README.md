# 気まぐれコイン — GitHub Pages 公開版

CPUと対戦するブラウザゲームです。サーバーやデータベースは不要です。

## GitHub Pages で公開する

1. GitHubで公開リポジトリ `kimagure-coin` を作成します。
2. このフォルダの `index.html`、`.nojekyll`、`README.md` をリポジトリのルートへアップロードします。
3. リポジトリの **Settings → Pages** を開き、**Build and deployment → Source** を **Deploy from a branch** に設定します。
4. Branch は `main`、Folder は `/(root)` に設定し、Save を押します。
5. 数分後に `https://<GitHubユーザー名>.github.io/kimagure-coin/` でアクセスします。

## 動作確認

- PCブラウザでタイトル画面→ルール表示→ゲーム開始→先手決定コイントス→カード配置を確認してください。
- 1ゲームを通して、コイン残数、チップ使用、黒白効果、オタカラ配布、終了画面を確認してください。

## 注意

- X共有機能は、HTTP/HTTPSで公開されたページのURLを投稿文に添付します。
- GitHub Pagesで公開すると、リポジトリ内のゲームソースコードも閲覧可能になります。
- このパッケージは公開用の初期版です。全対戦パターンの動作保証はありません。
