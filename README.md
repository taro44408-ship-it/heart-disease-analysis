# heart-disease-analysis - UCI Dataset

## 概要
UCI Heart Disease Data を用いた心臓病予測モデルの構築と分析.
医学的な知見を交えたEDA, 欠損値処理, ロジスティック回帰・ランダムフォレストによる分析を実施.

## データセットの特徴
- 920件, 16列 (4施設の統合データ)
- 欠損率50%超の列の取り扱いを考慮

## 使用技術
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Kaggle Notebook

## 主な結果
- ロジスティック回帰: Accuracy 82.6%, Recall 88.2%
- ランダムフォレスト: Accuracy 83.7%, Recall 88.2%
- 特徴量重要度では最大心拍数(thalch)と胸痛タイプ(cp)が上位

## Kaggle Notebook
https://www.kaggle.com/code/momotaro0803/heart-disease-uci
