# Mask RCNN 安裝
```
pip install tensorflow-gpu==1.15.2
pip install -r requirement
python setup.py install
```
# 資料集準備
下載以下連結中的圖像資料集，
放置道mrcnn_custom根目錄
```
mrcnn_custom/
│
└─── dataset/
     └─── train/
     │     └─── images/
     │     └─── train.json
     └─── val/
           └─── images/
           └─── val.json


```

# 訓練
python train.py
