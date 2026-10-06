# How to write a paper that looks like a good one? / 如何让论文在视觉排版上一眼看起来就是一篇好论文？

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1437443017510621185](https://twitter.com/jbhuang0604/status/1437443017510621185)

---

How to write a paper that looks like a good one?
You worked super hard and did great research, but somehow the reviewer 2 just doesn't buy it. Why? 🤔
It's probably because your paper does not look like a good paper *visually*. 🙄
How? 👇👇👇
#AcademicTwitter

如何让论文看起来就像一篇好论文？
你付出了极大的努力，做出了扎实出色的科研，但审稿人 2 却无论如何不买账。为什么？🤔
很有可能是因为你的论文在“视觉排版”上看起来不像一篇顶尖的高质量论文。🙄
如何改善？请看以下建议 👇👇👇

---

*Figure 1: WHAT did you do?*
Nothing is more frustrating than not being able to figure out what the paper is about until page 5. 😠Show a TEASER figure on the very first page highlighting the inputs/outputs/key findings.

*图 1：你具体做了什么？ (Figure 1: WHAT)*
没有什么比读到第 5 页还完全搞不懂这篇论文到底在干什么更让人暴躁的了。😠 在论文首页最上方放一张极其亮眼的代表图（Teaser figure），直观高亮突出输入、输出和最核心的发现成果。

![Figure 1](https://pbs.twimg.com/tweet_video_thumb/E_LSz6IWYAUxdFo.jpg)

---

*Figure 2: WHY did you do it?*
Motivate and justify the key insights/ideas of your work. It is often helpful to illustrate this more clearly by
1) SIMPLIFYING with a toy example and
2) CONTEXTUALIZING with prior work.

*图 2：你为什么要做这件事？ (Figure 2: WHY)*
充分阐明你工作的核心洞见与研究动机。通常借助以下两种手段能解释得最透彻：
1) 通过简化的小示例（Toy example）化繁为简；
2) 结合已有工作的局限性进行鲜明对照。

