
# Détection d’Anomalie et Adultération du Miel par Autoencodeur

Ce mini-projet vise à détecter des cas d’adultération du miel à l’aide de **réseaux de neurones autoencodeurs**, une technique non supervisée permettant d’apprendre une représentation compacte des données et de repérer les échantillons anormaux.

## Objectif

- Identifier des miels potentiellement falsifiés en se basant sur leurs propriétés physico-chimiques.
- Utiliser un **autoencodeur** pour reconstruire les données et détecter les anomalies à partir de l’erreur de reconstruction.


## Méthodologie

1. **Exploration des données** :
   - Statistiques descriptives

2. **Prétraitement** :
   - Nettoyage des données
   - Normalisation 

3. **Détection d’anomalies par autoencodeur** :
   - Construction d’un réseau autoencodeur simple (encodeur + décodeur)
   - Entraînement sur les données supposées normales
   - Calcul de l’erreur de reconstruction
   - Seuil défini à partir de la distribution des erreurs
   - Détection des échantillons avec une erreur supérieure au seuil

4. **Évaluation et visualisation** :
   - Répartition des anomalies détectées

## 🧠 Technologies utilisées

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- **TensorFlow / Keras** (pour les autoencodeurs)


