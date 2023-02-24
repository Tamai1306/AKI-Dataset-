# AKI-Dataset-Kanji Dataset

## Abstract
In this repository Augmented KajiSVG Image  Dataset (AKI-Dataset) is presented. This dataset is based on the [KanjiSVG Dataset](https://kanjivg.tagaini.net/index.html "KanjiSVG Dataset"), which is copyright © 2009-2012 Ulrich Apel and released under the Creative Commons Attribution-Share Alike 3.0 license. The AKI-Dataset takes the last version of KanjiSVG Dataset, which includes more than 10000 characters, and made a data augmentation of each character. For each character image, geometric transformations and noise addition is performed, generating 60 new samples for each character, resulting on 715103 images in total for the AKI-Dataset. All this images are split in several files due to the space limitations of Github. Furthermore, a CSV file is provided which includes significant information about the AKI-Dataset, including in separate columns the name of the image, the character label of the character and the number of strokes for that character. 

## Repository Structure
The repository contains 19 main files:
- 16 split zip files - This files includes all the AKI-Dataset characters images (Images20230110.zX)
- 1 ReadME file - ReadMe.md
- 1 zip file - Images20230110.zip This file include the split zip file to unzip it in a directory and get all the images
- 1 CSV file - AKI_Dataset20230110.csv This file include vital information about the AKI-Dataset

## Usage
To extract the zipped multi-file archive the following bash command has to be ran:
```bash
$ unzip Images20230110.zip -d ./Images
```

