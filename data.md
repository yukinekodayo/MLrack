# 13. 技術検証で使用したデータ・コード資産

- データセット：Oxford-IIIT Pet Dataset（GitHub `ml4py/dataset-iiit-pet` 経由で取得）
- 顔の切り出し：XMLのバウンディングボックス情報を使用
- 特徴量：Canny法によるエッジ密度、RGB各チャンネル平均、グリッド分割（5x5）による位置別統計
- 特徴量選定：SelectKBestで上位25候補に絞り、そこから5-fold CVで最良の8組み合わせを2000通りランダム探索
- 分類器：ロジスティック回帰（線形分類器、歯車の「加重和」に対応）
- Google Colab用ノートブック：`colab_weight_calculation.ipynb`（特徴量抽出〜重み計算まで全自動）
