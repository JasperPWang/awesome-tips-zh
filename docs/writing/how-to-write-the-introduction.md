# How to write the Introduction? / 如何撰写论文引言？

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1638029709073166336](https://twitter.com/jbhuang0604/status/1638029709073166336)

---

How to write the Introduction?

As a junior student, writing the introduction of a research paper is arguably the most daunting part of paper writing. 😱

Here is a simple template I find useful:  
3 Figures 🖼️ + 5 Questions 🤔

如何撰写论文引言？

作为一名低年级研究生，撰写科研论文的引言（Introduction）可以说是整篇论文写作中最令人望而生畏的部分。😱

这里有一个我发现非常实用的模板：  
3 张图 🖼️ + 5 个问题 🤔

---

*🖼️ WHAT figure*

Start with the paper with a WHAT figure (known as the "teaser").  
This figure shows only two things.  
1⃣ Input  
2⃣ Output  
This helps the readers understand what your work is about. Here are some of my favorite examples.

*🖼️ WHAT 图（成果展示图）*

用一张“WHAT 图”（通常被称为首页图 / Teaser）开启你的论文。  
这张图只展示两样东西：  
1⃣ 输入 (Input)  
2⃣ 输出 (Output)  
这能帮助读者立刻理解你的工作到底是做什么的。以下是一些我最喜欢的经典范例。

---

WHAT Example 1:  
Mask R-CNN showcases its key results upfront without waiting until the result section.  
1⃣ Input: Single images  
2⃣ Output: Instance segmentation masks

WHAT 范例 1：  
Mask R-CNN 在首页直接展示其核心成果，而不需要等到后面的实验结果章节。  
1⃣ 输入：单张图像  
2⃣ 输出：实例分割掩码 (Instance segmentation masks)

---

WHAT Example 2:  
CycleGAN shows its ability to solve various unpaired image-to-image translation problems.  
1⃣ Input: Images from domain A  
2⃣ Output: Images from domain B

WHAT 范例 2：  
CycleGAN 展示其解决多种无配对图像到图像转换问题的强大能力。  
1⃣ 输入：来自域 A 的图像  
2⃣ 输出：来自域 B 的图像

---

WHAT Example 3:  
Obstruction removal paper (alex04072000.github.io/SOLD/) shows:  
1⃣ Input: Obstructed images (reflection, fence, raindrop)  
2⃣ Output: Clean images  
Since the images are aligned, we can use split frames to 1) save space and 2) highlight the contrast.

WHAT 范例 3：  
障碍物移除论文 (SOLD) 展示：  
1⃣ 输入：受阻图像（反射、栅栏、雨滴）  
2⃣ 输出：干净图像  
由于图像是对齐的，我们可以使用分屏对比（split frames）：1) 节省版面空间，2) 突出强烈的视觉对比。

---

*🖼️ WHY figure*

This figure provides the "motivation" for your work.  
The best WHY figure illustrates the existing work's core issue/problem with a concrete example.  
Here are some of my favorite examples.

*🖼️ WHY 图（动机阐释图）*

这张图为你的研究工作提供“动机 (Motivation)”。  
最好的 WHY 图能够通过一个**具体而鲜活的例子**，直观展现现有核心工作的根本症结或缺陷所在。  
以下是一些我最喜欢的范例。

---

WHY Example 1:  
The Shiftable Multiscale Transforms paper shows the NEED for translation invariance with a concrete example.  
(a) Input signal  
(b-d) Coefficients of wavelet representations.  
(e) Shifted the input signal by ONE sample  
(f-h) LOOK! Completely DIFFERENT coefficients

WHY 范例 1：  
Shiftable Multiscale Transforms 论文通过一个具体实例展现了对平移不变性（translation invariance）的迫切需求。  
(a) 输入信号  
(b-d) 小波表示系数  
(e) 将输入信号仅平移一个样本  
(f-h) 瞧！系数完全改变了！

---

WHY Example 2:  
The Relative Attributes work highlights the NEED for a more informative and intuitive description using relative attributes with concrete examples.

WHY 范例 2：  
Relative Attributes 工作通过具体实例，强调了使用相对属性（relative attributes）提供更直观、更丰富描述的必要性。

---

WHY Example 3:  
The Feature Pyramid Networks work shows multiple alternative design options (a-c) and their drawbacks. This helps motivate the NEED for their design of a fast & accurate model.

WHY 范例 3：  
Feature Pyramid Networks (FPN) 展示了多种备选设计方案 (a-c) 及其各自的固有缺陷。这有力地激发了他们设计一种兼具快速与高精度模型的必要性。

---

*🖼️ HOW figure*

This figure describes how your method works.  
Some tips:  
✅ Link all sections  
✅ Use consistent notations  
✅ Self-contained caption  
✅ Visualize the variables  
✅ Cascade of small units: "Input -> some processing -> Output" (think about computational graph).

*🖼️ HOW 图（方法架构图）*

这张图详细描述你的方法是如何运转的。  
几个实用技巧：  
✅ 与论文各章节紧密对应链接  
✅ 使用统一规范的数学符号  
✅ 自成一体、信息完整的说明文字（Self-contained caption）  
✅ 将变量进行可视化呈现  
✅ 级联的小处理单元：“输入 -> 某种处理 -> 输出”（类似于计算图的思想）。

