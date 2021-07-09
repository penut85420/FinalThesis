+ [ ] 實驗部份：
    + [ ] 將 Pseudo Training Data 放入 RNN & Attention 的實驗中
    + [ ] 補上 Sentence Embedding 的實驗
    + [ ] 最後補上 GRU 與 LSTM 和 Vanilla RNN 的比較
+ [ ] 論文部份：
    + [ ] Sec 3.6.1 關於 Simple DNN 的描述過於簡短
    + [ ] 將 BERT 跑 CSA 與 ML Features 的實驗結果寫入論文
    + [ ] 解釋「Dev Set 使用 10 Fold CV 並計算 Micro F1 的效能」這部份
    + [ ] Sec 5.5 將 FD 寫成了 FC，只要使用一個 D 即可
    + [ ] 文字放大到至少 12 點，行距 1.5 倍
    + [ ] Chap 2. 說明包含 RTE、NLI 以及 RITE
        + [ ] Sec 2.1 Task Definition 介紹何謂 RTE，其他 Dataset 往後
    + [ ] Chap 3. 說明我們以兩種角度設計神經網路架構
        + [ ] 把句對用一個向量表示，因此可以用 DNN 來建構分類器
        + [ ] 把句對表示成詞的序列，因此需要用 RNN 來建構分類器
    + [ ] Sec 3.1 -> Sentence-based Feature Vector
        + [ ] 3.1.1 ML Features（原 3.3.1~3.3.3）
        + [ ] 3.1.2 Sentence Embedding 指的是 Word Embedding 的平均向量
            + [ ] 補一句說關於 Word Embedding 的詳細討論請見 Sec 3.2
    + [ ] Sec 3.2 -> Word-based Sequence Input
        + [ ] 3.2.1 Raw Text Input 說明 `S1<SEP>S2` 的輸入形式
            + [ ] 介紹四種 Word Embedding Models（原 Sec 3.4）
        + [ ] 3.2.2 Word-Alignment Groups
            + [ ] 指的是 CSA 但要講得比現在版本更清楚、要想像
    + [ ] Chap 4. Training Data Augmentation
        + [ ] Sec 4.1 Adding Other NLI datasets
            + [ ] Same Language: CNLI/OCNLI
        + [ ] Sec 4.2 Pseudo
            + [ ] Train Data: CNLI, OCNLI, MNLI, Pseudo, RITE2->RITE-VAL
