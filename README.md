# Brachial Plexus Segmentation
[![Contributors](https://img.shields.io/github/contributors/AIforAnesthesiology/Brachial-Plexus-Segmentation)](https://github.com/AIforAnesthesiology/Brachial-Plexus-Segmentation/graphs/contributors)
[![Last commit](https://img.shields.io/github/last-commit/AIforAnesthesiology/Brachial-Plexus-Segmentation)](https://github.com/AIforAnesthesiology/Brachial-Plexus-Segmentation/commits/master)
[![Release date](https://img.shields.io/github/release-date/AIforAnesthesiology/Brachial-Plexus-Segmentation)](https://github.com/AIforAnesthesiology/Brachial-Plexus-Segmentation/releases)
[![Licence](https://img.shields.io/github/license/AIforAnesthesiology/Brachial-Plexus-Segmentation)](https://github.com/AIforAnesthesiology/Brachial-Plexus-Segmentation/blob/main/LICENSE) 

Status: in preparation <!-- in preparation / ongoing (data collection) / ongoing (analysis) / completed -->  
Last updated: 27-05-2021 <!-- date when the information in this readme file was last updated -->

[![Repository DOI](https://img.shields.io/badge/Github_DOI-00000-blue)](#) <!-- Repository DOI for this github repository. Request a DOI from [Zenodo](https://zenodo.org) and replace '00000' -->

## Short summary

### Rationale
A failed nerve block not only results in a bad experience for the patient, it might even lead to damage to the patients’ health and in some cases complications could even threaten life.

It’s essential to recognise ultrasound anatomy when performing nerve blocks, however this may sometimes be hampered by patients’ habitus.

A possible solution might be the recent rise in artificial intelligence, especially deep learning. Nowadays, deep learning is being used in all walks of life. Facial recognition systems are being made, Google knows what objects are on your photos and manages to classify them correctly.

### Objective(s)
In this study we will attempt to create a dataset of ultrasound images depicting the brachial plexus and use this dataset to train an U-net model in order to identify the region of interest in these images, which may potentially be used in clinical practise.

**Primary Objective**\
1. Construct a dataset of ultrasound images depicting the brachial plexus with manual image segmentation

**Secondary Objective(s)**\
1. Train an U-net deep learning model using the dataset and teach it to properly identify the brachial
plexus

### Study design
We will prospectively collect 500 ultrasound images of 250 healthy adults by contacting colleagues in both hospitals, requesting their participation in this study. Ultrasound images of both the left and right brachial plexus will be obtained with an on-screen orientation where left equals lateral.

We will then feed the ultrasound images to the U-net model and set the manually marked masks (of the brachial plexus) as the output segmentation map to train the model.

### Study population
Healthy adults with intact brachial plexus without previous surgery or radiotherapy in the area.

### Main study parameters/endpoints
**Dataset creation**\
- 500 ultrasound images of the supraclavicular region with segmentation

**U-net model creation**\
- Intersection over union per image (see Eq 1.)
- Model accuracy (see Eq 2.)
- Ultrasound images with brachial plexus segmented by the machine learning model

### Results


### Conclusion


## Publications


<!--  
	Create a list of your publications related to this project. 

	Example:
	* Author One, Author Two, Author Three, et al. Title of the journal article. J Abbr. 2021;20(3):100-110. doi:[000.00000-0000](http://doi.org/000.00000-0000). 
 -->