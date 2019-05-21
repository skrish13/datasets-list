# Computer Vision Datasets

Probably this exists elsewhere I guess but contributing there/making sure that its maintained is not easier than creating our own.
Making it comprehensive with full detailes takes time so will do it over time. Just wanted to create asap to log few uknown old datasets initally.
Some of the datasets has multiple tracks, like classification and segmentation and detection, so refer to the link from above categories if repeated.
Mostly in order of current significance which is directly proportional to challenging nature/size of dataset.

## Classification


- OpenImages
  - 9 million images, 5000 trainable labels
  - https://github.com/openimages/dataset
- ImageNet
  - www.image-net.org
  - 1 million images, 1000 labels  
- CIFAR10/CIFAR100
  - 32x32
  - 60,000/10 Classes :: 60,000/100 Classes
  - https://www.cs.toronto.edu/~kriz/cifar.html
- TinyImages
  - http://horatio.cs.nyu.edu/mit/tiny/data/index.html
  - Source of CIFAR Dataset's creation
  
## Object Detection

- PASCAL VOC 2007/2012
  - 20 Classes (5k train, 8k val, 5k test? not sure about test)
  - http://host.robots.ox.ac.uk/pascal/VOC/
- Microsoft COCO
  - 330k images, >200k labeled, 80 Classes
  - http://cocodataset.org/#home
- ImageNet Object Detection
  - https://www.kaggle.com/c/imagenet-object-detection-challenge
- OpenImages
  - 1.6 Million images, 545 trainable classes
- [GTSDB](http://benchmark.ini.rub.de/?section=gtsdb&subsection=dataset), [Tsinghua-Tencent-100K](https://github.com/asyncbridge/tsinghua-tencent-100k) -- small object (traffic sign) detection

## Object Segmentation

- PASCAL VOC 2007/2012
- Microsoft COCO segmentation
- ImageNet Object Localization

## Self driving motivated
- CityScapes
  - CityPersons
- KITTI Dataset
- CamVid
- CalTech Pedestrians [see link for more related "Persons", "Pedestrians"]
- More to follow

## Video Object Detection

- Youtube-BoundingBoxes
  - https://research.google.com/youtube-bb/
  
## Grocery Datasets

- SKU100K Dataset (CVPR19)
  - https://github.com/eg4000/SKU110K_CVPR19
- Grocery Products Dataset (8k products)  (ECCV14)
  - https://sites.google.com/view/mariangeorge/datasets
- CAPG-GP Dataset (102 fine grained products)
  - http://zju-capg.org/capg-gp.html
- CMU Grocery Dataset (CMU10_3D) (Kitchen Environment Images)
  - http://www.cs.cmu.edu/~ehsiao/datasets.html
- SHORT-100 Grocery Dataset (shopping list)
  - http://www.bicv.org/datasets/short-100/
- The Freiburg Groceries Dataset (25 Food categories)
  - https://github.com/PhilJd/freiburg_groceries_dataset
- Grozi120 Dataset
  - http://grozi.calit2.net/grozi.html  
- Turkey Cigarette Dataset (Rack based)
  - https://github.com/gulvarol/grocerydataset

## Emotion Datasets

- [Multimodal EmotionLines](https://affective-meld.github.io/) :star:
- [Affect in the Wild](https://ibug.doc.ic.ac.uk/resources/first-affect-wild-challenge/)
- [One-Minute Gradual-Emotion](https://www2.informatik.uni-hamburg.de/wtm/OMG-EmotionChallenge/)

##### Smaller ones (comparitively)
- [EmotiW](https://sites.google.com/site/emotiwchallenge/)

## Misc

- [iNaturalist Challenge](https://www.kaggle.com/c/inaturalist-challenge-at-fgvc-2017)
  - Fine-grained classification challenge spanning 5,000 species.
  - Download [link](https://github.com/visipedia/inat_comp#data) [250GB]
- [Wildlife detection in videos](https://www.drivendata.org/competitions/49/deep-learning-camera-trap-animals/)
