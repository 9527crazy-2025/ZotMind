---
created: 2026/03/21 14:13:54
updated: 2026/03/21 14:25:38
title: 20260321-Readme
aliases:
tags:
rating: 
status:
comments:
---

<div align="center">
  <img src="docs/logo.png" alt="ZotMind Logo" width="120" />
  <h1>ZotMind</h1>
  <p>🧠 深度集成 AI 能力的 Zotero 智能研究助手插件</p>
  <p><em>An AI-powered academic research assistant plugin for Zotero</em></p>

  <p>
    <img src="https://img.shields.io/badge/Zotero-8%2B-red?logo=zotero" />
    <img src="https://img.shields.io/badge/status-beta-orange" />
    <img src="https://img.shields.io/badge/license-MIT-blue" />
  </p>
</div>

---

> ⚠️ **公测阶段 (Beta)**：本插件目前处于早期公测阶段，部分功能仍在开发中。欢迎试用并提交 Issue 反馈！

## ✨ 简介

ZotMind 旨在将 Zotero 从一个 " 文献存储库 " 升级为**智能研究工作台**。通过深度集成主流 AI 大模型，为研究人员提供文献问答、知识检索、划词助手和笔记管理的一站式闭环体验。

## 🚀 已实现功能

### 🤖 自定义 AI 模型

- 支持接入任意兼容 OpenAI 格式的 API（硅基流动、DeepSeek、Gemini、Ollama、OpenAI、阿里百炼、火山引擎等）
- 可自定义 Base URL、API Key、Temperature、Max Tokens、System Prompt 等参数
- 支持自定义 Embedding 模型（用于 RAG 向量化）

### 💬 AI 文献问答（ChatPDF）

- 基于当前打开的文献进行多轮 AI 问答
- 聊天界面支持快速调用自定义快捷指令（`/` 触发）
- 支持添加**多篇文献**作为上下文（`#` 触发）
- 支持添加**整个文件夹**作为上下文（`@` 触发）
- 内置预置问题（如 " 总结核心观点 "、" 解释研究方法 "、" 分析研究局限性 "），一键提问

### 🔍 RAG 知识库

- 支持将 Zotero 文献库向量化建立本地知识库
- 基于 RAG 技术实现跨文献的智能问答

### ⚡ 划词助手

选中 PDF 中的文字，即可快速触发：
- **翻译** — AI 即时翻译选中内容
- **解释** — AI 解释术语或句子含义
- **总结** — AI 摘要选中段落
- **优化** — AI 改写或润色
- **搜索** — 快速在线搜索
- **复制** — 一键复制文本
- **提问** — 将选中内容作为上下文向 AI 提问
- 支持 **+ 自定义**技能扩展

### 🗂️ 自定义 AI 快捷指令

- 支持在设置中预定义常用 Prompt，聊天时一键调用
- 避免重复输入相同提示词，提升问答效率

### 📝 笔记导出到 Obsidian

- 支持基于 Markdown 模板的笔记导出
- 笔记标题格式可自定义（如 `{{year}}-{{title}}.md`）
- 可配置导出目录和模板目录

## 🔧 安装方式

1. 前往 [Releases](../../releases) 页面下载最新的 `.xpi` 文件
2. 打开 Zotero → `工具` → `插件` → 点击右上角齿轮图标 → `从文件安装插件`
3. 选择下载的 `.xpi` 文件，重启 Zotero

**系统要求**：Zotero 7 及以上版本

## ⚙️ 快速配置

1. 打开 Zotero → `工具` → `ZotMind 设置`
2. 在 **AI 功能** 标签页中选择模型提供商，填入 API Key
3. 点击**测试连接**，确认配置正确
4. （可选）在 **笔记管理** 标签页中配置 Obsidian 导出路径

## 🗺️ Roadmap

以下功能正在开发中，敬请期待：

- [ ] 📊 **思维导图笔记** — 将笔记以思维导图形式可视化展示
- [ ] 🌐 **文献全文翻译** — PDF 全文双语对照翻译
- [ ] 🔎 **基于 RAG 的语义搜索** — 在整个文献库中进行语义级别检索

## 🤝 参与贡献

本项目目前处于公测阶段，非常欢迎社区反馈！

- 🐛 **发现 Bug**：请提交 [Issue](../../issues)
- 💡 **功能建议**：欢迎在 Issues 中分享你的想法
- 🔧 **参与开发**：欢迎提交 Pull Request

## 📄 许可证

[MIT License](LICENSE)

---

<div align="center">
  <sub>如果 ZotMind 对你有帮助，欢迎点一个 ⭐ Star 支持！</sub>
</div>
