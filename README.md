# 👋 你好，我是 VanGong

<p align="center">
  <img src="https://img.shields.io/badge/Location-北京-red?style=flat-square" />
  <img src="https://img.shields.io/badge/Role-AI%20开发工程师-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Agent%20%7C%20RAG%20%7C%20AIGC%20%7C%20影视创作-success?style=flat-square" />
  <a href="https://github.com/VanGong1999"><img src="https://img.shields.io/github/followers/VanGong1999?label=Followers&style=social" /></a>
</p>



| 维度 | 内容 |
|------|------|
| **身份** | AI 开发工程师  |
| **主线** | Production Agent · Multi-Agent · Skills / Tools · 企业交付与治理 |
| **垂直** | 短剧 / 长剧 IP 策划创作评估 · AI 视频分镜 · 内容聚合与报告 |
| **技术栈** | Python · FastAPI · React/TS · C++ · Java · AI · Docker |
| **模型与基建** | DeepSeek / 智谱等 LLM · RAG · vLLM / SGLang · Workflow / Graph · Prompt & Context 工程 |
| **在线站点** | [FDE 知识库](https://vangong1999.github.io/FDE/) · [Agent 面试手册](https://vangong1999.github.io/llm-agents-interview/) |
| **联系邮箱** | [gongfan1213@163.com](mailto:gongfan1213@163.com) |



---

## 📌 置顶 · juben（剧本创作 Agent 平台 / jubenagent）

<table>
<tr>
<td width="72%">

### [🎬 juben](https://github.com/VanGong1999/juben) 

**生产级多智能体短剧全流程创作系统**：Plan → Write → Evaluate → Ship。整合 **40+ 专业 AI Agents**，覆盖策划、创作、评估；支持故事大纲、情节点工作流、人物小传 / 关系、故事五元素、IP / 质量评估、批量剧本提示词与完整影视工作流；可对接飞书。

| 项 | 说明 |
|----|------|
| **定位** | 短剧 / 影视多智能体创作与评估平台（即 jubenagent） |
| **架构** | 前后端分离 · React 18 + TypeScript + Vite · FastAPI · Python 3.10+ |
| **能力** | Agent 调度 · SSE 流式交互 · 工作流编排 · 知识库 / 搜索 · LLM 连接池 |
| **关联仓** | [skills](https://github.com/VanGong1999/skills) 剧本知识库 · [screen-creative-skills](https://github.com/VanGong1999/screen-creative-skills) 影视 Skills |
| **Topics** | `multi-agent` · `agent-orchestration` · `agentic-workflow` · `agent-memory` |
| **License** | MIT |

</td>
<td width="28%" valign="top">

**一句话**：把短剧从策划到评估做成可编排的 Agent 流水线。

**适合**：制片 / 策划 / 编剧助手 · Agent 工程实践样本 · 影视 AIGC 落地参考

**技术关键词**：40+ Agents · SSE · Workflow · DeepSeek / 智谱

</td>
</tr>
</table>

---

## ⭐ 仓库

### 1. [screen-creative-skills](https://github.com/VanGong1999/screen-creative-skills) 

**影视剧本创作与评估 Skills 合集（v2.2）** —— 31+ 专业 Agent Skills，覆盖小说 / IP 筛选 → 题材提炼 → 大纲 / 情节点 → 人物小传与关系 → 剧本创作与优化 → 多维评估；兼容 **Claude Code / Cursor / Codex** 开放 Skills 格式。


---

### 2. [FDE](https://github.com/VanGong1999/FDE)  [在线阅读](https://vangong1999.github.io/FDE/)

**AI 前线部署工程师（Forward Deployed Engineer）中文知识库**：角色认知、Discover→Design→Deploy→Review 交付方法论、企业 AI 落地、面试通关、行业案例、约 **171** 个高频概念轨道（Token / RAG / Agent / Serving / MLOps / 安全与客户面等）。


---

### 3. [juben](https://github.com/VanGong1999/juben)  


---

### 4. [rss-aigc](https://github.com/VanGong1999/rss-aigc) 

**RSS 订阅 + AI 内容聚合平台**（Vibe-Coding 风格简易可落地）：多源聚合（Hacker News / GitHub / ArXiv 等）· AI 分类 / 总结 / 翻译 / 洞察 · 行业报告生成 · 飞书机器人定时推送与文档导出 · OPML / RSSHub · 全文抓取。


---

### 5. [llm-agents-interview](https://github.com/VanGong1999/llm-agents-interview)  [在线阅读](https://vangong1999.github.io/llm-agents-interview/)

**Agent Engineering Handbook**：从 LLM 基础到 Production Agent 的系统化知识库（非碎片收藏夹）。双支柱：`concepts/`（机制与边界）+ `engineering-experience/`（可复现坑与 playbook）。


---

### 6. [skills](https://github.com/VanGong1999/skills) 

**剧本知识库**：热门短剧剧本素材与拉片分析资料，服务影视创作 Skills / juben Agents 的语料与参考底座。与 `screen-creative-skills`、`juben` 交叉引用。

---

### 7. [ai-video-generation](https://github.com/VanGong1999/ai-video-generation) 

**AI Video Storyboard Platform** —— 无限画布 + React Flow，对标即梦 / Seedance 向的 **AI 视频自动生成工作台**：文生视频 · 图生视频 · 首尾帧 · 九宫格 · 创意 / 分镜对话 · 精细调控 · 批量生成；自动补齐八要素（主体、构图、光线、背景、动作、文字叠加、转场细节、音频）。

面向短视频 / MCN、独立创作者、广告提案、影视学生：解决分镜耗时、片段风格割裂、角色一致性、镜头语言表达难等问题。

---

### 8. [LLMuserprofile](https://github.com/VanGong1999/LLMuserprofile) 

**基于 LLM 的 AI 用户画像系统**（LangChain / LangGraph）：结构化 + 非结构化数据 → 语义标签、意图与偏好、自然语言查询画像。对比传统规则画像：从「行为是什么」到「为什么与意图」。含数据采集整合、画像加工、课程向完整架构说明。

---

### 9. [agent-skills-factory](https://github.com/VanGong1999/agent-skills-factory) 

**企业内网 Agent 应用工厂**：`agent.yaml` 声明式配置 + Skill 包 → Skill Compiler → RunSpec → 共享 Runner / Tool Gateway；权限、审计、限流、降级、会话轨迹。场景示例：合同审查、会议纪要、材料起草、剧本评估、AI 生 PPT 等。飞书集成，面向可治理的批量造 Agent。

---

### 10. [openwriting-skills](https://github.com/VanGong1999/openwriting-skills) 

**开放写作 Skills**：企业办公 / 商业文档 / 技术方案 / 合规审计；飞书办公套件（日历、审批、多维表格、考勤等）与项目跟踪报告自动生成。面向 OpenCode / Claude Code 自动化写作与「小龙虾」飞书工作流。



---



## 📊 GitHub 概览

<p align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=VanGong1999&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=VanGong1999&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=VanGong1999&theme=tokyonight&hide_border=true" />
</p>

---

## ☕ 支持与联系

如果这些仓库对你有帮助，欢迎 **Star**；也可用支付宝 / 微信打赏支持持续更新。加微信好友可交流 Agent / 影视 AIGC / FDE 落地；关注公众号获取更多 AI 动态。

| 支付宝打赏 | 微信打赏 | 添加微信好友 | 公众号 |
|:----------:|:--------:|:------------:|:------:|
| <img src="./pictures/支付宝收款.jpg" width="180" alt="支付宝收款" /> | <img src="./pictures/微信收款.jpg" width="180" alt="微信收款" /> | <img src="./pictures/微信好友.JPG" width="180" alt="微信好友" /> | <img src="./pictures/公众号.jpg" width="180" alt="公众号" /> |
| 支付宝扫码 | 微信扫码 | 扫码加好友 | 扫码关注 |

- **邮箱**：[gongfan1213@163.com](mailto:gongfan1213@163.com)
- **GitHub**：[VanGong1999](https://github.com/VanGong1999)
- **主推项目**：[juben · 剧本创作 Agent](https://github.com/VanGong1999/juben) · [screen-creative-skills](https://github.com/VanGong1999/screen-creative-skills) · [FDE](https://github.com/VanGong1999/FDE)

---

<p align="center">
  <sub>北京 · AI 开发 · Agent / Skills / 影视创作 · 开源交流欢迎邮件或微信</sub><br/>
  <sub>⭐ 感谢每一位 Star 与打赏支持</sub>
</p>
