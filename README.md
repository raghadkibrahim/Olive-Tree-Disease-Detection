

# Project Overview
This project explores the application of computer vision techniques for the analysis and classification of leaf images to identify potential diseases in the tree. The dataset used in this paper consists of images of leaves from three classes: healthy leaves, leaves infected with Aculus Olearius disease, and leaves affected by Peacock Spot disease. The goal is to develop an image classification model capable of accurately distinguishing between these classes based on features extracted from the images. Overall, this project aims to contribute to the field of agricultural diagnostics by providing a reliable tool for automated detection and classification of leaf diseases.

### [Table of Contents](#table-of-contents)
> 1. [Set up](#1)
> > 1.1 [Installation](#1.1)  
> > 1.2 [Directory Structure](#1.2)
> 2. [Dataset](#2)
<hr>

<a id='1'></a>
# 1. Set up

<a id='1.1'></a>
## 1.1 Installation
[(Back to top)](#table-of-contents)

```shell
gh repo clone raghadkibrahim/Olive-Tree-Disease-Detection
```

<a id='1.2'></a>
## 1.2 Directory Structure
[(Back to top)](#table-of-contents)

```
$ pwd
/path/to/project/directory/
$ ls
|- notebooks/
   |- 1. Project_Overview.ipynb
   |- 2. Data_Preprocessing.ipynb
   |- 3. EDA.ipynb
   |- 4. Baseline_Models.ipynb
   |- 5. Advanced_Models.ipynb
   |- archive/
	     |- Olive.ipynb
|- README.md
|- dataset/
   |- training/
      |- healthy
      |- aculus_olearius
      |- peacock_spot
   |- testing/
      |- healthy
      |- aculus_olearius
      |- peacock_spot
|- environment.yml
```

<a id='2'></a>
## 2. Dataset:
[(Back to top)](#table-of-contents)

The dataset used in this project is a collection of over 3,400
images of olive leaves collected from Denizli City, Turkey.
The images are classified into the following classes:  

- Leaves infected with Aculus Olearius.
- Leaves infected with peacock spot.
- Healthy olive leaves.
<hr>
