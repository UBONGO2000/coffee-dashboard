# Coffee Sales Dashboard

Projet d'analyse de donnees realise avec Microsoft Excel a partir d'un dataset de commandes de cafe. L'objectif est de transformer des donnees brutes de ventes, clients et produits en un dashboard lisible permettant de suivre les performances commerciales.

## Apercu

Le classeur analyse des commandes de cafe en croisant trois sources principales :

- `orders` : commandes, dates, quantites et produits achetes
- `customers` : informations clients, pays et carte de fidelite
- `products` : types de cafe, types de torrefaction, tailles, prix et profit

Le resultat final est un dashboard Excel qui permet d'observer les ventes par type de cafe, par pays et par client.

## Objectifs

- Nettoyer et enrichir un dataset de ventes dans Excel
- Relier plusieurs feuilles avec des formules de recherche
- Calculer automatiquement le chiffre d'affaires par commande
- Creer des tableaux croises dynamiques pour synthétiser les ventes
- Construire des graphiques clairs pour faciliter l'analyse
- Presenter les indicateurs principaux dans un dashboard exploitable

## Fonctionnalites

- Enrichissement de la table `orders` avec les donnees clients et produits
- Utilisation de `XLOOKUP` pour recuperer les informations clients
- Utilisation de `INDEX` et `MATCH` pour recuperer les informations produits
- Calcul du champ `Sales` a partir du prix unitaire et de la quantite
- Normalisation des libelles de types de cafe et de torrefaction
- Analyse des ventes par mois, annee et type de cafe
- Classement des ventes par pays
- Identification des meilleurs clients
- Dashboard Excel avec graphiques et vues de synthese

## Technologies et outils

- Microsoft Excel
- XLOOKUP
- INDEX / MATCH
- Tableaux croises dynamiques
- Graphiques Excel
- Nettoyage et transformation de donnees
- Dashboarding

## Structure du classeur

```text
coffeeOrdersData.xlsx
├── Dashboard
├── TotalSales
├── CountryBarChart
├── Top5Customers
├── orders
├── customers
└── products
```

## Analyses realisees

### Ventes par type de cafe

Le dashboard compare les ventes des differents types de cafe :

- Arabica
- Excelsa
- Liberica
- Robusta

### Ventes par pays

Une visualisation permet d'identifier les pays qui generent le plus de chiffre d'affaires, notamment :

- United States
- Ireland
- United Kingdom

### Top clients

Le projet met en avant les clients ayant genere le plus de ventes afin d'identifier les profils les plus importants pour l'activite.

## Ce que j'ai appris

- Croiser plusieurs feuilles Excel avec `XLOOKUP`, `INDEX` et `MATCH`
- Structurer un dataset brut pour le rendre exploitable
- Construire des tableaux croises dynamiques pour analyser des ventes
- Creer des graphiques lisibles pour communiquer des tendances
- Transformer des donnees commerciales en indicateurs utiles pour la decision
- Organiser un dashboard Excel autour de questions business simples

## Comment utiliser le projet

1. Telecharger ou cloner ce depot.
2. Ouvrir `coffeeOrdersData.xlsx` avec Microsoft Excel.
3. Consulter les feuilles `orders`, `customers` et `products` pour voir les donnees sources.
4. Explorer les feuilles d'analyse `TotalSales`, `CountryBarChart` et `Top5Customers`.
5. Consulter la feuille `Dashboard` pour visualiser la synthese.

## Ameliorations possibles

- Ajouter des segments interactifs pour filtrer par annee, pays ou type de cafe
- Ajouter des KPI de marge et de profit
- Comparer les clients avec et sans carte de fidelite
- Automatiser le nettoyage des donnees avec Power Query
- Ajouter une version Power BI du dashboard

## Auteur

Georges NTCHANGA  
GitHub : [UBONGO2000](https://github.com/UBONGO2000)
