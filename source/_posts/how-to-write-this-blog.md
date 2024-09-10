---
title: 這個 blog 的用法
date: 2023-02-15 03:21:42
categories: blog
tags:
  - 資料整理作法
  - 寫作筆記
  - 部落格管理
---

最近打算開始寫點筆記，但部落格形式依照時間排序，久了會很不好找資料，所以會用一個頁面來手動整理相關部落格文章。讓自己以後找資料也方便。

<!-- more -->

- 文件建立日期 2023-02-15
- 最後修改日期 2023-02-21

## 文章內文格式

### 繼續閱讀

沒意外的話會放在第一段後，但視情況使用。

```
<!-- more -->
```

### 文章子標題

hexo 的這個佈景主題 next ，h1 與文章本身的標題一樣大，部落格單篇文章內文的小標可能用 h2 開始比較恰當。

```
# h1

## h2 ，單篇文章內的小標從 h2 開始往下用
```

### 項目清單

```
項目清單舉例：

- 這是第一個項目
- 這是第二個項目，上項單純是項目，就不加句號。如果像這個項目是一個句子，則在項目清單中的結尾句號結束句子，英文亦同。
```

項目清單舉例：

- 這是第一個項目
- 這是第二個項目，上項單純是項目，就不加句號。如果像這個項目是一個句子，則在項目清單中的結尾句號結束句子，英文亦同。

## 頁面

目前有兩個頁面

- Notes
- Records
- TRPG

Notes 打算整理 2023 年開始（寫這篇的時候是 2023-02-15 ）的網頁前端學習與求職的筆記， Record 是一些我想特別做點紀錄的大事記（按照時序）。 TRPG 的頁面，就主要是 TRPG 的筆記。

## 寫作的週期與時間

- 如果不是特定主題，只是註記日期的雜記，「 memo 日期 」這種標題的記事
  - 標題寫法，以 2023-02-14 為例：「 memo 2023-02-14 」
  - categories: memo

## 其他

先簡單設定一些想遵循的規則或作法，之後再慢慢修訂。

### 插入圖片

檔案統一放在 ./source/image 資料夾裡

![插入圖片例子](/images/memo-images/2023-02-23.png)

```
![插入圖片例子](/images/memo-images/2023-02-23.png)
```

好像檔案太大會沒辦法顯示，我也覺得不用放太大的圖檔，如果是橫向的照片，目前可以考慮縮到 800x600 。

### 註腳

- [hexo-renderer-markdown-it](https://github.com/hexojs/hexo-renderer-markdown-it)
  - Use this for footnote. [^footnote-example]

```
- [hexo-renderer-markdown-it](https://github.com/hexojs/hexo-renderer-markdown-it)
  - Use this for footnote. [^footnote-example]


[^footnote-example]: This is an example footnote.
```

[^footnote-example]: This is an example footnote.
