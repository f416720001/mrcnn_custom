# Mask RCNN 安裝
```
pip install tensorflow-gpu==1.15.2
pip install -r requirement
python setup.py install
```
# 資料集準備
https://thinfi.com/06yrq (密碼: dlll密碼) <br />

下載後放置於mrcnn_custom根目錄如下
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
