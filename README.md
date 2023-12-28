# LGG Segmentation Dataset Analysis

## Abstract
This report presents an analysis of the LGG Segmentation Dataset, encompassing brain MR images and manual FLAIR abnormality segmentation masks from The Cancer Genome Atlas (TCGA) lower-grade glioma collection. It covers data preprocessing, descriptive statistics, visualization techniques, correlation analysis, and a Power BI dashboard for a comprehensive dataset analysis.

## Introduction
The LGG Segmentation Dataset comprises brain MR images and corresponding FLAIR abnormality segmentation masks from The Cancer Imaging Archive (TCIA). This report aims to provide insights into brain tumor characteristics and segmentation.

## Dataset Description
- **Data Source**: The Cancer Imaging Archive (TCIA)
- **Patient Information**: 110 patients from the TCGA lower-grade glioma collection
- **Image Format**: .tif format with 3 channels per image
- **Image Sequences**: Pre-contrast, FLAIR, and post-contrast sequences available for most cases
- **Mask Format**: Binary, 1-channel images segmenting FLAIR abnormalities

## Data Preprocessing
Various preprocessing steps were performed, including data cleaning, normalization, and alignment of images and masks.

## Descriptive Statistics
Statistical measures such as mean, standard deviation, minimum, maximum, and quartiles were calculated for relevant attributes.

## Visualization Techniques
Histograms, box plots, scatter plots, and heatmaps were generated to visualize image intensity distributions, tumor size distributions, and correlations.

## Correlation Analysis
Correlation coefficients and matrices were computed to identify potential associations and dependencies between variables.

## Brain Tumor Prediction using UNet Model
A UNet model was developed to predict brain tumor presence based on the dataset:

### Model Architecture: UNet
The UNet model architecture, consisting of an encoder-decoder structure with skip connections, was used for tumor segmentation.

### Data Preparation
Data augmentation techniques and splitting into training and validation sets were employed.

### Model Training
Training involved pixel-wise binary cross-entropy loss and dice coefficient loss optimization.

### Model Evaluation
Evaluation metrics such as dice coefficient, Jaccard index, accuracy, and qualitative analysis were utilized.

### Results and Discussion
Results and performance discussion of the UNet model for brain tumor prediction.

## Power BI Dashboard
A Power BI dashboard was created for interactive exploration and analysis of the dataset.

