# T客邦Recommendation Course

## 簡介
預設使用GCP Goole Cloud Platform Datalab環境, 本機無須安裝任何套件, Datalab set up請參考 [GCP Datalab set up](https://docs.google.com/presentation/d/1ycHlObI_YyydrEiECdag_V_n1sXd8StQqrqdrBSoPI8/edit#slide=id.g2b481b6fdb_0_282)

Python Version: 3.5
會使用到的 Python 函式庫有：

1. NumPy：矩陣運算函式庫
2. Scikit-learn, Scipy：機器學習函式庫
3. Pandas：資料處理函式庫
4. TensorFlow(1.3+): Deep Learning函式庫
5. Jupyter Notebook：編譯器環境
<br/>
<br/>

## 本機使用安裝簡易教學

### 使用Anaconda
#### Step1 下載Anaconda
[Anaconda 官方文件 Install Tutorial](https://conda.io/docs/user-guide/install/windows.html)

#### Step2 Conda virtual env 安裝與使用
創建虛擬環境，打開終端機（Terminal），輸入：
```shell
conda create -n {env_name} python=3.5
```
{env_name}輸入自己取的名字

啟動虛擬環境：
```shell
activate {env_name}
```

#### Step3 Git Clone專案
```shell
git clone https://github.com/GaryChenCloudMile/recommendation_course/blob/master/README.md
```

安裝相關套件：

```shell
pip install -r requirements.txt
```

#### Step4 確認安裝完成，開啟 Jupyter Notebook
確認安裝完成，開啟 Jupyter Notebook：

```shell
jupyter notebook
```

Jupyter Notebook 會開啟一個伺服器，通常網址是：[http://localhost:8888](http://localhost:8888)，在瀏覽器輸入網址就可以看到筆記本了，到這邊應該就完成環境的安裝了～


## Lab請開啟檔名lab開頭的notebook
```
lab_tutorial_x_square.ipynb             一元二次多項式regression example
lab_tutorial_dnn_practice.ipynb         DNN model training練習
lab_reco_model_mf.ipynb                 Recommendation Matrix Factorization基本款
lab_reco_model_mf_with_history.ipynb    Recommendation Matrix Factorization加入user interaction
lab_reco_model_mf_dnn.ipynb             Recommendation Matrix Factorization加入user interaction and item metadata
```

## 檔名非lab開頭的notebook
```
tutorial_linear.ipynb                   Linear regression example
tutorial_dnn_practice.ipynb             
reco_memory_base.ipynb                  Collaborative filtering演算法
reco_model_mf.ipynb                     
reco_model_mf_with_history.ipynb
reco_model_mf_dnn.ipynb         
```
