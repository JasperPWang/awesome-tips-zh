# 如何让论文“看起来”就是一篇优秀的佳作？ (How to write a paper that looks like a good one?)

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1437443017510621185](https://twitter.com/jbhuang0604/status/1437443017510621185)

---

如何让论文“看起来”就是一篇优秀的佳作？

审稿人也是普通人，他们的第一印象往往在打开 PDF 的前 30 秒内形成。如果一篇论文排版粗糙、图表模糊、格式混乱，审稿人会下意识怀疑研究本身的严谨度。  
分享一些提升论文视觉专业度与第一印象的关键细节。🧵

---

### 1. 首页 Teaser 图的精细打磨 (Stunning Teaser)

首页上半部分的质量决定了整篇论文的气场。  
- 避免使用低分辨率截图。
- 字体大小与正文排版字体保持协调。
- 确保裁切整齐、色彩对比鲜明。

---

### 2. 规避孤行与排版空隙 (Avoid orphan headings & white space)

- 使用 LaTeX 编译后，检查页面底部是否留有难看的单行或孤立标题。
- 合理调整图表位置（`[t]` / `[b]`）与间距宏，让每个页面的文字填充满格，绝不留下突兀的空白。

---

### 3. 表格的专业三线表格式 (Professional tables)

- 严禁使用纵向竖线！
- 使用 `booktabs` 宏包的 `\toprule`, `\midrule`, `\bottomrule`。
- 数字按照小数点或右对齐排列。
- 最优性能使用粗体（Bold），次优性能使用下划线（Underline）。

---

### 4. 符号与公式的排版规范 (Consistent math fonts)

- 变量使用意大利斜体，矩阵使用粗体大写，向量使用粗体小写。
- 文本在公式中必须使用 `\mathrm{}`（如 $\text{loss}$ 应写为 $\mathcal{L}_{\mathrm{loss}}$ 而非 $L_{loss}$）。
- 公式标点符号（逗号、句号）必须作为公式的一部分正确结尾。

---

### 5. 统一配色方案 (Consistent color palette)

- 全文图表中，同一类别或同一方法（例如“Ours”）在所有图中必须使用同一种颜色。
- 避免杂乱无章的高饱和度原色，选用更专业、色盲友好的学术调色板。
