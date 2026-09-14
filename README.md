# 觀光產業看盤日報 ‧ 歷史站

GitHub Pages 靜態網站，保留最近 30 期報表。

```
index.html               最新一期報表
history.html             日期清單（由新到舊）
reports/2026-09-14.html  每日存檔，內容與 index.html 相同
```

## 第一次設定

1. 建一個新的 GitHub repository，例如 `tourism-daily`。
2. 把 `index.html`、`history.html`、`reports/` 整包上傳到 repo 根目錄。
3. Settings → Pages → Source 選 `Deploy from a branch`，branch `main`、資料夾 `/ (root)`，Save。
4. 網址：`https://<你的帳號>.github.io/tourism-daily/`

免費方案的 Pages 只能從公開 repo 發佈。要保密的話，Cloudflare Pages 免費方案支援 private repo 加密碼保護。

## 每天怎麼更新

我每天產完報表會給你三個檔，覆蓋上去即可：

- `reports/YYYY-MM-DD.html`（新增當日）
- `index.html`（換成當日）
- `history.html`（清單多一筆）

## 保留 30 期

`history.html` 只列最近 30 期。超過的舊檔不會出現在清單裡，
可以留著不管，也可以直接從 `reports/` 刪掉，兩者都不影響網站運作。
