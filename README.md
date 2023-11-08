# CNN-Breastcancer-Detection
Using a pre-trained CNN algorithm to analyze breast mammogram images. 

## Requirements
- numpy==1.21.2
- Pillow==8.4.0
- streamlit==0.79.0 
- tensorflow==2.4.0


## Dataset
we collect the data from Kaggle - (https://www.kaggle.com/kmader/mias-mammography)


## Results
| version | traning accuracy | test accuracy | f1 score | recall  | precision | Total Parameters|
|--------|--------------|-------------|------------|----------|-------------|-------|
|ROI version | 0.96 | 0.91 | 0.91 | 0.92 |0.92|22,665,282|
| Whole Image version |0.96|0.96|0.97|0.95|0.98 |47,929,410|
