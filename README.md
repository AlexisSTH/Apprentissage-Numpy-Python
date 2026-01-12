# 📊 Apprentissage de NumPy

> Mes notes et exercices d'apprentissage de la bibliothèque NumPy en Python dans le cadre de mon parcours en Data Science.
---

## 🎯 À propos

Ce dépôt regroupe mes notebooks Jupyter créés lors de mon apprentissage de **NumPy**, la bibliothèque fondamentale pour le calcul scientifique en Python. Vous y trouverez des concepts de base, des manipulations avancées et des exercices pratiques.

---

## 📖 Contenu du dépôt

### 1️⃣ **Ipyhton & Jupyter base.ipynb**
Introduction à l'environnement Jupyter Notebook

- ✅ Exécution de scripts externes avec `%run`
- ✅ Partage de variables entre scripts et notebook
- ✅ Gestion de l'espace de travail interactif

---

### 2️⃣ **Numpy_base.ipynb**
Les fondamentaux de NumPy

- 🔢 Création de **scalaires, vecteurs et matrices** avec `np.array()`
- ➕ Opérations élémentaires (addition, multiplication)
- 📐 Propriété `.shape` pour connaître les dimensions
- 🔄 Opérations vectorielles élément par élément

---

### 3️⃣ **Manipuler les ndarray.ipynb**
Guide complet sur la manipulation des tableaux NumPy

#### 🔍 **Indexing et Slicing**
- **Index** : Accéder aux éléments avec `[]` (0-indexing)
- **Index négatifs** : Accéder depuis la fin avec `-1`, `-2`, etc.
- **Slicing** : Extraire des sous-tableaux avec `[debut:fin:pas]`
- **Matrices** : Notation `[ligne, colonne]`

#### ✏️ **Assigner des valeurs**
- Modifier un élément : `array[index] = valeur`
- Modifier une ligne/colonne complète
- Affecter avec le slicing : `array[2:4] = nouvelle_valeur`

#### 🧮 **Opérations élémentaires**
- ➕ **Addition** : `array + 5` ou `array1 + array2`
- ➖ **Soustraction** : `array1 - array2`
- ✖️ **Multiplication** : `array * 3` ou `array1 * array2`

---

### 4️⃣ **Manipuler les ndarray (Exercices).ipynb**
Mise en pratique des connaissances

- 💪 Exercices sur l'indexing avec matrices complexes
- 🎯 Slicing avec différents pas
- 📝 Assignation de valeurs dans divers contextes

---

## 🎓 Concepts clés appris

| Concept | Description |
|---------|-------------|
| **ndarray** | Structure de données principale de NumPy |
| **Dimensions** | Scalaire (0D), Vecteur (1D), Matrice (2D+) |
| **Slicing** | `[start:stop:step]` où `stop` est exclu |
| **Broadcasting** | Opérations entre tableaux de dimensions différentes |
| **Elementwise operations** | Opérations élément par élément |

---

📖 Ressources

📺 Chaîne YouTube FoxxPy - Tutoriels suivis
📚 Documentation officielle NumPy
🐍 Python.org

---

## 💻 Exemples pratiques

### Création et manipulation basique

```python
import numpy as np

# Créer un tableau
array = np.array([1, 2, 3, 4, 5])

# Accéder aux éléments
print(array[0])      # Premier élément : 1
print(array[-1])     # Dernier élément : 5
print(array[1:4])    # Slicing : [2 3 4]
