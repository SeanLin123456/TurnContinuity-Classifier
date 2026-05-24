# TurnContinuity-Classifier

## 專案簡介
這個專案是一個二元分類模型，用來預測語音片段是不是 **完整 (Complete, 1)** 或 **不完整 (Incomplete, 0)**。  

---

## 資料
- 使用資料：`train.csv` 與 `test.csv`  
- 每一列代表一個語音 turn 的特徵  
- 標籤：Complete (1) 或 Incomplete (0)  

---

## 技術與工具
- **程式語言**：Python  
- **執行環境**：Jupyter Notebook  
- **套件**：`pandas`, `numpy`, `xgboost`, `transformers`, `imbalanced-learn`, `nltk`, `accelerate`  
- **模型**：XGBoost、基於 Transformer 的分類模型  

---
