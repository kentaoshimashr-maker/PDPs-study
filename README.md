# PDP-based Feature Engineering for Wine Quality
# ワイン品質予測におけるPDP特徴変換の検証

This repository contains a project that performs feature engineering based on Partial Dependence Plots (PDP) to improve linear regression performance on the Kaggle "Wine Quality" dataset.

このリポジトリは、Kaggleの「Wine Quality」データセットを使用し、Partial Dependence Plots (PDP) に基づく特徴量エンジニアリングを検証したプロジェクトです。

## Project Objective
## プロジェクトの目的

The objective is to improve the prediction performance of linear models by incorporating non-linear relationships using PDP. Specifically, we compare the performance of linear models on the original dataset with that on a dataset with features transformed by PDP.

この研究の目的は、PDPを活用して非線形な関係性を線形モデルに取り込むことで、モデルの予測性能を向上させることです。具体的には、元のデータセットと、PDPから変換した特徴量を持つデータセットで線形モデルの性能を比較します。

## File Structure
## ファイル構成

* `wine_quality_pdp_analysis.ipynb.ipynb`: The main Jupyter Notebook containing the analysis and code.
* `requirements.txt`: A list of Python libraries required to run this project.

* `wine_quality_pdp_analysis.ipynb.ipynb`: 主要な分析とコードが含まれるJupyter Notebookです。
* `requirements.txt`: このプロジェクトを実行するために必要なPythonライブラリのリストです。

## How to Use
## 使い方

1.  Clone this repository.
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
2.  Install the required libraries.
    ```bash
    pip install -r requirements.txt
    ```
3.  Open the Jupyter Notebook and run the cells from top to bottom.

1.  このリポジトリをクローンします。
2.  必要なライブラリをインストールします。
3.  Jupyter Notebookを開き、上から順番にセルを実行してください。

## Summary of Results
## 結果の要約

Feature transformation based on the Random Forest model's PDP improved the R2 score for the linear model from 0.3171 to 0.3891.

Random ForestモデルのPDPに基づく特徴変換は、元のデータセットに対する線形モデルの性能をR2スコアで0.3171から0.3891に向上させました。

## Dataset
## 使用データセット

This project uses the following dataset from Kaggle:
* [Wine Quality (Kaggle)](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)

このプロジェクトでは、以下のKaggleデータセットを使用しています。