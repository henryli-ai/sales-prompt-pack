# 📚 Sales Prompt Pack v1

一個精美的網頁應用，展示 25 條專業的 AI Sales Prompts，支援填寫變數、即時生成和一鍵複製。

## ✨ 功能特色

- 📋 **25 條精選 Prompts** - 涵蓋銷售全流程的專業提示詞
- ✍️ **變數填寫表單** - 直接在網頁上填寫變數，無需手動替換
- ✨ **即時生成 Prompt** - 填寫完變數後自動生成可用的 Prompt
- 🔍 **即時搜尋** - 快速搜尋 Prompt 名稱、使用時機、變數等
- 🏷️ **分類篩選** - 按 Category（分類）和 Stage（階段）篩選
- 📝 **雙版本顯示** - 每個 Prompt 提供快速版和強化版範本
- 📋 **一鍵複製** - 點擊按鈕立即複製到剪貼簿
- 🎨 **精美設計** - 漸變紫色主題，卡片式佈局
- 📱 **響應式** - 支援桌面和移動裝置

## 🚀 快速开始

### 方式一：直接打开
双击 `index.html` 文件即可在浏览器中打开网站。

### 方式二：使用本地服务器
```bash
# 使用 Python
python -m http.server 8000

# 使用 Node.js
npx serve

# 然后访问 http://localhost:8000
```

## 📖 使用说明

### 1️⃣ 搜索 Prompt
在顶部搜索框中输入关键词，系统会即时筛选匹配的 Prompts。

### 2️⃣ 分类筛选
点击分类按钮，可以按照以下维度筛选：

**Category（分类）**
- Outreach - 外联沟通
- Strategy - 策略规划
- Competitive - 竞品分析
- Data - 数据分析
- Visuals - 视觉素材

**Stage（阶段）** - 已优化为 5 个高层次分组
- 销售流程 - 包含 Prospecting, Demo, Renewal, Discovery（6 个 Prompts）
- 策略规划 - 包含 Planning, Account Planning, Expansion（4 个 Prompts）
- 团队管理 - 包含 Mgmt, Daily Ops, Internal（3 个 Prompts）
- 赋能培训 - 包含 Enablement（7 个 Prompts）
- 数据分析 - 包含 Pipeline, Performance（5 个 Prompts）

### 3️⃣ 填寫變數
在「填寫變數」區域，輸入所需的資訊：
- **客戶** - 輸入客戶名稱
- **公司概況** - 填寫公司背景資訊
- **優先事項** - 輸入已知的優先事項
- 等等...

### 4️⃣ 兩種使用方式

**方式一：客製化 Prompt（推薦）**
1. 在「填寫變數」區域輸入您的資訊
2. 「已生成」區域會即時顯示替換好變數的 Prompt
3. 點擊「📋 複製已生成的 Prompt」直接使用

**方式二：快速複製範本**
1. 直接複製「快速版範本」或「強化版範本」
2. 貼到 AI 聊天室中手動修改變數
3. 適合快速使用或微調需求

## 📁 文件结构

```
Prompt Machine/
├── index.html                    # 主页面
├── prompts-data.js              # Prompt 数据文件（25 条记录）
├── README.md                    # 使用说明
└── Sales_Prompt_Pack_v1_GoogleSheet_Template.xlsx  # 原始数据
```

## 🎯 Prompt 分类

### Outreach（外联）- 5 个
- 冷开发邮件
- Demo 后跟进
- 续约 Pitch
- 每日活动摘要
- Pipeline 状态更新

### Strategy（策略）- 5 个
- 战略客户计划
- Territory 规划
- 客户优先级排序
- 加权评分
- 市场进入规划

### Competitive（竞品）- 5 个
- 竞品 Battlecard
- 竞品定位分析
- Sales Enablement 文件
- 异议处理
- 客户证明点

### Data（数据）- 5 个
- Pipeline 转换率分析
- 销售代表排名
- Deal Velocity 趋势
- Campaign 归因分析
- 绩效对比图

