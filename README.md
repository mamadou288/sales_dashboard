## Sales Data Analysis Dashboard

# Présentation

L'objectif est de construire un dashboard interactif permettant à une entreprise e-commerce d'analyser ses ventes sur plusieurs dimensions : temps, produits, régions.

ma démarche:

- Nettoyage des données : correction des erreurs, traitement des valeurs manquantes, normalisation.
- Exploration et visualisation : analyse des ventes et identification d'insights.
- Construction du dashboard : Streamlit pour rendre les insights interactifs.



# Objectifs Business

- Suivre l'évolution du chiffre d'affaires dans le temps.
- Identifier les produits les plus performants.
- Analyser la répartition géographique des ventes.
- Mesurer la valeur moyenne des commandes.
- Permettre une analyse dynamique par année, catégorie, et région.


# dashboard
Filtres : 
- par année 
- catégorie produit
- région

KPIs :
- Chiffre d'affaires total
- Nombre de commandes
- Valeur moyenne par commande

Graphiques :
- Evolution du chiffre d'affaires dans le temps
- Produits les plus vendus
- Répartition des ventes par région
- Répartition par catégorie de produits

# Stack technique
- Python 
- pandas
- numpy
- matplotlib
- seaborn
- Streamlit




# Lancer le projet localement

git clone https://github.com/mamadou288/sales_dashboard.git
cd sales_dashboard
python -m venv venv
source venv/bin/activate  # (ou venv\Scripts\activate sous Windows)
pip install -r requirements.txt
streamlit run app.py
