# 书生·浦语大模型实战培训营第三课笔记

## 课程概述

- **讲师**: 北辰，书生·浦语社区贡献者

- 内容

  :

  - RAG 基础知识介绍
  - 茴香豆产品简介
  - 使用茴香豆搭建 RAG 知识库实战
  - 视频地址：https://www.bilibili.com/video/BV1QA4m1F7t4/
  - 官方文档：https://github.com/InternLM/Tutorial/blob/camp2/huixiangdou/readme.md
  - 作业要求：https://github.com/InternLM/Tutorial/blob/camp2/huixiangdou/homework.md

## RAG 基础知识介绍

- **RAG** (Retrieval Augmented Generation) 是一种结合检索和生成的技术，用于增强大型语言模型的回答能力。

- 工作原理

  :

  - 索引知识源，如文档、网页等，将其编码为向量存入向量数据库。
  - 用户问题同样编码为向量，并在向量数据库中检索相关信息。
  - 结合检索结果和用户问题作为提示，生成最终回答。

**RAG技术概述**
<img width="1081" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/13d2dd2c-3ff4-4e00-81f9-099def5a9f12">

**RAG技术原理**
<img width="991" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/aff2a5cb-5c8d-4690-8831-ae08c0c8a422">

**向量数据库简介**
<img width="1063" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/8e71e83c-b29f-4b02-b439-c49cec82c2fd">

**RAG工作流程**
<img width="927" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/22de5455-4973-4603-8aaa-f175ec9fbd5c">

**RAG的发展进展**
<img width="1070" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/f124c271-4077-47a7-a705-ac19f4935c0e">

**RAG vs. Fine-Tuning**
<img width="1060" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/bf092500-7403-44a6-b642-541a9fadcd89">

**LLM优化方法比较：**
<img width="928" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/94ecbd0d-526c-4ab0-98a8-5f64ba2b7528">


**RAG小结**

<img width="935" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/030832d3-fa85-4033-b421-b3ef3ff805fb">



## 茴香豆产品简介

- **茴香豆** 是基于 RAG 技术构建的智能助理，能够快速有效地搭建知识领域助手。

- 核心特性

  :

  - 非参数化的知识更新，无需额外训练即可掌握新知识。
  - 适用于群聊场景，能有效管理消息流量，避免信息过载。
  - 提供完整的 Web、Android 和源代码，便于工业级应用和商业化。


**“茴香豆”简介**
<img width="1056" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/5302ca62-a7ac-4427-bd89-3fbe1e8a7a26">

**茴香豆的技术组件**
<img width="1096" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/67be5913-906d-44ee-b017-f8e8028198e4">

**茴香豆的工作流**
<img width="1019" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/68ee1a16-148c-4559-80ce-eab47018dace">


## 使用茴香豆搭建 RAG 知识库实战

- 环境配置

  :

  - 在 Intern Studio 上创建开发机并配置环境。
  - 下载并安装茴香豆及其依赖。

- 知识库构建

  :

  - 向量化知识语料和问题列表，创建向量数据库。
  - 定义接受和拒答问题列表，提高检索的相关性和准确性。

- 运行茴香豆

  :

  - 修改配置文件以指向正确的模型路径。
  - 运行茴香豆主程序，开始知识助手服务。

## 总结

通过本次课程，我们学习了 RAG 技术的基础知识和工作原理，了解了茴香豆产品的核心特性和优势。通过实战操作，我们掌握了如何使用茴香豆搭建一个 RAG 知识库，增强了大型语言模型的应用能力。




