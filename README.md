[README.md](https://github.com/user-attachments/files/32195460/README.md)
# 觀光產業看盤日報 ‧ 歷史站

```
index.html               自動導向最新一期
history.html             自動列出 reports/ 裡的所有日期
reports/YYYY-MM-DD.html  每日報表，唯一需要每天新增的檔案
```

`index.html` 和 `history.html` 設定一次就不用再動。兩支頁面都會即時去問 GitHub
「reports 資料夾裡現在有哪些檔案」，所以新報表丟進 reports/ 之後重新整理就會出現。

## 每天怎麼更新

把當天的 `YYYY-MM-DD.html` 上傳到 `reports/` 資料夾，commit，結束。
檔名一定要是 `年-月-日.html` 這個格式，否則兩支頁面認不出來。

## 兩個限制

1. repo 必須維持公開。改成私有後自動列表會失效（GitHub 不允許匿名查詢私有 repo）。
2. 同一個網路出口短時間重整太多次，可能碰到 GitHub 每小時 60 次的查詢上限，
   頁面會顯示讀取失敗。等幾分鐘就恢復，報表檔案本身不受影響。

## 保留 30 期

清單只顯示最新 30 期，舊檔留著不管或從 `reports/` 刪掉都可以。

## 網址

https://chenhouchun77-design.github.io/tourism-daily/
