## 1/10 TUE
* 了解什麼是 [BepInEx](https://github.com/BepInEx/BepInEx/releases)

* 安裝.NET反編譯器 [dnSpy](https://github.com/dnSpy/dnSpy)

* 建立相關環境 ( VS、VS Code )

* 成功實作 Hello World 的 Plugin ( 測試遊戲 : [PlateUp!](https://store.steampowered.com/app/1599600/_/) )

![插件圖片](https://github.com/Dino65535/vacation_daily_log/blob/19b3bf88fd65f3bdbde4298da08274995631ed45/daily_log/0110~0115/HelloWorldPlugin.png "Hello World Plugin")

## 1/11 WED
* 安裝 Git

* 熟悉 Git 與 cmd 常用指令

* 成功實行 push 和 pull 等操作

* 學習 README 書寫語法 [markdown](https://github.com/guodongxiaren/README#readme)

## 1/12 THU
* 創建 & 編寫配置文件 ![文件圖片](https://github.com/Dino65535/vacation_daily_log/blob/5133508bb42b880d9ca70b44caec8f9682d50f2b/daily_log/0110~0115/ConfigEntry.png "Plugin  .cfg")

* 利用 dnSPY 反編譯 .NET 檔案( 用自己寫的 Plugin ) ![反編譯圖片](https://github.com/Dino65535/vacation_daily_log/blob/5133508bb42b880d9ca70b44caec8f9682d50f2b/daily_log/0110~0115/dnSPY01.png "dnSPY decode")

* 嘗試解讀遊戲的 `Assembly-CSharp.dll` 反編譯檔案( 遊戲邏輯 )，但有點複雜看不太懂

* 考慮從別人寫的插件去反編譯解讀 ?

## 1/13 FRI
* 嘗試搞懂遊戲的整體架構，但檔案太多了( 約 200+ 個 `.dll` 檔 )，扣掉 Unity 本身跟一些連線協議還是有 100+ 個，暫時棄這條路

* 發現 workshop 有人寫了一個 [KitchenLib](https://github.com/KitchenMods/KitchenLib/) 用來讓人方便製作 Mod，看起來簡單一些。( [KitchenLib Wiki](https://github.com/KitchenMods/KitchenLib/wiki) )

* 逆向工程真的不簡單 :dizzy_face: :dizzy_face: 窩頭好痛

## 1/14 SAT
* 持續解讀 KitchenLib 的原始碼，搭配一個用 KitchenLib 寫的插件 [Starting Meal Selector](https://github.com/propstg/plateup-starting-meal-selector) 

* 嘗試寫一個測試用的 Menu，但沒成功 :persevere:

## 1/15 SUN
* 成功添加一個測試用的 Menu  
![Menu圖片](https://github.com/Dino65535/vacation_daily_log/blob/ae73a77fa67fc03cfd0a22e5379160e12b992306/daily_log/0110~0115/TestMenu.png)
![AddLabel](https://github.com/Dino65535/vacation_daily_log/blob/ae73a77fa67fc03cfd0a22e5379160e12b992306/daily_log/0110~0115/AddLabel.png)

* 發現 KitchenLib 的 Wiki 中的 Menu 程式碼似乎有 Bug，直接複製編譯器會報錯，經過一番更改後雖然能讓編譯器不報錯並且成功建置，但在遊戲內仍然沒有成功，不太確定是哪方面出了問題，持續研究

* 或者 issue 問一下作者?
