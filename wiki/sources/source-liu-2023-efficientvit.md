# EfficientViT: Memory Efficient Vision Transformer with Cascaded Group Attention

- 作者：Xinyu Liu、Houwen Peng、Ningxin Zheng、Yuqing Yang、Han Hu、Yixuan Yuan
- 年份：2023
- arXiv：`2305.07027v1`
- 原始 PDF：[arXiv PDF](https://arxiv.org/pdf/2305.07027v1)
- 原始網址：[arXiv 摘要](https://arxiv.org/abs/2305.07027v1)
- 收錄日期：2026-11-23
- 已上傳的 PDF：[2305.07027v1.pdf](https://chatgpt.com/library?file_id=libfile_4600ca0e68fc81919552fcac7e0a4ccb&account_id=personal)
- 本機原始 PDF：[[2305.07027v1.pdf|2305.07027v1.pdf]]（11 頁）

## 核心內容

以單層注意力搭配前後的前饋網路減少記憶體相關開銷。串接式群組注意力把特徵依通道分組供各注意力頭使用，並把前一個頭的輸出加到下一個頭的輸入（§3.1、圖 6）。

## 可用於教學的內容

可用來和 U-ViT 比較：兩篇都調整視覺 Transformer，但 EfficientViT 的主要任務是辨識與取特徵。其 ImageNet-1K 結果同時報告準確率與吞吐量（§4、表 2）。

## 限制與待查證事項

吞吐量取決於硬體、批次與執行環境。這篇論文的速度結果來自所測的辨識設定，未提供 U-ViT 去噪效率的證據。

## 相關條目

- [[concept-transformer|Transformer 與注意力]]
- [[synthesis-genai-model-roles|辨識、影像生成與圖文問答]]
