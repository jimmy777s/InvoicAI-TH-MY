# 📌 InvoicAI-TH-MY 使用指南

**自动化发票信息提取工具**  
（支持泰国 & 马来西亚发票PDF处理）

---

## 🚀 快速开始
### 方式一：从 SharePoint 上传
1. **访问路径**  
   `SalesandCash-Vistra/NDF2/Tax invoice`
2. **选择类别** → 输入月份文件夹名  
   - 常规格式：`MM Mon YY`（如 `07 Jul 24`）  
   - Robinhood 特殊格式：`06 Jun 25/M184519`

### 方式二：本地上传
1. **先选择类别**  
2. **上传文件夹**（自动读取所有PDF文件）  
   ⚠️ 仅支持PDF格式

---

## 📂 文件结构规范
### 输入路径示例
```plaintext
Thailand & Maylaysia - Extract invoice information/
└── 3. Thailand/
    └── 6. SBUX/
        └── NDF2/
            └── 4. Invoices/
                ├── Jul/
                │   ├── BBL_Starbucks/  [PDF存放处]
                │   └── SBUX_NDF2_Jul_results.xlsx    [输出文件]
                └── processing_log.txt   [全局日志]
```

---

## 🔄 数据恢复
### 如需修复历史数据
- 访问备份路径 \\10.86.2.112\Thailand & Maylaysia - Extract invoice information
- 按时间戳查找最近的文件

---
# Tips
- 如果文件之前识别过，希望再识别一次，在processing_log里面将文件的状态改为失败，就可以让程序重新识别。


