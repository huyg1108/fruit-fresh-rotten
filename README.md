# Fruit fresh and rotten classification

Dinh dưỡng là một phần không thể thiếu của cuộc sống và trong đó, trái cây đóng vai trò rất quan trọng. Do nhu cầu lớn nên cần đến hệ thống sản xuất lớn. Nhóm em lên ý tưởng về một mô hình phân loại trái cây theo 2 nhóm tươi và hỏng bằng phương pháp CNN.
## Structure
```bash
├── README.md
├── datasets "--> We download and use datasets in kaggle"
│   ├── test
│   │   ├── fresh apples
│   │   ├── fresh banana
│   │   ├── fresh oranges
│   │   ├── rotten apples
│   │   ├── rotten banana
│   │   └── rotten oranges
│   └── train
│       ├── fresh apples
│       ├── fresh banana
│       ├── fresh oranges
│       ├── rotten apples
│       ├── rotten banana
│       └── rotten oranges
└── fruit-classification.ipynb "--> baseline python notebook"
```

## Datasets
Training Data and Testing Data that were used are sourced from kaggle :https://www.kaggle.com/sriramr/fruits-fresh-and-rotten-for-classification <br/> The dataset contains 13599 images of apple, banana, and orange divided into fresh and rotten each.
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
- **Triệu Gia Huy**
- **Nguyễn Tấn Bảo Lễ**
