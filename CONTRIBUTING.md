# 共建指南

欢迎参与神经多样性 Wiki 共建。无需安装任何软件，可全程在浏览器完成。

## 目录

- [谁需要读这份指南](#谁需要读这份指南)
- [修改已有页面](#修改已有页面)
- [新建页面](#新建页面)
- [页面规范](#页面规范)
- [Markdown 速查](#markdown-速查)
- [注意事项](#注意事项)
- [FAQ](#faq)

## 谁需要读这份指南

- **内容共建者**：新建或编辑 wiki 页面
- **审校者**：修正错误、补充信息、改进表述
- **繁体协作者**：请前往 [ndwiki-hant](https://github.com/xyzhou0323/ndwiki-hant) 阅读 [COLLABORATING.md](https://github.com/xyzhou0323/ndwiki-hant/blob/master/COLLABORATING.md)

不需要编程背景。你只需要熟悉 Markdown 基本语法。

## 修改已有页面

1. 打开 [wiki 仓库文件列表](https://github.com/xyzhou0323/wiki)
2. 找到你要修改的 `.md` 文件，点进去
3. 点右上角笔形图标（**Edit this file**）
4. 在网页编辑器里修改内容
5. 改完后点 **Commit changes** → 选择 "Create a new branch" → 点 **Propose changes**
6. 等待维护者审核合并

## 新建页面

1. 打开 [wiki 仓库文件列表](https://github.com/xyzhou0323/wiki)
2. 进入对应文件夹：
   - `01-基础/` → 范式、术语、运动
   - `02-批判分析/` → 政治经济学、意识形态
   - `03-历史脉络/` → 历史脉络
   - `04-体验与实践/` → 研究、教育、干预
   - `05-诊断与现象/` → ASD、ADHD、述情障碍等
   - `06-测试/` → 量表与工具
   - `authors/` → 作者
   - `works/` → 参考文献
3. 点 **Add file** → **Create new file**
4. 复制 [TEMPLATE.md](TEMPLATE.md) 作为起点，填入内容
5. 点 **Commit changes** → 选择 "Create a new branch" → 点 **Propose changes**

## 页面规范

### 必需 Frontmatter

每个页面开头必须包含 YAML frontmatter：

```yaml
---
title: 页面标题
description: 一句话描述这个页面的内容，会显示在搜索结果和页面列表里
aliases: [英文名, 其他别名]
tags: [类型标签, 领域标签]
created: YYYY-MM-DD
updated: YYYY-MM-DD
---
```

### 命名规则

| 页面类型 | 格式 | 示例 |
|----------|------|------|
| 概念页 | 中文，无分隔符 | `神经多样性教育.md` |
| 作者页 | `FirstName-LastName.md` | `Robert-Chapman.md` |
| 著作页 | `AuthorYear.md` | `Chapman2023.md` |

- 文件名避免特殊符号 `# ? / \ : * " < > |`
- 英文概念保留英文原名，中文译名放入 `aliases`

### Wikilinks

使用 Obsidian wikilink 格式链接到其他 wiki 页面：

```markdown
[[页面名]]              → 链接到另一个 wiki 页面
[[页面名|显示文字]]     → 链接到页面，但显示不同文字
[[页面名#章节]]         → 链接到页面的特定章节
```

优先链接已有页面。链接到尚不存在的页面会自动创建"待写页面"，方便后续补充。

### 著作页额外要求

所有 `works/` 目录下的页面必须包含：

1. **Frontmatter `citation_apa` 字段**：
```yaml
citation_apa: "Author, A. A. (Year). Title. Journal, Volume(Issue), Pages. https://doi.org/xx"
```

2. **正文引用行**：标题下方紧跟 `引用：` 行，方便读者复制：
```markdown
# 标题

引用：Author, A. A. (Year). Title. Journal, Volume(Issue), Pages. https://doi.org/xx
```

### 标签

| 类型标签 | 说明 |
|----------|------|
| `concept` | 概念与批判分析 |
| `author` | 作者页 |
| `work` | 著作页 |
| `test` | 测试/量表 |

| 领域标签 | 说明 |
|----------|------|
| `neurodiversity` | 神经多样性 |
| `autism` | 孤独谱系 |
| `adhd` | ADHD |
| `disability` | 残障 |
| `capitalism` | 资本主义批判 |
| `education` | 教育 |

完整标签体系见主仓库 [wiki-schema.md](https://github.com/xyzhou0323/ndwiki-cn/blob/main/wiki-schema.md#标签体系)。

## Markdown 速查

```markdown
# 一级标题（页面标题）
## 二级标题
### 三级标题

**加粗文字**
*斜体文字*

- 无序列表
- 无序列表 2

1. 有序列表
2. 有序列表 2

> 引用文字

| 表格 | 列2 |
|-----|-----|
| 内容 | 内容 |

[[页面名]]          → 链接到另一个 Wiki 页面
[[页面名|显示文字]]  → 链接到页面，但显示不同文字
```

## 注意事项

- **文件名**：不要用特殊符号 `# ? / \ : * " < > |`
- **内部链接**：用 `[[页面标题]]`，不要用 `[页面标题](url)`
- **描述字段**：一句话概括页面内容，会显示在搜索结果和页面列表中
- 不确定放哪个文件夹？放根目录就行，维护者会帮你归类
- 一个页面聚焦一个主题，主题过大的页面应拆分为多个子页面
- 优先概括和总结，不要直接复制大段原文

## FAQ

### Q: 我不确定我的内容是否适合 Wiki？

A: 只要与神经多样性相关——概念解释、研究动态、人物介绍、文献摘要——都欢迎。不确定时直接提交 PR，维护者会反馈。

### Q: 可以用英文写页面吗？

A: 本 Wiki 以中文为主。英文概念和术语可在正文中保留原文，但页面正文应为中文。

### Q: 我想共建繁体中文页面？

A: 繁体内容请提交至 [ndwiki-hant](https://github.com/xyzhou0323/ndwiki-hant) 仓库，而非本仓库。详见 [COLLABORATING.md](https://github.com/xyzhou0323/ndwiki-hant/blob/master/COLLABORATING.md)。

### Q: 没有 Git 经验可以参与吗？

A: 可以！GitHub 网页版支持直接在浏览器中编辑文件。按照上述步骤操作即可，全程不需要命令行。
