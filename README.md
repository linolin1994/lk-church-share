# LK Church 小組分享

每週小組分享的手機友善網頁集合。

## 結構

```
lk-church-share/
├── index.html                  # 目錄首頁（列出每次分享）
├── 0529-filled-with-what/      # 5/29「被甚麼充滿？」
│   └── index.html
└── （之後每次新增一個資料夾）
```

## 新增一次分享的步驟

1. 在根目錄建立資料夾，命名格式：`MMDD-主題slug`（例如 `0605-priority`）
2. 在資料夾內放 `index.html`
3. 編輯根目錄的 `index.html`，加上新分享的卡片連結
4. commit + push

## 部署

透過 GitHub Pages 自動部署（main 分支根目錄）。

網址：
- 目錄：https://linolin1994.github.io/lk-church-share/
- 各週：https://linolin1994.github.io/lk-church-share/{資料夾名}/
