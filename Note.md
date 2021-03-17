# 緒論 Introduction
## 研究動機
- 盡量用自己的話寫一遍
- 可以參考其他 NLI Paper
- 初稿這部份可以先不寫

## 相關研究
- 別人的研究與我們的研究有何不同
- 這段可以晚點寫
- NLI Leaderboard
    - 第二章詳細介紹資料集

# 論文架構
## 實驗資料介紹
- 介紹 RITE 與其他 NLI 資料集的相關資訊
    - 數量、種類 (RITE1, RITE2, RITE-VAL)
+ MNLI, CNLI, OCNLI (, SNLI)

## 實驗方法
- 先定義要做什麼事情，要如何去做
- 提所有使用的方法
    - 可解釋的方法
- 提了哪些新架構，為什麼想用
- 過去使用規則式、機器學習的方法
    - 機器學習特徵
- 使用深度學習 Transformer 的 Transfer Learning 方法

## 實驗結果及討論
- 使用哪些資料集
- 重新講一次實驗資料量有多大
- 每一個工作的評估公式為何
    - ACC for ECN & F1 for BFCI
    - Micro F1 vs. Marco F1
- 很多表格
    - 該表格的實驗為何
    - 效果如何，解讀表格

# 結論
- 可以先不寫

# 參考書目
- 可以先不寫

## 參考

# 備註
+ 所有實驗設定的驗證都會和「以 MNLI 訓練 + RITE 測試 + BERT」為比較對象
+ 比對過程中看有缺什麼實驗就趕出來

# 雜記
+ 調參數寫在實驗裡面
+ CSA 可以用示意圖來解釋
+ Chapter 換頁, section 換成 chapter, 標題置中
  + 3 -> Chapter 3. Approaches
+ 如何讓 ML Features 出現在 Deep Learning 裡面
