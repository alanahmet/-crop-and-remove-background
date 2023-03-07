# Crop and remove background with [yolov7](https://github.com/WongKinYiu/yolov7) and [rembg](https://github.com/danielgatis/rembg)

Paste python and requirements files in yolov7 folders then install requirements.

Example run 
```python
python remove.py --weights yolov7.pt --conf 0.25 --img-size 640 --source inference/images/image.jpg --crop True --boundbox False
```

![example image](https://github.com/alanahmet/-crop-and-remove-background/blob/main/runs/detect/exp2/image1.jpg?raw=true "Logo Title Text 1")

![example image](https://github.com/alanahmet/-crop-and-remove-background/blob/main/result.png?raw=true "Logo Title Text 1")
