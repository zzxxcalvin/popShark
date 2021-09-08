
2021/9/8
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
