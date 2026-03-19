---
name: nonfiction-research
description: Academic source gathering, citation management, fact-checking for nonfiction
author: AuthorClaw
version: 1.0.0
triggers:
  - "nonfiction"
  - "citation"
  - "cite"
  - "bibliography"
  - "source"
  - "academic"
  - "fact check"
  - "reference"
permissions:
  - network:http
  - file:read
  - file:write
---

# 非虚构作品研究技能

为纪实文学作者提供全面的研究支持

## 资源管理
- 记录所有来源并包含完整引用数据
- 按章节/主题分类整理
- 标注一手与二手资料
- 备注来源可靠性及潜在偏见

## 引用格式支持
APA、MLA、芝加哥（注释与参考文献）、芝加哥（作者-日期）、哈佛格式
自动按作者偏好生成参考文献/引用作品列表

## 事实核查流程
1. 识别文稿中所有事实性主张
2. 追溯每个主张的来源
3. 验证来源可靠性
4. 标记：✅已验证 ⚠️需更强力来源 ❌无法验证
5. 区分作者观点与既定事实

## 访谈管理
- 记录受访者信息、日期及关键引述
- 权限/同意书追踪
- 引述准确性验证

## 数据可视化
- 协助构建图表、信息图数据结构
- 核查统计声明
- 建议复杂数据的优化呈现方式

## 法律风险提示
- 标注潜在诽谤风险
- 提示需要法律审查的内容
- 追踪引用材料所需授权
- 合理使用原则考量

## 输出
将研究数据库保存至`projects/[项目名]/research/sources.md`