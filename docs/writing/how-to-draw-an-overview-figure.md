# 如何绘制论文方法总览图？ (How to draw an overview figure?)

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1665738070002483201](https://twitter.com/jbhuang0604/status/1665738070002483201)

---

如何绘制论文方法总览图？

方法总览图（Overview Figure / Framework Architecture）是论文中最关键的图表之一。审稿人往往会对照这张图来阅读你的整个 Method 章节。  
如何画出一张既美观又易懂的高水准总览图？🧵

---

### 1. 数据流向清晰统一 (Consistent data flow)

数据流动方向必须严格统一（例如：统一从左至右，或从上至下）。  
切忌箭头四处乱飞、来回折返。

---

### 2. 模块化封装与层级分明 (Modular design)

将复杂系统拆解为 2-4 个逻辑模块（例如：特征提取模块、对齐模块、渲染模块），并使用浅色半透明背景框加以分组。每个模块上方标注清晰名称。

---

### 3. 符号与正文 100% 对应 (Symbol-text bijection)

图中出现的所有数学变量符号（如 $x$, $z$, $\hat{y}$, $\mathcal{L}_{reg}$），必须在正文中一一对应且符号完全一致。

---

### 4. 自成一体的说明文案 (Self-contained caption)

Caption 中必须按照流程顺序依次解释各个模块：“输入 X 首先经过模块 A……随后在模块 B 中进行融合……最后通过损失函数 $\mathcal{L}$ 进行联合优化”。

---

### 5. 避免“图标堆砌”而忽略数学本质

总览图不仅是漂亮的卡通图标，更应该是一张精确的计算图（Computational Graph）。
