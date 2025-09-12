# Prédisez les patients ayant un risque de diabète grâce à l’analyse de données médicales

## 🎯 Problématique client :
Le diabète touche plus de 400 millions de personnes dans le monde. Une détection précoce permet de prévenir les complications et d’améliorer la qualité de vie des patients. Mais comment identifier les personnes à risque sans tests coûteux et invasifs ?

## 💡 Notre solution :
Nous avons développé un modèle prédictif capable d’estimer le risque de diabète à partir de données médicales standard (âge, IMC, historique familial, etc.). Notre méthodologie est d'utiliser l'analyse exploratoire (EDA), la gestion des données déséquilibrées et la classification supervisée afin d'identificatier les variables les plus prédictives et le score de risque personnalisé.

## 🛠️ Technologies utilisées :
Python, Pandas, Scikit-learn, Matplotlib, techniques de rééquilibrage de données (SMOTE).

## 🚀 Résultats pour votre entreprise/organisation :
- Prévention ciblée : Identifier les patients à risque pour des campagnes de sensibilisation ou des suivis personnalisés.
- Optimisation des coûts : Réduire le nombre de tests inutiles en ciblant les patients prioritaires.
- Outil d’aide à la décision : Intégrable dans un dossier patient ou une plateforme de télémédecine.

--------------------------------------------------------------------

## 📚 Données :
- **Source** : [Pima Diabete Dataset](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)
- **Taille** : 768 individus, 9 variables (dont la classe)

## ⚙️ Méthodologie :
- EDA
- ACP
- Clustering (Kmeans)
- Modelisation : Regression Logistique, Knn, SVM, Random Forest, Xgboost
  

## 📊 Résultats

#### Corrélations : 

<img width="800" height="772" alt="Corr" src="https://github.com/user-attachments/assets/7df5873e-dec1-4050-b7bb-a5d16b6e31a6" />

#### Résulats finaux : 

<img width="613" height="225" alt="Final_results" src="https://github.com/user-attachments/assets/9d00f43b-5c9a-4dea-83aa-c440f6a540a1" />

#### Meilleur modèle : **XGBoost**
- Accuracy = 0.88
- Recall = 0.88
- F1 = 0.88
- Variables importantes : Insulin, Glucose, Age

#### Matrice de confusion finale : 

<img width="498" height="432" alt="Xgboost_cm" src="https://github.com/user-attachments/assets/7fe457e4-f739-41e2-975b-7f2a3c4abf82" />



