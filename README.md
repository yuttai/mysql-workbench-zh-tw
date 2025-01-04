# mysql workbench 功能表繁中漢化

### 說明

> MySQL workbench 版本: 8.0.x
>
> mysql workbench 是一個面向資料庫架構師、開發人員和dba的統一視覺化工具。 MySQL工作台為伺服器設定、使用者管理、備份等提供了資料建模、SQL開發和全面的管理工具。 MySQL Workbench在Windows、Linux和Mac OS X上可用。
>
>MySQL工作台讓DBA、開發人員或資料架構師能夠視覺化地設計、建模、產生和管理資料庫。它包括資料建模師創建複雜的ER模型、正向和逆向工程所需的一切，還提供了執行困難的變更管理和文件任務（通常需要大量時間和精力）所需的關鍵功能。



## 文件說明

* main_menu_en.xml *英文*(*原版自带*)
* main_menu.xml *中文版*

>PS：為什麼還有英文版呢？
>
> * 主要與現有`mysql workbranch` 的`main_menu.xml` 進行對比，新增刪除等，畢竟並不是所有人都是用的`8.x` 版本，日後新增選單也可以很快找到不同來進行修改。

### 使用說明
* 1.從github上下載檔案，點一下綠色的code案紐並點下下載ZIP
* ![image](https://github.com/user-attachments/assets/19be5265-1ad1-4355-80b2-8b6729335924)
* 2.建立一個文件夾，裡面分別有中文及英文的文件夾，這樣到時候就不會搞混哪個是英文版哪個是中文版的文件，然後解壓縮
* ![image](https://github.com/user-attachments/assets/3cbd6a77-7975-4ddf-9813-55bdf74f3ac9)
* ![image](https://github.com/user-attachments/assets/9b275131-f8c8-48f8-98f6-d8cd34bd7e6e)
* 3.右鍵點選workbrench之後再點選`到檔案位置`
* ![image](https://github.com/user-attachments/assets/efecd84d-9d8f-44c6-808f-fbef57f6a6da)
* 4.複製 `main_menu.xml` 取代 `mysql workbench` 安裝目錄的 `data` 中的`main_menu.xml` 檔案。
* ![image](https://github.com/user-attachments/assets/c6832764-4be1-47ca-aec3-57a390d93527)
* 執行中時會問說是否以管理員權限執行，點是。登入後看到左上角有中文就成功了
* ![image](https://github.com/user-attachments/assets/774c8c6f-3d85-43b8-acaa-c0524060b3f4)
* 5.如果有不成功或無法打開mysql的情況，可以檢查一下檔案名稱是否與原版一樣，如果不同的話會打不開
>PS：有加en的是英文原檔

