# README

2023年度新卒の成果物置き場

## Firebaseプレビュー環境の情報

- URL: https://new-grads-2023.web.app

## デプロイについて

- `master`ブランチが更新されると、`dist`ディレクトリ配下のソースがプレビュー環境に自動デプロイされるようになっています
  - `dist`ディレクトリがルートとなるため、ディレクトリ構造に注意してください


## こんな時はご一報ください

以下のような場合は、コード編集以外の作業が発生します。
そんな時はGLにご一報ください。

- デプロイ対象フォルダの名称を`dist`以外にしたい場合
- `master`以外の別ブランチをビルドして欲しい
- `master`以外の別ブランチが更新された時にビルドするようにしてほしい
- pipeline上で実行されるビルドコマンドを`yarn build`以外にしたい
