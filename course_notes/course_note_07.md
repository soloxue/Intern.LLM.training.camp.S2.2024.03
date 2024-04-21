# 书生大语言模型实战培训营第六次课程笔记

## 课程概述

- **讲师**: 曹茂松、刘卓鑫，OpenCompass 贡献者
- **内容**: OpenCompass 大模型评测实战
- **目标**: 掌握如何使用 OpenCompass 工具对大模型进行评测
- **视频地址**：https://www.bilibili.com/video/BV1Pm41127jU/
- **课程文档**：https://github.com/InternLM/Tutorial/blob/camp2/opencompass/readme.md
- 课程作业：https://github.com/InternLM/Tutorial/blob/camp2/opencompass/homework.md

## **课程内容**

### 1. 大模型评测的重要性

- **评测目的**: 为用户选择最适合的大模型提供参考，全面了解模型的优势和限制。
- **评测促进发展**: 指导和改进人机交互，规划模型发展，预防潜在风险。

<img width="809" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/1096af8c-fda9-4194-bd2d-724f5946c8b5">


大模型评测的挑战：

<img width="880" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/be4abd8b-fb9b-481b-9a01-16b07248a0e4">

### 2. OpenCompass 评测体系

- **介绍**: OpenCompass 是一个用于评测大型语言模型的工具，支持多种模型和数据集。

OpenCompass体系发展历程：

<img width="852" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/ce427671-ee8b-467f-9546-2acac033961c">


如何评测LLM：

<img width="914" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/fd1f3634-2b04-46dc-9966-0a881d3503a1">



- **特点**: 结合客观评测与主观评测，全面评估模型性能。

主观节后结合客观

<img width="914" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/e752b692-31a9-4ea6-8d1d-946283b9566a">


提示词工程：

<img width="952" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/36dfe1aa-af41-445c-a6fd-b771b8ed9cfa">

<img width="920" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/07b986d6-d8df-4fea-8d35-201d6befc4cd">

长文本测试（大海捞针）

<img width="939" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/c12cf0be-ced3-44fe-a8c7-ad983d79bb81">




### 3. 评测流程

- **配置**: 选择模型和数据集，设置评估策略。
- **推理**: 模型产生输出。
- **评估**: 衡量输出与标准答案的匹配程度。
- **可视化**: 整理结果，生成报告。

### 4. 实战操作

- **环境配置**: 使用 `studio-conda` 命令创建评测环境。
- **数据准备**: 下载并解压数据集。
- **启动评测**: 使用 `run.py` 脚本启动评测过程。

### 5. 自定义数据集评测

- **方法**: 介绍如何自定义数据集进行评测。
- **步骤**: 包括配置文件的修改和评测命令的执行。


## 总结

本次课程详细介绍了大模型评测的意义、OpenCompass 评测工具的使用以及如何进行实战操作。通过学习，参与者能够理解评测对大模型发展的重要性，并掌握使用 OpenCompass 进行模型评测的方法。
