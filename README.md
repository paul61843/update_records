# update_records

> 紀錄專案更新內容

## 網頁相關

- 將天氣預報頁面，部分功能建立成 Component
- 使用 socket.io 製作聊天室功能 (後來忙教授的案子，這個專案就沒再調整了)

## GA
- 新增 GA4 收集使用者瀏覽紀錄

## nginx 相關

- 使用 nginx 進行反向代理
- 建立子網域
- 將 vscode server 設定至子網域，解決無法輸入密碼的問題
- 從 ssl for free 取得憑證，透過nginx新增網頁憑證

## 尚未解決

- 問題 nginx 反向代理路徑
1. weather project 畫面成功顯示，但圖片無法顯示
後來將專案指向子路由的根目錄解決

2. vscode server 無法透過 queryString 輸入密碼
同上