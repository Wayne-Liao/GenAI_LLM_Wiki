# Transformer 與注意力

## 一句話定義

Transformer 是以注意力機制處理序列中各個位置關係的神經網路架構。

## 運作流程

1. 把輸入轉成向量，加入位置資訊。
2. 利用注意力依各位置之間的關聯計算加權組合，再由前饋網路轉換各位置的表示。
3. 依任務使用輸出。例如原始 Transformer 用解碼器逐步生成譯文。

## 例子

**教學示例**。翻譯時，解碼器可參考來源句子和已產生的譯文，預測下一個詞元（token）。

## 常見誤解

看到 Transformer 就能判斷它在做什麼。應同時看輸入、訓練目標和輸出。例如 EfficientViT 輸出分類結果，U-ViT 的網路預測雜訊。

## 進階原理

縮放點積注意力先以查詢向量與鍵向量計算相似度，除以鍵向量維度的平方根，再經 softmax 得到對值向量的權重。多頭注意力在多組投影空間中各自計算，再合併結果。

## 相關條目

- [[concept-diffusion|擴散與潛在擴散]]
- [[concept-multimodal|影像與語言對齊]]
- [[synthesis-genai-model-roles|辨識、影像生成與圖文問答]]

## 來源

- [[source-vaswani-2017-transformer|Vaswani 等]] §3、圖 1–2
- [[source-liu-2023-efficientvit|Liu 等]] §3.1、圖 6
- [[source-bao-2023-uvit|Bao 等]] §2–3、圖 1
