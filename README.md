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

![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/9b539999-1c52-40ed-ac55-be4b7676ccbe)
![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/5e284fa7-07e2-44ee-bcc0-85f7412eaba7)
![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/cd6ae0c2-1fb6-489c-a081-c029fdf97069)
![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/1f928d24-6bc3-4243-8a76-37fc38334adc)
![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/939166a9-e5d6-4cb3-b3e0-34614e2648e3)
![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/fce74181-a1ef-41cd-8718-764a188c509d)
![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/8bef938a-6c74-4f77-a1f0-a3a55bd9d717)
![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/55359931-d1ac-4d0f-9532-d584fb04aaa6)
![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/b43fca11-083c-416c-b21c-2069201aaf23)
![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/18b91fec-3aff-4cbd-bdd8-bf7d9b02d5bb)
![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/90452578-647e-4d9e-a907-429dbcc7a46f)

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

![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/d1711e3a-8862-4071-ac66-9973d46442a2)
![image](https://github.com/Bala-Saatvik/Brain_Tumor_Analysis/assets/94885375/2013aeab-ba65-4f0c-8c81-8060ceb699da)


