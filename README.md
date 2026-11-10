# W02 AIGC 产品图像实验刺激

## 研究概述
本数据集用于视觉真实感与风格化程度的 2×2 AIGC 产品图像实验。

**图像生成与编辑平台：Midjourney。** 证据类型：研究者本人确认（Researcher-confirmed）。

## 刺激材料组成
正式刺激为 P006—P040 的35个匹配区组，每区组4种条件，共140张 PNG 图像。

## 实验条件
| 条件 | 视觉真实感 | 风格化程度 |
| --- | --- | --- |
| C1 | 高 | 高 |
| C2 | 高 | 低 |
| C3 | 低 | 高 |
| C4 | 低 | 低 |

高、低为实验指令水平，不是评价分数。

## 文件组织
`images/` 存放图像；`stimulus_manifest.csv` 提供区组、条件、相对文件路径及 SHA-256。

## 研究材料公开范围
本仓库提供W02研究使用的正式实验图像及实验条件对应信息，用于研究刺激材料的展示与核查。公开内容包括140张正式图像、35个匹配区组的条件索引及基本说明。计算评价原始评分、内容原子记录、评价器执行记录及统计分析代码不属于本仓库的公开范围。

为保护非研究性元数据信息，公开图像副本已进行元数据清理。图像的像素内容和实验条件保持不变。

## 使用和引用
相关稿件：IR2751，Visual Realism and Stylization in AIGC-Generated Product Images: A Multidimensional Computational Evaluation of Content Naturalness, Quality, and Prompt–Image Alignment。引用材料时请注明稿件编号及本材料版本。本仓库未授予开放再利用许可。

## 版本信息
候选版本 v1.0.0；正式发布日期和版本链接待发布后登记。
