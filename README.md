# titanic-kaggle-challenge
Kaggle Titanicコンペの分析＆提出記録

## 🎯 目的
Titanicの生存予測を通じて、前処理・特徴量エンジニアリング・モデリング・評価・提出までを実践。

## 🔧 使用した特徴量
- Pclass
- Sex
- Age（Titleごとに補完）
- SibSp / Parch / FamilySize / IsAlone
- Embarked
- Fare
- HasCabin
- Title（称号）

## 🤖 使用モデルと検証精度
| モデル | 検証精度 | Kaggleスコア |
|--------|----------|---------------|
| RandomForest | 0.8379 | 0.75598 |
| XGBoost | 0.8268 | 未提出 |
| LogisticRegression | 0.7877 | 未提出 |

## 📁 ファイル構成
- `タイタニック３.ipynb`：分析ノートブック
- `タイタニックチャレンジ３(モデル比較ランダムフォレスト).csv`：提出ファイル
