# Contextawarecaptioning
Context-aware Captioning using CGCVIT and guided GPT

# Context-aware captioning #
**Dataset :**
*Flickr 30k :*
Images: https://www.kaggle.com/datasets/nunenuh/flickr30k?select=images
Annotations: https://www.kaggle.com/datasets/nunenuh/flickr30k?select=captions.txt 
*Training, validation and testing image for Flickr 30k* 
https://github.com/BryanPlummer/flickr30k_entities/blob/master/train.txt
https://github.com/BryanPlummer/flickr30k_entities/blob/master/val.txt
https://github.com/BryanPlummer/flickr30k_entities/blob/master/test.txt
*MSCOCO :*
Images : http://images.cocodataset.org
Annotations : http://images.cocodataset.org/annotations/annotations_trainval2017.zip
*Training, validation and testing image for MSCOCO*
http://images.cocodataset.org/zips/train2017.zip
http://images.cocodataset.org/zips/val2017.zip
http://images.cocodataset.org/zips/test2017.zip

**Required Installation of the following package**

!pip install tensorflow==2.18.0
!pip install Keras-Preprocessing
!pip install --quiet vit-keras
!pip install tensorflow_addons
!pip install pycocoevalcap
!pip install gtts
!pip install numpy==2.0.0
!pip install pandas==2.2.2

**Fit the code according to dataset**

