# Gephora_marketing_analysis
Analyse marketing et performance client pour l'entreprise fictive Gephora

Gephora Data Pipeline – Analyse Marketing et Performance Client
🧴 À propos de Gephora

Gephora est une entreprise spécialisée dans la vente de produits cosmétiques en ligne et en boutique.
Elle s’appuie sur une stratégie marketing omnicanale (réseaux sociaux, campagnes publicitaires, e-mailing, partenariats) et cherche à optimiser ses investissements marketing tout en améliorant la valeur vie client (LTV) et le taux de rétention.

Ce projet vise à centraliser, nettoyer et analyser les données de Gephora afin de suivre et de piloter les principaux indicateurs de performance.

🎯 Objectifs du projet

L’objectif principal est de construire un pipeline de données complet pour :

Nettoyer et uniformiser les données marketing et clients.

Calculer les indicateurs clés de performance (KPI) :

CAC – Coût d’Acquisition Client

LTV – Lifetime Value (Valeur Vie Client)

ROAS – Return On Advertising Spend

ROI – Return On Investment

Taux de rétention

Visualiser les résultats et produire des rapports automatisés permettant une prise de décision data-driven.

🧩 Description du pipeline

<img width="1704" height="859" alt="image" src="https://github.com/user-attachments/assets/58da38f0-5554-4b39-bd75-a4b2103a4d7d" />

Le pipeline est composé de plusieurs modules interdépendants :

1. Default / Import

Regroupe les différentes sources de données brutes :

Campagnes publicitaires (Facebook Ads, Google Ads, Instagram)

Données de ventes et commandes

Données clients (CRM, historique d’achats)

2. CLEANING

Étapes de préparation et de normalisation :

Suppression des doublons et des valeurs manquantes

Harmonisation des formats (dates, devises, noms de campagnes)

Fusion des datasets marketing et ventes

3. CAC_compute

Calcul du Coût d’Acquisition Client à partir des dépenses publicitaires et du nombre de nouveaux clients acquis.

4. LTV_compute

Estimation de la valeur vie moyenne d’un client à partir de son historique d’achats, de sa fréquence d’achat et de son panier moyen.
<img width="910" height="858" alt="image" src="https://github.com/user-attachments/assets/af7f7037-17ff-460e-a364-d9cdbce93c17" />


5. ROAS (Return On Advertising Spend)

Mesure du retour sur les dépenses publicitaires :
<img width="1231" height="514" alt="image" src="https://github.com/user-attachments/assets/7a0221d9-680b-4066-9be4-427183d6e358" />


6. ROI (Return On Investment)

Évalue la rentabilité globale des campagnes :
<img width="1446" height="601" alt="image" src="https://github.com/user-attachments/assets/4cdcdb3a-741b-467b-bc0e-48d2679f8e09" />

	​

7. Taux de rétention

Analyse de la fidélité client à travers le taux de retour et la récurrence d’achat.
<img width="743" height="858" alt="image" src="https://github.com/user-attachments/assets/b3d87eda-f90e-43d9-89d1-1fa239a8885d" />


8. LTV_vs_CAC

Compare la valeur vie client (LTV) au coût d’acquisition (CAC) pour évaluer la durabilité du modèle marketing.
<img width="1446" height="838" alt="image" src="https://github.com/user-attachments/assets/a738dc39-7a9e-4176-9d56-0e39098c6749" />


🧮 Métriques clés
Indicateur	Description	Objectif
CAC	Coût moyen pour acquérir un client	Réduire
LTV	Revenu généré par client sur sa durée de vie	Augmenter
ROAS	Retour sur investissement publicitaire	> 3 idéalement
ROI	Rentabilité globale	Maximiser
Rétention	Fidélité des clients	Améliorer
