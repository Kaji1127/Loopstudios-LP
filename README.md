# Frontend Mentor - Loopstudios landing page solution

This is a solution to the [Loopstudios landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/loopstudios-landing-page-N88J5Onjw). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## 目次

-   [概要](#overview)
    -   [チャレンジ](#the-challenge)
    -   [スクリーンショット](#screenshot)
    -   [リンク](#links)
-   [プロセス](#my-process)
    -   [使用したスキル](#built-with)
    -   [学んだこと](#what-i-learned)
    -   [役に立ったリソース](#useful-resources)

## 概要

### チャレンジ

ユーザーができること:

-   ユーザーの画面サイズによって最適なレイアウトが表示される。
-   ページ上の全てのインタラクティブな要素にホバー状態を見ることができる。

### スクリーンショット

![](./screenshot.jpg)

### リンク

-   Live Site URL: [リンク](https://kaji1127.github.io/Loopstudios-LP/)

## プロセス

### 使用したスキル

-   Sass
-   Flexbox
-   CSS Grid
-   JavaScript
-   モバイルファースト

### 学んだこと

・CSS のカスタムプロパティの使い方について学んだ。
・Sass において@use, @forward の使い方について学んだ。

```css
:root {
	--white: hsl(0, 0%, 100%);
	--black: hsl(0, 0%, 0%);
	--gray: hsl(0, 0%, 55%);
	--darkgray: hsl(0, 0%, 41%);
	--light-white: hsla(0, 0%, 100%, 0.75);
}
```

```css
@use 'base';
@use 'components';
@use 'layout';
```

### 役に立ったリソース

-   [リソース 1](https://haniwaman.com/dart-sass/) - 現在推奨されている@use, @forward の使い方について知ることができた。
-   [リソース 2](https://qiita.com/obr-note/items/32ed30ce149e9f9f6619) - Sass でのブレイクポイントの記述方法について知ることができた。
