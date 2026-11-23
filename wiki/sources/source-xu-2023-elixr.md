# ELIXR: Towards a general purpose X-ray artificial intelligence system through alignment of large language models and radiology vision encoders

- 作者：Shawn Xu、Lin Yang 等（共 28 位作者，完整名單見 arXiv）
- 年份：2023
- arXiv：`2308.01317v2`
- 原始 PDF：[arXiv PDF](https://arxiv.org/pdf/2308.01317v2)
- 原始網址：[arXiv 摘要](https://arxiv.org/abs/2308.01317v2)
- 收錄日期：2026-11-23
- 已上傳的 PDF：[2308.01317v2.pdf](https://chatgpt.com/library?file_id=libfile_88f108d53a208191b2045ae54e756f1a&account_id=personal)
- 本機原始 PDF：[[2308.01317v2.pdf|2308.01317v2.pdf]]（52 頁）

## 核心內容

ELIXR-C 對齊胸部 X 光影像與報告表示。ELIXR-B 使用 Q-Former 和投影層，把凍結的影像編碼器輸出接到凍結的 PaLM 2。適配器來自影像與報告配對的訓練（Methods、圖 1）。

## 可用於教學的內容

同一研究涵蓋分類、語意搜尋和能輸出文字的視覺問答。VQA-RAD 的胸部 X 光問題整體正確率為 58.7%（表 5），可用來討論如何依任務評估輸出。

## 限制與待查證事項

作者指出結果對提示敏感，並可能出現幻覺或過度自信（Discussion）。正文與摘要對報告品質檢查提到 62.5%，但表 7、8 的整體列標為 60.4%（48 例）。兩處數字不一致，備課暫以表 5 結果為例。

## 相關條目

- [[concept-multimodal|影像與語言對齊]]
- [[concept-transformer|Transformer 與注意力]]
- [[synthesis-genai-model-roles|辨識、影像生成與圖文問答]]
