# 辨識、影像生成與圖文問答

這份備課筆記用「給模型什麼，它回傳什麼」區分五篇論文裡的任務。

| 論文 | 代表性輸入 | 代表性輸出 |
| --- | --- | --- |
| [[source-liu-2023-efficientvit|EfficientViT]] | 一張影像 | 分類標籤或可供下游任務使用的影像特徵 |
| [[source-vaswani-2017-transformer|原始 Transformer]] | 來源語言句子 | 目標語言的文字序列 |
| [[source-rombach-2022-ldm|潛在擴散]] | 潛在雜訊與文字條件 | 解碼後的影像 |
| [[source-bao-2023-uvit|U-ViT]] | 含雜訊的區塊、時間步與條件 | 骨幹輸出雜訊預測，反覆取樣後得到影像 |
| [[source-xu-2023-elixr|ELIXR-B]] | 胸部 X 光與問題 | 文字答案 |

**教學示例**。拿一張狗的照片問「照片裡是哪種動物？」可以預期分類器給標籤、圖文問答系統給文字回覆。改成提供「草地上的黃金獵犬」的文字描述，再讓模型產出一張圖，則是條件式影像生成。請學生先判斷輸入與輸出，再解釋任務差異。

## 相關條目

- [[concept-transformer|Transformer 與注意力]]
- [[concept-diffusion|擴散與潛在擴散]]
- [[concept-multimodal|影像與語言對齊]]
