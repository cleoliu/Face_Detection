
# 
- 積分、特徵、級聯分類器
- 首先定義一些 Haar-Like 特徵（眼睛、嘴、髮際線…等等）。
- 給定大量 sample 做訓練，我們要做的為人臉偵測，所以第一部分需要輸入正向人臉特徵的sample。另一部分需要反向sample 其他任意的圖片。有了這些 sample，接著利用 AdaBoost learning algorithm 來挑出某幾個代表性的 Haar-Like Features，最後製成分類器。
- 接著就可利用此分類器用來判斷所輸入的圖片或影像是否為人臉，最後回傳結果。


## 階層式模組化架構（IDEF0）
![](https://d2mxuefqeaa7sj.cloudfront.net/s_2BBB4D0B3F341D8E8A4E71FFB1F531249F0737F7768794B44B7B7878B85F2785_1536833955791_2018-9-13++06-16-54.jpg)

## 離散事件建模（Grafcet）

 

![](https://d2mxuefqeaa7sj.cloudfront.net/s_2BBB4D0B3F341D8E8A4E71FFB1F531249F0737F7768794B44B7B7878B85F2785_1536833882479_2018-9-13++06-17-27.jpg)


