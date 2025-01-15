# MySQL Workbench 繁中漢化

### 專案說明

[MySQL Workbench](https://dev.mysql.com/downloads/workbench/) 是提供給資管庫管理員及開發者的官方圖形化使用者介面。在 Windows 下的使用者可於 Oracle 官方網站直接下載含 MySQL Server、Workbrench 及其他套件的 [MySQL Installer for Windows](https://dev.mysql.com/downloads/installer/)一次裝好常用的所有 MySQL 工具。Linux 和 Mac OS X 上的使用者也可以於單獨安裝 MySQL Workbench 及其他套件。

雖然 MySQL 還是世界上最多人使用的資料庫軟體之一，不論於 [Stack Overflow 問卷統計的結果](https://survey.stackoverflow.co/2023/)、[DB-Engines 的排名](https://db-engines.com/en/ranking)還是[Red9 的排名](https://red9.com/database-popularity-ranking/)，MySQL 皆排名第二。但 MySQL 官方早於 [2016 年就已於官方論壇宣布在可預見的未來不打算進行國際化](https://forums.mysql.com/read.php?152,652539,652543)。但很多資料庫的初學者不見得熟悉英文，全英文的界面及使用環境可能會對初學者造成障礙。對台灣的使用者而言，GitHub 上也只有[簡體中文化的功能表](https://github.com/web-zyh/mysql-workbench-zh-cn)，為提供繁體中文初學者友善的學習環境，本專案會將簡中漢化的結果進一步繁中漢化，並進一步漢化簡中功能表中沒有漢化到的部份。

## 文件說明

* main_menu_en.xml *英文*(*原版自带*)
* main_menu.xml *中文版*

PS：為什麼還有英文版呢？
* 主要與現有`mysql workbranch` 的`main_menu.xml` 進行對比，新增刪除等，畢竟並不是所有人都是用的`8.x` 版本，日後新增選單也可以很快找到不同來進行修改。

### 安裝說明
> MySQL Workbench 版本: 8.0.x
* 1.從github上下載檔案，點一下綠色的code案紐並點下下載ZIP
* ![image](https://github.com/user-attachments/assets/19be5265-1ad1-4355-80b2-8b6729335924)
* 2.解壓縮之後主要使用data的資料夾
* 3.右鍵點選workbrench之後再點選`到檔案位置`
* ![image](https://github.com/user-attachments/assets/efecd84d-9d8f-44c6-808f-fbef57f6a6da)
* 4.複製將安裝目錄中的`data`檔案替換成現在的`data`檔案。
* 執行中時會問說是否以管理員權限執行，點是。登入後看到左上角有中文就成功了
* ![image](https://github.com/user-attachments/assets/774c8c6f-3d85-43b8-acaa-c0524060b3f4)
* 5.如果有不成功或無法打開mysql的情況，可以檢查一下檔案名稱是否與原版一樣，如果不同的話會打不開
>PS：有加en的是英文原檔

## 翻譯幫忙

如果想要幫忙翻譯的話，可以把MySQL的檔案中有 `<caption>` 這一欄文字從英文翻成中文就可以了
當然如果有任何翻譯上的不通順也可以在底下留言，會盡快修正
