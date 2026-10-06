# How to cite papers? / 如何在学术论文中规范引用文献？

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1672342931473137664](https://twitter.com/jbhuang0604/status/1672342931473137664)

---

How to cite papers?
Citing papers properly
👉 gives credit where credit's due,
👉 provides supporting evidence of your claim, and
👉 presents an organized view of related work.
Sharing some tips I found useful. 🧵

如何规范引用学术论文？
妥善规范地引用文献：
👉 给予原作者应有的学术认可与尊重，
👉 为你提出的主张提供坚实的证据支撑，
👉 呈现出条理清晰的相关工作学术全景。
分享一些我认为非常实用的经验。🧵

---

*Parenthetical citations*
"Parenthetical": removing the citations, your sentences should still make sense.
When writing the related work, focus on the STORY and cite relevant papers along the way.
This provides an organized structure of how individual papers are connected.

*括号型引用 (Parenthetical citations)*
“括号型”引用：即如果删掉括号里的文献引用序号，整个句子在语法和语意上依然完全通顺独立。
在撰写相关工作时，把重心放在**学术叙事的主线故事（STORY）**上，并在叙述过程中顺带引用关联文献。
这能清晰展现出各篇论文之间是如何相互承接与关联的。

---

*Narrative citations*
This style often starts with authors' name in your sentence.
Examples: A et al. propose X. B et al. explore Y.
Pro: Useful if you want to highlight a particular work.
Con: Easily leads to a poorly written "laundry list".

*叙述型引用 (Narrative citations)*
这种风格通常直接以作者名字作为句子的主语。
例如：“A 等人提出了 X 方法；B 等人探索了 Y 路径。”
优点：当你需要重点突出某项里程碑工作时非常有效。
缺点：极易沦为机械罗列的“流水账清单（Laundry list）”。

---

*Grouping citations*
Avoid adding a looong list of citations without meaningful grouping.
❌ Recent work extends X to improve speed, quality, and memory efficiency [1, 2, 3, 4].
✅ Recent work extends X to improve speed [1], quality [2, 3], and memory efficiency [4].

*分组归类引用 (Grouping citations)*
避免在句末毫无逻辑地堆砌一长串未经分类的文献引用。
❌ 近期的工作对 X 进行了扩展，提升了速度、质量和显存利用率 [1, 2, 3, 4]。
✅ 近期的工作对 X 进行了扩展，分别提升了运行速度 [1]、生成质量 [2, 3] 以及显存利用率 [4]。

---

*Repetitive citations*
It's okay to cite the papers whenever appropriate, e.g., citing methods/datasets in your tables.
No one can remember all these acronyms. 🥱

*适度重复引用 (Repetitive citations)*
只要场景合适，在多处重复引用同一篇文献完全没问题（例如在表格的方法名和数据集名称旁边再次附上引用）。
没有读者能记住所有生僻的模型缩写。🥱

---

*Broad citations*
If possible, cite relevant papers more broadly. Giving others credit does not hurt yours.
Live view of authors finding their work is not cited in your paper:

*广泛客观地引用 (Broad citations)*
如果可能，尽量更加广泛全面地引用相关文献。大方给予同行认可，丝毫不会减损你自己的工作价值。
想想同行在读你论文时发现自己的工作居然没被引用时的崩溃表情吧！

---

*BibTeX formatting (conference/Journal)*
Never trust BibTeX downloaded from Google Scholar.
They suck!
Manually correct those entries.
conference 👉 inproceedings
journal 👉 article

*BibTeX 格式校验 (conference/Journal)*
永远不要盲目信任直接从 Google Scholar 导出的 BibTeX 项。
它们的格式往往非常糟糕！
务必手动检查校正这些条目：
会议论文 👉 @inproceedings
期刊论文 👉 @article

---

*BibTeX formatting (label)*
I find the style of labels
<FirstAuthorLastName><Year><FirstWord> easy to use.
Never use the BibTeX label from dblp.
They suck!
You will have a hard time knowing which papers you are citing. 🥴

*BibTeX 引用键命名规则 (label)*
我发现采用 `<一作姓氏><年份><标题首词>` 的命名风格最为直观好用。
尽量不要直接用 DBLP 导出的随机无意义引用键（如 DBLP:conf/cvpr/Huang...）。
它们非常难记，你在写作时会痛苦地根本想不起自己引的是哪篇。🥴

---

*BibTeX formatting (macros)*
BibTeX offers macros to help standardize your citations.
Use them for frequently cited conferences/journals to cite them consistently throughout your paper.

*使用宏定义保持期刊会议名称一致 (macros)*
BibTeX 支持使用宏（Macros）来标准化引用字符串。
为你经常引用的顶级会议和权威期刊设置统一宏变量，确保整篇论文的参考文献格式绝对统一。

---

*BibTeX formatting (capital letters)*
BibTeX is case-sensitive. Be cautious when entering author names, titles, and journal names.
Use curly braces {} to preserve capitalization when needed.

*用花括号保护专有名词大小写 (capital letters)*
BibTeX 默认会自动将标题中的大写字母转为小写。
对于模型缩写、专有名词、地名等，务必用花括号 `{}` 保护起来（例如 `{GAN}`、`{BERT}`），以防大小写丢失。
