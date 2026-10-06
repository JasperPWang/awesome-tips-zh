# How to write math in a paper? / 如何在学术论文中规范书写数学公式？

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1643118681960923137](https://twitter.com/jbhuang0604/status/1643118681960923137)

---

How to write math in a paper?
Math allows you to convey your idea precisely and concisely. But how to write them clearly? 🤔
Check out some high-level tips (with examples). 🧵

如何在学术论文中规范书写数学公式？
数学公式能让你极其精准、凝练地传达核心构想。但如何把数学公式写得清晰典雅？🤔
分享一些高层次的实用技巧与规范。🧵

---

*Make it readable*
Math writing blends both NATURAL and MATH languages. It should be *readable*.

*保证数学公式具有可读性 (Make it readable)*
数学写作是有机融合了**自然语言**与**符号语言**的复合表达。公式在语法上必须是“句子的一部分”，能够顺畅朗读通顺。

---

*Follow good style*
• texts in math: \mathrm for words
• transpose: use ^\top instead of ^T
• big parentheses: use \left and \right

*遵循良好的 LaTeX 排版规范 (Follow good style)*
• 公式中的文字词组：使用 `\mathrm{...}` 避免被斜体解析为变量乘积
• 转置符号：使用 `^\top` 而非生硬的 `^T`
• 大型括号：配合使用 `\left(` 与 `\right)` 保证括号自动随内部公式尺寸自适应拉伸

---

*Refer to notation together with their name*
Nothing is more frustrating than flipping pages to figure out what your notations mean.

*提及符号时附带其物理名称 (Refer with names)*
没有什么比读者不得不来回翻上三页去查某一个字母符号究竟代表什么更让人抓狂的了。在后文提及符号时，务必顺带说出其概念全称。

---

*Name every equation*
Your readers will thank you!

*为每一个核心方程命名 (Name every equation)*
给你的关键公式冠以明确的名称（例如：特征重建损失、几何一致性约束）。读者一定会为此感谢你！

---

*Write in a consistent format*
Reduce the mental load of your readers.

*保持符号风格绝对统一 (Write in a consistent format)*
向量用粗体小写、矩阵用粗体大写、集合用花体、标量用普通斜体。保持通篇严格一致，最大程度减少读者的认知负荷。

---

*Avoid redundant notation*
If you will not use them again, you don't need to introduce unnecessary notations.

*避免引入冗余符号 (Avoid redundant notation)*
如果某个中间变量在后文压根不再使用，就完全没有必要引入多余的符号定义。

---

*Define notation & macros*
Use descriptive names as your macros.
It helps avoid notation inconsistency in your paper.

*统一定义 LaTeX 宏命令 (Define notation & macros)*
为关键符号定义具备描述性的 LaTeX 宏命令（Macros）。这能从根源上避免全文符号前后冲突不一致。

---

*Simplify notation*
e.g., avoid parenthesized indexes

*简化符号下标 (Simplify notation)*
尽量避免层层嵌套的带括号下标（Parenthesized indexes），保持公式清爽精炼。

---

*Use negative numbers correctly*
The "-" is interpreted as a hyphen by your LaTeX editor. Use $-1$ instead.

*正确输入负号 (Use negative numbers correctly)*
在普通文本中直接输入的 `-` 会被 LaTeX 当成连字符（Hyphen）。在表示负数时，必须置于数学模式中书写成 `$-1$`，以保证渲染为标准负号。

---

*Resources/References*
Check out the excellent resources here!
robots.ox.ac.uk/~phst/Style/Te…
cs.dartmouth.edu/~wjarosz/writi…
ece.ucdavis.edu/~jowens/common…
people.csail.mit.edu/fredo/PUBLI/wr…

*学习资源与参考文献 (Resources)*
强烈推荐研读以下几篇经典的学术写作与排版规范指南：
• 牛津大学公式排版风格指南 (robots.ox.ac.uk/~phst/Style/TeXStyle.pdf)
• 达特茅斯学院写作规范 (cs.dartmouth.edu/~wjarosz/writing.html)
• UC Davis 常见排版错误总结 (ece.ucdavis.edu/~jowens/commonerrors.html)
• MIT 写作建议 (people.csail.mit.edu/fredo/PUBLI/writing.pdf)
