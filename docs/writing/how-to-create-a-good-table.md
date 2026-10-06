# 如何制作一张高质量的论文实验表格？ (How to create a good table?)

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1626372600824844289](https://twitter.com/jbhuang0604/status/1626372600824844289)

---

如何制作一张高质量的论文实验表格？

实验表格是评测成果的最核心凭据。杂乱无章的表格不仅让读者费解，更会降低论文的可信度。  
分享制作学术表格的关键规范。🧵

---

### 1. 分组对比与基准划分 (Clear grouping)

将表格中的方法按类别清晰分组：
- 传统方法 / 经典 Baseline
- 近期 SOTA 方法
- 你的方法（Ours）  
使用 `\midrule` 或适度空行分隔不同阵营，切勿乱序堆放。

---

### 2. 指标方向标注 (Metric directionality)

在表头的指标名称旁明确标注箭头方向：
- PSNR $\uparrow$（越高越好）
- LPIPS $\downarrow$（越低越好）  
这能让读者无需猜测即可迅速判断优劣。

---

### 3. 正确的高亮策略 (Highlighting convention)

- 最优结果：粗体 (**Bold**)
- 次优结果：下划线 (<u>Underline</u>) 或次级浅灰标注  
在 Caption 中明确注明说明：“粗体表示最佳结果，下划线表示次优结果”。

---

### 4. 保持数值精度一致 (Consistent decimal places)

同一列中的数值，小数点后位数必须保持严格一致（例如全部保留 2 位或 3 位）。严禁出现一行 32.1、下一行 32.1458 的不规范现象。
