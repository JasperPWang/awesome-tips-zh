# 如何在论文中书写数学公式？ (How to write math in a paper?)

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1643118681960923137](https://twitter.com/jbhuang0604/status/1643118681960923137)

---

如何在论文中书写数学公式？

数学公式能够极其精准凝练地传达你的思想。但如何书写才能让它们清晰易懂？🤔  
分享一些高层次的规范与技巧。🧵

---

### 1. 让公式具有可读性 (Make it readable)

数学写作是自然语言与数学语言的有机融合。它本身应当像英语句子一样流畅可读。  
独立行公式本质上是句子的一部分，公式末尾必须有正确的标点符号（句号或逗号）。

---

### 2. 遵循优雅的排版风格 (Follow good style)

- 公式中的纯英文单词：必须使用 `\mathrm{}`（如 `\mathrm{min}`），否则字母间距会按变量乘积排版。
- 转置符号：使用 `^\top` 或 `^{\intercal}`，避免直接使用大写字母 `^T`。
- 大括号与括号：使用 `\left(` 与 `\right)` 自动匹配内容高度。

---

### 3. 公式中的变量必须在正文立即交代 (Define variables immediately)

永远不要抛出一个复杂的公式后就直接跳过。  
紧跟其后使用：“where $x$ denotes ..., and $\sigma(\cdot)$ represents ...”逐一解释每个符号的物理含义。
