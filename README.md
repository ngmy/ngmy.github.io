# ngmy.github.io
ngmy（永宮 悠大）のホームページ。

## 公開先
[GitHub Pages](https://ngmy.github.io/)

## 公開手順
1. リポジトリをクローンする
   ```console
   git clone https://github.com/ngmy/ngmy.github.io.git
   ```
2. Hugoサーバーを起動する
   ```console
   hugo server --ignoreCache
   ```
3. `config.toml`を編集する
4. masterブランチにプッシュする
   ```console
   git push origin master
   ```
5. [ビルド](https://github.com/ngmy/ngmy.github.io/actions/workflows/gh-pages.yml)が無事完了したらGitHub Pagesに公開される
