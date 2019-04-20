# SODdataset


Dataset|Pub. / Year|URL|Source|Info.
:-: | :-: | :-: | :-: | :-:
**MSRA**|Learning to Detect a Salient Object, **CVPR 2007**.|Not Found|Not Specific| Image set A: 20840 images, Image set B: 5000 images selected from A with less ambiguity. (Training set: Randomly select 2000 from set A, and 1000 from set B)
**MSRA-B**|Salient Object Detection: A Discriminative Regional Feature Integration Approach, **CVPR 2013**.|[Homepage](https://people.cs.umass.edu/~hzjiang/drfi/)|Image set B of MSRA|2500 images for training, 500 for validation, and 2000 for testing (full list can be found at the bottom of the project page.)
**MSRA10K**<br>(**THUS10000**)|Global Contrast based Salient Region Detection, **PAMI 2015**.|[Homepage](https://mmcheng.net/msra10k/)|MSRA|--
**SED1/2**|Image Segmentation by Probabilistic Bottom-up Aggregation and Cue Integration, **CVPR 2007**.|[Homepage](http://www.wisdom.weizmann.ac.il/~vision/Seg_Evaluation_DB/index.html)|Unknown|200 images, 1 or 2 clear objects.
**MSRA-1000**|Frequency-tuned Salient Region Detection, **CVPR 2009**.|[Homepage](https://ivrlwww.epfl.ch/supplementary_material/RK_CVPR09/) |MSRA| Contour label. Work that be evaluated on this dataset has less power of  persuasion, suggested by CMM.
**CSSD**|Hierarchical Saliency Detection, **CVPR 2013**.|[Homepage](http://www.cse.cuhk.edu.hk/leojia/projects/hsaliency/) |BSD300, VOC dataset and internet.| Complex Scene Saliency Dataset(CSSD). 200 images.(Normally used for test.)
**ECSSD**|Hierarchical Image Saliency Detection on Extended CSSD, **PAMI 2016**.|[Homepage](http://www.cse.cuhk.edu.hk/leojia/projects/hsaliency/dataset.html)|Internet| Semantically meaningful but structurally complex images. 1000 images.(Normally used for test.)
**THUR**|SalientShape: Group Saliency in Image Collections, **The Visual Computing 2014**.|[Homepage](https://mmcheng.net/gsal/)|Flickr| 6000+ images for 5 categories: butterfly, coffe mug, dog jump, griaffe, and plane.
**PASCAL-S**|The Secrets of Salient Object Detection, **CVPR 2014**.|[Homepage](http://cbi.gatech.edu/salobj/)|the validation set of the PASCAL VOC 2010| Relative saliency between salient instances. 850 images(Normally used for test.).
**HKU-IS**|Deep Contrast Learning for Salient Object Detection, **CVPR 2015**.|[Homepage](https://i.cs.hku.hk/~yzyu/research/deep_saliency.html)|Unknown| 2500 images for training, 500 for validation, and 1447 for testing.
**Judd-DB**|What is a salient object? A dataset and a baseline model for salient object detection, **TIP 2015**|Unknown|Judd|900 images.
**DUT-OMRON**|Saliency Detection Via Graph-Based Manifold Ranking, **CVPR 2013**.|[Homepage](http://saliencydetection.net/dut-omron/)|SUN database| 5019 images for testing. More details could be found in their [FCV paper](http://saliencydetection.net/dut-omron/download/FCV2014.pdf). 
**DUTS**|Learning to Detect Salient Objects with Image-level Supervision, **CVPR 2017**.|[Homepage](http://saliencydetection.net/duts/)|ImageNet DET datasets|10553 training images and 5019 test images. 
**ILSO**|Instance-Level Salient Object Segmentation, **CVPR 2017**.|[Homepage](http://www.sysu-hcp.net/instance-level-salient-object-segmentation/)|ECSSD, DUT-OMRON, HKU-IS, and MSO datasets.|Two-thirds of the chosen images contain multiple occluded salient object instances while the remaining one-third consists of images with no salient regions, a single salient object instance or multiple salient instances without occlusion. Totally 1000 images, 500 for training, 200 for validation, and 300 for testing.
**XPIE**|What is and what is not a salient object? learning salient object detector by ensembling linear exemplar regressors, **CVPR 2017**.|[Homepage](http://cvteam.net/projects/CVPR17-ELE/ELE.html)|Panoramio, ImageNet, and two fixation datasets.|10000 images.
**SOC**|Salient Objects in Clutter: Bringing Salient Object Detection to the Foreground, **ECCV 2018.**|[Homepage](http://dpfan.net/SOCBenchmark/)|MSCOCO|6K images(3.6K for training, 1.2K for validation, 1.2K for testing). Accurate and clear boundary label. instance-level segmentation. Visual attributes for result evaluation.
**SOS**|Salient Object Subitizing, **CVPR 2015**.|[Homepage](http://cs-people.bu.edu/jmzhang/sos.html)|6900images in total. 2064 from the COCO, 2141 from the VOC07, 1610 from the ImageNet, 1085 from the SUN.| This dataset is built for predicting the existence and the number of salient objects in a scene.**MSO is a subset of SOS, which is used for reasonable testing.**
**BSDS**|A Database of Human Segmented Natural Images and its Application to Evaluating Segmentation Algorithms and Measuring Ecological Statistics, **ICCV 2001**.|[Homepage](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/)|Unknown| Original version: 200 training images, 100 testing images. Extented version: 200 test images were added.




Remaining questions:
1. More details about how to split train/val/test sets for MSRA10K.

