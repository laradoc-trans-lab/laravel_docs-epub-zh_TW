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
* Hyread Gaze Pro XC
  * 檔案放入 `書櫃`的`匯入`區，打開來看沒問題
  * greyscael 版的檔案可看，程式碼區塊高亮效果的背景是淡灰色似乎沒辦法顯示，但區塊內文字完全沒問題很清晰。
  * color 版的檔案不適合，程式碼區塊高亮效果文字幾乎無法辨認。
  * 放到`個人藏書`打開看，不建議，尤其是 LIST 部分每行間距太大了，看起來是與 `書櫃` 使用的瀏覽引擎不同。
* Calibre 內建的閱讀軟體沒問題，LCD 螢幕不論是 greyscale 或 color 兩種版本都有呈現該有的程式碼高亮效果。

## 相關連結

* [翻譯好的文件](https://github.com/laradoc-trans-lab/laravel_docs-zh_TW)
* [轉換方式與工具](https://github.com/laradoc-trans-lab/laradoc-sphinx-epub)

## 免責聲明

1. 翻譯內容是採用 https://github.com/laradoc-trans-lab/laradoc-trans 先行翻譯的，也就是請 AI 進行翻譯，後續有機會會校稿，該專案近日內會 Public , 目前在整理 code 中。
2. 若對內容有疑慮，可至 https://github.com/laradoc-trans-lab/laravel_docs-zh_TW 提 Issue，此為翻譯後的 Markdown
3. EPUB 版本也是透過某某工具來製作的，近日也會整理後 PUBLIC 出來。
4. 如果有翻譯錯誤，一切以 Laravel 官方為主。
5. 著作權屬於 Laravel 官方，本人只是透過工具翻譯並分享出來給大家用。
