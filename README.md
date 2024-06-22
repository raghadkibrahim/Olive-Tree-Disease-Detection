> "If the Olive Trees knew the hands that planted them, Their Oil would become Tears." - Mahmoud Darwish

My first project is dedicated to my dear grandfather, the wisest and most peaceful man that I have ever known. He was displaced in 1967 and passed away in 2015 far away from his beloved trees, or any trees for that matter, in the refugee camps of Zarqa, Jordan. Growing up, he vehemently refused to move to a better place unless it was to go back home to his Olive Trees. He never did.

My grandfather was an Arabic teacher, and growing up, he used to tell us grandkids stories about the Olive Trees he left behind but would often refer to the individual trees using various female names, and I never understood why until until I read the works of poet Mahmoud Darwish as an adult. Author Fady Joudah who translated a collection of Darwish's poetry speaks about it in his translation *The Butterfly's Burden*: 
> "[Darwish's] early poetry transformed the dispossessed land into the unattained beloved whose images inform the poet's lexicon. The features of Palestine - its flowers and birds, towns and waters - became integrated in the poet's witness to the string of tragedies, political and humanitarian, that have continued to afflict his people." - Fady Joudah in *The Butterfly's Burden*

While AI is being used to carry out brutal bombing campaigns, I would like to use it to help heal the Olive Trees he loved so dearly. The way people have been fighting for Palestine made me believe in the power of data and telling stories, because all it took was the world knowing the one truth for the tides to turn.

# Disease Detection in Olive Trees using AI
The Olive Tree, an ancient symbol of peace and endurance, holds significant cultural and agricultural importance across the Mediterranean region and beyond. The production of olive oil is facing a significant threat nowadays due to climate change and the spread of diseases. This project explores the application of computer vision techniques for the analysis and classification of leaf images to identify potential diseases or health issues. The dataset used in this paper consists of images of leaves from three classes: healthy leaves, leaves infected with Aculus Olearius disease, and leaves affected by Peacock Spot disease. The goal is to develop an image classification model capable of accurately distinguishing between these classes based on features extracted from the images. Overall, this project aims to contribute to the field of agricultural diagnostics by providing a reliable tool for automated detection and classification of leaf diseases.

### Objectives:
- Construct a model for image classification of diseases in olive leaves

### [Table of Contents](#table-of-contents)
> 1. [Project Overview](#1)
> > 1.1 [Motivation](#1.1)  
> > 1.2 [Dataset](#1.2)
> 
> 2. [Set up](#2)
> > 2.1 [Installation](#2.1)  
> > 2.2 [Directory Structure](#2.2)
> 
<hr>

<a id='1'></a>
# Project Overview  

<a id='1.1'></a>
## 1.1 Motivation
[(Back to top)](#table-of-contents)

Olive trees are suseptible to getting sick with some diseases that could affect a tree's health and its ability to produce olives, which makes it very important for farmers to be able to catch these conditions early on to address them before harvesting season.  These conditions include diseases like Aculus Olearius which is caused by mites and causes leaf discoloration, as well as Peacock Spot Disease which causes dark spots on an olive leaf. More details about the symptoms and causes of these two diseases will be provided in the next section.

Most farmers rely on traditional techniques, such as visual observation, or biological tests and fungal analysis, to detect these diseases. However, these methods require significant expertise and resources, including time. Hence, increasing the efficiency of the process of detecting and diagnosing olive trees becomes imperative to save as many trees as possible. The potential for improving disease diagnostics lies in developing effective alternatives to traditional plant disease identification methods, including those for olive trees. We can utilize technological advancements in machine learning and deep learning to facilitate precise disease identification through data and image analysis.


<a id='1.2'></a>
## 1.2 Dataset:
[(Back to top)](#table-of-contents)

The dataset used in this project is a collection of over 3,400
images of olive leaves collected from Denizli City, Turkey.
The images are classified into the following classes:  

- Leaves infected with Aculus Olearius.
- Leaves infected with peacock spot.
- Healthy olive leaves.
<hr>

<a id='2'></a>
# 2. Set up

<a id='2.1'></a>
## 2.1 Installation
[(Back to top)](#table-of-contents)

```shell
gh repo clone raghadkibrahim/Olive-Tree-Disease-Detection
```

<a id='2.2'></a>
## 2.2 Directory Structure
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
