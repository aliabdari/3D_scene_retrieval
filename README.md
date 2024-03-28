# Metaverse Apartment Retrieval Challenge 

This repository contains information about the baseline of the [Metaverse Apartment Retrieval Challenge ](http://ailab.uniud.it/apartment-recommendation-challenge/)

## Registration
If you are interested in this challenge please register through [this form](https://docs.google.com/forms/d/e/1FAIpQLSeWG1h2Pn6ix50_myZYE816dENbYzWhaGAEdQdAzrjekr4Uhw/viewform).

## Data
In this challenge, you are supposed to rank 3D scenes based on their textual description. [3DFRONT](https://tianchi.aliyun.com/specials/promotion/alibaba-3d-scene-dataset) dataset with the corresponding descriptions for each scenario will be used.

- The 3DFRONT dataset can be obtained [here](https://tianchi.aliyun.com/dataset/65347). 

- The descriptions can be found in the [descriptions](https://github.com/aliabdari/3D_scene_retrieval/tree/main/descriptions) directory. 

- If you want to use point-of-view images to represent the scenes, they can be found at [this repository](https://github.com/xheon/panoptic-reconstruction) which can be downloaded through [front3d-2d.zip](https://kaldir.vc.in.tum.de/panoptic_reconstruction/front3d-2d.zip).

## Data Split
The data split which should be used for train/validation/test sets can be found at [data_split](https://github.com/aliabdari/3D_scene_retrieval/tree/main/data_split).

## Pre Extracted Features
There are two sets of pre-extracted features for the scenes and descriptions. In the first set, you can find [open_clip_features](https://drive.google.com/file/d/1RDV1JaUasXqzFfRhlj_DAoRgYg3RWwZO/view?usp=sharing) and in the second set, you can find [resnet_bert_features](https://drive.google.com/file/d/1G80D5_8Q7jZPn5bGLeK1zPzAxZWQCa_G/view?usp=sharing). Each of these sets contains two directories including images (point of view images features) and descriptions which contains sentence level and token level features.

## Baseline Code
To have a baseline code you can use [this repository](https://github.com/aliabdari/FArMARe) containing a couple of approaches to rank the scenes based on the textual descriptions.
