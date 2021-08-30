# AutoML

- テーブルデータを対象としたAutoML のexample リポジトリ

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

- Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/AutoML）

```
cd Desktop/AutoML
```

- Dockerによる環境構築（フォルダをマウント：Desktop/AutoML）

```
docker-compose -f docker-compose-{*構築対象}.yml up --build
```

- ブラウザーを立ち上げてlocalhost:8888へアクセス
- ローカルフォルダがマウントされている

## 動作環境

マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
