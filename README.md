# Graph Cricket: Predicting Player Performance Across ODI Format Using Graph Neural Networks
## Abstract
Cricket analytics has taken a significant leap forward with Graph Cricket, a novel approach designed to predict player performance across the One-Day International (ODI) format using Graph Neural Networks (GNNs). By leveraging the structural relationships between players and incorporating comprehensive statistical data, our model surpasses traditional prediction methods. This project explores the efficacy of Graph Convolutional Networks (GCNs) alongside various machine learning algorithms, setting a new benchmark for accuracy in cricket performance prediction.

## Methodology
### Data Collection and Preprocessing
Our journey began with a rich dataset sourced from Kaggle, comprising detailed statistics of ODI cricket players. The preprocessing phase included:

- Removal of redundant columns
- Splitting concatenated player names and regions
- Addressing missing values to ensure data integrity

### Machine Learning Models
To establish a baseline, we employed the following machine learning models to predict player averages:

- Linear Regression
- Decision Tree
- KNeighbors Regressor
- Random Forest
Each model was trained on 80% of the dataset and evaluated on the remaining 20%. The Random Forest model stood out with the highest accuracy.

### Graph Convolutional Network (GCN)
The core innovation of this project is the GCN, a sophisticated neural network model that integrates both statistical features and the relational structure of players. This dual consideration enables the GCN to capture complex patterns and dependencies, enhancing prediction accuracy.

## Results
![Screenshot 2024-05-13 092713](https://github.com/user-attachments/assets/88fdd255-bbbf-465e-b4a2-e1b5af382e10)

The GCN model outperformed traditional machine learning models, demonstrating superior predictive capabilities. It not only forecasts player performance metrics with high accuracy but also provides actionable insights for analysts, selectors, and coaches.

## Conclusion
Graph Cricket showcases the transformative potential of Graph Neural Networks in sports analytics. By accurately predicting player performance and revealing the underlying factors of success, our approach opens new avenues for research and application in various sports domains.
