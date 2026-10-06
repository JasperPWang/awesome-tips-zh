# How to make steady progress in my research? / 如何在科研中保持稳步进展？

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始链接：[https://twitter.com/jbhuang0604/status/1419880122006519809](https://twitter.com/jbhuang0604/status/1419880122006519809)

---

I worked so damn hard but "IT JUST DOESN'T WORK!"  
How can I unblock myself quickly and make good progress toward the goals?

我付出了巨大的努力，但“它就是跑不通！”  
我怎样才能快速打破僵局，朝着目标取得良好进展？

Below I compiled a list of tips that I found useful.

下面我整理了一份我发现非常有用的建议清单。

---

## Imagine success / 想象成功

Forget about all the technical difficulties for a moment. Imagine you finish your project successfully, would you find the outcome exciting?

暂时忘掉所有的技术困难。设想你顺利完成了这个项目，你会对这个成果感到兴奋吗？

If not, drop the project. Yep, just drop it. Free up your time to work on important problems.

如果不兴奋，那就放弃这个项目。是的，直接放弃。把你的时间释放出来，去攻克重要的问题。

---

## Work backward / 倒推工作流

Say your project involves three steps: A -> B -> C.

假设你的项目包含三个步骤：A -> B -> C。

First, assume that you have perfect output of B and work on the step C.  
Next, assume that you have perfect output A and work on the step B and so on.  
In the end, you will have a fully working method.

首先，假设你已经拥有了 B 的完美输出，先去攻克步骤 C。  
接下来，假设你已经拥有了 A 的完美输出，去攻克步骤 B，以此类推。  
最终，你将获得一个完整可运行的方法。

Okay, this is weird. WHY?  
Because you get to  
1) see final outcome early  
2) measure the performance upper bound  
3) focus on each task with perfect inputs without distraction  
4) figure what are needed to achieve the desire results.

好吧，这听起来很奇怪。为什么？  
因为你能够：  
1) 尽早看到最终成果  
2) 测算性能的理论上限（upper bound）  
3) 在不受干扰的情况下，基于完美的输入专注于每个子任务  
4) 搞清楚要达到理想结果到底需要哪些前置条件。

---

## Toy examples / 简化示例

Design toy examples that capture the essence of your problem. They are sufficiently simple so you can focus on the core problem.

设计能够抓住问题本质的“简化示例（Toy examples）”。它们足够简单，能让你心无旁骛专注于核心难题。

It's also often helpful to construct/synthesize such toy examples so that you have access to all the ground truth in all the steps.

构建或合成这类简化示例往往非常有帮助，因为这样你就能在所有中间步骤中掌握全部的真实基准（Ground truth）。

---

## Baseline first / 基准先行

Don't know where to start? Start with trying out baseline methods on your problem.

不知道从何入手？从在你的问题上测试基准方法（Baselines）开始。

It helps identify limitations of the state-of-the-art. If they work perfectly well, why do you need to work on this problem?  
Finding specific gap helps motivate your work.

这有助于发现现有最先进技术的局限性。如果基线方法已经完美解决了问题，那你为什么还要研究这个课题？  
找出具体的不足与鸿沟，正是激发你开展这项研究的根本动力。

---

## Simple case first / 简单案例优先

If your method does not work on simple/trivial cases, how could you expect it to work on unconstrained, real-world cases?

如果你的方法在最简单、甚至平凡（trivial）的案例上都跑不通，你怎么能指望它在无约束的真实世界复杂场景中奏效呢？

---

## One thing at a time / 一次只改变一个变量

When doing experiments, change exactly ONE thing at a time. This helps you understand what the results mean.

做实验时，每次严格只改变一个变量。这有助于你准确理解实验结果背后的真正原因。

---

## Identify proxy / 寻找快速代理指标

Do not use full-scale experiments (that may take weeks to complete) as the only way to validate your ideas. Run smaller-scale/simpler experiments with short turnaround time so you get to iteratively refine your ideas a lot faster.

不要把动辄需要数周才能跑完的全量实验作为验证想法的唯一手段。运行周转周期短的小规模、简化实验，这样你就能以快得多的速度迭代打磨你的想法。

---

## Automate everything / 自动化一切重复劳动

If you find that you need to do the same task twice, write a script for that.  
Your future self will thank you.

如果你发现某项任务需要重复做两次以上，立刻写一个脚本来自动化它。  
未来的你一定会感谢现在的自己。

---

## Visualize everything / 可视化所有细节

You cannot debug what you cannot see. Investing time in visualizing your inputs/intermediate steps/outputs is definitely worthwhile!

你无法调试你看不到的东西。花时间将输入、中间步骤和输出结果完整可视化，绝对物超所值！

---

## Quantify success / 量化评估指标

Instead of always eyeballing a few results on your own, identify a couple of quantitative metrics for your problem and let them guide your exploration.

不要总是凭肉眼主观打量少数几个样例，为你的问题确立几个明确的量化评估指标，让客观数字指引你的探索方向。

---

## Make the best use of machine time / 充分利用机器空闲时间

Plan your experiments so that your machines still work for you while you are not working.

精心规划你的实验任务，让你在休息睡眠的时候，计算集群依然在不知疲倦地为你工作。
