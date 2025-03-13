# Defaults_Analysis_Industry4.0
## Introduction
Dans l'industrie, la visualisation des données est essentielle pour optimiser la production, anticiper les pannes et assurer un suivi précis des ressources. Grâce à Power BI, les entreprises peuvent analyser en temps réel leurs performances, détecter les anomalies et prendre des décisions rapides. Ce projet explore l'apport de Power BI dans l'amélioration du pilotage industriel.

## Problématique
Assurer la qualité des pièces, optimiser la performance des machines et évaluer la fiabilité des fournisseurs sont des enjeux majeurs dans un contexte industriel. Une analyse efficace des données permet d'identifier les pièces défectueuses, de détecter les pannes récurrentes et de comparer les performances des fournisseurs. Notre objectif est d'exploiter Power BI pour visualiser ces données, distinguer les fournisseurs les moins performants et optimiser le suivi des machines afin d'améliorer la production.

## Description des Données
Nous avons utilisé deux bases de données principales :

Machine Performance : Cette base suit les performances des machines et contient des informations telles que l'identifiant du produit, les températures ambiante et du processus, la vitesse de rotation, le couple appliqué, l'usure de l'outil, les indicateurs de panne, l'identifiant de l'usine et la date d'enregistrement.

Quality Analysis : Cette base concerne l'analyse de la qualité des pièces et le suivi des fournisseurs. Elle comprend des informations sur la date d'enregistrement, l'identifiant du fournisseur, l'identifiant du matériau, le type et l'identifiant du défaut, la quantité de pièces défectueuses, le temps d'arrêt lié au défaut, et des informations sur le fournisseur et l'usine.

## Développement des Visuels
Pour exploiter ces données efficacement dans Power BI, nous avons réalisé un travail de transformation sur la table Quality Analysis afin d'obtenir une structure optimisée. Ce travail a permis de créer :

Des tables de dimensions : Vendors (fournisseurs), Plants (usines), Defects (défauts), Defect Types (types de défauts), Materials (matériaux) et Material Types (types de matériaux).
Des tables de faits : Regroupant les informations sur les défauts et leur impact sur la production.
Cette structuration permet une analyse plus détaillée et une meilleure visualisation des performances des fournisseurs et des machines.

## Dashboard Global de l’Analyse
Un dashboard global a été conçu pour centraliser l’analyse des principaux indicateurs liés à la qualité, aux fournisseurs, aux arrêts machines et à la performance des équipements. Ce tableau de bord interactif permet une visualisation claire et synthétique des données à travers plusieurs KPIs clés :

Qualité : Suivi de la quantité de pièces défectueuses et analyse des types de défauts.
Arrêts : Évaluation du temps d’arrêt machine et de son évolution dans le temps.
Fournisseurs : Identification des fournisseurs les plus performants et des moins performants à partir des données de défauts.
Performance : Analyse des défaillances machines et suivi de leur évolution.
Pages du Rapport
Qualité : Quantité totale de produits défectueux détectés, répartition des défauts par type de défaut et par type de matériel, identification des défauts ayant un impact et des défauts rejetés, analyse des défauts sur les jours de la semaine vs. week-ends, identification du site ayant les meilleures performances en termes de qualité.

Analyse des Arrêts : Analyse du temps d’arrêt total enregistré, répartition des arrêts par mois et par catégorie (électrique, logistique, mécanique, etc.), corrélation entre les arrêts et les types de défauts ayant un impact.

Analyse des Fournisseurs : Nombre total de fournisseurs et nombre de fournisseurs sans défauts, identification des cinq fournisseurs avec les pires performances en termes de défauts, types de rejets majeurs associés aux fournisseurs les plus défaillants.

Performance : Analyse des pannes machines et leur évolution au fil du temps, corrélation entre les pannes machines et le temps d’arrêt, identification des catégories influençant le plus les temps d’arrêt (logistique, mécanique, emballage, etc.).

Des rôles ont été ajoutés pour permettre aux équipes de chaque continent et de chaque état de visualiser uniquement les données relatives à leurs usines.

## Conclusion
Ce projet démontre l'importance de la visualisation des données dans l'industrie. Grâce à Power BI, nous avons pu centraliser et analyser des données complexes, permettant ainsi une prise de décision plus éclairée et une optimisation des processus industriels. Nous espérons que notre travail inspirera d'autres professionnels à exploiter les outils de data visualisation pour améliorer leurs performances.
