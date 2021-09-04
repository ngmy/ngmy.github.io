# ngmy.github.io
ngmy（永宮悠大）のホームページです。

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
   hugo server --ignoreCache
   ```
4. コンテンツを作成・編集・削除する
5. masterブランチにプッシュする。[ビルド](https://github.com/ngmy/ngmy.github.io/actions/workflows/gh-pages.yml)が無事完了したらGitHub Pagesに公開される。
   ```console
   git push origin master
   ```
