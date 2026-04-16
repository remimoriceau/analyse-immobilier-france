# Analyse du marché immobilier français

Analyse de 224 000 transactions immobilières réelles issues des Demandes de Valeurs Foncières 2024, disponibles en open data sur data.gouv.fr.

## Objectifs

Comparer les prix au m² dans les 10 plus grandes villes françaises et analyser le marché parisien par arrondissement.

## Questions analysées

- Quelles sont les villes les plus chères au m² ?
- Quel est l'écart de prix entre les arrondissements parisiens ?
- Quelle est la répartition appartement vs maison ?
- Comment évoluent les ventes au fil des mois ?

## Résultats clés

- Paris à 10 900€/m², soit 3 fois plus cher que Lille (3 500€/m²)
- Le 7ème arrondissement à 16 300€/m² contre 8 700€/m² pour le 19ème
- 99,6% des ventes parisiennes sont des appartements
- Juillet est le mois le plus actif, août le plus calme

## Stack technique

- Python (pandas, matplotlib, seaborn)
- SQL (SQLite)
- Power BI

## Fichiers

- `python_Paris.ipynb` : nettoyage et analyse Paris par arrondissement
- `projet python 10 villes.ipynb` : nettoyage et analyse des 10 villes
- `sql_10_villes.ipynb` : requêtes SQL analytiques
- `paris.pbix` : dashboard Power BI Paris
- `power bi 10 Villes.pbix` : dashboard Power BI 10 villes
