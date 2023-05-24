# 六角學院「使用 HTML、CSS 開發一個網站」最終試煉
作業網址：[【最終試煉】使用 HTML、CSS 開發一個網站](https://rpg.hexschool.com/user/task/47252/show)

## Table of contents
- [Overview](#overview)
  - [Link](#link)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#whtat-i-learned)

## Overview
- 第一次總共花費 20 小時，1 小時完成大架構，17 小時進行 HTML、CSS切版並並，2 小時調整 GitHub 部署問題

### Link
- Live Site URL: [Hex School Home Page](https://chunjull.github.io/hexschool-html-final/)

## My process

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
- 為了避免主機檔案結構與本地專案資料夾結構不同，造成檔案讀取的問題，將絕對路徑調整成相對路徑
```
background-image: url(/images/logo.png);

調整成

background-image: url(./images/logo.png); 

./ 表示當前目錄
以當前工作目錄為基礎來定位檔案。
```
