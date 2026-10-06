# How to draw an overview figure? / 如何绘制出色的方法流程总览图？

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1665738070002483201](https://twitter.com/jbhuang0604/status/1665738070002483201)

---

How to draw an overview figure?
Creating a clear and informative overview figure is crucial for visualizing HOW your method works.
But how? 🤔 Let's deep dive with 🐢

如何绘制方法流程总览图？
一张清晰、信息量丰富的方法总览图（Overview Figure），对于视觉化呈现你的算法究竟**如何运作（HOW it works）**至关重要。
但该如何画好？🤔 让我们一起深入探讨 🐢

---

*Choose the right level of abstraction*
Simplifying complex procedures helps improve clarity.
Ask yourself what the key message you want to convey. Don't overwhelm your readers with unnecessary details.

*选择恰到好处的抽象层级 (Choose abstraction level)*
简化复杂的流程有助于极大提升清晰度。
问问自己：你最想传递的核心信息是什么？千万不要用次要的技术琐碎细节把读者彻底淹没。

---

*Think in terms of computational graph*
Most methods process some INPUT with some COMPUTATION to produce some OUTPUT.
Visualize the flow with a "computational graph".
• Nodes: Computation
• Arrows: Dependency

*以计算图的视角思考架构 (Computational graph)*
绝大多数方法本质上都是：接收某些**输入（INPUT）**，经过一系列**计算模块（COMPUTATION）**，最终产生**输出（OUTPUT）**。
用“计算图（Computational Graph）”的逻辑来绘制数据流向：
• 节点模块：代表具体运算处理
• 箭头连线：代表依赖流转关系

---

*Use an example*
While your overview figure illustrates an *abstract* workflow, visualizing the intermediate variables/data with a *concrete* example makes it easier to understand.

*结合具体生动的图例 (Use an example)*
尽管总览图描绘的是抽象的算法流水线，但通过一个**具体的实例**来展示中间变量和特征数据流，会让整个流程百倍容易被理解。

---

*Follow the left-to-right direction*
Most languages read from left to right. ⏩⏩
Following this direction makes your figure "read" better.

*遵循自左向右的视觉流向 (Left-to-right direction)*
人类大多数语言都自左向右阅读。⏩⏩
顺应这一视觉阅读习惯，能让你的方法总览图具备行云流水般的“可读性”。

---

*Apply formatting strategically*
Be purposeful when you use formatting to highlight similarity, grouping, and contrast.
Make sure that you don't overdo it.

*有策略性地运用格式与色彩 (Apply formatting strategically)*
有明确目的地运用色彩和形状格式来强调：相似性、归类成组与对比反差。
切记凡事适可而止，绝不要过度堆砌花哨特效。

---

*Use proper font size*
Use consistent and clearly visible font size.
Don't make your overview figure a vision test. 🧐

*使用清晰合适的字号 (Use proper font size)*
保持字号大小前后一致且清晰可辨。
千万别让你的方法总览图变成一张折磨审稿人的视力测试表。🧐

---

*Use consistent formatting*
• Capitalize the first character for the first word?
• Capitalize the first character for every word?
• All caps?
• All lowercase?
Pick one and stick with it.

*保持文字排版规范一致 (Use consistent formatting)*
• 仅首字母大写（Sentence case）？
• 每个单词首字母均大写（Title Case）？
• 全部大写（ALL CAPS）？
• 全部小写？
选定一种规则，并在整张图中从始至终严格执行。

---

*Align everything*
Tiny bits of misalignment here and there distract your readers. (Look how annoying this looks like!)
Align the positions, spacing, and sizes.

*严格对齐所有视觉元素 (Align everything)*
各处微小的不对齐会极度分散读者的注意力。
严格对齐模块的相对位置、间距与边界尺寸。

---

*Use consistent styles*
Put the label
• below the image?
• above the image?
• within the image?
• to the right of the image?
Pick one and be consistent.

*标签风格统一 (Use consistent styles)*
图片下方的标签文字放在：
• 图像正下方？
• 图像正上方？
• 图像内部嵌字？
• 图像右侧？
选定一种布局方式，并保持通篇统一。

---

*Provide a roadmap for the paper*
Add labels for sections, equations, and figures to provide a roadmap for the paper.

*为整篇论文充当路线图 (Provide a roadmap)*
在流程图的各个模块旁边标注对应的正文章节（如 Sec. 3.2）和公式编号（如 Eq. 4），让总览图真正成为贯穿全篇技术细节的“导航路线图”。

---

*Be explicit about the dependency/computation*
When you merge two arrows, it's unclear what happened there.
Did you add/subtract/multiply/max/min/some other things? Or does the DO SOMETHING module take two separate inputs? Make it explicit!

*明确运算与依赖关系 (Be explicit)*
当两个箭头汇聚在一起时，往往让人费解此处到底发生了什么操作。
是相加？相减？矩阵乘法？取最大/最小值？还是后续模块接收了两个独立输入？务必明确标出！

---

*Avoid overloading the interface*
Here the DO SOMETHING module takes only ONE single input.
The example above obscures this process (it looks like the module takes two inputs simultaneously).

*避免混淆接口输入 (Avoid overloading interface)*
如果某个模块只接收一个输入，切勿画出容易让人误以为同时接收两个输入的歧义连线。让数据接口关系一清二楚。

---

*Summary*
I am not a designer, but these tips have helped me improve the clarity of my work.
Hope you will find them useful as well!
What are your favorite tips for creating an overview figure?

我虽然不是专业的平面设计师，但这些原则切实帮助我极大提升了论文图表的清晰度。
希望大家也能从中受益！
你在绘制架构图时最看重的心得是什么？
