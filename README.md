# homework-task-analyzer

[English](#english) | [中文](#chinese)

---

## English

**Homework Task Analyzer** — an AI-powered tool that transforms your homework descriptions, assignment requirements, and even screenshots into structured, actionable to-do lists using the DeepSeek API.

### Features

- 🤖 **AI-Powered Analysis** — Paste assignment text or upload images, and DeepSeek AI extracts and organizes all tasks.
- 📋 **Structured Output** — Tasks are categorized, prioritized, and formatted into a clear checklist with estimated effort.
- 📤 **Multi-Format Export** — Export your task list to **PDF**, **DOCX**, or **PNG image** with a single click.
- 💾 **Local Storage** — Your DeepSeek API key is stored securely in browser localStorage — never sent anywhere except DeepSeek's API.
- 🎨 **Modern UI** — Clean, responsive interface with light/dark-friendly design.
- 🌐 **Zero Dependencies** — A single `index.html` file. No build step, no server required.

### Usage

1. Open `index.html` in a browser.
2. Click ⚙️ in the top-right corner and enter your [DeepSeek API Key](https://platform.deepseek.com/api_keys).
3. Paste your assignment text (or upload screenshots) and click **Analyze**.
4. Review the generated task list, then export to PDF, DOCX, or image.

### Example

> **Input:** "下周一交数学作业第3章习题1-10题，周三有英语作文关于环境保护，周五之前完成物理实验报告"
>
> **Output:** A structured checklist with 3 tasks, each tagged by subject, deadline, priority, and estimated time.

### Tech Stack

- Vanilla HTML/CSS/JavaScript
- [DeepSeek Chat API](https://platform.deepseek.com/)
- [jsPDF](https://github.com/parallax/jsPDF) — PDF export
- [html2canvas](https://html2canvas.hertzen.com/) — Image export
- [docx.js](https://github.com/dolanmedia/docx) — DOCX export

---

## 中文

**作业待办事项分析工具** — 基于 DeepSeek AI 的智能工具，可将作业描述、任务要求和截图一键转换为结构化的待办清单。

### 功能特点

- 🤖 **AI 智能分析** — 粘贴作业文字或上传图片，DeepSeek AI 自动提取并整理所有任务。
- 📋 **结构化输出** — 任务按科目分类、优先级排序，生成清晰的任务清单，附带预估用时。
- 📤 **多格式导出** — 一键导出为 **PDF**、**DOCX** 或 **PNG 图片**。
- 💾 **本地存储** — DeepSeek API 密钥安全存储在浏览器 localStorage 中，仅发送至 DeepSeek 官方 API。
- 🎨 **现代化界面** — 简洁、响应式设计，适配亮色/暗色主题。
- 🌐 **零依赖部署** — 仅一个 `index.html` 文件，无需构建、无需服务器。

### 使用方法

1. 在浏览器中打开 `index.html`。
2. 点击右上角 ⚙️ 图标，输入你的 [DeepSeek API Key](https://platform.deepseek.com/api_keys)。
3. 粘贴作业文字（或上传截图），点击 **分析**。
4. 查看生成的待办清单，可导出为 PDF、DOCX 或图片。

### 示例

> **输入：** "下周一交数学作业第3章习题1-10题，周三有英语作文关于环境保护，周五之前完成物理实验报告"
>
> **输出：** 包含 3 项任务的结构化清单，每项标注科目、截止日期、优先级和预估时间。

### 技术栈

- 原生 HTML/CSS/JavaScript
- [DeepSeek Chat API](https://platform.deepseek.com/)
- [jsPDF](https://github.com/parallax/jsPDF) — PDF 导出
- [html2canvas](https://html2canvas.hertzen.com/) — 图片导出
- [docx.js](https://github.com/dolanmedia/docx) — DOCX 导出

---

## License

MIT
