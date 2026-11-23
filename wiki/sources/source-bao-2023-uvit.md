# All are Worth Words: A ViT Backbone for Diffusion Models

- 作者：Fan Bao、Shen Nie、Kaiwen Xue、Yue Cao、Chongxuan Li、Hang Su、Jun Zhu
- 年份：2023（2022 年首版）
- arXiv：`2209.12152v4`
- 原始 PDF：[arXiv PDF](https://arxiv.org/pdf/2209.12152v4)
- 原始網址：[arXiv 摘要](https://arxiv.org/abs/2209.12152v4)
- 收錄日期：2026-11-23
- 已上傳的 PDF：[2209.12152v4.pdf](https://chatgpt.com/library?file_id=libfile_1ee2bd62d6fc8191a4ae079f7cefcd44&account_id=personal)
- 本機原始 PDF：[[2209.12152v4.pdf|2209.12152v4.pdf]]（21 頁）

## 核心內容

U-ViT 把時間步、條件與帶有雜訊的影像或潛在表示區塊轉為 token，交給 Transformer 預測雜訊，並在淺層和深層之間加入長跳接（§2–3、圖 1）。

## 可用於教學的內容

可對照 U-Net 與 U-ViT 如何在相同的擴散框架中擔任去噪骨幹。CIFAR-10 消融實驗比較了多種淺層特徵融合方式（§3.2、圖 2）。

## 限制與待查證事項

文章報告 ImageNet 256 × 256 類別條件生成的 FID 為 2.29，MS-COCO 文字生圖為 5.48（摘要、§5）。兩個分數來自不同任務與資料集。長跳接的效果應以論文的實驗設定解讀。

## 相關條目

- [[concept-diffusion|擴散與潛在擴散]]
- [[concept-transformer|Transformer 與注意力]]
- [[synthesis-genai-model-roles|辨識、影像生成與圖文問答]]
