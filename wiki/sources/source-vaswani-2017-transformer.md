# Attention Is All You Need

- 作者：Ashish Vaswani、Noam Shazeer、Niki Parmar、Jakob Uszkoreit、Llion Jones、Aidan N. Gomez、Łukasz Kaiser、Illia Polosukhin
- 年份：2017（v7 修訂於 2023）
- arXiv：`1706.03762v7`
- 原始 PDF：[arXiv PDF](https://arxiv.org/pdf/1706.03762v7)
- 原始網址：[arXiv 摘要](https://arxiv.org/abs/1706.03762v7)
- 收錄日期：2026-11-23
- 已上傳的 PDF：[1706.03762v7.pdf](https://chatgpt.com/library?file_id=libfile_2fedf166377081919489c1d6eb17957d&account_id=personal)
- 本機原始 PDF：[[1706.03762v7.pdf|1706.03762v7.pdf]]（15 頁）

## 核心內容

原始 Transformer 以編碼器處理來源句子，解碼器透過遮罩自注意力與編碼器－解碼器注意力，逐步產生目標序列。架構也包含位置編碼與逐位置前饋網路（§3、圖 1）。

## 可用於教學的內容

可用翻譯說明「看到來源句子與已產生的譯文，再預測下一個 token」。自注意力與跨注意力的 Q、K、V 來源可對照 §3.2、圖 2。

## 限制與待查證事項

論文主實驗聚焦機器翻譯，也評估句法分析（§6）。原始的編碼器－解碼器架構只是 Transformer 的一種用法。

## 相關條目

- [[concept-transformer|Transformer 與注意力]]
- [[concept-multimodal|影像與語言對齊]]
- [[synthesis-genai-model-roles|辨識、影像生成與圖文問答]]
