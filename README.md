# MDGAN

### Requirements and Dependencies
- python 3.8
- Pytorch 1.9
- torchvision==0.10.0
- easydict
- nltk
- scikit-image
- At least 1x12GB NVIDIA GPU

### Installation

Clone this repo.
```
git clone https://github.com/zxcnmmmmm/MDGAN.git
cd MDGAN/code/
```

### Datasets Preparation
1. Download the preprocessed metadata for [birds](https://drive.google.com/open?id=1O_LtUP9sch09QH3s_EBAgLEctBQ5JBSJ) [coco](https://drive.google.com/open?id=1rSnbIGNDGZeHlsUlLdahj0RJ9oo6lgH9) and save them to `data/`
2. Download the [birds](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html) image data. Extract them to `data/birds/`.Raw text data of CUB dataset is avaiable [here](https://drive.google.com/file/d/1KyTQVo67izP4NEAAZBRnqrGG3yRh3azD/view?usp=sharing)
3. Download [coco](http://cocodataset.org/#download) dataset and extract the images to `data/coco/images/`

### Download pre-train model
1. [pre-trained text encoder for bird] Download the [pre-trained text encoder](https://drive.google.com/open?id=1GNUKjVeyWYBJ8hEU-yrfYQpDOkxEyP3V) for CUB and save it to `../bird/`
2. [pre-trained text encoder for coco] Download the [pre-trained text encoder](https://drive.google.com/open?id=1zIrXCE9F6yfbEJIbNP5-YrEe2pZcPSGJ) for coco and save it to `../coco/`
3. [DMGAN for bird](). Download and save it to `./code/saved_models/bird/`
4. [DMGAN for coco](). Download and save it to `./code/saved_models/coco/`

### Testing pipelines
Run `python main.py --cfg cfg/bird.yml`

### Results
Example results on the CUB. 

Example results on the COCO. 
