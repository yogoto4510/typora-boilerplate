# typora-boilerplate

## 概要

Typora テーマ開発環境のオレオレ流テンプレ

## 特徴

- Prettier & Stylelint の環境
- VSCode でのファイル保存時の Fix & Format
- typora-theme-toolkit を格納
- 日本語用の .md テンプレあり
- LESS や Sass は未対応

## 事前準備

1. Git, Node.js, Yarn を用意
2. VSCode を使う場合は EditorConfig と Prettier と Stylelint の拡張機能を導入

## 導入

### GitHub にユーザー登録している場合

ログインして`Use this template`からリポジトリを作成

```bash
$ git clone [あなたのリポジトリ]
$ cd ./[あなたのリポジトリ名]
$ yarn install
```

### ユーザー登録していない場合

```bash
$ git clone https://github.com/yogoto4510/typora-boilerplate.git
$ cd ./typora-boilerplate
$ yarn install
```

## 使い方

1. src/test.css を編集（template.less も参考になる）
2. (html) html-preview 内の目的のファイルを開く
3. (md) Typora テーマフォルダの css を上書きして japanese-preview.md などを Typora で開く
