---
title: 把蘋果無線巧拼鍵盤 apple magic keyboard 更改成 windows配置!!
date: 2019-09-26 23:26:25
tags: 
  - 鍵盤
---
### 介紹
最近入手了蘋果的巧拼鍵盤，結果發現他的鍵盤位置的左下角是 fn 鍵而不是 ctrl，讓我覺得跟其他鍵盤比巧來用得太卡了。

畢竟工程師最常用的就是 ctrl + 各種按鈕了  

![test](https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/MLA22CH?wid=572&hei=572&fmt=jpeg&qlt=95&op_usm=0.5,0.5&.v=1496100487492)  

那我最主要想要的功能就是把 ctrl 鍵換成在鍵盤的左下角這樣跟原本的鍵盤操作才會一致  

於是我 google 了一下還真的給我找到有人做了轉換的工具 [WinAppleKey](https://github.com/samartzidis/WinAppleKey)  

真的是太強了(跪)，順手就給了一顆 star

### 安裝

其實在 github 裡面的說明已經很清楚了，第一步就是先下載這個 [軟體](https://github.com/samartzidis/WinAppleKey/releases)

第二步你要在 cmd 裡面下 `bcdedit.exe -set TESTSIGNING ON` 這串指令， 

#### **注意** window 的話請用系統管理者打開 cmd 不然權限不夠 

#### **注意** 開啟 `bcdedit.exe -set TESTSIGNING ON` 是有風險的，請在使用前先評估自己有沒有辦法承擔風險

第三步 重開機

第四步 安裝剛剛下載的 Setup.msi

接著應該就完成了(灑花)