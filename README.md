# webextension-typescript-template
自分用オレオレTypeScript製ブラウザ拡張機能用のテンプレート

## 使う上でまず変更する点
- [ ] プロジェクト名（package.json, package-lock.json, manifest.json）
- [ ] プロジェクト説明文（package.json, manifest.json）
- [ ] package.json内の各リンク
- [ ] LICENSE
- [ ] git initからやり直した方がよさそう

## 使い方等々

### 置いてあるnpm script
- test
  - 現状何もなし。必要ならjest等導入して変える
- build
  - そのままproductionモードでビルド
- build:dev
  - そのままdevelopモードでビルド
- watch
  - ファイル変更したらdevelopモードでビルド
- commit
  - 対話的にcommitlintに沿ったコミットをする
- lint
  - eslint。内容的にはstandard styleそのまま
- zip
  - ビルドしたファイルをzip化する。↑のbuildコマンドを実行後にする