![Figure 2](https://pbs.twimg.com/tweet_video_thumb/E_LS0YTWUAcarz9.jpg)

---

*Figure 3: HOW did you do it?*
Show an *overview* figure on how your method works. Label everything so that it provides a clear roadmap of the entire paper.

*图 3：你是如何做到的？ (Figure 3: HOW)*
展示一张详尽的方法总览图（Overview figure），解释算法架构如何运转。为各个模块标明公式与章节索引，为整篇论文提供清晰的技术路线图。

![Figure 3](https://pbs.twimg.com/tweet_video_thumb/E_LS03gWEAQLxuw.jpg)

---

*Move figures/tables to the top*
Add "[!t]" parameter to your figure/table so that LaTeX will try placing them on the top of the page. Why?
Figures/tables are much easier to understand than reading plain texts. Moving them to the top helps readers quickly understand your work.

*图表一律置顶 (Move figures/tables to top)*
在 LaTeX 的 figure 和 table 环境中添加 `[!t]` 参数，让系统优先将图表置于页面最顶端。为什么？
图表远比枯燥纯文本更直观易懂。将它们置于页顶有助于读者在快速翻阅时瞬间领悟核心信息。

![Figures to top](https://pbs.twimg.com/tweet_video_thumb/E_LS1VLX0AI121G.jpg)

---

*Self-contained figure/table caption*
Whatever you want to say for the figure/table, say them in the caption. It's annoying to find and match the corresponding texts describing the figure/table in your paper.
More on avoiding mental correspondence:
https://twitter.com/jbhuang0604/status/1279992087497314305

*图表说明文字必须完全自包含 (Self-contained caption)*
你想就这张图表表达的所有关键信息，直接在标题说明（Caption）里讲清楚！迫使读者在正文密密麻麻的段落里翻找对应解释非常折磨人。

![Self-contained](https://pbs.twimg.com/tweet_video_thumb/E_LS2BHWQAIvWtT.jpg)

---

*Concise notations*
Use SINGLE letters for your math notations. Examples:
• Color_j -> C_j
• Net -> F(\cdot)
All the other descriptions should be within \mathrm

*精炼的数学符号定义 (Concise notations)*
数学符号一律使用单个英文字母表示：
• Color_j ➡️ C_j
• Net ➡️ F(\cdot)
所有描述性词汇一律置于 `\mathrm{...}` 字体中。

![Concise notations](https://pbs.twimg.com/tweet_video_thumb/E_LS2h8WQAMUdLH.jpg)

---

*Short titles*
Add titles (e.g., using \paragraph) to your figure/table captions and the main texts. They make your paper more structured and organized and help your readers navigate the paper with ease.

*添加小标题 (Short titles)*
为图表标题说明和正文段落添加醒目的小标题（如使用 `\paragraph{...}`）。这能让整篇论文层次分明、井井有条，大幅提升读者的阅读体验。

![Short titles](https://pbs.twimg.com/tweet_video_thumb/E_LS3OPXEAEtS36.jpg)

---

*Clean table*
Follow simple design principles for making clean a table:
• no \line, use \toprule, \midrule, \bottomrule
• no vertical lines
• left align text
• center align numbers
• group and remove repetition with multirow/multicol

*整洁高雅的表格 (Clean table)*
遵循极简专业的表格排版规范：
• 抛弃普通 \hline，使用 booktabs 宏包的三线表规则
• 坚决不要任何竖线
• 文本左对齐，数值居中对齐
• 使用 multirow / multicol 合并重复信息

![Clean table](https://pbs.twimg.com/tweet_video_thumb/E_LS3ucXMAQeeyJ.jpg)

---

*Avoid empty spaces*
Fill the paper into full page limit. It gives your readers a sense of a POLISHED and not RUSHED paper.
More on Deep Paper Gestalt:
arxiv.org/abs/1812.08775

*避免空缺空白页 (Avoid empty spaces)*
将论文内容扎实写满到页数上限。这能让读者和审稿人立刻感受到这是一篇经过反复精雕细琢、而非仓促交差的成熟论文。
延伸阅读：论文排版完形心理学（Deep Paper Gestalt）：
https://arxiv.org/abs/1812.08775

---

*Summary*
Hope this helps! If your paper looks like a good paper, reads like a good paper, then it's probably a good paper.
Happy writing!
Any additional tips on making your papers look awesome?

希望这些技巧对大家有所启发！如果你的论文在视觉上看起来像一篇好论文，读起来也像一篇好论文，那它大概率就是一篇好论文。
祝大家写作顺利！
关于如何让论文脱颖而出，大家还有什么秘笈？

---

*Opps...*
Opps... I didn't mean "clean a table"... 😄

哎呀……我刚才口误说成了“擦干净桌子”……😄

![Opps](https://pbs.twimg.com/tweet_video_thumb/E_ME_WXWEAMMm7u.jpg)

---

*Example "What did you do?" figure*
The teaser should specify the input/output and applications that your work could enable.
Source:
pose-with-style.github.io

*示例：图 1 “你做了什么？”*
首图应清楚交代算法的输入、输出以及所能解锁的下游应用场景。
来源：
https://pose-with-style.github.io

---

*Example "Why did you do it?" figure*
Here they use a TOY example to highlight the key issue from PRIOR WORK (wavelet transforms), i.e., the coefficients of original signal and the shifted version change dramatically.
Source: Shiftable Multiscale Transforms '92

*示例：图 2 “为什么要做这件事？”*
这里作者使用了一个极简的小示例，鲜明揭示了以往工作（小波变换）中的核心硬伤：原始信号与其平移版本的系数发生了剧烈突变。
来源：Shiftable Multiscale Transforms '92

---

*Example "How did you do it?" figure*
This figure provides an overview of how the method work by connecting inputs and outputs and all the intermediate steps.
Source:
robust-cvd.github.io

*示例：图 3 “你是如何实现的？”*
总览图通过串联输入、输出以及所有中间步骤，为整套方法的运转提供了全局全景呈现。
来源：
https://robust-cvd.github.io
