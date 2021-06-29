# yolov5 訓練口罩偵測與inference

* reference: https://github.com/ultralytics/yolov5
* dataset: https://www.kaggle.com/andrewmvd/face-mask-detection

## training:
yolov5_mask.ipynb

## inference on webcam

git clone https://github.com/ultralytics/yolov5v

git https://github.com/funpi89/yolov5_mask.git

sudo mv yolov5_mask/mask_inference.py yolov5/

sudo mv yolov5_mask/yolov5_mask.pt yolov5/

cd yolov5

python mask_inference.py

# result of mask_inference.py on webcam

mask

![image](https://github.com/funpi89/yolov5_mask/blob/main/images/with_mask.PNG)

no mask

![image](https://github.com/funpi89/yolov5_mask/blob/main/images/no_mask.PNG)

mask but incorrect

![image](https://github.com/funpi89/yolov5_mask/blob/main/images/incorrect.PNG)

