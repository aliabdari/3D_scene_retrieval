# Metaverse Apartment Retrieval Challenge 

This repository contains information about the baseline of the [Metaverse Apartment Retrieval Challenge ](http://ailab.uniud.it/apartment-recommendation-challenge/)

## Data
In this challenge, you are supposed to rank 3D scenes based on their textual description. In this challenge [3DFRONT](https://tianchi.aliyun.com/specials/promotion/alibaba-3d-scene-dataset) dataset with the corresponding descriptions for each scenario will be used. The 3DFRONT dataset can be obtained [here](https://tianchi.aliyun.com/dataset/65347). 

The descriptions can be found in the [descriptions](https://github.com/aliabdari/3D_scene_retrieval/tree/main/descriptions) directory. 

If you need point-of-view images to represent the scenes, they can be found at [this repository](https://github.com/xheon/panoptic-reconstruction) which could be downloaded through [front3d-2d.zip](https://kaldir.vc.in.tum.de/panoptic_reconstruction/front3d-2d.zip).

## Data Split
The data split which should be used for train/validation/test sets can be found at [data_split](https://github.com/aliabdari/3D_scene_retrieval/tree/main/data_split) 

## Pre Extracted Features
The are two sets of pre-extrated features for the scenes and descriptions. In the first set, you can find [open_clip_features](https://drive.google.com/file/d/1GfB1UHSb1KCqKLFjpk80I3Oi08ocwIBi/view?usp=sharing) and in the second set, you can find [resnet_bert_features](https://drive.google.com/file/d/1jDT7MUl3VWJY7fs6GlcWYUsI041V98Tm/view?usp=sharing). 

## Baseline Code
To have a baseline code you can use [this repository](https://github.com/aliabdari/FArMARe) containing a couple of approaches to rank the scenes based on the textual descriptions.
