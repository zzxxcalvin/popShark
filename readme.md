

### 專案目標
PoPGura Cat 
大概就如題

### 未實作功能:
-   計數器
-   確認 IP 來源

### 目前功能:
-   POP
-   CUTE

#### 實作方式:
>用 eventlistener 監聽keydown、mousedown
> function 使用 pop , 讓 popcat 圖片的 visibility : visible
>相反的監聽 keyup、mouseup , 沒有按下的時候顯示原本的圖片

#### 目前問題:
1. 目前持續按住鍵盤會持續觸發event
    * (暫解) 加了一個 counter 判斷,不確定這樣有沒有讓效率變慢之類的

2021/9/8

一般的 POP 完成
手機上可以運作,可是圖片比例不對

2021/9/9

加了一個 counter 
並且目前圖片應該是響應式的了(自己手機測試比例正常)
發現可能 pointerdown 跟 mousedown 有重疊觸發到的部分
手機上按下跟 release 都會觸發一次counter