### Visuals（视觉）- 5 个
- Sales Funnel 图
- B2B 漏斗标准图
- Persona 插图
- Territory 地图
- 团队庆祝图

## 🔧 自定义修改

### 修改数据
编辑 `prompts-data.js` 文件，按照现有格式添加或修改 Prompt：

```javascript
{
  "ID": "SLS-XXX-001",
  "Category": "分类名称",
  "Stage": "阶段名称",
  "Use Case": "使用场景",
  "When to Use": "使用时机说明",
  "Variable List": "变量列表",
  "Prompt Quick ZH": "快速版提示词",
  "Prompt Robust ZH": "强化版提示词",
  "Notes": "备注信息"
}
```

### 修改样式
编辑 `index.html` 中的 `<style>` 部分，可以自定义：
- 主题颜色（渐变紫色）
- 卡片布局
- 字体和字号
- 间距和圆角

## 💡 使用技巧

1. **組合篩選** - 可以同時使用搜尋和分類篩選來精確定位
2. **關鍵詞搜尋** - 支援搜尋 ID、標題、使用時機、變數等任何內容
3. **填寫變數** - 直接在輸入框中填寫，系統會即時生成可用的 Prompt
4. **複製使用** - 填寫完變數後，點擊「複製已生成的 Prompt」即可直接使用
5. **查看範本** - 如需了解 Prompt 結構，可展開「查看原始 Prompt 範本」
6. **儲存常用值** - 瀏覽器會記住您填寫的內容（直到重新整理頁面）

## 📌 注意事项

- 网站使用纯前端技术，无需服务器
- 所有数据保存在本地，不会上传到云端
- 建议使用现代浏览器（Chrome、Edge、Firefox）
- 复制功能需要浏览器支持 Clipboard API

## 🎨 界面预览

网站采用现代化设计：
- 渐变紫色背景
- 白色卡片式布局
- 醒目的分类标签
- 清晰的版本区分
- 流畅的交互动画

## 📝 数据来源

数据来自 OpenAI Academy Sales Use Cases：
https://academy.openai.com/public/clubs/work-users-ynjqu/resources/use-cases-sales

## 🔄 更新日誌

**v3.0 (2026-03-12)** - TPI 風格重大改版
- ✅ **採用 TPI 品牌規範** - 使用 TPI 紫色主題（#662E8D）和設計語言
- ✅ **清晰的步驟引導** - 步驟 1（填寫變數）→ 步驟 2（已生成）→ 步驟 3（原始範本）
- ✅ **區塊化設計** - 不同功能使用不同顏色區塊，一目了然
- ✅ **標籤式範本切換** - 快速版/強化版使用 Tab 切換，節省空間
- ✅ **更直觀的使用動線** - 參考 TPI 課程大綱模板的卡片設計
- ✅ **專業視覺效果** - 漸層背景、陰影、圓角等精緻細節

**v2.1 (2026-03-12)** - UI 優化
- ✅ 並列顯示輸入框
- ✅ 直接顯示範本
- ✅ 雙軌使用模式

**v2.0 (2026-03-12)** - 重大更新
- ✅ **變數填寫表單** - 將必填變數改為可填寫的輸入框
- ✅ **即時生成 Prompt** - 填寫變數後自動生成可用的 Prompt
- ✅ **全繁體中文** - 所有介面文字改為繁體中文
- ✅ **優化使用流程** - 更符合實際使用場景的互動設計

**v1.1 (2026-03-12)**
- ✅ 優化 Stage 篩選分組
- ✅ 將 13 個原始 Stage 合併為 5 個高層次分組
- ✅ 解決部分標籤點擊後沒有足夠 Prompts 的問題
- ✅ 改善篩選體驗和資料分佈

**v1.0 (2026-03-12)**
- ✅ 初始版本發佈
- ✅ 25 條 Sales Prompts
- ✅ 搜尋和篩選功能
- ✅ 一鍵複製功能
- ✅ 響應式設計

---

**享受使用这个工具！如果有任何问题或建议，欢迎反馈。** 🚀
