# 神经多样性 Wiki

本仓库是[神经多样性 Wiki](https://github.com/xyzhou0323/ndwiki-cn) 的纯页面镜像——一个关于神经多样性（Neurodiversity）的中文知识库，**228 个页面**横跨核心概念、批判分析、历史脉络、研究实践、诊断现象、测试工具、作者与参考文献。用 [Obsidian](https://obsidian.md) 打开即可浏览。

> 本仓库仅包含 wiki 页面。完整项目（源文件 + 工具链 + 繁体子模块）见 [ndwiki-cn](https://github.com/xyzhou0323/ndwiki-cn)。

## 快速开始

**在线阅读**：[neuroxyz.cn/wiki](https://neuroxyz.cn/wiki/) 提供部署版本，无需安装任何软件。

**本地使用**：用 [Obsidian](https://obsidian.md) 打开本仓库。入口页面：

- **新读者** → [[阅读路线]]：四层递进导航，四个起点
- **查概念** → [[00-知识地图|知识地图]]：八部分完整索引

## 目录结构

```
01-基础/               # 范式、术语、运动（7 页）
02-批判分析/            # 政治经济学、意识形态（16 页）
03-历史脉络/            # "正常"的发明与抵抗（4 页）
04-体验与实践/          # 研究、教育、干预（12 页）
05-诊断与现象/          # ASD、ADHD、述情障碍等（6 页）
06-测试/               # 量表与工具（25 页）
authors/               # 84 位作者
works/                 # 73 部参考文献
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

无需安装任何软件，全程在浏览器完成。详见 [COLLABORATING.md](COLLABORATING.md)。

写作和翻译遵循[[术语翻译对照表]]的术语约定。

## 维护

本 Wiki 由 Claude Code 通过 `llm-wiki` 技能协助维护，每次操作记录于 [wiki-log.md](../wiki-log.md)。页面数量和链接状态定期自动更新。

## 致谢

初始内容由 NeuroXYZ 团队整理，感谢所有共建者的知识协作。

如果你新建或大幅编辑了某个页面，欢迎在页面底部署名，可链接到个人网站。格式见 [COLLABORATING.md#署名](COLLABORATING.md#署名)。
