# Image Classification with CNN & VGG16 (Transfer Learning)

> 本リポジトリは、CNNからVGG16、Transfer Learningまでの流れを学習・実装した記録であり、  
> 画像分類モデル構築の基礎から応用までを一通り学べる内容となっている。

---

## 概要
本プロジェクトは、SAMURAI ITスクールでの学習内容をもとに、Pythonを用いた画像分類技術を実装・整理したものである。

以下のステップで段階的に理解できるよう構成している：

- CNNによるベースラインモデルの構築  
- VGG16（事前学習モデル）の活用による精度向上  
- Transfer Learningによるモデルの最適化  

各Notebookには詳細なコメントを記載しており、処理の流れを理解しながら学習できる構成となっている。

---

## このリポジトリで学べること
- CNNを用いた画像分類モデルの基本的な作り方  
- 既存の高性能モデル（VGG16）の使い方  
- Transfer Learningの考え方と実装方法  
- 少量データでも精度を改善するアプローチ  

---

## ファイル構成

- `cnn_image_classification_baseline.ipynb`  
  CNNによる画像分類モデルのベースライン実装  

- `vgg16_image_classification.ipynb`  
  VGG16を用いた画像分類モデルの構築  

- `vgg16_transfer_learning.ipynb`  
  Transfer Learningによるモデルの改善  

※ 各ファイルは独立して実行可能であり、順番に進めることで理解が深まる構成となっている。

---

## 実行結果

- CNN（ベースラインモデル）：Accuracy = **0.6951**  
- VGG16：精度算出は未実施（モデル構築まで実装）  
- VGG16 + Transfer Learning：Accuracy = **0.8750**  

→ Transfer Learningを適用することで、ベースラインと比較して精度が大幅に向上した。

---

## 使用技術

### 言語・フレームワーク
- Python  
- TensorFlow / Keras  

### モデル・手法
- CNN（畳み込みニューラルネットワーク）  
- VGG16  
- Transfer Learning  

### 開発環境
- Google Colab（実行環境）  
- Google Drive（データ保存）  

---

## 実行方法

### 実行環境
本プロジェクトは **Google Colab** 上での実行を前提としている。  
画像データはGoogle Driveに保存しているため、ローカル環境ではそのまま実行できない場合がある。

---

### 手順
1. Google ColabでNotebookを開く  
2. Google Driveをマウントする  
3. コメントに従って画像データを準備する  
4. 上から順にセルを実行する  

---

## 補足
- 各Notebookには詳細なコメントを記載しているため、初学者でも理解しやすい構成となっている  
- データセットを変更することで、他の画像分類タスクにも応用可能  

---

## 作者
HAN YUJIA
