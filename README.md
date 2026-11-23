<!--
  林子航 · GitHub 主页 README v4（去 AI 味版）
  放进 lin612320/lin612320 仓库根目录，命名 README.md
  抖音那条若是两个账号或昵称含「临安」，改这一行即可。
-->

<div align="center">

# 林子航

**做 AI 工作流、Agent 和 LLM 应用，也折腾 AIGC。**

[![GitHub](https://img.shields.io/badge/GitHub-lin612320-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lin612320)
[![Email](https://img.shields.io/badge/Email-1696480691%40qq.com-0A7CFF?style=flat-square&logo=maildotru&logoColor=white)](mailto:1696480691@qq.com)
[![抖音](https://img.shields.io/badge/抖音-春晓%20·%20临安-000000?style=flat-square&logo=tiktok&logoColor=white)](https://www.douyin.com/)

</div>

<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg">
    <img src="https://readme-typing-svg.demolab.com/?lines=ai%E5%B7%A5%E4%BD%9C%E6%B5%81%20%C2%B7%20subagent%20%E5%9B%A2%E9%98%9F%20%C2%B7%20%E8%AE%B0%E5%BF%86%E6%9E%B6%E6%9E%84;LLM%20%E5%BA%94%E7%94%A8%20%C2%B7%20RAG%20%C2%B7%20%E5%B7%A5%E5%85%B7%E8%B0%83%E7%94%A8;%E5%A4%9A%E6%A8%A1%E6%80%81%20%C2%B7%20%E9%9F%B3%E9%A2%91%20%C2%B7%20%E9%81%A5%E6%84%9F;AIGC%20%C2%B7%20%E8%A7%86%E9%A2%91%E7%94%9F%E6%88%90%E4%B8%8E%E5%89%AA%E8%BE%91&font=Fira+Code&center=true&width=560&height=42&color=2F81F7&vCenter=true&pause=1200&size=20" alt="typing" />
  </a>
</p>

<p align="center">
  <a href="#工作"><img src="https://img.shields.io/badge/%E5%B7%A5%E4%BD%9C-2F81F7?style=flat-square" /></a>
  <a href="#经历"><img src="https://img.shields.io/badge/%E7%BB%8F%E5%8E%86-1F6FEB?style=flat-square" /></a>
  <a href="#现在"><img src="https://img.shields.io/badge/%E7%8E%B0%E5%9C%A8-0A7CFF?style=flat-square" /></a>
  <a href="#栈"><img src="https://img.shields.io/badge/%E6%A0%88-4493F8?style=flat-square" /></a>
  <a href="#合作"><img src="https://img.shields.io/badge/%E5%90%88%E4%BD%9C-58A6FF?style=flat-square" /></a>
</p>

---

## ⚙️ 工作

**ai工作流搭建。** 装环境、建仓库，subagent团队划分，记忆分层设计，强化学习范式。

**人工智能理论。** 搜索求解、机器学习、深度学习、NLP、RNN、Transformer、llm蒸馏微调、扩散模型。

**基础ai全栈应用开发。** 前端后端数据库、桌面端打包、安装包、上架，从头拉到底。

**AIGC。** 抖音「春晓 · 临安」，做视频生成和剪辑。素材、脚本、字幕、成片。

**算法**。 不定期在力扣受虐。

**科研**。 掌握阅读论文的范式，走过一轮完整的从选题调研、提出idea、跑实验、到论文撰写的全流程。

---

## 🧩 经历

### ⚖️ 法元 Faron（律政工作台）

> <img src="https://img.shields.io/badge/Tauri%202-24C8DB?style=flat-square&logo=tauri&logoColor=white" /> <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" /> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" /> <img src="https://img.shields.io/badge/%E6%9C%AC%E5%9C%B0%E4%BC%98%E5%85%88-1F6FEB?style=flat-square" />

给法律场景做的本地工作台，Tauri 2 桌面端加一个 Electron 悬浮球，装上就能用，离线也能查。内置日美法库 152,940 条条文。

花力气最多的是文书智能体「小元」：接到委托先出计划，然后自己去调本地工具查真实法条，最后交一份 .docx 文书。引用是确定性自检的，不是让模型自己声明查过了。另外做过知识图谱规划加人工确认的自进化、多模态材料输入；赛事版把侧栏收到 8 个版块，法规查询改成整法浏览，双语、条文跳转、能打印。

0.8.0 有个还在方案阶段的东西，联邦配方进化。借联邦学习那套做法，本地只上传匿名的进化包，云端加权聚完签名下发。应用里的 /evolution 页能调 ε、K、轮次看收敛，白名单拦截和 K 匿名丢弃可以自己试。页面上明写了这不是强化学习，免得别人误会。

桌面端和移动端都出过包，走 GitHub Releases 发。

### 📄 论文阅读助手（春晓论文助手）

> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Vue%203-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" /> <img src="https://img.shields.io/badge/PyMuPDF%20%2F%20PDF.js-EC1C24?style=flat-square" /> <img src="https://img.shields.io/badge/DeepSeek-4D6BFE?style=flat-square" /> <img src="https://img.shields.io/badge/RAG%20%2B%20%E8%81%94%E7%BD%91%E6%A3%80%E7%B4%A2-2F81F7?style=flat-square" />

给本科生做论文用的，当时定的五个目标是找得到、下得全、看得懂、标得住、问得清。

- 从 arXiv、Semantic Scholar、DBLP、DOAJ、PMC 这些开放渠道拿官方 PDF，用 PyMuPDF 和 PDF.js 原生渲染，不走文本抽取，图表不会丢。
- 翻译时公式和代码不进去。先抠成占位符，翻完原样贴回，模型看不见也就改不动，不会出现公式被拆散、变量被翻成中文。
- 内嵌 RAG 加联网检索的 agent，回答带引用，点一下跳回原文位置。还有锚点批注、词级对照、顶会检索。
- 模型分档用。翻译、术语这些走 flash，全文精读才落到 pro，按每月精读 10 篇加泛读 15 篇算，一个月五块到三十块。

### 🎤 音频克隆 + QQ bot部署

> <img src="https://img.shields.io/badge/NapCat%20%2F%20OneBot%20v11-12B886?style=flat-square" /> <img src="https://img.shields.io/badge/Demucs-8957E5?style=flat-square" /> <img src="https://img.shields.io/badge/RVC-FF6B6B?style=flat-square" /> <img src="https://img.shields.io/badge/%E7%BA%AF%E4%BA%91%E7%AB%AF%E6%8E%A8%E7%90%86-1F6FEB?style=flat-square" />

群里 @ 机器人，让它用某个音色唱一首歌，它把歌唱完发回群里。

链路是 NapCat（OneBot v11）收消息，先用正则解析「用 X 的音色唱 Y」，兜不住才叫 LLM，省点钱；查缓存，命中就直接发；先回一句收到，再走云端：取音频、Demucs 分出人声、RVC 换音色、去静音、响度归一、转 mp3。整首 40 秒到 2 分钟，缓存命中 0 秒。本机不用显卡，训练在云端跑一次就够。

### 🛰️ 遥感多模态大模型

> <img src="https://img.shields.io/badge/VLM-2AA7BB?style=flat-square" /> <img src="https://img.shields.io/badge/%E9%81%A5%E6%84%9F%E5%9F%BA%E7%A1%80%E6%A8%A1%E5%9E%8B-0B4F6C?style=flat-square" /> <img src="https://img.shields.io/badge/%E6%96%87%E7%8C%AE%E7%B2%BE%E8%AF%BB%2020%2B-1B7A8F?style=flat-square" />

把遥感这块的多模态文献读了一遍，整理成能检索的笔记库。从 GeoChat、SkySense、EarthDial、GeoCLIP、VRSBench、DiffusionSat、SpectralGPT，到后面的 RS-EoT、GeoMMBench、GeoSolver、RSICCLLM、GeoLLaVA-8k、DisasterM3、CHOICE、Moonstone，二十多篇。

每篇固定记几样：训练目标、指令数据怎么造、评测用什么口径，配中文摘要和全文翻译，最后汇成信息表，再做个方向汇报。主要想知道这些模型是哪一层真解决了问题，哪一层只是换了种说法。

相关工作：RGB图像和osm数据的特征级与决策级融合。

### 🔊 音频多标签识别

> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/Spectrogram-FFB000?style=flat-square" /> <img src="https://img.shields.io/badge/multi--label-8957E5?style=flat-square" />

深度学习的一条完整链路，从原始音频到频谱图再到神经网络，输出多标签。

文件先处理，解码、重采样、规整声道和时长，坏文件和太短的先剔掉。不同来源的采样率和响度本来就不统一，归一化放太晚，模型学到的会是设备差异，不是声音本身。

然后按固定窗长切片，长音频不整段进网络，短片段补齐或者丢掉。切片要留重叠，不然要识别的事件正好卡在边界，就被劈成两半了。

接着把波形转成频谱图，时间-频率的二维表示，听的问题变成看的问题，交给视觉那套网络处理。窗长和频谱参数决定模型能看见多短的事件。

输出是多标签，不是挑一个最像的。类别、风格、地区可以同时成立，每个标签单独判断，所以评估不能只看 top-1。

### 🗂️ 开源情报资料中心

> <img src="https://img.shields.io/badge/%E6%9C%AC%E5%9C%B0%E9%83%A8%E7%BD%B2-1F6FEB?style=flat-square" /> <img src="https://img.shields.io/badge/%E6%8E%88%E6%9D%83%E9%97%B8%E9%97%A8-2EA043?style=flat-square" /> <img src="https://img.shields.io/badge/%E4%B8%8D%E5%81%9A%E4%BA%BA%E8%84%B8%E8%AF%86%E5%88%AB-b3261e?style=flat-square" />

人物和机构资料的可检索归档系统。把聊天导出、PDF、Word、图片和获准公开的来源整理进一个库，每条资料能回溯出处，留人工复核环节，不自动下结论。

本地部署，默认只监听 127.0.0.1。开工前先过授权闸门：来源登记表和数据分类表填完、批下来，才允许导入真实数据。程序内置禁止名单，Facebook、Instagram、X、LinkedIn、WhatsApp、Telegram 这些平台在登记那一步就拒绝。不做人脸识别，图片指纹（SHA-256 加感知哈希）只用来识别重复文件，不是生物特征比对。

这类系统最容易做歪的地方是自动给结论，所以我只做到归档和检索，判不判断交给人。

### 🩻 胸部 X 光片多标签分类

> <img src="https://img.shields.io/badge/PyTorch%202.10-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/torchvision%20%E5%8E%9F%E7%94%9F-EE4C2C?style=flat-square" /> <img src="https://img.shields.io/badge/ConvNeXt%20%2F%20Swin-8957E5?style=flat-square" /> <img src="https://img.shields.io/badge/Macro--AUC-2EA043?style=flat-square" /> <img src="https://img.shields.io/badge/T4%C2%B7%E2%89%A4100ms-1F6FEB?style=flat-square" />

胸片多标签分类，一张片子上可以同时存在好几种异常征象，按 CheXpert 的 10 个类别做，主指标 Macro-AUC。

跑在单卡 T4 16GB 上，模型压缩前不超过 500 MB，单图端到端不超过 100 ms，并且只能用 torchvision 原生实现，timm 这类额外模型库带不进去。所以方案不是往大了堆，是在预算里挑组合：几个骨干做集成，用成员数和分辨率的取舍换延迟余量。

工程上手上没有 GPU，本地写代码、验逻辑，云 GPU 十分钟一轮试错，定稿的批量任务放到有卡的机器上跑，一次六到八个 run。数据归档下载没完成时没有中央目录，`zipfile` 打不开，写了个顺序解析 local file header 的脚本提前读，顺手全量普查了 2218 张测试图的 JPEG 头。

仓库私有，数据不外传，这里只写做法。

---

## 🕒 现在

在学 RL 的奖励设计与策略约束、LLM 蒸馏微调、扩散模型。在做 subagent 的团队工作模式和验收机制，还有记忆架构的分层与按需召回。

---

## 🧰 栈

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Vue](https://img.shields.io/badge/Vue%203-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-1F6FEB?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

<details>
<summary>📈 仓库数据</summary>
<br />

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=lin612320&show_icons=true&hide_border=true&theme=transparent&locale=cn&rank_icon=github" alt="stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lin612320&layout=compact&hide_border=true&theme=transparent&locale=cn" alt="top langs" />
</p>

</details>

---

## 🤝 合作

做 agent 和 LLM 的工程落地。

我能接的，是把一个业务流程做成 agent 产线，任务拆解、工具接入、记忆分层、失败兜底、验收标准这几块；或者 LLM 应用从零做到能装，检索、引用溯源、成本控制、桌面端和安装包；多模态数据的取数整理也算，遥感、文档、音频都做过。

邮件 1696480691@qq.com，或者直接开 issue。

<p align="center">
  <a href="mailto:1696480691@qq.com"><img src="https://img.shields.io/badge/%F0%9F%93%AE%20%E5%8F%91%E9%82%AE%E4%BB%B6-1696480691%40qq.com-0A7CFF?style=for-the-badge&logo=maildotru&logoColor=white" /></a>
  <a href="https://github.com/lin612320/lin612320/issues"><img src="https://img.shields.io/badge/%F0%9F%92%AC%20%E5%BC%80%20issue-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p align="center"><sub>因为相信，所以看见。</sub></p>
