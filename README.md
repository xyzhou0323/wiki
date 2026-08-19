# 神经多样性 Wiki

[本仓库]([GitHub - xyzhou0323/wiki · GitHub](https://github.com/xyzhou0323/wiki))是[神经多样性 Wiki](https://github.com/xyzhou0323/ndwiki-cn) 的纯页面镜像——一个关于神经多样性（Neurodiversity）的中文知识库，**273 个页面**横跨核心概念、批判分析、历史脉络、研究实践、诊断现象、测试工具、作者与参考文献。用 [Obsidian](https://obsidian.md) 打开即可浏览。

> 本仓库仅包含简体中文 wiki 页面。完整项目（源文件 + 工具链 + 繁体子模块）见 [ndwiki-cn](https://github.com/xyzhou0323/ndwiki-cn)。

## 快速开始

**在线阅读**：[neuroxyz.cn/wiki](https://neuroxyz.cn/wiki/) 提供部署版本，无需安装任何软件。

**本地使用**：用 [Obsidian](https://obsidian.md) 打开本仓库。入口页面：

- **新读者** → [[阅读路线]]：四层递进导航，四个起点
- **查概念** → [[00-知识地图|知识地图]]：八部分完整索引

## 目录结构

```
01-基础/               # 范式、术语、运动（7 页）
02-批判分析/            # 政治经济学、意识形态（18 页）
03-历史脉络/            # "正常"的发明与抵抗（6 页）
04-实践应用/            # 研究、教育、干预（13 页）
05-诊断与现象/          # ASD、ADHD、述情障碍等（8 页）
06-测试/               # 量表与工具（25 页）
authors/               # 105 位作者
works/                 # 85 部参考文献
00-知识地图.md          # 总导航
阅读路线.md             # 入门导航
```

## 繁体中文

繁体中文版位于独立仓库 **[ndwiki-hant](https://github.com/xyzhou0323/ndwiki-hant)**，使用 ISO 15924 脚本代码（`zh-hant` 涵盖台湾、香港、澳门等所有繁体使用者），不预设地区。

> 术语转换目前由 AI（OpenCC）自动完成，字形转换由机器处理，但词汇层面的选择尚未经过社群讨论——全部页面均待人工审校。繁体协作者请前往 [ndwiki-hant](https://github.com/xyzhou0323/ndwiki-hant) 阅读 [COLLABORATING.md](https://github.com/xyzhou0323/ndwiki-hant/blob/master/COLLABORATING.md) 了解完整审校流程。

| | 简体版 | 繁体版 |
|---|---|---|
| 路径 | `wiki/` | `wiki-zh-hant/` |
| 仓库 | [ndwiki-cn](https://github.com/xyzhou0323/ndwiki-cn) | [ndwiki-hant](https://github.com/xyzhou0323/ndwiki-hant) |
| 脚本 | zh-hans | zh-hant |
| 内容来源 | 作者原创 | OpenCC 转换 + 人工审校 |

每个繁体页面 frontmatter 自动包含 `zh-hans` 字段指向对应简体页面，简体页面包含 `zh-hant` 字段指向对应繁体页面，便于跨变体跳转。

## 参与共建

无需安装任何软件，全程可以在浏览器完成。页面格式与署名方式见 [COLLABORATING.md](COLLABORATING.md)，写作和翻译遵循[[术语翻译对照表]]的术语约定。

### 本仓库适合哪些贡献

本仓库是简体中文页面镜像，适合直接提交：

- 错别字、措辞、格式和失效链接修正；
- 已有页面的局部补充或事实纠正；
- 来源明确、不改变目录和标签体系的单页修改或新增。

如果修改在审阅过程中扩大为多个相互关联页面，维护者可能会请贡献者把它迁移到主仓库。原 PR 可以保留并链接新的主仓库 PR，已经完成的内容不需要重写。

### 专题级贡献请提交到主仓库

以下改动请从完整项目 [ndwiki-cn](https://github.com/xyzhou0323/ndwiki-cn) 提交：

- 一次新增或重构多个相互关联的页面；
- 批量新增文献页、作者页或原始资料；
- 建立完整专题或改变现有目录、页面边界和导航；
- 新增大量标签，或需要扩展 `wiki-schema.md`；
- 涉及医疗安全、自伤、自杀等需要重点来源复核的内容；
- 会引起大规模繁体同步的改动。

这类贡献属于 LLM Wiki 的“专题级摄入”。它不仅修改 Markdown 页面，还需要在主仓库同时完成：

1. 将原始资料归档到不可变的 `sources/`；
2. 用页面 frontmatter 的 `sources` 建立可追溯关系；
3. 更新 `wiki-purpose.md`、`wiki-schema.md`、全量知识地图和目录统计；
4. 写入 `wiki-log.md`，运行 lint 与 `llm-wiki sync`；
5. 简体复核后，再同步本页面镜像和繁体仓库。

页面数量不是唯一标准：只要需要批量来源归档、结构调整或跨仓库同步，就应从主仓库进入。若不确定，可以先提交草稿 PR 或 Issue，维护者会协助判断；已有页面内容也可以直接作为迁移基础。

## 维护

本 Wiki 由 LLM Wiki 工作流协助维护。完整项目中的原始资料、schema、操作日志和同步工具位于 [ndwiki-cn](https://github.com/xyzhou0323/ndwiki-cn)；本仓库只保存简体页面镜像。每次专题级操作记录于主仓库的 `wiki-log.md`，页面数量、链接状态和搜索索引由主仓库统一更新。

## 致谢

初始内容由 NeuroXYZ 整理，感谢所有共建者的知识协作。

如果你新建或大幅编辑了某个页面，欢迎在页面底部署名，可链接到个人网站。格式见 [COLLABORATING.md#署名](COLLABORATING.md#署名)。
