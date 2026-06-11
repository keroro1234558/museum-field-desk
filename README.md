# 展後分析台 PWA

這個資料夾是可直接部署的手機版網站。

## 手機使用

1. 使用 iPhone Safari 開啟部署後的 HTTPS 網址。
2. 點 Safari 分享按鈕。
3. 選「加入主畫面」。
4. 之後直接點主畫面的「展後分析」圖示。

安裝並成功開啟一次後，核心功能可離線使用。

## 公開網址

- 分析台：<https://keroro1234558.github.io/museum-field-desk/>
- 手機說明：<https://keroro1234558.github.io/museum-field-desk/guide.html>

網站使用 GitHub Pages，直接發布 `main` 分支根目錄。每次推送 `main` 後會自動更新。

## 驗證項目

- `index.html`：分析台主程式
- `manifest.webmanifest`：主畫面名稱與圖示
- `sw.js`：離線快取
- `icon-180.png`：iPhone 主畫面圖示
- `icon-512.png`：PWA 圖示
- `guide.html`：簡化使用說明
