# AutoML-PyCaret
* AutoML-PyCaret を活用した回帰モデル全般のプログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── .dockerignore        
├── Dockerfile                Dockerファイル
├── docker-compose.yml
├── requirements.txt          requirementsファイル
└── notebook                  jupyter notebook
```

## 環境構築

* Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/AutoML-PyCaret）
```
cd Desktop/AutoML-PyCaret
```

* Dockerによる環境構築（フォルダをマウント：Desktop/AutoML-PyCaret）
```
docker-compose up --build
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている

## jupyter notebook説明
* [AutoML-PyCaret-RegressionModels.ipynb](https://github.com/ykato27/AutoML-PyCaret/blob/main/notebook/AutoML-PyCaret-RegressionModels.ipynb) : PyCaretを活用したAutoMLのnotebook

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
