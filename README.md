# Analyse de Séries Temporelles - Fréquentation Touristique

## Description
Analyse et prévision de la fréquentation touristique mensuelle (Jan 2020 - Déc 2023)


## Méthodes utilisées
- **Excel** : Décomposition additive + Holt-Winters (α=β=γ=0.1, MAPE=8.80%)
- **Python** : SARIMA(1,0,2)(1,1,1)₁₂ — méthode Box-Jenkins

## Résultats clés
- Pic saisonnier : Avril (+31.6 unités)
- Creux saisonnier : Octobre (-27.5 unités)
- Prévision Avril 2024 : ~138 unités

## Fichiers
- `Excel.xlsx` : Décomposition + prévisions Holt-Winters
- `Python.ipynb` : Notebook SARIMA complet
- `Rapport.docx` : Rapport de synthèse (10 pages)
