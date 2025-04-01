# Flight Ticket Type Prediction

### Description
This project predicts ticket types for airlines, including economy, premium economy, business, and first class, using machine learning to improve ticket classification and enhance the booking experience.

The dataset used contains detailed information on domestic flights in India for the period of July to August 2023. The dataset can be downloaded from [Kaggle - Goibibo Flight Data](https://www.kaggle.com/datasets/iamavyukt/goibibo-flight-data).

### Methods Used
This project employs **KMeans Clustering** to group flights based on key features, with the optimal number of clusters determined using the **Elbow Method**.

### Models Used
Several machine learning models were tested and compared:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **XGBoost**

Each model was evaluated under two scenarios:
1. **Without tuning** (using default parameters)
2. **With tuning using GridSearchCV** (to find the best parameter combination)

### Results & Conclusion
- **XGBoost showed performance improvement after tuning**, making it the best model for flight ticket classification.
- **Random Forest and KNN remained stable but require improved recall for minority classes.**
- **Decision Tree experienced a performance drop after tuning.**
- **Logistic Regression remains suboptimal for this dataset.**

➡ **XGBoost is the best model after tuning but requires further optimization to improve recall for minority classes.**
➡ **Random Forest and KNN can still be considered with additional tuning.**

### Social Media
Follow me on:
- [Instagram](https://www.instagram.com/nafishusen24/)
- [LinkedIn](https://www.linkedin.com/in/nafishusen24/)
- [GitHub](https://github.com/nafishr24/)

