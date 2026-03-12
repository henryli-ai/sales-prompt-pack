# 🚀 部署指南

## ✅ GitHub 已完成

你的代碼已成功推送到 GitHub：
**https://github.com/henryli-ai/sales-prompt-pack**

---

## 📦 在 Vercel 上部署

### 方式一：使用 Vercel Dashboard（推薦）

1. **訪問 Vercel**
   - 前往 https://vercel.com
   - 使用 GitHub 帳號登入

2. **導入專案**
   - 點擊 "Add New..." → "Project"
   - 選擇 "Import Git Repository"
   - 找到並選擇 `sales-prompt-pack` 倉庫

3. **配置專案**
   - **Project Name**: `sales-prompt-pack`（或自訂名稱）
   - **Framework Preset**: 選擇 "Other"
   - **Root Directory**: `.`（保持預設）
   - **Build Command**: 留空
   - **Output Directory**: `.`（保持預設）
   - **Install Command**: 留空

4. **部署**
   - 點擊 "Deploy" 按鈕
   - 等待 1-2 分鐘完成部署

5. **完成**
   - 你會獲得一個網址，格式類似：
   - `https://sales-prompt-pack.vercel.app`
   - 或 `https://sales-prompt-pack-xxx.vercel.app`

---

### 方式二：使用 Vercel CLI

```bash
# 1. 安裝 Vercel CLI（如果尚未安裝）
npm install -g vercel

# 2. 登入 Vercel
vercel login

# 3. 在專案目錄中部署
cd "C:\Users\henryli\Desktop\Prompt Machine"
vercel

# 4. 按照提示操作：
# - Set up and deploy? Yes
# - Which scope? 選擇你的帳號
# - Link to existing project? No
# - Project name? sales-prompt-pack
# - In which directory? ./ (保持預設)
# - Want to override settings? No

# 5. 部署到生產環境
vercel --prod
```

---

## 🔄 未來更新

每次你更新代碼並推送到 GitHub 後，Vercel 會自動重新部署：

```bash
git add .
git commit -m "Update: 描述你的更新"
git push origin master
```

---

## 🎨 自訂域名（選用）

1. 在 Vercel Dashboard 進入你的專案
2. 前往 "Settings" → "Domains"
3. 添加你的自訂域名
4. 按照指示配置 DNS

---

## 📝 注意事項

- ✅ 專案是純前端靜態網站，無需後端
- ✅ 所有資料都在 `prompts-data.js` 中
- ✅ 支援自動 HTTPS
- ✅ 全球 CDN 加速
- ✅ 每次 Git push 自動部署

---

## 🆘 遇到問題？

### 問題 1：部署失敗
- 確認 `index.html` 和 `prompts-data.js` 都已推送到 GitHub
- 檢查 Vercel 的錯誤日誌

### 問題 2：頁面空白
- 確認瀏覽器控制台是否有錯誤
- 檢查 `prompts-data.js` 是否正確載入

### 問題 3：樣式問題
- 清除瀏覽器快取
- 使用無痕模式測試

---

**部署成功後，記得分享你的網站連結！** 🎉
