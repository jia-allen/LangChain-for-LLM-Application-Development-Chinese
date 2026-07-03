<div align="center">

# 使用 LangChain 开发基于 LLM 的应用程序

中文教程与课程笔记整理，配套 DeepLearning.AI 短课  
**LangChain for LLM Application Development**

[![Course](https://img.shields.io/badge/DeepLearning.AI-Course-blue)](https://learn.deeplearning.ai/langchain/lesson/1/introduction)
[![LangChain](https://img.shields.io/badge/LangChain-LLM%20Application-1C3C3C)](https://www.langchain.com/)
[![GitHub stars](https://img.shields.io/github/stars/jia-allen/LangChain-for-LLM-Application-Development-Chinese?color=yellow)](https://github.com/jia-allen/LangChain-for-LLM-Application-Development-Chinese/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/jia-allen/LangChain-for-LLM-Application-Development-Chinese?color=9cf)](https://github.com/jia-allen/LangChain-for-LLM-Application-Development-Chinese/network/members)
![Visitors](https://visitor-badge.lithub.cc/badge?page_id=jia-allen.LangChain-for-LLM-Application-Development-Chinese&left_text=Visitors)

</div>

## 项目简介

这是吴恩达老师与 LangChain 作者 Harrison Chase 合作推出的短期课程
《LangChain for LLM Application Development》的中文学习笔记与代码整理。

课程围绕如何使用 LangChain 与 ChatGPT API 构建大模型应用展开，内容覆盖模型调用、提示模板、输出解析、记忆存储、链式编排、文档问答、评估与智能代理等核心主题。适合希望从零开始理解 LangChain 应用开发流程，并快速搭建 LLM 原型的开发者学习参考。

## 你可以学到什么

- 理解 LangChain 在 LLM 应用开发中的定位与常见抽象
- 使用模型、提示模板和输出解析器构建稳定输入输出流程
- 为应用加入 Memory，让多轮对话具备上下文能力
- 通过 Chains 组合多个步骤，搭建更完整的业务流程
- 构建基于文档的问答系统，让模型回答私有知识库问题
- 学习 LLM 应用评估方法与 Agent 的基本使用方式

## 课程目录

| 序号 | 章节 | 主题 | 笔记 |
| --- | --- | --- | --- |
| 01 | Introduction | LangChain 的诞生、定位与课程概览 | [查看](./notebook/01-intro.md) |
| 02 | Models, Prompts and Output Parsers | 模型、提示与输出解析器 | 整理中 |
| 03 | Memory | 对话记忆与状态管理 | 整理中 |
| 04 | Chains | 链式组合与流程编排 | 整理中 |
| 05 | Question and Answer | 基于文档的问答系统 | 整理中 |
| 06 | Evaluation | LLM 应用评估 | 整理中 |
| 07 | Agents | 智能代理与工具调用 | 整理中 |
| 08 | Conclusion | 课程总结与延伸方向 | 整理中 |

## 仓库结构

```text
.
├── README.md
└── notebook
    └── 01-intro.md
```

## 推荐学习方式

1. 先观看课程视频，建立对 LangChain 模块的整体认识。
2. 阅读本仓库对应章节笔记，梳理关键概念与代码逻辑。
3. 跟着课程示例动手改参数、换提示词、替换数据源。
4. 最后尝试组合 Memory、Chains、QA 和 Agent，完成一个小型 LLM 应用。

## 课程资源

- DeepLearning.AI 原课程：[LangChain for LLM Application Development](https://learn.deeplearning.ai/langchain/lesson/1/introduction)
- 宝玉老师中文翻译视频：[《使用 LangChain 开发基于 LLM 的应用程序》](https://www.youtube.com/playlist?list=PLiuLMb-dLdWIYYBF3k5JI_6Od593EIuEG)
- LangChain 官网：[langchain.com](https://www.langchain.com/)

## 参考与致谢

感谢 DeepLearning.AI、LangChain 社区以及 DataWhale 社区在大模型应用开发教程与中文内容整理方面的贡献。

如果这份笔记对你有帮助，欢迎 Star 支持，也欢迎一起补充后续章节内容。
