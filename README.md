# dataset-project

## Description

This project includes a dataset of images and their annotations, generated using the Labelme library. The original dataset is stored in a main folder named `data`, which contains two subfolders:
- `images`: Contains all the images of the dataset.
- `labels`: Contains the corresponding annotations, generated with Labelme.

A Jupyter notebook titled `datasetaugmentation.ipynb` is included for dataset augmentation. This notebook facilitates the augmentation of the dataset by generating additional versions of the images and labels.

## Dataset Augmentation

After augmentation, the dataset is divided into three subfolders:
- `train`: Contains the augmented training data with their labels.
- `test`: Contains the augmented testing data with their labels.
- `val`: Contains the augmented validation data with their labels.

These new subfolders are organized within a main folder named `augdata`.

## Project Structure

```plaintext
Project Root/
│
├── data/
│   ├── images/
│   └── labels/
│
├── augdata/
│   ├── train/
│   │   ├── images/
│   │   └── labels/
│   ├── test/
│   │   ├── images/
│   │   └── labels/
│   └── val/
│       ├── images/
│       └── labels/
│
└── datasetaugmentation.ipynb

