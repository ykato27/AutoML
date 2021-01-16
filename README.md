# PyCaret
* PyCaretを活用した回帰モデル全般のプログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── Dockerfile                Dockerファイル
└── notebook                  jupyter notebook
```

## 環境構築
Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/PyCaret）
```
cd Desktop/PyCaret
```
Dockerによる環境構築
```
docker build .
```
docker run実行（対象フォルダをマウントする／例：Desktop/PyCaret）
```
docker run -p 8888:8888 -v ~/Desktop/PyCaret/:/work --name Regression_Models <docker image>
```
ブラウザーを立ち上げてlocalhost:8888へアクセス
workフォルダ内が対象フォルダにマウントされている

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3