# React 專案檔案結構

```text
project-root/
├── public/
│   ├── index.html
│   └── ...
├── 💻 src/
│   ├── 🖼️ assets/         # 靜態資源（圖片、字型等）
│   ├── 🧩 components/     # 共用元件
│   ├── 📄 pages/          # 頁面元件
│   ├── 🪝 hooks/          # 自訂 Hook
│   ├── 🛠️ utils/          # 工具函式
│   ├── ⚛️ App.js          # 主要 App 元件
│   ├── 🚀 index.js        # 入口檔案
│   └── ...
├── 🙈 .gitignore
├── 📦 package.json
├── 📖 README.md
└── ...
```

## 說明

- 🗂️ `public/`：靜態檔案資料夾，通常只放 index.html 與 favicon 等。
- 💻 `src/`：主要程式碼資料夾。
  - 🖼️ `assets/`：圖片、樣式等靜態資源。
  - 🧩 `components/`：可重複使用的 React 元件。
  - 📄 `pages/`：頁面級元件，對應路由。
  - 🪝 `hooks/`：自訂 Hook。
  - 🛠️ `utils/`：工具函式。
  - ⚛️ `App.js`：應用程式主元件。
  - 🚀 `index.js`：應用程式進入點。
- 📦 `package.json`：專案設定與相依套件。
- 🙈 `.gitignore`：Git 忽略設定。

---

## 18 週課程章節目錄

1. 認識 React 與開發環境建置

   [Week1](./course/week01.md)
3. JSX 與元件基礎
4. Props 與元件組合
5. State 與事件處理
6. 條件渲染與列表渲染
7. 表單處理與受控元件
8. 元件生命週期與 useEffect
9. 自訂 Hook 與狀態管理
10. Context API 與全域狀態
11. 路由（React Router）
12. API 串接與資料取得
13. 樣式處理（CSS-in-JS, styled-components）
14. 元件設計模式與最佳實踐
15. 測試（Jest, React Testing Library）
16. 部署與建置
17. 進階 Hooks 與效能優化
18. 第三方套件整合（如 Redux, MobX, Chart.js 等）
19. 期末專題與成果發表
