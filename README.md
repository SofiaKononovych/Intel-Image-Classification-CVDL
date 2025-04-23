# Intel Image Classification

This project focuses on the analysis and modeling of the **Intel Image Classification Dataset**, which includes natural scene images divided into 6 categories:  
`buildings`, `forest`, `glacier`, `mountain`, `sea`, and `street`.

## Completed Stage

At the current stage, we have:
- Loaded and explored the dataset.
- Performed EDA
- Transformed images into tensors and normalized them.
- Created DataLoaders for training, validation, testing, and prediction sets.
- Defined best manually created CNN model (tuned and optimised parameters like lr, number of convolutional layers, fully-connected layers, channels, optimizer etc. - see in notebook)
- Used Resnet18 pretrained model with my dataset and utilised transfer learning techniques.
  
## Best Results
- Manual CNN: 0.8 f1-score on test 
- ResNet18: 0.93 f1-score on test

## Environment Setup

1. Make sure you have **Python 3.8+** installed.
2. Install required libraries:
```bash
pip install torch torchvision matplotlib seaborn
```
3. Enable GPU if you run the notebooks in Google Colab or elsewhere.
