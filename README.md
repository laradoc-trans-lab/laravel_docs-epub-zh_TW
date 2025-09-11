# Laravel 說明文件 EPUB 繁體版

因網路上找不到繁體版 EPUB , 所以自己做了，請關注本專案，因為我會不斷的修正轉換中遇到的問題，所以檔案隨時會更新

## 檔名解說

以 Laravel-12-Documentationc-zh_TW-color.epub 為例子

- 這份文件是 Laravel 12
- zh_TW 代表繁體中文
- color 代表程式碼的部分是彩色的 , 如果是 greyscale 則程式碼的部分是黑白灰階的

如果你使用的是 `E-INK` 電子書閱讀器想閱讀，我會建議選擇 greyscale，這樣就算是用彩色電子紙 kaleido 3，程式碼的部分仍會是 300PPI。

## 閱讀軟體/閱讀器

目前我只有測試以下方式，歡迎回報問題
* Hyread Gaze Pro XC (彩色 150PPI , 黑白 300PPI)
  * color 版的檔案不適合，因為彩色的文字部分會以 150PPI呈現，彩色文字會比較不清晰。
  * 放到`個人藏書`打開看效果不錯，但是要調整設定
    * 進階/灰階效果打開
    * 文字排版選第5個，ICON右下角有個小圈圈那個，不然LIST會很怪
  * 程式碼過長會跑出版面，目前沒有很好解法，原因如下 :
    * E-INK 這類閱讀器不會為 `<pre>` 標籤自動加上 scroll-bar ，但電腦可以。
    * 如果強制斷行會讓人誤會，所以目前都沒有強制斷行。
    * **建議遇到超長程式碼時，將閱讀器方向改為橫向應該可以看到完整程式碼，甚至縮小字體也能讓呈現的字數更多。**
* Calibre 內建的閱讀軟體沒問題，LCD 螢幕不論是 greyscale 或 color 兩種版本都有呈現該有的程式碼高亮效果。

## 相關連結

EPUB 檔產生主要是透過以下三個專案達成的

* [翻譯工具](https://github.com/laradoc-trans-lab/laradoc-trans) : 透過 AI 技術進行大量翻譯的工具
* [翻譯好的繁體文件](https://github.com/laradoc-trans-lab/laravel_docs-zh_TW) : 透過翻譯工具翻譯好的 MARKDOWN 都放於此
* [轉換方式與工具](https://github.com/laradoc-trans-lab/laradoc-sphinx-epub) : 將 MARKDOWN 轉換為 EPUB 的工具

## 免責聲明

1. 若對內容有疑慮，可至[翻譯好的文件](https://github.com/laradoc-trans-lab/laravel_docs-zh_TW) 提 Issue 校正，此為翻譯後的 Markdown 檔案，結構與官方文件一致。
2. 如果有翻譯錯誤，一切以 Laravel 官方為主。
3. **著作權屬於 Laravel 官方，本專案僅提供翻譯好的檔案並分享出來給大家用。**
