# High-Resolution Image Synthesis with Latent Diffusion Models

- 作者：Robin Rombach、Andreas Blattmann、Dominik Lorenz、Patrick Esser、Björn Ommer
- 年份：2022（2021 年首版）
- arXiv：`2112.10752v2`
- 原始 PDF：[arXiv PDF](https://arxiv.org/pdf/2112.10752v2)
- 原始網址：[arXiv 摘要](https://arxiv.org/abs/2112.10752v2)
- 收錄日期：2026-11-23
- 已上傳的 PDF：[2112.10752v2.pdf](https://chatgpt.com/library?file_id=libfile_46cb0ad0463881918095d6617cf9b56d&account_id=personal)
- 本機原始 PDF：[[2112.10752v2.pdf|2112.10752v2.pdf]]（45 頁）

## 核心內容

先用自編碼器學習壓縮影像的潛在表示，再訓練擴散模型在該表示上預測雜訊。條件編碼器可透過跨注意力把文字等條件送入去噪網路。生成後由解碼器把潛在表示轉回影像（§3.1–3.3、圖 3）。

## 可用於教學的內容

可把文字生圖拆成「文字條件」「潛在空間迭代去噪」「影像解碼」。論文也評估修補、超解析與其他合成任務（§4）。

## 限制與待查證事項

壓縮程度會影響細節與計算成本（§4.1）。迭代去噪仍需要多次模型運算。

## 相關條目

- [[concept-diffusion|擴散與潛在擴散]]
- [[concept-transformer|Transformer 與注意力]]
- [[synthesis-genai-model-roles|辨識、影像生成與圖文問答]]
