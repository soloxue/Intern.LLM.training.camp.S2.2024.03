## 基础作业 (结营必做)

### 使用 InternLM2-Chat-1.8B 模型生成 300 字的小故事（需截图）
- 生成了一个300字的英文故事：
<img width="950" alt="course 2 homework 01" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/9790c7cc-948c-4c90-b88c-955edc1e12a1">

- 再生成了一个中文故事：
<img width="656" alt="course 2 homework 02" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/a1206bc1-860a-4716-8aff-6940c916fd43">



## 进阶作业 (优秀学员必做)

### 熟悉 huggingface 下载功能，使用 huggingface_hub python 包，下载 InternLM2-Chat-7B 的 config.json 文件到本地（需截图下载过程）

### 完成 浦语·灵笔2 的 图文创作 及 视觉问答 部署（需截图）

### 完成 Lagent 工具调用 数据分析 Demo 部署（需截图）
升级到30%的GPU，然后按照教程，完成了Lagent的启动和问答。我问了一个新问题：请解方程 X ^ 2 - 3X + 4 = 535 之中 X 的结果
<img width="869" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/6b428ce2-7a45-4f4f-9a78-95f49624f783">


### 八戒
一开始遇到无法访问的问题：
![tBr0OboFPF](https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/946b6a2d-f898-47ec-a974-f658a14990eb)

后来我换了个端口，就ok了。
streamlit run /root/Tutorial/helloworld/bajie_chat.py --server.address 127.0.0.1 --server.port 8088
ssh -CNg -L 8088:127.0.0.1:8088 root@ssh.intern-ai.org.cn -p 40186

<img width="834" alt="image" src="https://github.com/soloxue/Intern.LLM.training.camp.S2.2024.03/assets/36829965/2144231e-14d6-4c70-97b0-31128a0ed917">


