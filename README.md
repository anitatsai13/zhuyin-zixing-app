# 字音字形學習

單一自包含 HTML 的國語**字音字形／成語**學習網頁 —— 注音、字形、近似字辨識、成語擂臺、測驗、錯題本、雲端會員(跨裝置同步錯題)。國小～國中月考/題庫多冊。

🌐 線上版:https://fascinating-longma-d5e170.netlify.app/

## 檔案
- `index.html` —— **App 本體**(所有資料、程式、樣式都內嵌;離線可開,不需安裝任何東西)。

## 修改
用文字編輯器打開 `index.html` 改即可,存檔後用瀏覽器開就能測試。

## 部署
把 `index.html` 拖到 Netlify(該站台的 Deploys 頁面)即可更新,網址不變。

> 資料與建置腳本(parse*.py / build.py / 各 .json)存放在作者本機的「字音字形_建置工具」資料夾;此 repo 只放最終成品 `index.html`。雲端會員用 Supabase,HTML 內的 anon key 為公開安全金鑰(RLS 保護)。
