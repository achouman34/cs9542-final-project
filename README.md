# CS 9542 Final Project

**Group Members**: Ali Chouman, Alfredo Varela Vega, Wenyi Yao

This repository is the formal submission of all project files and code for the project, "**Leveraging Segmentation and Vision-Language Models for Vehicle Scene Captioning**".

# Dataset Files
The dataset is a ZIP file containing 50 image files under the folder *indian_vehicle_images* and their corresponding caption text files under the folder *indian_vehicle_txt_annos*.

# Project Files

- **panoptic_SAM.ipynb**
	 - performs panoptic segmentation with SAM on vehicle image dataset
- **grounding_dino_and_SAM.ipynb**
	- combines Grounding DINO zero-shot object detection with SAM
- **preprocessing_for_finetuning_microsoft_git.ipynb**
	- performs pre-processing on dataset before fine-tuning GIT
- **finetuning_microsoft_git.ipynb**
	- performs fine-tuning on GIT
