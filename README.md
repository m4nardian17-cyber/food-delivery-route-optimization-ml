
# food-delivery-route-optimization-ml

Machine learning project untuk memprediksi optimalitas rute pengiriman makanan berdasarkan jarak, waktu pengiriman, kondisi lalu lintas, cuaca, moda pengiriman, waktu pemesanan, dan zona pengiriman.

Project ini menggunakan pendekatan klasifikasi dengan tiga algoritma utama:

- Decision Tree
- K-Nearest Neighbour (KNN)
- Logistic Regression

Dataset yang digunakan adalah Food Delivery Route Efficiency Dataset. Karena label `optimal_route` tidak tersedia langsung, target dibentuk melalui rule-based scoring berdasarkan indikator efisiensi rute seperti waktu per kilometer, durasi pengiriman, dan tingkat ketidakefisienan rute.

## Main Steps

1. Data loading
2. Exploratory Data Analysis
3. Feature engineering
4. Target engineering
5. Model training
6. Hyperparameter tuning
7. Model evaluation
8. Feature importance analysis

## Tech Stack

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Output

- Model evaluation results
- Confusion matrix
- ROC-AUC comparison
- Feature importance
- Predicted optimal route classification

## Team Members

- Muhammad Ardiansyah Nugraha
- Minati Nur Alifa
