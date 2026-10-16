---
title: Garau 等（2023）：单焦点注意问卷的开发与初始验证
description: Garau 等（2023）的 Development and Validation of a Novel Self-Report Measure of Monotropism in Autistic and Non-Autistic People 研究介绍：1,110人的 MQ 组均分、孤独谱系与 ADHD 分组结果，以及探索性八因素结构和测量局限。
aliases:
  - GarauEtAl2023
  - Garau et al. (2023)
  - 单焦点注意问卷的开发与验证
tags:
  - work
  - autism
  - attention
  - methodology
sources:
  - tests/2026-10-13/MonotropismQuestionnaire/NeuroXYZ-website-reference/mq-data.js
  - tests/2026-10-13/MonotropismQuestionnaire/NeuroXYZ-website-reference/mq-reference.js
  - tests/2026-10-13/MonotropismQuestionnaire/MQ_preprint_manuscript-tables-supplement.pdf
citation_apa: "Garau, V., Murray, A., Woods, R., Chown, N., Hallett, S., Murray, F., Wood, R., & Fletcher-Watson, S. (2023). Development and validation of a novel self-report measure of monotropism in autistic and non-autistic people: The Monotropism Questionnaire [Preprint]. https://osf.io/g4kc9/"
created: 2026-10-13
updated: 2026-10-13
---

# Garau 等（2023）：单焦点注意问卷的开发与初始验证