---

HOW Example 1:  
The HyperReel paper (hyperreel.github.io) visualizes the four main algorithmic steps.  
Note the math notations, name, and detailed, self-contained figure caption.

HOW 范例 1：  
HyperReel 论文将四个主要算法步骤进行了清晰的可视化。  
注意其规范的数学符号命名以及详细完整的图表说明。

---

HOW Example 2:  
My video completion work back in my Ph.D. years shows how the processing steps in each iteration.

HOW 范例 2：  
我在博士期间发表的视频补全工作，清晰展示了每次迭代中的具体处理步骤。

---

HOW Example 3:  
The Robust Dynamic Radiance Fields paper (robust-dynrf.github.io) shows how all the math notations and variables connect with each other using this HOW figure. Note the descriptive figure caption.

HOW 范例 3：  
Robust Dynamic Radiance Fields 论文展示了所有数学符号与变量如何通过这张 HOW 图互相关联。注意其具有高度描述性的图注。

---

With the WHAT-WHY-HOW figures, we are now ready to answer the following five questions!  
🤔 What's the problem?  
🤔 What have others done?  
🤔 What's the gap?  
🤔 What have you done?  
🤔 What do you contribute?

有了 WHAT-WHY-HOW 这三张核心图，我们现在可以从容回答以下 5 个核心问题！  
🤔 问题是什么？  
🤔 别人做了什么？  
🤔 差距在哪里？  
🤔 你做了什么？  
🤔 你的贡献是什么？

---

*🤔 Q1: What's the problem?*  
✅ State clearly what problem you are addressing.  
✅ Tell the readers explicitly why they should care about the problem (e.g., applications).  
🖼️ Use your WHAT figure for visual references.

*🤔 问题 1：问题是什么？ (What's the problem?)*  
✅ 清晰阐明你要解决的核心问题到底是什么。  
✅ 明确告诉读者他们为什么要关心这个问题（例如：现实应用价值）。  
🖼️ 引用你的 **WHAT 图** 作为直观参考。

---

*🤔 Q2: What have others done?*  
✅ Describe what other solutions (SOTAs) are to your problem.  
✅ Usually follows a historical trajectory, e.g., classical geometric methods did X, learning-based methods did Y, and recent hybrid methods did Z.

*🤔 问题 2：别人做了什么？ (What have others done?)*  
✅ 描述当前解决该问题的代表性已有方案（SOTA）。  
✅ 通常遵循历史演进轨迹展开，例如：经典几何方法做了 X，基于深度学习的方法做了 Y，最近的混合方法做了 Z。

---

*🤔 Q3: What's the gap?*  
✅ Explain why all these existing solutions are NOT satisfactory (in some aspects). This is important as your work often addresses a specific gap/flaw/drawback of existing work.  
🖼️ Use the example in your WHY figure to illustrate the *gap*.

*🤔 问题 3：差距在哪里？ (What's the gap?)*  
✅ 解释为什么所有这些现有方案在某些方面是**不令人满意**的。这至关重要，因为你的工作正是针对现有工作的特定缺陷、短板或瓶颈而设计的。  
🖼️ 引用你的 **WHY 图** 中的具体实例来说明这个“差距（gap）”。

---

*🤔 Q4: What have you done?*  
✅ Add "In this paper, ..." at the beginning of this paragraph. It helps provide a clean separation of the past/current work.  
✅ Talk about a) Task, b) High-level idea, c) Evaluation  
🖼️ Use your HOW figure to ground your discussions.

*🤔 问题 4：你做了什么？ (What have you done?)*  
✅ 在该段开头明确加上：“In this paper, we ...（在本文中，我们……）”。这有助于将前人工作与本文工作进行清晰的切割。  
✅ 分三个维度展开：a) 任务 (Task), b) 高层核心思想 (High-level idea), c) 评测验证 (Evaluation)。  
🖼️ 引用你的 **HOW 图** 来锚定具体讨论。

---

*🤔 Q5: What do you contribute?*  
✅ Not everything you do is "novel" e.g., a large part of your work may build upon some existing methods. Thus, it is a good practice to explicitly state your contributions.  
✅ Make a list so that lazy reviewers can use them in their reviews 😜

*🤔 问题 5：你的贡献是什么？ (What do you contribute?)*  
✅ 并非你做的每件事都是全新原创的（例如大部分工作建立在现有方法之上）。因此，明确提炼列出你的核心学术贡献是非常良好的写作实践。  
✅ 使用项目符号列表（List），方便审稿人直接在审稿意见中引用！😜

---

In sum, the introduction section would look like this:  
🤔 What's the problem? (see 🖼️ WHAT figure)  
🤔 What have others done?  
🤔 What's the gap? (see 🖼️ WHY figure)  
🤔 What have you done? (see 🖼️ HOW figure)  
🤔 What do you contribute?  
Hope this helps!

总结起来，引言部分的完整框架如下：  
🤔 问题是什么？（参见 🖼️ WHAT 图）  
🤔 别人做了什么？  
🤔 差距在哪里？（参见 🖼️ WHY 图）  
🤔 你做了什么？（参见 🖼️ HOW 图）  
🤔 你的核心贡献是什么？  
希望对大家的论文写作有所启发！
