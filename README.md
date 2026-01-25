# 🚀 大模型算法岗实习面经 | 包含 DeepSeek/Qwen 技术报告解析、手撕 PPO/RoPE/Transformer、RLHF 核心与八股文 | 持续更新中...


[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![DeepSeek](https://img.shields.io/badge/Focus-DeepSeek%2FRLHF-red)](README.md)

> **写在前面**：
> 本仓库记录了我（26届）在准备大模型算法岗实习过程中的核心笔记。
> 这里的每一个知识点都是我在面试美团、快手等大厂时被实际问到，或者在 DeepSeek/Qwen 技术报告中挖掘出的考点。
> 内容全部托管在飞书文档

## 📚 核心文档导航 (Document Navigation)

所有内容已整理为飞书文档，**点击下方链接即可查看**：[笔记链接](https://my.feishu.cn/wiki/Ipm5woCF1i28pPkFqtMcAhQyndh?from=from_copylink)


<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/4ca9cebc-49d6-4068-8f9d-6c21e4be8e74" width="260" />
      <br />
      <sub>目录</sub>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/b8e6b2a8-a944-4828-a800-9196ad0a77b1" width="260" />
      <br />
      <sub>目录</sub>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c785c30d-b7e6-44d3-8900-891da8ef8fb9" width="260" />
      <br />
      <sub>目录</sub>
    </td>
  </tr>
</table>



### 🔥 第一章：大模型基础与架构 (Architecture)
*在这个板块，我详细推导了面试中最爱考的底层细节。*
- [x] **[Transformer 核心架构与手撕 Multi-Head Attention](你的飞书链接)** `High Frequency`
- [x] **[位置编码详解：从绝对位置到 RoPE (旋转位置编码) 的推导](你的飞书链接)**
- [x] **[KV Cache 原理与显存优化计算](你的飞书链接)**

### ⚔️ 第二章：RLHF 与对齐算法 (Alignment)
*当前最火的板块，结合了 DeepSeek-V3/R1 的技术细节。*
- [x] **[RLHF 全流程：从 Reward Model 到 PPO 算法手撕](你的飞书链接)**
- [x] **[DPO (Direct Preference Optimization) vs PPO：核心公式推导与差异](你的飞书链接)**
- [x] **[Reward Hacking 详解：为什么模型会作弊？(含案例)](你的飞书链接)** ### 🔧 第三章：微调与实战 (Fine-tuning & Engineering)
- [x] **[LoRA/QLoRA 核心原理：为什么只训练线性层？rank 怎么选？](你的飞书链接)**
- [x] **[DeepSeek-V3 & Qwen 全系列技术报告精读笔记](你的飞书链接)**
- [x] **[大模型面试手撕代码 Top 20 (C++/Python)](你的飞书链接)**

---

## 🌟 为什么要做这个仓库？
现在的面经太杂，很多只是简单的问答。我希望从**原理推导**和**工程实践**两个角度，把知识点揉碎。
文档中包含了：
1.  **小白友好的白话解释**（如用“狗和骨头”解释 RLHF）。
2.  **面试官视角的追问预测**（比如问了 LoRA 必定会问矩阵秩的选择）。
3.  **核心代码的逐行注释**。

## 📅 更新日志 (Changelog)
- **2026-01-20**: 新增 DeepSeek-R1 技术报告对于强化学习部分的分析。
- **2026-01-16**: 整理美团/快手实习面试的高频 LeetCode 题解。
- **2026-01-14**: 完成手撕 Multi-Head Attention 代码注释版。

---

## 🤝 交流与贡献
如果你觉得这些笔记对你有帮助，请点亮右上角的 ⭐️ **Star**！
如有错误，欢迎在 Issue 中指出。
