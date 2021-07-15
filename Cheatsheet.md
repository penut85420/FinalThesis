# 重要數據整理

## Table of Contents
- [重要數據整理](#重要數據整理)
    - [Table of Contents](#table-of-contents)
    - [整體最佳](#整體最佳)
    - [RITE-VAL Test 過 55% 的實驗](#rite-val-test-過-55-的實驗)
    - [RITE2 Test 過七成的實驗](#rite2-test-過七成的實驗)
    - [雜記](#雜記)
        - [RITE-VAL](#rite-val)
        - [RITE2](#rite2)

## 整體最佳
+ 使用 MNLI 做 Pre-train 再 Fine-tune 的 Multi-lingual BERT
    + Sec 5.5 - 55.61%/71.07%

## RITE-VAL Test 過 55% 的實驗
+ MNLI-CNLI - 56.50%
+ Mixed-NLI - 55.92%
+ MNLI - 55.61%

## RITE2 Test 過七成的實驗
+ MNLI - 71.07%
+ Mixed-NLI - 70.36%
+ MNLI + MLFT - 70.32%

## 雜記
### RITE-VAL
+ BERT: 49% ~ 56%
+ RNN + WAG + MLFT: 33% ~ 35%
+ RNN: 25%
+ RNN SentEmb: 25%
+ SVM: 35%
+ DNN: 35% ~ 37%

### RITE2
+ BERT: 58% ~ 71%
+ RNN + WAG + MLFT: 40%
+ RNN: 25%
+ RNN SentEmb: 27%
+ SVM: 35% ~ 46%
+ DNN: 32% ~ 46%
