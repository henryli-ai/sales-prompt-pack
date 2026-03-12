# 🚀 Vercel 部署步驟指南

## 你的 Vercel 帳戶
https://vercel.com/beliefrabbits-projects

## GitHub 倉庫
https://github.com/henryli-ai/sales-prompt-pack

---

## 📝 部署步驟（5 分鐘完成）

### 步驟 1：進入 Vercel Dashboard
1. 訪問 https://vercel.com/beliefrabbits-projects
2. 確認已登入你的帳號

### 步驟 2：新增專案
1. 點擊右上角 **"Add New..."** 按鈕
2. 選擇 **"Project"**

### 步驟 3：導入 Git 倉庫
1. 在 "Import Git Repository" 頁面
2. 如果看到 `henryli-ai/sales-prompt-pack`，直接點擊 **"Import"**
3. 如果沒看到，點擊 **"Adjust GitHub App Permissions"**
   - 給予 Vercel 存取該倉庫的權限
   - 返回後應該就能看到了

### 步驟 4：配置專案
在 "Configure Project" 頁面：

**Project Name（專案名稱）**
```
sales-prompt-pack
```
或自訂名稱，例如：
- `ai-sales-prompts`
- `prompt-generator`
- `sales-assistant`

**Framework Preset（框架預設）**
```
Other
```

**Root Directory（根目錄）**
```
./
```
（保持預設，不需要更改）

**Build and Output Settings（構建設定）**
- Build Command: **留空**
- Output Directory: **留空**
- Install Command: **留空**

**Environment Variables（環境變數）**
- **不需要設置**，直接跳過

### 步驟 5：部署
1. 確認所有設定正確
2. 點擊 **"Deploy"** 按鈕
3. 等待 1-2 分鐘

### 步驟 6：完成！
部署成功後，你會看到：

✅ **部署成功頁面**
- 顯示慶祝動畫 🎉
- 顯示你的網站網址

**網址格式：**
- `https://sales-prompt-pack.vercel.app`
- 或 `https://sales-prompt-pack-xxx.vercel.app`

---

## 🎨 可選：自訂域名

如果你有自己的域名：

1. 進入專案設定
2. 點擊 **"Settings"** → **"Domains"**
3. 輸入你的域名
4. 按照指示配置 DNS

**常見域名服務商：**
- Cloudflare
- GoDaddy
- Namecheap
- Google Domains

---

## 🔄 自動部署設置

部署完成後，Vercel 會自動監聽 GitHub 倉庫：

**每次你推送代碼：**
```bash
git add .
git commit -m "更新內容"
git push origin master
```

**Vercel 會自動：**
1. 檢測到新的 commit
2. 開始構建
3. 部署新版本
4. 更新網站（通常 1-2 分鐘）

---

## 📊 查看部署狀態

**在 Vercel Dashboard：**
1. 進入你的專案
2. 查看 **"Deployments"** 標籤
3. 可以看到：
   - 部署歷史
   - 每次部署的詳情
   - 部署時間
   - Git commit 訊息

---

## 🔧 進階設定（可選）

### 設定生產分支
預設是 `master` 分支，如果你想改成 `main`：

1. **Settings** → **Git**
2. **Production Branch**: 改為 `main`

### 設定部署通知
1. **Settings** → **Notifications**
2. 可以設定：
   - Email 通知
   - Slack 通知
   - Discord webhook

### 啟用評論預覽
1. **Settings** → **Git**
2. 勾選 **"Enable Comments"**
3. 之後每個 Pull Request 都會自動產生預覽網址

---

## 🆘 常見問題

### Q1: 找不到我的倉庫怎麼辦？
**解決方法：**
1. 點擊 "Adjust GitHub App Permissions"
2. 給予 Vercel 存取權限
3. 或者直接使用倉庫 URL 導入

### Q2: 部署失敗怎麼辦？
**檢查清單：**
- ✅ 確認 `index.html` 存在
- ✅ 確認 `prompts-data.js` 存在
- ✅ 查看部署日誌中的錯誤訊息

### Q3: 網站顯示空白頁面
**解決方法：**
1. 檢查瀏覽器控制台（F12）
2. 確認 JavaScript 沒有錯誤
3. 清除瀏覽器快取

### Q4: 如何回滾到之前的版本？
**步驟：**
1. 進入 **"Deployments"**
2. 找到想要的版本
3. 點擊 **"..."** → **"Promote to Production"**

---

## 📱 分享你的網站

部署成功後，你可以：

1. **複製網址** 分享給同事
2. **加入書籤** 方便使用
3. **嵌入其他網站**（如果需要）

---

## 🎯 下一步

- [ ] 完成 Vercel 部署
- [ ] 測試所有功能
- [ ] 分享給團隊成員
- [ ] （可選）設定自訂域名
- [ ] （可選）啟用分析工具

---

**準備好了嗎？現在就去部署吧！** 🚀

完成後記得分享你的網站連結！
