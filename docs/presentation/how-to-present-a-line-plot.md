# How to present a line plot? / 如何在演讲中清晰讲解折线图？

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1506101759911116809](https://twitter.com/jbhuang0604/status/1506101759911116809)

---

How to present a line plot?
Line plots are effective for describing the relationship between two variables of interests.
Unfortunately, most junior students would simply copy&paste the figure from the paper in their talk and cause much confusion. 😕
Let's break it down ... 🧵

如何在演讲中讲解折线图？
折线图是描绘两个关键变量之间函数关系的极佳工具。
遗憾的是，大多数低年级学生在作报告时只会机械地把论文里的图原封不动复制粘贴到 PPT 上，导致听众一头雾水。😕
让我们一步步拆解正确的展示节奏…… 🧵

---

*Step 1: Describe the X-axis*
❌ Show the entire plot. Waaaay too much to unpack.
✅ Show *only the X-Y axis* (no lines yet!). Describe what factors you SUSPECT have an impact on the Y-axis, e.g., time, model complexity, dataset size.

*第 1 步：解释横坐标 X 轴 (Describe the X-axis)*
❌ 一股脑把整张图的所有曲线全放出来，信息量过大让人无法消化。
✅ **只展示 X-Y 坐标轴**（此时先不要出现任何曲线！）。阐明你“推测”对纵轴产生影响的关键因素，例如：时间、模型复杂度、数据集规模。

---

*Step 2: Describe the Y-axis*
Tell us ...
👉 what are we measuring?
👉 is higher or lower number better?
👉 what would a perfect/oracle curve look like?

*第 2 步：解释纵坐标 Y 轴 (Describe the Y-axis)*
向听众说明：
👉 我们测量的到底是什么指标？
👉 数值是越高越好还是越低越好？
👉 理论上的完美最优曲线（Oracle curve）应该长成什么样？

---

*Step 3: Set the stage*
Now that you explain what the plot is about, set the stage by showing the results from
✅ naïve results (e.g., random guess)
✅ baseline methods
✅ competing approaches

*第 3 步：铺垫对比基准 (Set the stage)*
既然坐标轴的物理含义已经交代清楚，接下来通过展示对照组来铺垫舞台：
✅ 基础对照结果（如随机猜测）
✅ 经典基线方法（Baseline methods）
✅ 现有的主要竞争方法（Competing approaches）

---

*Step 4: Reveal*
Show yourself! Oh I meant show your results!

*第 4 步：揭晓你的成果 (Reveal)*
闪亮登场！我是说，展示你自己提出的方法的结果！

---

*Step 5: Compare*
Don't just show, relate and compare!
Examples:
⏩ (fixed Y-axis) Ours achieves the same accuracy but runs 100x faster / uses only 5% of the training data
⏩ (fixed X-axis) Under the same model, ours reduces the errors by 30%.

*第 5 步：对比印证 (Compare)*
不要只展示单条曲线，要联系基线展开量化对比！
示例：
⏩ （固定纵轴性能）我们的方法达到了相同的准确率，但运行速度快了 100 倍 / 仅使用了 5% 的训练数据。
⏩ （固定横轴算力）在相同模型规模下，我们的方法将误差降低了 30%。

---

*Step 6: Contextualize your results*
Convert the numbers to something that others can easily relate.
For example,
❌ the code runs one frame per second
✅ for a car running at 90 km/hr, by the time we process the next image, the car has move forward by 25 meters.

*第 6 步：具象化结果的实际意义 (Contextualize your results)*
将抽象的数字转换为听众能够直观感知的具体现实场景。
例如：
❌ 算法运行速度为每秒处理 1 帧。
✅ 对于一辆以 90 公里/小时行驶的汽车，当算法处理完下一张图像时，汽车已经向前开出了足足 25 米。
