# ngmy.github.io
永宮悠大のポートフォリオサイトです。

## 公開先
[GitHub Pages](https://ngmy.github.io/)

## 公開手順
1. リポジトリをクローンする。
   ```console
   git clone https://github.com/ngmy/ngmy.github.io.git
   ```
2. 依存関係をインストールする。
   ```console
   npm install
   ```
3. Hugoサーバーを起動する。
   ```console
   docker compose up -d
   ```
4. コンテンツを作成・編集・削除する。
5. [http://localhost:1313/](http://localhost:1313/)で作成・編集・削除結果を確認する。
6. masterブランチにプッシュする。[ビルド](https://github.com/ngmy/ngmy.github.io/actions/workflows/gh-pages.yml)が無事完了したらGitHub Pagesに公開される。
   ```console
   git push origin master
   ```
