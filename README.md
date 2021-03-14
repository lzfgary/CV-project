# Mushroom Genus Classification

## Overview:
  
  The purpose of this project is to classify mushrooms into their corresponding genus based on their images. With the dataset consists of images from nine commonly found genera of mushrooms, we trained two models that could distinguish mushrooms.
  
## Problem setup & Data used:
- The data that are used to train the models is collected by [CatoDogo from Kaggle][1].
  - The dataset consists of `6714` images from `9` commonly found Mushroom genera in Northen Europe:
    - `Agaricus`, `Amanita`, `Boletus`, `Cortinarius`, `Entoloma`, `Hygrocybe`, `Lactarius`, `Russula`, `Suillus`
  - The dataset is randomly splitted into `train_dataset` and `test_dataset`.
    - Model 1:
      - `train_dataset`: 4000 images
      - `test_dataset`: 2714 images
      - All images are:
        - normalized (μ, σ):
          - channel R, G, B: `(0.5, 0.5)`
        - resized to `256 * 256` pixels
    - Model 2:
      - `train_dataset`: 6042 images
      - `test_dataset`: 672 images
      - All images are:
        - resized to `256 * 256` pixels
        - center cropped to `224 * 224` pixels
        - normalized (μ, σ):
          - channel R: `(0.485, 0.229)`
          - channel G: `(0.456, 0.224)`
          - channel B: `(0.406, 0.225)`
## Techniques:

## Area of improvements:

## Link to the Colab Notebook:

[1]: https://www.kaggle.com/maysee/mushrooms-classification-common-genuss-images
