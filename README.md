# 🧭 DRL-Algorithm-Selection-Wizard | 深度强化学习选型交互指南

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen" alt="Status">
  <img src="https://img.shields.io/badge/Domain-Reinforcement%20Learning-blue" alt="Domain">
  <img src="https://img.shields.io/badge/Focus-Sim2Real%20%7C%20Robotics-orange" alt="Focus">
  <img src="https://img.shields.io/badge/License-MIT-purple" alt="License">
</p>

> 拒绝“玄学炼丹”与“盲目试错”！  
> 这是一份面向真实物理世界部署、硬件算力约束与复杂系统控制的**深度强化学习 (DRL) 算法交互式选型指南**。

## 🌟 项目初衷

在深度强化学习领域，从基础的 DQN 到 2026 年最前沿的 GRPO、DroQ，算法库日益庞大。然而，大多数开源资料仅停留在数学推导层面。当研究者真正面对**极度稀疏奖励的迷宫导航**、**无人机/无人车的多机协同**、或是需要部署在**算力极其受限的边缘端硬件（如 Jetson Nano）**时，往往陷入“不知道该用什么算法”的困境。

本项目旨在打破理论与工程落地的壁垒。通过构建一个**纯前端、无依赖、高交互**的决策体系，将 60 余款主流及前沿算法融入到真实的工程痛点决策流中。帮助开发者在 1 分钟内，根据系统的物理约束，精准定位最优算法解。

---

## ✨ 核心亮点

* 🌗 **丝滑动态分屏交互**：左侧提供上帝视角的**算法全景族谱拓扑树**，右侧提供沉浸式的**一问一答动态决策流**。
* 🧠 **海量前沿算法覆盖**：收录了 60+ 款硬核算法。不仅包含 PPO、SAC 等常青树，更全面覆盖了离线 RL (CQL, IQL)、多智能体 (MAPPO, HAPPO)、分布评估 (FQF)、以及最前沿的大模型/轻量化框架 (GRPO, DayDreamer, RMA)。
* 🛠️ **直击工程部署痛点**：选项设计完全脱胎于实战场景，涵盖：
  * **Sim2Real 零样本迁移**（物理参数突变如何处理？）
  * **边缘计算部署**（显存吃紧/无法在线交互怎么办？）
  * **稀疏反馈与冷启动**（寻路找不到终点怎么解决？）
* ⚡ **零部署成本**：纯 HTML + CSS + JS 实现，极客美学，无需安装任何环境，双击 `index.html` 即可在浏览器中丝滑运行。

---

## 📸 界面预览

<img width="1350" height="953" alt="QQ_1775531435440" src="https://github.com/user-attachments/assets/f1925f03-2f47-43dd-9c85-ce180927b469" />
<img width="1405" height="766" alt="QQ_1775531472108" src="https://github.com/user-attachments/assets/5d6fe039-0545-43a5-8586-d915070b9ba8" />

---

## 🗺️ 覆盖的算法生态体系

本指南深度拆解并结构化了以下七大领域的算法：

1. **无模型离散控制 (Discrete Value-Based)**: Double DQN, Rainbow, C51, IQN, FQF...
2. **无模型连续控制 (Continuous Actor-Critic)**: PPO, GRPO, SAC, TD3, DroQ, REDQ...
3. **离线强化学习 (Offline RL)**: CQL, TD3+BC, IQL, Decision Transformer...
4. **多智能体协同 (MARL)**: MAPPO, HAPPO, QMIX, QPLEX, MADDPG...
5. **稀疏探索与动机 (Sparse Exploration)**: HER, ICM, RND, Go-Explore...
6. **世界模型 (World Models)**: Dreamer 系列, DayDreamer, MuZero...
7. **元学习与物理适应 (Meta-RL / Sim2Real)**: MAML, RMA, Domain Randomization...

---

---

## 🤝 参与贡献与交流

强化学习的发展日新月异，一个人的认知始终有限。如果本手册遗漏了您心目中的 SOTA 算法，或者决策流逻辑有待商榷，非常欢迎提交 **Pull Request** 或开启 **Issue** 进行讨论！

如果你觉得这个项目拯救了你在 RL 炼丹路上的掉发危机，或者在面试和开题时为你提供了清晰的思路，**求点一个 ⭐ Star 鼓励一下！**

📧 **交流反馈邮箱**: 2559906288@qq.com

---
