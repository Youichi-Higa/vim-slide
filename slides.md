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

- 指定行に移動 \{行番号\} + <kbd>G</kbd>
- 直前の場所に戻る <kbd>Ctrl</kbd> + <kbd>o</kbd>
