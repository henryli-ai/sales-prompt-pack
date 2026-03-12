# 🚀 快速部署指南

## 方式一：使用 Vercel Dashboard（最簡單，推薦）

### 步驟 1：進入 Vercel
訪問：https://vercel.com/beliefrabbits-projects

### 步驟 2：導入專案
1. 點擊右上角 **"Add New..."**
2. 選擇 **"Project"**
3. 找到 `henryli-ai/sales-prompt-pack`
4. 點擊 **"Import"**

### 步驟 3：配置（保持預設）
- **Project Name**: `sales-prompt-pack`
- **Framework Preset**: Other
- **Build Command**: 留空
- **Output Directory**: 留空

### 步驟 4：部署
點擊 **"Deploy"** 按鈕，等待 1-2 分鐘

### 步驟 5：完成！
你會獲得網址：`https://sales-prompt-pack.vercel.app`

---

## 方式二：使用 Vercel CLI

### 在命令提示字元中執行：

```bash
# 進入專案目錄
cd "C:\Users\henryli\Desktop\Prompt Machine"

# 登入 Vercel（會開啟瀏覽器）
vercel login

# 部署（首次）
vercel

# 根據提示操作：
# - Set up and deploy? Y
# - Which scope? 選擇 beliefrabbits-projects
# - Link to existing project? N
# - Project name? sales-prompt-pack
# - In which directory? ./ (Enter)
# - Want to override settings? N

# 部署到生產環境
vercel --prod
```

### 完成後會顯示：
```
✅ Production: https://sales-prompt-pack.vercel.app
```

---

## ⚡ 一鍵部署按鈕

點擊下面的按鈕直接部署：

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/henryli-ai/sales-prompt-pack)

---

## 📋 檢查清單

部署前確認：
- ✅ GitHub 倉庫：https://github.com/henryli-ai/sales-prompt-pack
- ✅ index.html 已推送
- ✅ prompts-data.js 已推送
- ✅ README.md 已推送

部署後確認：
- ✅ 網站可以正常訪問
- ✅ 卡片正常顯示（兩欄布局）
- ✅ 展開/折疊功能正常
- ✅ 填寫變數功能正常
- ✅ 複製按鈕正常

---

## 🔄 自動部署

設定完成後，每次推送到 GitHub，Vercel 會自動重新部署：

```bash
git add .
git commit -m "更新描述"
git push origin master
```

Vercel 會在 1-2 分鐘內自動部署新版本。

---

## 🎯 預期結果

**網站網址格式：**
- `https://sales-prompt-pack.vercel.app`
- 或 `https://sales-prompt-pack-beliefrabbits-projects.vercel.app`

**功能檢查：**
- ✨ 毛玻璃高級視覺效果
- 📱 兩欄響應式布局
- 🎯 折疊/展開卡片
- ✍️ 填寫變數即時生成
- 📋 一鍵複製功能

---

**準備好了嗎？選擇一個方式開始部署！** 🚀