> [!infobox] Garau et al. (2023)
> **作者**：Valeria Garau、Aja Murray、Richard Woods、Nick Chown、Sonny Hallett、Fergus Murray、Rebecca Wood、Sue Fletcher-Watson
> **年份**：2023
> **类型**：预印本；问卷开发与初始验证研究
> **原题**：Development and Validation of a Novel Self-Report Measure of Monotropism in Autistic and Non-Autistic People: The Monotropism Questionnaire
> **原文**：[OSF 预印本](https://osf.io/g4kc9/)
> **项目资料**：[问卷、研究与开放数据](https://osf.io/wpx5g/)
> **问卷介绍**：[[MQ|单焦点注意问卷（MQ）]]

引用：Garau, V., Murray, A., Woods, R., Chown, N., Hallett, S., Murray, F., Wood, R., & Fletcher-Watson, S. (2023). *Development and validation of a novel self-report measure of monotropism in autistic and non-autistic people: The Monotropism Questionnaire* [Preprint]. https://osf.io/g4kc9/

Garau 等人的研究尝试把[[单焦点注意]]理论转化为可测量的自填问卷，并初步检验[[MQ]]的群体差异、与已有量表的关联及内部结构。47题由孤独谱系成年人结合生活经验和学术知识共同提出与修订；研究支持进一步探索这种认知风格，没有建立孤独谱系或 ADHD 诊断测试。

## 样本与分组方式

研究通过社交媒体、通讯和口耳相传招募参与者，排除不符合资格及少于40题有效作答者后，分析样本为1,110人，年龄16至78岁，平均39岁（SD＝12）。孤独谱系组756人，非孤独谱系组354人。

孤独谱系组包括临床诊断、自我认同和认为自己可能为孤独谱系者；非孤独谱系组包括回答“不是”或“不确定”者。ADHD 状态采用同样的合并规则，因此“ADHD 组”也不等于全部已经临床确诊。研究结果依赖这套分组方式，不能推广为所有诊断人群的常模。

## 各组整体均分

MQ 采用反向计分后的有效题平均分，范围1至5。预印本第8页和表1报告：

| 研究分组 | 人数 | MQ 均分 | 标准差（SD） |
|---|---:|---:|---:|
| 非孤独谱系组 | 354 | 3.19 | 0.578 |
| 孤独谱系组 | 756 | 4.15 | 0.347 |

孤独谱系组均分显著较高（Mann–Whitney 检验，p＜.001）。这是两组分布的比较，均分和标准差不能用作个人身份判定界线。

### 孤独谱系组内部的诊断／认同状态

作者在敏感性分析中进一步区分三组（均分与标准差见第8页，人数见表1）：

| 孤独谱系状态 | 人数 | MQ 均分 | 标准差（SD） |
|---|---:|---:|---:|
| 临床诊断 | 394 | 4.19 | 0.352 |
| 自我认同 | 204 | 4.19 | 0.319 |
| 认为自己可能为孤独谱系 | 158 | 4.01 | 0.329 |

临床诊断与自我认同组的均分差异不显著；“可能”组均分较低。这个结果不意味着问卷能裁定自我认同是否有效，也不意味着4.19是身份阈值。

### 孤独谱系与 ADHD 状态的联合分析

表2的回归模型纳入1,109人；另1人缺少 ADHD 状态。由表1的分组人数与表2四舍五入后的系数，可整理出以下模型拟合均分近似值：

| 研究分类组合 | 人数 | 模型拟合均分（约） |
|---|---:|---:|
| 非孤独谱系、非 ADHD | 253 | 3.03 |
| 非孤独谱系、ADHD | 100 | 3.59 |
| 孤独谱系、非 ADHD | 323 | 4.07 |
| 孤独谱系、ADHD | 433 | 4.20 |

这些近似值由截距3.03、孤独谱系系数1.04、ADHD 系数0.56和交互系数−0.43相加得到，不是从图2读取的精确观测均分。正文将 ADHD 系数写为0.55，表2为0.56；这里统一按表2计算，不赋予两位小数以上的精度。

孤独谱系状态与 ADHD 状态均关联较高 MQ 得分，但两者的关联并非简单相加：负交互项表示同时被归入两组者的得分增量小于纯加和预期，并不表示 ADHD 会使孤独谱系者的均分低于非 ADHD 孤独谱系者。模型解释约57.4%的分数方差；横断面关联不能确定因果关系。

## 探索性八因素结构

作者使用最小残差法提取因素、斜交旋转，允许维度相互关联。平行分析建议保留八因素，MAP 检验建议四因素，碎石图支持四至八因素；作者比较五个方案后，综合拟合指标、概念区分和解释性选择八因素。八因素方案的 RMSEA＝.035、TLI＝.935，但 BIC 更偏向七因素，说明因素数量并非所有方法一致支持。

下表依据补充表 S3 和补充材料，沿用原问卷题号；中文名称与本站测试显示一致。

| 因素／本站主题 | 原文维度名称 | 题号 | 内容 |
|---|---|---|---|
| 1．兴趣与热情 | Special interests | 44、43、25、45、28、39、40、14 | 深入、持续的兴趣投入与热情 |
| 2．反复思考与焦虑 | Rumination and anxiety | 37、42、22、36、47、46 | 反复思考事件、选择及不确定性 |
| 3．固定安排的需要 | Need for routines | 20、21 | 日常安排提供稳定感并帮助应对不确定性 |
| 4．环境对注意的影响 | Environmental impact on the attention tunnel | 4、2、3、16、5、26、1、18 | 打断、环境刺激与活动切换对专注的影响 |
| 5．专注时忽略其他需要 | Losing track of other factors when focusing on special interests | 32、33、12、10 | 专注时较少察觉身体需要、时间及其他事件 |
| 6．决策与任务投入困难 | Struggle with decision-making | 34、35、38、23 | 信息处理、选择以及投入无兴趣任务的困难 |
| 7．兴趣对焦虑的缓解 | Anxiety-reducing effect of special interests | 8、19、9 | 兴趣活动缓解焦虑并提高围绕兴趣交流的舒适感 |
| 8．社交互动中的体验 | Managing social interactions | 30、6、27、31、15、13 | 多人交流、目光接触、表达及对他人反应的预期 |

作者以绝对载荷大于.30为显著载荷标准。第26题同时载荷于因素4与8，因在因素4的载荷略高而归入因素4；第7、11、17、24、29、41题未强载荷于任何因素，排除在八因素结构之外。因此八个题组共41题，不能把八个主题均分直接平均，代替47题的整体均分。

这八个维度用于描述体验的不同方面，不是八种人格或诊断类型。高分的含义依赖题目内容，例如兴趣缓解焦虑与决策困难分别描述调节作用和困难，不能统一解释为“问题更严重”。各维度仍需独立样本和进一步结构验证。

## 信效度结果与局限

MQ 与 RAADS-14 的 Spearman 相关为.78，与 AQ-10 为.71；这支持与相关特征的聚合效度，但不能证明可替代诊断评估。内部一致性计算针对排除上述六题后的结构，报告总 omega＝.96、一般因素的层级 omega＝.81；这些整体指标不等于八个题组各自已经充分验证，也不等于重测信度。

样本约88%为白人，教育程度较高；研究自填方式可能限制伴随智力障碍者参与。研究未检验重测信度，本页所据研究也未验证本站中文译文。[[MQ|本站测试页介绍]]另外列出的八主题组均分，是网站按公开数据计算的描述性参考，来自不同于本研究1,110人分析的筛选样本，不能归为论文直接报告的结果。

研究稿的作者顺序与问卷文件的推荐引用不同：研究稿将 Aja Murray 列为第二作者，问卷推荐引用将其列在第七位。引用研究结论时应使用本页研究稿引用，引用问卷本身时使用[[MQ]]页面的问卷引用。

## Related

- [[单焦点注意]] — 被操作化测量的认知风格
- [[MQ]] — 问卷计分、本站测试与主题参考均分
- [[AQ]] — 研究使用其10题短版 AQ-10
- [[RAADS-R]] — 本研究使用 RAADS-14，不能混同于80题 RAADS-R
- [[相关测试]] — 测试与工具导航
