# Fruit fresh and rotten classification

Nutrition plays an essential part in our daily life and we can be nutritious without a suitable amount of fruit. Due to the high consumption of this kind of food, we need massive productivities because we can't filter every single apple or banana. From this momentous problem, we have a golden solution that our goal is to create a model classifying fresh and rotten fruit!



## Project Structure
```bash
├── README.md
├── dataset "--> We download and use dataset in kaggle"
│   ├── test
│   │   ├── freshapples
│   │   ├── freshbanana
│   │   ├── freshoranges
│   │   ├── rottenapples
│   │   ├── rottenbanana
│   │   └── rottenoranges
│   └── train
│       ├── freshapples
│       ├── freshbanana
│       ├── freshoranges
│       ├── rottenapples
│       ├── rottenbanana
│       └── rottenoranges
└── fruit-classification.ipynb "--> baseline python notebook"
    ├── Import library
    ├── Download dataset
    ├── Import dataset
    ├── Handling dataset
    ├── Training model
    ├── Evaluate Model
    ├── Save model
    └── Demo
```


## Dataset
Training data and testing data that were used are sourced from kaggle: https://www.kaggle.com/sriramr/fruits-fresh-and-rotten-for-classification <br/> The dataset contains 13599 images of apple, banana, and orange divided into fresh and rotten each.
Dataset       | Directories     | Files
------------- | -------------   | -------------
Test          | freshapples     | 395
|             | freshbanana     | 381
|             | freshoranges    | 388
|             | rottenapples    | 601
|             | rottenbanana    | 530
|             | rottenoranges   | 403
Train         | freshapples     | 1693
|             | freshbanana     | 1581
|             | freshoranges    | 1466
|             | rottenapples    | 2342
|             | rottenbanana    | 2224
|             | rottenoranges   | 1595



## Build with
* [Convolution neural network (CNN) using tensorflow](https://www.tensorflow.org/tutorials/images/cnn)
* [InceptionV3](https://keras.io/api/applications/inceptionv3/)



## Installation

**Before you continue, ensure you meet the following requirements:**
- Download google colab
- Download file "kaggle.json" which we add to this git

#### How to use
- Run the code in google colab.
- In the "Import data", import file "kaggle.json" to download datasets.
- Wait for the trained model.
- Insert pictures from devices and wait for the result!!!


## Authors:
- **Triệu Gia Huy** - [huyg](https://github.com/huyg1108)
- **Nguyễn Tấn Bảo Lễ** - [baroleex](https://github.com/baroleex04)
