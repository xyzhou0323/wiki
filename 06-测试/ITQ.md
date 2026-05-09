---
title: ITQ
description: 国际创伤问卷——基于 ICD-11 标准评估 PTSD 与 CPTSD 症状的自填工具
aliases: [ITQ 国际创伤问卷, 国际创伤问卷, International Trauma Questionnaire]
tags: [test, trauma, PTSD, CPTSD, neurodiversity]
created: 2026-05-08
updated: 2026-05-09
---

# ITQ 国际创伤问卷

**ITQ**（International Trauma Questionnaire）是一份基于世界卫生组织 **ICD-11** 标准设计的自评问卷，用于评估**创伤后应激障碍**（PTSD）和**复合型创伤后应激障碍**（CPTSD）的症状表现。

> **本站测试**：[ITQ 国际创伤问卷](https://neuroxyz.cn/tests/itq.html)

## 测试结构

- **18题（12症状+6功能）**，约5分钟完成
- 基于 ICD-11 的诊断框架
- 评估 PTSD 三大症状群（再体验、回避、威胁感）以及 CPTSD 的附加症状群（情绪失调、负面自我概念、人际关系困难）

### 评分方式

采用 **5 点李克特量表**，每题 0-4 分：

| 分值 | 标签 |
|------|------|
| 0 | 完全没有 |
| 1 | 有少许 |
| 2 | 中等 |
| 3 | 相当多 |
| 4 | 极度 |

### 测试前信息收集

测试开始时需选择创伤经历的发生时间（6个选项）：
- 少于6个月前
- 6至12个月前
- 1至5年前
- 5至10年前
- 10至20年前
- 多于20年前

### 维度分数范围

| 维度 | 缩写 | 题数 | 分数范围 |
|------|------|------|----------|
| 再体验 | Re | 2 | 0-8 |
| 回避 | Av | 2 | 0-8 |
| 威胁感 | Th | 2 | 0-8 |
| PTSD 总分 | PTSD_Total | 6 | 0-24 |
| PTSD 功能受损 | PTSD_FI | 3 | 0-12 |
| 情绪失调 | AD | 2 | 0-8 |
| 负面自我概念 | NSC | 2 | 0-8 |
| 人际关系困难 | DR | 2 | 0-8 |
| DSO 总分 | DSO_Total | 6 | 0-24 |
| DSO 功能受损 | DSO_FI | 3 | 0-12 |

## 结果解读

### 诊断逻辑

ITQ 基于 ICD-11 的诊断算法：

**PTSD 核心标准：**
- 再体验 (Re)：至少 1 项 ≥ 2 分
- 回避 (Av)：至少 1 项 ≥ 2 分
- 威胁感 (Th)：至少 1 项 ≥ 2 分
- 功能受损 (PTSD_FI)：3 项中至少 1 项 ≥ 2 分
- PTSD 诊断：上述四项全部满足

**DSO（自我组织干扰）标准：**
- 情绪失调 (AD)：至少 1 项 ≥ 2 分
- 负面自我概念 (NSC)：至少 1 项 ≥ 2 分
- 人际关系困难 (DR)：至少 1 项 ≥ 2 分
- 功能受损 (DSO_FI)：3 项中至少 1 项 ≥ 2 分
- DSO 全部满足：上述四项全部满足

**最终判定：**
| 条件 | 结果 |
|------|------|
| PTSD + DSO 均满足 | CPTSD（复合型创伤后应激障碍） |
| 仅 PTSD 满足 | PTSD（创伤后应激障碍） |
| 均不满足 | 无显著创伤相关障碍 |

> **重要提示：** PTSD 和 CPTSD 的诊断标准是基于特定症状组合和功能受损的存在，而不仅仅是总分。若症状仅集中在部分群组而非分布于所有必要领域，即使严重程度评分较高仍无法满足诊断标准。

### 严重程度分级

各维度分数基于 NovoPsych (2025) 创伤暴露人群常模进行百分位数计算和严重程度分级：

| 等级 | 百分位范围 |
|------|-----------|
| 极轻 (Minimal) | < 25th |
| 轻度 (Mild) | 25th - 50th |
| 中等 (Moderate) | 51st - 75th |
| 严重 (Severe) | 76th - 95th |
| 极重 (Very Severe) | > 95th |

结果以雷达图可视化六个症状维度（Re、Av、Th、AD、NSC、DR）的分数剖面。

## 开发者与版权

- **开发者**：Cloitre, Shevlin, Brewin 等人 (2018)
- **量表来源**：[traumameasuresglobal.com](https://www.traumameasuresglobal.com/)
- **中文翻译**：Dr. Grace W.K. Ho (2017) 提供，本站版本有少许字词和标点调整
- **版权声明**：ITQ 作为公共领域资源，可免费供所有相关方使用

## 参考文献

1. Cloitre, M., et al. (2018). The International Trauma Questionnaire: Development of a self-report measure of ICD-11 PTSD and Complex PTSD. *Acta Psychiatrica Scandinavica*.
2. Ho, G. W. K., et al. (2019). Translation and validation of the Chinese ICD-11 International Trauma Questionnaire (ITQ) for the assessment of posttraumatic stress disorder (PTSD) and complex PTSD (CPTSD). *European Journal of Psychotraumatology*.
3. Baker, S., et al. (2025). A Review of the Clinical Utility and Psychometric Properties of the ITQ. NovoPsych.

## PTSD 与 CPTSD 的关键区分

ICD-11 的一个重要进展是将 CPTSD 独立于 PTSD：

- **PTSD**：通常由单一创伤事件引发
- **CPTSD**：由长期、反复的创伤（如童年虐待、长期家庭暴力）引发，不仅包括 PTSD 症状，还伴有持久的人格功能改变

## 与神经多样性的关系

创伤与[[神经殊异]]的关系是多重的：

- 神经殊异个体（尤其是[[孤独谱系]]和 [[ADHD]] 群体）面临更高的创伤暴露风险，包括欺凌、社交排斥和歧视
- 神经殊异个体对创伤的反应可能与[[神经典型]]者不同——感官过敏可能加剧创伤反应，而不同的认知风格可能影响创伤加工
- 创伤症状（如解离、情感调节困难）有时与孤独谱系和 ADHD 特征重叠，导致两者难以区分

## 相关测试

- [[ITQ-CA]] — 适用于 7-17 岁儿童青少年的版本

## Related

- [[神经殊异]] — 创伤与神经殊异的交叉
- [[孤独谱系]] — 面临更高创伤暴露风险的神经殊异形式
- [[ADHD]] — 同样面临更高创伤暴露风险
- [[神经典型]] — 神经反应差异的参照
- [[ITQ-CA]] — 儿童青少年版本
