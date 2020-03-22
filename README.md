# blender-branches-tw
Traditional Chinese translation for blender [branch], manually synced with upstream svn repo.

## Blender 翻譯概覽
Blender 的開發仰賴志工與基金會員工發展，翻譯這部分也是。
在 2.4、2.5 版本時代，Blender 尚無法翻譯，直到 Google Summer of Code 的 Internationalization 專案完成基礎工作後，才開始支援多國語言介面。

## 正體中文翻譯歷史
官方的開發儲存庫僅限有經驗的開發者與志工可以存取，L10n-tw 組織貢獻者 zerng07 以多年自由軟體翻譯經驗取得提交者身份，並在 2.6 時代起開始參與翻譯工作，依據簡體中文翻譯為基礎，從頭到尾修訂整份翻譯檔，於2013年12月3日完成 97% 翻譯，之後僅在業餘時間維護。

過去相關歷史紀錄，請參見 [Blender 翻譯近況](http://breezymove.blogspot.com/2012/08/bledner.html) [2013/08/14]，以及 [Blender 翻譯故事](http://breezymove.blogspot.com/2013/12/blender_8.html) [2013/12/08]。

## 本專案貢獻流程
* 先 fork 一份到你自己的 repo
* 編修你 repo 下的 po 檔
* 每週一晚上從 https://svn.blender.org/svnroot/bf-translations/branches/blender.pot 手動下載 pot 檔，並用 pot 檔更新 po 檔
* 完成你想要編修的部份後，git add 和 git commit 到你 repo
* 提請本 repo 的 pull requst，並簡介說明你編修了什麼項目，例如「修正統一所有 metaball 的翻譯為變幻球、增補了雕塑的相關翻譯」
* 若合併上沒有衝突就會整合，整合後本專案會再校對修訂
* 本專案維護者提交檔案回官方 svn repo

## 專案目標
Blender 2.8 版介面大改，2020年1月14日時翻譯程度已降至 61% (15289/24755)，歡迎大家協助參與，一同討論並訂立出術語翻譯，翻譯成果將由 l10n-tw 提交回上游，讓整個社群一起受益。
