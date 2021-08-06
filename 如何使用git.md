# Git學習筆記
## 如何使用Git

### 進入專案資料夾
- 開啟終端機
- 輸入**資料夾位置**
```
cd 資料夾位置（也可以把資料夾從桌面拖拉到終端機）
``` 

### 檢查git是否安裝成功
- 在終端機輸入 **git --version** 
```git
git --version
```
- 看是否回傳git版本資訊

### 初始化數據庫
- 在終端機輸入 **git init**
```
git init
```
- 顯示 **Initialized empty Git repository....**，會在專案資料夾裡**建立空的數據庫**
- 專案資料夾內會有**git(名稱)的隱藏資料夾**

### 設定個人資料
- 輸入姓名
```
git config --global user.name "姓名"
```
- 輸入個人e-mail
```
git config --global user.email "xxxxx@gmail.com"
```
- 查詢git設定內容
```
git config --list
```