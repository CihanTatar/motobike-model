# Motorcycle Price Prediction with XGBoost

Bu proje, veri bilimi ve makine öğrenmesi tekniklerini kullanarak motosiklet fiyatlarını tahmin etmeyi amaçlamaktadır.  
Model, veri analizi, özellik mühendisliği, hyperparameter tuning ve XGBoost algoritmasıyla optimize edilmiştir.  
Ayrıca model FastAPI ile API’ye entegre edilip yerel ortamda pickle formatında kaydedilmiştir.

---

## Dosyalar

**motobike(1).ipynb**  
Veri analizi süreci, keşifsel veri analizi (EDA), görselleştirmeler, özellik seçimi ve adım adım model hazırlama sürecini içerir.  
Modelin oluşturulmasında XGBoost, Random Forest ve Support Vector Regressor algoritmaları karşılaştırılmış, en iyi sonuç XGBoost ile elde edilmiştir.  

**SavingModel.ipynb**  
Modelin farklı Python IDE’lerinde çalıştırılabilmesi ve deploy edilmesi için hazırlanmıştır.  
Eğitilen model pickle formatında kaydedilmiş ve FastAPI üzerinden tahmin yapılabilecek şekilde entegre edilmiştir.  
Bu yapı sayesinde model, gerçek dünya senaryolarında hızlı ve esnek bir şekilde kullanılabilir.

---

## Proje Özellikleri

• Eksiksiz veri analizi ve görselleştirme süreci  
• Gelişmiş XGBoost modeli ile yüksek tahmin doğruluğu  
• GridSearchCV ile parametre optimizasyonu  
• FastAPI ile modelin API olarak çalıştırılması  
• Modelin farklı ortam ve IDE’lerde yeniden kullanılabilir olması  
• Kod yapısı, ölçeklenebilir ve genişletilebilir şekilde tasarlandı

---

## Kullanılan Kütüphaneler
pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, fastapi, pickle

---

## Gelecekteki Geliştirmeler
• Modelin yeni verilerle düzenli olarak güncellenmesi  
• Kullanıcı dostu bir web arayüzü eklenmesi  
• Modelin buluta deploy edilerek çevrimiçi kullanılabilir hale getirilmesi  
• Marka bazlı ortalama fiyat analizleri ve dinamik grafiklerin eklenmesi  

---

## Yazar
Cihan Tatar  
[tatarcihan25@hotmail.com](mailto:tatarcihan25@hotmail.com)

---

# English Version

This project aims to predict motorcycle prices using data science and machine learning techniques.  
The model was optimized with feature engineering, hyperparameter tuning, and the XGBoost algorithm.  
It was saved locally as a pickle file and integrated into an API using FastAPI.

---

## Files

**motobike(1).ipynb**  
Includes data exploration (EDA), visualizations, feature selection, and step-by-step model preparation.  
XGBoost, Random Forest, and Support Vector Regressor were compared, and XGBoost achieved the highest performance.  

**SavingModel.ipynb**  
Contains the implementation for deploying and running the model in different Python IDEs.  
The model was saved in pickle format and integrated with a FastAPI endpoint for real-time predictions.  
This structure allows the model to be easily reused and adapted to real-world use cases.

---

## Project Features

• Complete data analysis and visualization workflow  
• High accuracy with optimized XGBoost model  
• Hyperparameter tuning with GridSearchCV  
• FastAPI integration for API-based predictions  
• Cross-environment model usability  
• Scalable and reusable code structure

---

## Libraries
pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, fastapi, pickle

---

## Future Improvements
• Regular retraining with updated datasets  
• Adding a user-friendly web interface  
• Deploying the model to the cloud for online predictions  
• Brand-based price range visualizations and dynamic charts  

---

## Author
Cihan Tatar  
[tatarcihan25@hotmail.com](mailto:tatarcihan25@hotmail.com)
