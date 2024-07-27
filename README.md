# Dimensionality Reduction Using K-Means for Activity Recognition

## Objective
Improved activity recognition models using high-dimensional sensor data from smartphones by implementing k-means clustering for dimensionality reduction.

## Approach

### Baseline Model
- Constructed an initial model using all 561 features from various smartphone sensors.

### Dimensionality Reduction
- Applied k-means clustering to group similar features.
- Reduced the feature set to 50 by selecting representative features from each cluster.
- Normalized the data and used Gaussian Naive Bayes for classification.

## Results

### Baseline Model (All Features)
- *Accuracy:* 73.15%
- *Training Time:* 0.15 seconds

### Reduced Model (K-Means)
- *Accuracy:* 78.59%
- *Training Time:* 0.01 seconds

### Efficiency
- Reduced the number of features from 561 to 50, improving model interpretability and computational efficiency.

## Key Achievements
- *Increased Accuracy:* Achieved a 7.44% improvement in model accuracy through effective feature selection using k-means clustering.
- *Enhanced Efficiency:* Reduced training time by approximately 92%, significantly boosting computational efficiency.
- *Feature Reduction:* Streamlined the feature set from 561 to 50, leveraging k-means clustering to maintain essential information and discard redundancy.
- *Activity Recognition:* Utilized the reduced feature set to build robust models for Human Activity Recognition using smartphone sensor data.

## Bullet Points
- Developed and implemented a k-means clustering approach for dimensionality reduction, improving activity recognition model accuracy from 73.15% to 78.59%.
- Achieved a 92% reduction in model training time by effectively selecting representative features from clusters, enhancing computational efficiency.
- Streamlined feature set from 561 to 50, simplifying the model and improving interpretability without sacrificing performance.
- Built accurate Human Activity Recognition (HAR) models using high-dimensional smartphone sensor data, demonstrating advanced machine learning techniques for real-world applications.
