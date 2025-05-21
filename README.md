# Facial-Expressions-Classification

---

## 📌 Objectif

Prédire automatiquement une des 7 émotions à partir d’une image de visage :

- 😐 Neutre
- 😡 Colère
- 🤢 Dégout
- 😨 Peur
- 😄 Joie
- 😢 Tristesse
- 😲 Surprise

---

## 🔍 Dataset

- **Source** : [FER-2013 on Kaggle](https://www.kaggle.com/datasets/msambare/fer2013)
- **Nombre d’images** : 35 000+
- **Dimensions** : 48x48 pixels (niveaux de gris)
- **Labels** : 7 émotions annotées

---

## ⚙️ Méthodologie

1. **Prétraitement** : redimensionnement, normalisation, augmentation.
2. **Modélisation** :
   - Baseline : CNN classique
   - Avancé : ResNet, MobileNetV2, Vision Transformers
3. **Évaluation** :
   - Accuracy, Matrice de confusion, Classification report

---

## 🧪 Dépendances

```bash
pip install -r requirements
