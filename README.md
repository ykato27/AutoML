# AutoML

- テーブルデータを対象としたAutoML のexample リポジトリ

## リポジトリ構成
```
.
├── README.md
├── data
│   └── AirPassengers.csv
├── docker
│   ├── auto-sklearn
│   │   ├── Dockerfile
│   │   └── requirements.txt
│   ├── autokeras
│   │   ├── Dockerfile
│   │   └── requirements.txt
│   ├── evalml
│   │   ├── Dockerfile
│   │   └── requirements.txt
│   ├── flaml
│   │   └── Dockerfile
│   ├── ludwig
│   │   ├── Dockerfile
│   │   └── requirements.txt
│   ├── mljar-supervised
│   │   ├── Dockerfile
│   │   └── requirements.txt
│   ├── pycaret
│   │   ├── Dockerfile
│   │   └── requirements.txt
│   └── tpot
│       ├── Dockerfile
│       └── requirements.txt
├── docker-compose-auto-sklearn.yml
├── docker-compose-autokeras.yml
├── docker-compose-evalml.yml
├── docker-compose-flaml.yml
├── docker-compose-ludwig.yml
├── docker-compose-mljar-supervised.yml
├── docker-compose-pycaret.yml
├── docker-compose-tpot.yml
├── docs
├── models
├── notebooks
│   ├── auto-sklearn
│   │   ├── Auto_sklearn-example.ipynb
│   │   └── googlecolab
│   ├── autogluon
│   │   ├── AutoGluon-SHAP.ipynb
│   │   ├── AutoGluon.ipynb
│   │   ├── AutoGluon_SHAP.ipynb
│   │   └── AutoGluon_example.ipynb
│   ├── autokeras
│   │   ├── AutoKeras-regression-example.ipynb
│   │   ├── googlecolab
│   │   └── structured_data_regressor
│   ├── evalml
│   │   ├── AutoML-EvalML.ipynb
│   │   ├── evalml_debug.log
│   │   └── model.pkl
│   ├── flaml
│   │   ├── AutoML-FLAML.ipynb
│   │   ├── boston.log
│   │   └── catboost_info
│   ├── h2o
│   │   └── AutoML-h2o.ipynb
│   ├── ludwig
│   │   ├── regression_boston_example.ipynb
│   │   ├── regression_example.ipynb
│   │   └── results
│   ├── mljar-supervised
│   │   ├── AutoML-mljar-supervised.ipynb
│   │   ├── AutoML_1
│   │   ├── AutoML_2
│   │   ├── AutoML_3
│   │   └── AutoML_4
│   ├── pycaret
│   │   ├── AutoML-PyCaret-RegressionModels-example2.ipynb
│   │   ├── AutoML-PyCaret-RegressionModels.ipynb
│   │   ├── AutoML-PyCaret-Time-Series.ipynb
│   │   ├── catboost_info
│   │   └── logs.log
│   └── tpot
│       ├── AutoML-TPOT-RegressionModels.ipynb
│       └── proc_folder
├── pyproject.toml
├── setup.cfg
├── src
│   └── __init__.py
├── tests
│   └── __init__.py
└── work
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

## Display notebooks

- [View Jupyter notebooks in nbviewer](https://nbviewer.jupyter.org/github/ykato27/AutoML/tree/main/notebooks/)

## 動作環境

マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3

- Google Colab
