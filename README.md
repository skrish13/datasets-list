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

- [PASCAL VOC 2007/2012](http://host.robots.ox.ac.uk/pascal/VOC/); 20 Classes (5k train, 8k val, 5k test? not sure about test)
- [Microsoft COCO](http://cocodataset.org/#home); 330k images, >200k labeled, 80 Classes
- [ImageNet Object Detection](https://www.kaggle.com/c/imagenet-object-detection-challenge)
- OpenImages; 1.6 Million images, 545 trainable classes
- [GTSDB](http://benchmark.ini.rub.de/?section=gtsdb&subsection=dataset), [Tsinghua-Tencent-100K](https://github.com/asyncbridge/tsinghua-tencent-100k) -- small object (traffic sign) detection

##### Logo Detection
- [PL2K Dataset](https://arxiv.org/abs/1811.08009)
- [WebLogo-2M Dataset](http://www.eecs.qmul.ac.uk/~hs308/WebLogo-2M.html/)
- [FlickrLogo-32](http://www.multimedia-computing.de/flickrlogos/): A total of 32 logo classes, 70 images per class.
- [TopLogo-10](http://www.eecs.qmul.ac.uk/~hs308/qmul_toplogo10.html/): A total of 10 logo classes, 70 images per class.
- [OpenLogo Challenge](https://www.qmul-openlogo.github.io/): A total of 352 logo classes, 27,083 images total.

## Object Segmentation

- PASCAL VOC 2007/2012
- Microsoft COCO segmentation
- ImageNet Object Localization

##### Hand Segmentation/Detection

  - [VIVA](http://cvrr.ucsd.edu/vivachallenge/index.php/hands/hand-detection/)
  - [Oxford-Hands](http://www.robots.ox.ac.uk/~vgg/data/hands/)
  - [EgoHands](http://vision.soic.indiana.edu/projects/egohands/)
  - [EgoYouTubeHands](https://github.com/aurooj/Hand-Segmentation-in-the-Wild)
  - [GTEA](http://www.cbi.gatech.edu/fpv/)
  - [HandOverFace](https://github.com/aurooj/Hand-Segmentation-in-the-Wild)


## Self driving motivated
- CityScapes
  - CityPersons
- KITTI Dataset
- CamVid
- CalTech Pedestrians [see link for more related "Persons", "Pedestrians"]
- More to follow

## Visual Relationship
- Visual Genome
- [OpenImages](https://www.kaggle.com/c/google-ai-open-images-visual-relationship-track)
- [Visual-relevant Relationships Dataset](http://vrr-vg.com/)
- [VidVRD](https://lms.comp.nus.edu.sg/research/VidVRD.html)

## Video Object Detection

- Youtube-BoundingBoxes
  - https://research.google.com/youtube-bb/
  
## Grocery Datasets

- [SKU100K Dataset](https://github.com/eg4000/SKU110K_CVPR19) (CVPR19)
- [Grocery Products Dataset](https://sites.google.com/view/mariangeorge/datasets) (8k products)  (ECCV14)
- [CAPG-GP Dataset](http://zju-capg.org/capg-gp.html) (102 fine grained products)
- [Grozi120 Dataset](http://grozi.calit2.net/grozi.html)
- [Tobacco Shelves Dataset](https://github.com/gulvarol/grocerydataset) (Rack based)
- [WebMarket](http://yuhang.rsise.anu.edu.au/)
- [Selecta Vending Machine](https://github.com/tobiagru/ObjectDetectionGroceryProducts)
- [Hierarchical Grocery Store Image Dataset](https://github.com/marcusklasson/GroceryStoreDataset) (WACV19)
- [The Freiburg Groceries Dataset](https://github.com/PhilJd/freiburg_groceries_dataset) (25 Food categories)
- [SHORT-100 Grocery Dataset](http://www.bicv.org/datasets/short-100/) (shopping list)
- [CMU Grocery Dataset](http://www.cs.cmu.edu/~ehsiao/datasets.html) (CMU10_3D) (Kitchen Environment Images)
- [GMU Kitchen Dataset](https://cs.gmu.edu/~robot/gmu-kitchens.html)

## Local features/patch matching

- [Multi-view Stereo Correspondence Dataset](https://github.com/osdf/datasets/tree/master/patchdata)
- [PS-Dataset](https://github.com/rmitra/PS-Dataset/blob/master/DownloadDataset.md)
- [Mikolajczyk et al](http://www.robots.ox.ac.uk/~vgg/research/affine/)
- [GL3D Dataset](https://github.com/lzx551402/GL3D)

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
