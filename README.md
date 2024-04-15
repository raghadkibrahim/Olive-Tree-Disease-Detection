***“If the olive trees knew what's happening to the hands that planted them, their oil would turn into tears”***


# Abstract
 The Olive Tree, an ancient symbol of peace and endurance, holds significant cultural and agricultural importance across the Mediterranean region and beyond. The production of olive oil is facing a significant threat nowadays due to climate change and the spread of diseases. This project explores the application of computer vision techniques for the analysis and classification of leaf images to identify potential diseases or health issues. The dataset used in this paper consists of images of leaves from three classes: healthy leaves, leaves infected with Aculus Olearius disease, and leaves affected by Peacock Spot disease. The goal is to develop an image classification model capable of accurately distinguishing between these classes based on features extracted from the images. Overall, this project aims to contribute to the field of agricultural diagnostics by providing a reliable tool for automated detection and classification of leaf diseases.

### Objectives:
- Construct a model for image classification of diseases in olive leaves

## Table of Contents
<i><p style="border-width:2px; border-style:solid; border-color:#808080; padding: 0.5em;text-align:left;">PART I: Project Overview</p></i>

> **1. [Introduction](#intro)**
> > 1.1 [Motivation](#1.1)  
> > 1.2 [Background](#1.2)  
> > 1.3 [Dataset](#1.3)  
>
<i><p style="border-width:2px; border-style:solid; border-color:#808080; padding: 0.5em;text-align:left;">PART II: Data Analysis</p></i>
> 
> **2. [Methodology](#methodology)**
> > 2.1 [Approach](#2.1)   
> > 2.2 [Dataset](#2.2)     
> > 2.3 [Dependencies](#2.3)   
> > 2.4 [Getting Started](#2.4)
>
> **3. [Data Preprocessing](#preprocessing)**
> > 3.1 [A First Look At The Data](#3.1)  
> > 3.2 [Identifying Image Imbalance](#3.2)  
> > 3.3 [Plotting Image Size](#3.3)     
>
> **4. [Exploratory Data Analysis](#eda)**   
> > 4.1. [Orientation](#4.1)  
> > 4.2. [RGB Channels](#4.2)  
>
> **5. [Baseline Models and Evaluation](#baseline_model)**
>
> **6. [Advanced Models and Evaluation](#advanced_model)**
>
<i><p style="border-width:2px; border-style:solid; border-color:#808080; padding: 0.5em;text-align:left;">PART III: Findings</p></i>
> 
> **6. [Discussion](#discussion)**  
    </font>
<hr>

<a id='1.1'></a>
## 1.1 Motivation

Olive trees are suseptible to getting sick with some diseases that could affect a tree's health and its ability to produce olives, which makes it very important for farmers to be able to catch these conditions early on to address them before harvesting season.  These conditions include diseases like Aculus Olearius which is caused by mites and causes leaf discoloration, as well as Peacock Spot Disease which causes dark spots on an olive leaf. More details about the symptoms and causes of these two diseases will be provided in the next section.

Most farmers rely on traditional techniques, such as visual observation, or biological tests and fungal analysis, to detect these diseases. However, these methods require significant expertise and resources, including time. Hence, increasing the efficiency of the process of detecting and diagnosing olive trees becomes imperative to save as many trees as possible. The potential for improving disease diagnostics lies in developing effective alternatives to traditional plant disease identification methods, including those for olive trees. We can utilize technological advancements in machine learning and deep learning to facilitate precise disease identification through data and image analysis.

<a id='1.2'></a>
## Background  

Aculus Olearius is a disease caused by Aceria Oleae, a mite that belongs to eriophyid mites. This barely visible mite is a worm-like mite with circular cross section which dimensions are in the micrometers range, yet its microscopic size doesn't stop it from inflicting great harm to olive trees as it is the main pest found in olive trees in the Mediterranean region. Cases of this condition were reported in Palestine, Egypt, Tunisia, and Turkey. The mite feeds on the growing points in the leaves, thus causing deformations in the way a leaf grows. Therefore younger trees tend to be more vulnerable to these brutal attacks. The pest may even kill the productive center for the plant significantly inhibiting its growth.

Peacock Spot Disease is another common fungal disease that affects olive trees. It is caused by the fungus Spilocaea oleagina, but took its named from its distinctive peacock feather-like spots that appear on the leaves of an infected tree. These spots are usually dark, circular, and have a yellow halo around them, making them quite noticeable against the green of the olive leaves. These can lead to premature leaf drop, weakening the tree over time. With the tree being infected, its ability to photosynthesize is practically diminished inhibiting its ability to grow fruits and can spread quickly to other trees.

In both cases we can see why an early diagnosis is ablsolutely crucial to a farmer.

<a id='1.3'></a>
## Dataset:

The dataset used in this project is a collection of over 3,400 
images of olive leaves collected from Denizli City, Turkey. 
The images are classified into the following classes:  

- Leaves infected with Aculus Olearius.
- Leaves infected with peacock spot.
- Healthy olive leaves.