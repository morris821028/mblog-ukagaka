# Web-Ukagaka Proj #

Web-Ukagaka based on jquery.js, typed.js, and lightweight design.

[Demo Page](http://morris821028.github.io/mblog-ukagaka/)

## About Ukagaka ##

[wiki](http://en.wikipedia.org/wiki/Ukagaka)

> Ukagaka, also known as Nanika, Sakura, Nin'i-tan  or Nise-Haruna, is a catch-all term for Japanese software which shares a single format and function: to provide a pair of mascot characters for the user’s computer desktop. These mascot characters can perform some useful functions such as checking e-mail or adjusting the clock of the computer, but are most popular as an aesthetic add-on, which “says” weird things.

Now, move it from computer desktop to website.

## Usage ##

### HTML ###

```
<div id='ukagaka_panel'></div> 
```

### Javascript ###

```
$(document).ready(function() {
    $('#ukagaka_panel').ukagaka();
}); 
```

### Config ###

```
$.ukagaka.defaults = {
    googleKey: '0ArRwmWo93u-mdG93a2dkSWxIbHEzZjRIeDdxZXdsU1E',
    googleFormkey: '1xADUIiBq1ksH7lxwSch1Nz_p2gSxdJttmv5OJOxJye0',
    googleSheet: "od6",
    googleSheetField: "entry.2030600456",
    talkTime: 60000,

    ukagakaText: "千代",
    loadingText: ' .^100.^100.',
    learnPlaceholder: "default: input for learn.",
    menuMainText: "使用選單功能&#65292; 為什麼要聽你的！",
    menuLearnText: "$ 學習",
    menuLogText: "$ 日誌",
    menuExitText: "$ 結束",
    menuCancelText: "$ 取消",
    menuSubmitText: "$ 確認",
    menuQueryText: "請輸入想要讓千代學的話<br/><br/>",
    logText: "更新日誌<br/><br/>Morris 修正<br/><br/>找尋 AI 系統<br/>找尋 AI 對話<br/>",
    imgs: ['img/uk12.png', 'img/uk13.png', 'img/uk14.png', 'img/uk15.png', 'img/uk16.png', 'img/uk17.png', 'img/uk18.png', 'img/uk20.png', 'img/uk21.png', 'img/uk23.png', 'img/uk24.png', 'img/uk25.png', 'img/uk26.png']
};
```

## How to get google spreadsheet ##

We get Google Spreadsheet key and formkey

* [利用 Google Spreadsheet 作資料庫](http://www.kamira.co.vu/2012/11/jquery-google-spreadsheet.html)


## Feature ##

* Chat AI
