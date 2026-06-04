
# Dataframe & Prédiction EEG — SDD1002

Notebook Jupyter d'analyse et de prédiction sur des données EEG et catégorielles issues de fichiers AXE_UQTR, avec régression multivariée et réseau de neurones (MLP).

## Contenu du notebook

- Lecture de fichiers CSV depuis Google Drive et ajout d'une colonne ID
- Fusion automatique des données AXE_UQTR (1 à 4) avec le fichier IPM
- Génération d'un fichier `Final.csv` consolidé
- Régression linéaire multivariée pour prédire `IPM_TOTAL`
- Classification par réseau de neurones MLP (données EEG + catégorielles)
- Normalisation avec StandardScaler, split 80/20 entraînement/test

## Technologies

- Python
- Pandas
- scikit-learn (LinearRegression, MLPClassifier, StandardScaler)
- Jupyter / Google Colab

## Prérequis

```bash
pip install pandas scikit-learn requests
```

Le notebook a été développé sous Google Colab. Les données source sont chargées depuis Google Drive via des liens directs — les cellules de montage Drive peuvent nécessiter une adaptation selon l'environnement.

## Structure

```
Dataframe_Et_Prediction.ipynb  — notebook principal (5 questions)
```

---

Projet universitaire solo — cours SDD1002, UQTR.
