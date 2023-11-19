# Image_segmentation
This project aims to predict human age from brain MRI scans with two approaches: 
  1. **Two-stage**: extract brain features via segmentation and predict age based on the extracted features.
  2. **End-to-end**: develop end-to-end models to predict age directly from raw data.

See ```report.pdf``` for results and ```CW-Brain-Age-Regression.ipynb``` for code and detailed working process.

# In this project
**Two-stage approach**:
- We performed image segmentation with a CNN. We examined the segmentation performance with the DICE score. 
- We experiemented with different regression models, including Ridge, Lasso, SVM, and Decision Tree regression, for age prediction.

**End-to-end approach**
- We constructed another CNN directly for age prediction.

We compared the performance of two approaches in terms of mean absolute error (MAE) and a $R^2$ socre. Our result shows that the end-to-end approach achieved a better performance due to less accumulation of prediction errors. 
