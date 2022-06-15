Create a data folder under the repository,

```
cd {repo_root}
mkdir data
```

- **VOC**:
  Download the voc images and annotations from [VOC2007](http://host.robots.ox.ac.uk/pascal/VOC/voc2007) or [VOC2012](http://host.robots.ox.ac.uk/pascal/VOC/voc2012). Make sure to put the files as the following structure:
  
```
data
  ├──VOCDevkit
  │  ├── VOC2007
  │  │   ├── Annotations  
  │  │   ├── ImageSets
  │  │   ├── JPEGImages
  │  │   └── ...
  │  └── VOC2012
  │      ├── Annotations  
  │      ├── ImageSets
  │      ├── JPEGImages
  │      └── ...
  └──COCO
  
  ```
  
- **COCO**:
  Download the coco images and annotations from [coco website](http://cocodataset.org/#download). Make sure to put the files as the following structure:
  
```
data
  ├──VOCDevkit
  └──COCO
     ├── annotations
     │   ├── instances_train2014.json
     │   ├── instances_train2017.json
     │   ├── instances_val2014.json
     │   └── instances_val2017.json
     │── images
     │   ├── train2014
     │   ├── train2017
     │   ├── val2014
     │   └── val2017
     └── anno_pickle
         ├── COCO_train2014.pkl
         ├── COCO_val2014.pkl
         ├── COCO_train2017.pkl
         └── COCO_val2017.pkl
  ```
  
