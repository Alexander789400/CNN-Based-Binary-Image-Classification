# Deep Learning Image Classification Model (Keras + CNN)

## Asian vs African Elephants Dataset

[Dataset Link](https://www.kaggle.com/datasets/vivmankar/asian-vs-african-elephant-image-classification)

Dataset details :
- Number of classes: 2 (Asian elephant and African elephant )
- Number of images: 1028
- Image shape range: ( 100, 100) to (4992, 3328)
- To increase complexity the train set contains less than 5% mislabeled images, while all images in the test set have the correct label.

- ### Final Conclusion :

Your validation accuracy steadily improves and stabilizes around 66–69%, which means your model is learning useful patterns

Precision vs Recall Imbalance :

- You can see fluctuations like:
- High precision, low recall (model is conservative)
- High recall, low precision (model guesses too many positives)
- Later epochs stabilize around:

- val_precision ≈ 0.63–0.70  
- val_recall ≈ 0.64–0.71


This is actually good balance, especially for binary classification.

This project successfully demonstrates building an end-to-end deep learning image classification system using CNNs. The dataset was preprocessed with augmentation techniques to improve performance. The model achieved around 68% accuracy with balanced precision and recall.
