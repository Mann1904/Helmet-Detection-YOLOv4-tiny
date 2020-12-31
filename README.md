# Helmet-Detection-YOLOv4-tiny


## How to run ?
### Conda (Recommended)

```bash
# Tensorflow CPU
conda env create -f conda-cpu.yml
conda activate yolov4-cpu

# Tensorflow GPU
conda env create -f conda-gpu.yml
conda activate yolov4-gpu
```

### Pip
```bash
## TensorFlow CPU
pip install -r requirements.txt

## TensorFlow GPU
pip install -r requirements-gpu.txt
```

## Run yolov4-tiny tensorflow model
```bash
python detect.py --weights ./checkpoints/yolov4-tiny-416 --size 416 --model yolov4 --images ./data/images/bike1.png --tiny
```
## Run yolov4 on video
```bash
python detect_video.py --weights ./checkpoints/yolov4-tiny-416 --size 416 --model yolov4 --video ./data/video/video.mp4 --output ./detections/results.avi
```
## Run yolov4 on webcam
```bash
python detect_video.py --weights ./checkpoints/yolov4-tiny-416 --size 416 --model yolov4 --video 0 --output ./detections/results.avi --tiny
```

# Result Images

![3](https://github.com/Mann1904/Helmet-Detection-YOLOv4-tiny/blob/main/data/helpers/3.png)

![1](https://github.com/Mann1904/Helmet-Detection-YOLOv4-tiny/blob/main/data/helpers/1.png)

![2](https://github.com/Mann1904/Helmet-Detection-YOLOv4-tiny/blob/main/data/helpers/2.png)




