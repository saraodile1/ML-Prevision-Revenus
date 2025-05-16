# ML-Prevision-Revenus
Prédire si un individu gagne plus ou moins de 50 000 $ par an. Identifier les facteurs importants qui influencent le revenu. Étudier les disparités selon le genre ou la race. Rechercher d’éventuels clusters sous-jacents aux données

# Prédiction des Revenus (>50K) - Machine Learning

Ce projet de classification supervisée vise à prédire si un individu gagne plus ou moins de **50 000 dollars par an**, à partir de données socio-démographiques issues du recensement américain.

Il s'inscrit dans un cadre d'apprentissage automatique appliqué à un jeu de données réel et illustre un cycle complet de data science : **préparation des données, modélisation, optimisation, évaluation et interprétation**.

---

## Technologies utilisées

- Python 3.10+
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
- GridSearchCV, OneHotEncoder, LabelEncoder, AdaBoost, etc.

---

## Étapes du projet

1. **Exploration et nettoyage des données**
2. **Transformation des variables asymétriques**
3. **Mise à l’échelle des variables numériques**
4. **Encodage des variables catégorielles (Label + OneHot)**
5. **Évaluation de plusieurs modèles (Logistic Regression, Random Forest, SVC, AdaBoost)**
6. **Optimisation d’AdaBoost via GridSearchCV**
7. **Analyse des performances (Accuracy, F-score, temps)**
8. **Visualisation des importances de variables**
9. **Conclusion et recommandations**

---

## Résultats principaux

- **Meilleur modèle :** `AdaBoostClassifier` optimisé
- **F-score (test)** : **0.730**
- **Accuracy (test)** : **0.861**
- **Variables les plus influentes :** `capital_gain`, `education_num`, `hours_per_week`

---

## Exécution rapide

1. Clonez ce dépôt :

```bash
git clone https://github.com/saraodile1/ML-Prevision-Revenus
cd ML-Prevision-Revenus
