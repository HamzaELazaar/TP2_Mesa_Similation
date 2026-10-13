# TP2_Mesa simulation multi-agents

Ce dépôt contient deux notebooks réalisés dans le cadre des travaux pratiques de Python et de simulation multi-agents.

## Contenu du dépôt

- `TP1python_partie1.ipynb` — exercices de Python : types, conditions, boucles, fonctions et structures de données.
- `TP2Mesa_Simulation_MA.ipynb` — simulation de la formation de l’opinion publique avec Mesa 3. Le notebook présente un modèle d’agents sur une grille, collecte des données et analyse l’évolution des opinions.

## Prérequis

- Python 3.11 ou version ultérieure
- Jupyter Notebook ou JupyterLab

Pour exécuter le notebook de simulation, les bibliothèques suivantes sont utilisées :

- Mesa 3
- NumPy
- pandas
- Matplotlib

## Installation

Depuis la racine du dépôt, créez un environnement virtuel et installez les dépendances :

```bash
python -m venv .venv
```

Activez ensuite l’environnement :

**Windows (PowerShell)**

```powershell
.venv\Scripts\Activate.ps1
```

**macOS / Linux**

```bash
source .venv/bin/activate
```

Installez les bibliothèques nécessaires :

```bash
python -m pip install notebook mesa numpy pandas matplotlib
```

## Ouvrir les notebooks

Lancez Jupyter depuis la racine du dépôt :

```bash
jupyter notebook
```

Vous pouvez ensuite ouvrir le notebook souhaité dans l’interface. Les notebooks peuvent aussi être consultés directement sur GitHub.

> Certaines cellules du TP1 demandent une saisie au clavier avec `input()`. Exécutez-les dans un environnement interactif et fournissez les valeurs demandées.

## Simulation d’opinion

Le TP2 représente les individus par des agents placés sur une grille. À chaque étape, un agent rapproche son opinion de la moyenne de celles de ses voisins. Le notebook permet d’observer l’évolution de l’opinion moyenne, de sa dispersion et des trajectoires individuelles.

Les principaux paramètres de la simulation — taille de la grille, coefficient d’influence `alpha` et nombre d’étapes — peuvent être modifiés dans le notebook.
