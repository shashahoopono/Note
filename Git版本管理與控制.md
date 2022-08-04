# Git版本管理與控制


## 是什麼Git

- 是 **分散式** 的版本控制系統，是來管理程式碼的工具。
- 使用Git的不外乎三個原因：版本控制、程式碼管理、團隊協作。




## Git安裝與配置

- 安裝完後即可以Git Bash進行Git指令操作。
- 需設定使用者名稱與信箱，並確認是否設置成功。
    > `git config --global user.name "name"`
    > `git confih --global user.email "mail"`
    > `git config --global --list`
    > `--global` ：表示此電腦所有git儲存庫都將會以此使用者配置。



## Git常用指令

- 新建資料夾：mkdir + 資料夾名稱
- 切換資料夾：cd + 資料夾名稱
- 顯示當前資料夾： pwd
- 返回上一層：cd




## 創建本地端的Git儲存庫

### 創建方式有兩種：
1. 將本地資料夾納入Git管理
    > 使用Git指令`git init`，生成.git隱藏資料夾。
    > 初始化後建立.gitignore(不納入管理)與README.md(說明文檔)
2. 從遠端儲存庫clone
    ![](https://i.imgur.com/InwJ3iY.png)
- `git clone HTTP URL` 將遠端複製到本地
    




## 創建遠端的Git儲存庫

- 在Git Hub網站個人頁面儲存庫中NEW一個
    ![](https://i.imgur.com/ad6t8Hz.png)

### 遠端與本地端連結的兩種方式：

1. 創建一個本地新資料夾後連結
2. 將現有本地資料夾直接連結

> `git remote add origin HTTP URL`
> `git branch -M main`
> `git push -u origin main`



## Git的本地推送與提交遠端

1. `git add`(加至暫存區) 
2. `git commit -m"XXX"`(下註釋) 
3. `git push`(推送遠端) 

- git restore (file)(取消暫存)

## 建立分支與切換

- `git branch -m 分支名`(創建分支)
- `git checkout + 分支名`(切換分支)

###### tags: `Git` `學習筆記`


