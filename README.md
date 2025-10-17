# タイタニック生存予測：基礎集計による仮説の検証

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tomnyancat/Kaggle-Titanic-Basic-Hypothesis-Test/blob/main/titanic-basic-hypothesis-test.ipynb)

本リポジトリは、Kaggleの**タイタニック号生存予測**データセットを使用し、乗客の属性と生存率の関連性を**Pandasによる基礎集計とデータ探索**を通じて検証した学習ノートブックです。

---

## 分析の目的とハイライト

当時の社会的な背景に基づいた直感的な仮説が、実際のデータで裏付けられるか（または反証されるか）を検証しました。

* **検証した主な仮説:**
    1.  **性別**：女性は男性より生存率が高いか？
    2.  **客室等級 (Pclass)**：等級が高い乗客は生存率が高いか？
* **分析の深掘り:**
    * 性別と等級を組み合わせた生存率の比較
    * 年齢（子供を仮定）、および**敬称（Title）**による生存率の傾向分析
* **最終ステップ:** シンプルな**「女性は生存」モデル**を作成し、Kaggle提出用のCSVファイルを出力しています。

---

## 使用技術とデータセット

* **データ**: Kaggle Titanic Survival Prediction (train.csv / test.csv)
* **主要な手法**: Pandas `groupby()`、`mean()`、`agg()`、`loc`による**基礎集計**とデータ操作

---

## ✍️ 書いた人

[TOM](https://github.com/tomnyancat)
