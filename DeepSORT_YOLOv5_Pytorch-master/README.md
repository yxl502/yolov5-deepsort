# DeepSORT_YOLOv5_Pytorch

1 Install all dependencies
~~~
pip install -r requirements.txt
~~~

2 Download the yolov5 weight. 
I already put the `yolov5s.pt` inside. If you need other models, 
please go to [official site of yolov5](https://github.com/ultralytics/yolov5). 
and place the downlaoded `.pt` file under `yolov5/weights/`.   
And I also aready downloaded the deepsort weights. 
You can also download it from [here](https://drive.google.com/drive/folders/1xhG0kRH1EX5B9_Iz8gQJb7UNnn_riXi6), 
and place `ckpt.t7` file under `deep_sort/deep/checkpoint/`


3 Run

# on video file
python main.py --input_path [VIDEO_FILE_NAME]

# on webcam 
python main.py --cam 0 --display

