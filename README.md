# GitHub 繁體中文教學站

把 GitHub 從帳號、第一個 repo、分支合併、Pull Request 協作，到 Issues、GitHub Pages、GitHub Actions 與開源貢獻，做成**中英對照**的分層教學。

- 目標讀者：初階工程師 / 學生
- 單元數：8 單元
- 授權：本站內容 CC-BY-4.0
- 網站：[https://shumingyang-opencode.github.io/github-tech-zh-tw/](https://shumingyang-opencode.github.io/github-tech-zh-tw/)

## 網站結構

```
github-tech-zh-tw/
├── index.html            # 課程總覽 + 入口卡片
├── map.html              # 平台功能地圖
├── learning-path.html    # 學習路線：L0 → L4 分層
├── about.html            # 關於本站
├── docs/                 # 單元教學頁
│   ├── index.html        # 單元一覽
│   ├── unit-01-*.html    # …共 8 篇
├── assets/site.css       # 單一共享樣式
└── .nojekyll
```

## 單元列表

| # | 單元 | 內容 |
|---|------|------|
| 01 | GitHub 是什麼 | Git vs GitHub、平台功能總覽、帳號與認證 |
| 02 | 第一個 Repo | repo、clone、add/commit/push、README、.gitignore |
| 03 | 分支與合併 | branch、merge、pull、衝突處理 |
| 04 | Pull Request 協作 | PR 流程、code review、保護分支 |
| 05 | Issues 與專案管理 | Issues、labels、milestones、Projects、Wiki |
| 06 | GitHub Pages | 靜態網站部署（以本站為實例） |
| 07 | GitHub Actions | CI/CD、workflow、secrets、常用 action |
| 08 | 開源協作與最佳實踐 | Fork、contribute、License、社群禮儀、gh CLI、安全 |

## 開發

本站為純靜態 HTML，無建置步驟。`assets/site.css` 為唯一樣式來源，所有頁面引用之。

```sh
python3 -m http.server 8000
```

## 授權

本站教學內容（繁體中文解說）為本站原創，採 CC-BY-4.0；文中技術名詞與操作引用自 GitHub Docs 與 Git 官方文件。

## 相關連結

- 學習路徑建議服務：[learning-path-advisor](https://shuming-yang.github.io/learning-path-advisor/) — 依角色推薦教學網站學習路徑
