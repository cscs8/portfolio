---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Scala Memo June 14 2020"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-06-14T17:34:55+09:00
lastmod: 2020-06-14T17:34:55+09:00
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
---

### メモ

- メモリフットプリント
  - -> メモリ使用量
- GoとJavaの実行環境比較
  - JavaのJVMでいう仮想マシン上じゃなくてOSとCPUアーキテクチャに合わせて実行ファイル作るから、直接実行できる?
- 定数は大文字のキャメルケース
  - e.g. DocumentNumber
- defはメソッド
- メソッド名 + 空白 + _ -> 関数オブジェクト
  - e.g. isAlphametric _
- 文(statement)は評価しても値返さない
  - e.g. Javaのif/else文 if(isSuccess) { ... } -> 何もかえってこない
- 式(expression)は評価すると値が帰ってくる
  - e.g. KotlinやScalaのif/else(?) val value = if(isSuccess) { ... }
- match -> switchみたいなやつ
  - defaultじゃなくて case other
  - :じゃなくて =>
    - e.g. case 1 => println("Gold!")  ... case other => println("Other!")
- trait : 実装できるinterface
  - implementsじゃなくてwith
  - インターフェースを実装じゃなくてトレイトをミックスイン
  - abstract classだと継承1つしかできないけど、traitは複数継承(ミックスイン)できる
  - トレイトの定義はスーパートレイトもある

- コードスタイル見る
  - https://docs.scala-lang.org/style/indentation.html

