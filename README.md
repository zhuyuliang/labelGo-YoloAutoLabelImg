# labelGo
<p>Guide Language:<a href="https://github.com/cnyvfang/labelGo-Yolov7AutoLabelImg/blob/master/readme_zh_cn.md">简体中文</a></p>
<p>A graphical Semi-automatic annotation tool based on <a href="https://github.com/tzutalin/labelImg">labelImg</a> and <a href="https://github.com/WongKinYiu/yolov7">YOLOv7</a></p> and <a href="https://github.com/cnyvfang/labelGo-Yolov5AutoLabelImg">labelGo-Yolov5AutoLabelImg</a></p>
<p>Semi-automatic annotation of datasets by existing yolov7 pytorch models</p>

## News
**labelGo now supports the latest version of YOLOv5/YOLOv7, and automatic classes.txt file generation**

## Demonstration of semi-automatic labeling function
![image](https://github.com/zhuyuliang/labelGo-YoloAutoLabelImg/demo/demo1.gif) 
## Function demonstration of converting Yolo format to VOC format with one click
![image](https://github.com/zhuyuliang/labelGo-YoloAutoLabelImg/demo/demo2.gif) 

## Attention
<p>If there is a problem, please put it forward in the issue.</p>
<p>The annotation file is saved in the same location as the picture folder.</p>
<p>Recommended version of python: python 3.8.</p>
<p>Recommended for conda environments.</p>
<p>The item is completely free and it is forbidden to sell the item in any way. </p>
<p>This project has support for the latest version of YOLOv5/YOLOv7</p>


## Installation and use
<p>1.Fetching projects from git</p>

```bash
git clone https://github.com/zhuyuliang/labelGo-YoloAutoLabelImg.git
```

<p>2.Switching the operating directory to the project directory</p>

```bash
cd labelGo-YoloAutoLabelImg
```

<p>3.Installation environment</p>

```bash
pip install -r requirements.txt
```

<p>4.Launching applications</p>

```bash
python labelGo.py
```

<p>5. Click on the "Open directory" button to select the folder where the images are stored</p>

<p>6. Click on the "Auto Annotate" button to confirm that the information is correct and then select the trained yolov5 pytorch model to complete the auto annotation</p>

<p>7. Adjust the automatic annotation results according to the actual requirements and save them</p>

## Acknowledgements
Thanks to [cnyvfang](https://github.com/cnyvfang/labelGo-Yolov5AutoLabelImg)
