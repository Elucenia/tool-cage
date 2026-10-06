<!-- ELUCENIA technical documentation · cage · zh · no clinical/professional/rights approval -->

# CAGE 问卷

[条件、来源与许可](https://elucenia.org/zh/tools/cage)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### C – 您是否曾觉得应少喝或戒酒？

`c`

### A – 别人批评您的饮酒方式是否使您烦恼？

`a`

### G – 您是否对平时的饮酒方式感到内疚？

`g`

### E – 您是否常在早晨饮酒以减轻紧张或宿醉？

`e`

## 方法版本

CAGE/Ewing 1984：4个二元问题，0–4，阈值≥2；葡语Masur–Monteiro 1983

## 已记录的公式

每个回答一分 “是”: Cut down (减少), Annoyed (因批评烦恼), Guilty (内疚), Eye-opener (醒来饮酒)。阈值：≥ 2.

## 限制与适用人群

用于筛查酒精相关问题的简短问卷，之后需进行临床评估。所引用的巴西验证研究纳入了精神病院住院男性；不能假定其在其他人群中表现完全相同。该队列构成并不是按性别排除的普遍规则。

## 参考文献

- [Ewing JA. Detecting alcoholism: the CAGE questionnaire. JAMA, 1984.](https://doi.org/10.1001/jama.1984.03350140051025)

- [Masur J, Monteiro MG. Validation of the "CAGE" alcoholism screening test in a Brazilian psychiatric inpatient hospital setting. Braz J Med Biol Res, 1983.](https://pubmed.ncbi.nlm.nih.gov/6652293/)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

筛查阴性

CAGE阴性并不排除当前的风险性使用：应优先使用AUDIT来评估摄入量。


### 2

一项回答为阳性：低于截断值

询问摄入量和频率（AUDIT）。


### 3

筛查阳性（≥ 2）：怀疑酒精滥用或依赖

筛查工具：请通过临床评估确认。

