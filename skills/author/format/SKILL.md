---
name: format
description: Export manuscripts to DOCX, EPUB, PDF, KDP-ready formatting
author: AuthorClaw
version: 1.0.0
triggers:
  - "format"
  - "export"
  - "epub"
  - "kindle"
  - "KDP"
  - "pdf"
  - "docx"
  - "manuscript format"
permissions:
  - file:read
  - file:write
---

# 格式设置与导出技能

将手稿转换为可出版的格式

## 支持的格式

### 标准稿件格式（供代理商/编辑使用）
- 12磅Times New Roman或Courier字体
- 双倍行距，1英寸页边距
- 页眉：作者姓名/书名/页码
- 场景分隔：居中#或***
- 章节分隔：新页面，居中标题

### EPUB（电子书发行格式）
- 规范的HTML/CSS结构
- 自动生成目录
- 元数据（书名、作者、简介、ISBN）
- 封面图片嵌入
- 章节导航功能

### KDP就绪格式（亚马逊Kindle直接出版）
- 符合KDP格式指南
- 前辅文：扉页、版权页、献词页
- 后辅文：作者介绍、其他作品、致谢
- 正确的裁切尺寸设置
- 印刷出血设置

### PDF（印刷/审阅用）
- 专业排版
- 完善的孤行/寡行控制
- 页眉标题
- 页码设置

### DOCX（编辑/协作用）
- 使用样式保持格式整洁
- 支持修订跟踪
- 便于添加批注

## 工作流程
1. 从项目文件夹收集所有章节
2. 应用所需格式
3. 生成前辅文和后辅文
4. 导出至`workspace/exports/`目录
5. 报告发现的格式问题