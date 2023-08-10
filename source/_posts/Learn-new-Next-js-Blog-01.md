---
title: 學習 | 用 Next,js 建新的 Blog | 01
date: 2023-08-10 17:16:48
categories: ToLearn
tags:
---

自學、或者說準備找新工作的事情又停擺了許久。總是該從什麼地方開始做點東西。打算用 Next.js ，參考[ EasonChang 「從零開始打造炫砲個人部落格」的這個系列文章](https://ithelp.ithome.com.tw/articles/10291960)來做一個以前端乃至廣義的資訊相關的學習過程筆記用的 blog 。

稍微記錄一些環境的版本：

- node v18.15.0
- npm 9.6.4
- nvm 0.39.3

## 建立 Next.js 專案

教學使用 pnpm 這個套件管理器（我也跟著用看看吧），安裝方式：

```shell
npm install -g pnpm
```

建立 Next.js 專案：

```shell
pnpm create next-app --typescript
```

建立專案中的選項備忘：

```
專案名稱很老套地用： "my-nextjs-blog"
ESLint, Yes
Tailwind CSS, Yes
`src/` directory, No
App Router, Yes
customize the default import alias, No
```

圖書館網路有點糟糕，第一次建專案的時候用圖書館的網路中間裝東西好像有東西沒裝好，用手機的熱點分享相對穩定的網路才把專案裝起來。

## 佈署到 Vercel

1. 修改 README.md ，把預設產生的 README.md 改成 README-default-backup.md 。
2. 將專案推送到 Github
3. 將專案佈署到[ Vercel ](https://vercel.com/)

這裡基本上要做的只是把 Github 的專案 repo 導入到 Vercel ，一些權限設定之類。我有做一個小改變，專案的名稱在 Vercel 是叫做「 jchans-blog 」。因為覺得這樣還沒買網域名稱之前的網址看起來好看一點。

https://jchans-blog.vercel.app/

其實今天進度很少，但是自己的狀況沒有很好，今天的想法只是不管懂不懂，先動手弄點東西再說。只是把 Next.js 預設的頁面換掉，隨便寫幾個字，跟 Hello World 的概念差不多。但重要的是不要停在這裡。明天繼續吧。
