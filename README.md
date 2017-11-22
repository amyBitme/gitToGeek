可以使用Visual Studio Code觀察
## 創建 
創立資料夾
```
mkdir gitToGeek
```

進入資料夾
```
cd gitToGeek
```

啟動git
```
<!-- 資料夾內會新增 .git的隱藏資料夾-->
git init
```

將檔案新增至暫存區
```
<!-- 請注意有空格 -->
git add .
```

提交至儲存庫
```
git commit -m "這裡寫你想新增的筆記"
```

---
## 查詢
查看git的狀態
```
<!-- 檔案是否更動-->
git status
```
查看提交的筆記紀錄
```
git log
```
---

## 還原

還原查看指定提交版本
```
git reset 2bba28
<!-- --hard 自動置換內容 -->
git reset --hard 2bba28
```

```
> git log
commit 2bba28331ffa4b91b6937722b10d1e4d5a2f370d (HEAD -> master)
Author: amyBitme <amy@bit.me>
Date:   Wed Nov 22 17:40:09 2017 +0800

    no add to commit

```
