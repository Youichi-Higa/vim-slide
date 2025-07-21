---
theme: slidev-theme-ncdc
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Vimmerになろう
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
# class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
aspectRatio: 4/3
---

# Vimmerになろう

### Presentation slides for developers

<!--
最後のコメントブロックはスライドノートとして扱われます。プレゼンターモードでスライドと一緒に表示され、編集も可能です。

詳細: [https://sli.dev/guide/syntax.html#notes](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# Vimって何?

Vimはエディタ

- キーボードで操作
- <br>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: slide-up
level: 2
---

# 基本操作

|                                |                  |
| ------------------------------ | ---------------- |
| \{行番号\} + <kbd>G</kbd>      | 指定行に移動     |
| <kbd>Ctrl</kbd> + <kbd>o</kbd> | 直前の場所に戻る |

- モーション(移動)

  - ←↓↑→ <kbd>h</kbd> <kbd>j</kbd><kbd>k</kbd><kbd>l</kbd>
  - 次の単語の先頭(記号は単語として認識) <kbd>w</kbd>
  - 次のブロックの先頭 <kbd>W</kbd>
  - 現在か前の単語の先頭 <kbd>b</kbd>
  - 前のブロックの先頭 <kbd>B</kbd>
  - 現在か次の単語の末尾<kbd>e</kbd>
  - 次のブロックの末尾<kbd>E</kbd>
  - 前の単語の末尾<kbd>g</kbd> + <kbd>e</kbd>
  - 行の先頭<kbd>0</kbd>
  - 行の末尾`$` <kbd>Shift</kbd> + <kbd>4</kbd>
  - 対応する括弧`%` <kbd>Shift</kbd> + <kbd>5</kbd>
  - 上の空行 <kbd>\{</kbd>
  - 下の空行 <kbd>\}</kbd>
  - 指定行 \{行番号\} + <kbd>G</kbd>
  - 同一行の右側の文字<kbd>f</kbd> + \{文字\}
  - 同一行の左側の文字<kbd>F</kbd> + \{文字\}
  - 同一行の右側の文字の直前<kbd>t</kbd> + \{文字\}
  - 同一行の左側の文字の直前<kbd>T</kbd> + \{文字\}
  - 次の文字 <kbd>;</kbd>
  - 前の文字 <kbd>.</kbd>
  - 1ページ次<kbd>Ctrl</kbd> + <kbd>f</kbd>
  - 1ページ前 <kbd>Ctrl</kbd> + <kbd>b</kbd>
  - 半ページ次 <kbd>Ctrl</kbd> + <kbd>u</kbd>
  - 半ページ前 <kbd>Ctrl</kbd> + <kbd>d</kbd>
  - 画面最上部 <kbd>T</kbd>
  - 画面中央 <kbd>M</kbd>
  - 画面最下部 <kbd>L</kbd>
  - ファイル先頭 <kbd>g</kbd> + <kbd>g</kbd>
  - ファイル末尾 <kbd>G</kbd>

- スクロール

  - 上 <kbd>Ctrl</kbd> + <kbd>y</kbd>
  - 下 <kbd>Ctrl</kbd> + <kbd>e</kbd>
  - カーソル位置が画面中央 <kbd>z</kbd> + <kbd>z</kbd>
  - カーソル位置が画面上部<kbd>z</kbd> + <kbd>t</kbd>
  - カーソル位置が画面下部<kbd>z</kbd> + <kbd>b</kbd>

- マーク
  - カーソル位置をマークする <kbd>m</kbd> + \{a-zA-z\}
  - 指定のマークに移動 ` + \{a-zA-z\}
  - 指定のマークの行頭に移動 ' + \{a-zA-z\}
  - 直前のマークに移動 <kbd>\`</kbd> + <kbd>\`</kbd>
  - 古いマークに移動 <kbd>Ctrl</kbd> + <kbd>o</kbd>
  - 新しいマークに移動 <kbd>Ctrl</kbd> + <kbd>i</kbd>

---
transition: slide-up
level: 2
---

# 基本操作

- ワード検索

  - カーソル位置後方への検索 <kbd>/</kbd>
  - カーソル位置前方への検索 <kbd>?</kbd>
  - 次のワード <kbd>n</kbd>
  - 前のワード<kbd>N</kbd>

- 元に戻す
  - 元に戻す(undo) <kbd>u</kbd>
  - やり直し(redo) <kbd>Ctrl</kbd> + <kbd>r</kbd>
