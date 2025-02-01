# Insurance
## Analyse de Données et Prédiction

Analyse des données et prédiction des charges d'assurance d'un client d'une société d'assurance-vie en fonction de différents paramètres tels que l'âge, le nombre d'enfants à charge, l'IMC, le statut de fumeur, la région de résidence, etc.

## 1. Chargement et Compréhension du Dataset

Le dataset <a href="Data\Insurance-data.xlsx">Insurance-data.xlsx</a> contient **1000 lignes (observations)** et **7 colonnes (variables)**.

### Description des variables
- **age** : Âge de l'individu
- **sex** : Sexe de l'individu
- **bmi** : Indice de masse corporelle (IMC)
- **children** : Nombre d'enfants à charge
- **smoker** : Statut de fumeur (yes/no)
- **region** : Région de résidence
- **charges** : Coûts médicaux facturés

Le dataset fournit des informations essentielles pour comprendre les profils des assurés et les facteurs influençant les coûts des assurances santé.

## 2. Prétraitement des Données

Avant d'appliquer un modèle de prédiction, il est nécessaire de préparer les données correctement :

1. **Vérification des valeurs manquantes** :
   - Identifier et traiter les valeurs nulles s'il y en a.

2. **Encodage des variables catégoriques** :
   - Conversion des variables qualitatives (*sex, smoker, region*) en variables numériques (ex. : encodage one-hot ou label encoding).

3. **Normalisation des données** :
   - Mise à l'échelle des variables continues (*age, bmi, children, charges*) pour éviter des disparités entre les valeurs.

4. **Division du dataset** :
   - Séparation des données en ensemble d'entraînement (80%) et ensemble de test (20%).

## 3. Modélisation avec KNN

Nous utilisons le modèle des k-plus proches voisins (*K-Nearest Neighbors, KNN*) pour prédire les charges d'assurance.

### Choix du Modèle
- Le KNN est un modèle non paramétrique basé sur la proximité des données.
- Il est essentiel de choisir une bonne valeur de **k** (nombre de voisins) pour optimiser les performances du modèle.

### Étapes de Modélisation
1. **Sélection des features** : Choix des variables pertinentes pour la prédiction.
2. **Optimisation de k** : Utilisation d'une validation croisée pour déterminer la meilleure valeur de k.
3. **Mise en place du modèle** : Entraînement du modèle KNN sur l'ensemble d'entraînement.
4. **Évaluation du modèle** : Mesure de la performance sur l'ensemble de test (MSE, RMSE, R^2).

### Métriques d'évaluation
- **Erreur quadratique moyenne (MSE)** : Permet de mesurer la différence moyenne entre les valeurs prédites et les valeurs réelles.
- **Racine de l'erreur quadratique moyenne (RMSE)** : Évalue la précision globale des prédictions.
- **Coefficient de détermination (R^2)** : Indique la proportion de variance expliquée par le modèle.

## Conclusion
Cette analyse nous permet de comprendre les facteurs influençant les charges d'assurance et de prédire celles-ci avec un modèle KNN. L'optimisation du modèle et le choix des paramètres sont essentiels pour garantir de bonnes performances en prédiction.

## Auteur
👤 **Bryan LEKE**  
📧 Contact : bryanlkcontact0@gmail.com  
🔗 GitHub : [github.com/Bryan-lk4]

---

📌 **Note** : Ce projet est réalisé à des fins éducatives pour explorer la prediction en utillisant le KNN , la regression et l'analyse de données.