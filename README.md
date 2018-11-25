# COCO API for CrowdPose
The origin codes are from https://github.com/cocodataset/cocoapi

## How to use
```
git clone https://github.com/cocodataset/cocoapi
cd cocoapi/PythonAPI/pycocotools
mv coco.py coco.py_old; mv cocoeval.py cocoeval.py_old
git clone https://github.com/BernieZhu/CrowdPose-cocoapi
cd CrowdPose-cocoapi
cp coco.py cocoeval.py ..
```