
                                     But du Projet

Ce projet académique, réalisé dans le cadre de mon Master 1, a pour objectif :
- De comprendre les attentes de l’entreprise à travers l’analyse des users stories.
- D’identifier des indicateurs de performance (KPI) pertinents en fonction des users stories.
- De concevoir des tableaux de bord interactifs afin de maîtriser l’utilisation de l’outil Tableau.

                                     Contexte

Le projet est basé sur les données d’une entreprise américaine spécialisée dans la vente au détail à l’échelle mondiale. Cependant, les données disponibles concernent uniquement les ventes effectuées aux États-Unis.

Pour répondre aux exigences de l’entreprise et fournir des informations stratégiques adaptées aux différents niveaux de responsabilité, l’objectif est de développer des tableaux de bord dynamiques permettant :
- Un suivi efficace des indicateurs de performance (KPI).
- Une prise de décision éclairée et stratégique.

                                       Remarque
Je vous joins le fichier Tableau en pièce jointe. Vous pouvez l’ouvrir pour visualiser mon travail dans l’outil Tableau.

                                  Les differents Users-Stories

Voici les besoins recueillis auprès des parties prenantes, notamment le Directeur Général, le Directeur de Région, le Directeur d’État, le Responsable de Ville, le Responsable Financier et le Responsable Import/Export, qui ont permis d’identifier des attentes spécifiques et des objectifs à intégrer dans la conception des tableaux de bord interactifs:

![image](https://github.com/Hadad-Ahmed-Ali/Business-Intelligence/assets/128106188/eb8f7cf0-f5d2-41c3-bd45-cb118eb6a142)


                                  Identifications des Indicateurs de performence (KPI)

À partir des informations recueillies auprès des différentes parties prenantes, j’ai identifié quatre indicateurs clés de performance : **le profit, les ventes, le chiffre d’affaires et le coût**, qui ont été sélectionnés pour leur pertinence dans l’évaluation des performances de l’entreprise et leur impact stratégique.

                                  Prototypage

Le prototypage constitue une étape essentielle pour répondre efficacement aux attentes des responsables. Cette méthode permet de regrouper les users stories en fonction des indicateurs de performance spécifiques, offrant ainsi une vue structurée et alignée sur les objectifs stratégiques de l’entreprise.

En nous concentrant sur les indicateurs de performance identifiés (Profit, Ventes, Chiffre d’affaires, Coûts), nous avons développé quatre prototypes distincts :
- Prototype lié au profit – Pour analyser les marges bénéficiaires.
- Prototype lié aux ventes – Pour suivre les volumes et tendances des ventes.
- Prototype lié au chiffre d’affaires – Pour évaluer les revenus générés.
- Prototype lié aux coûts – Pour identifier les postes de dépense et optimiser les ressources.
  
Ces prototypes offrent une base solide pour la conception de tableaux de bord interactifs, adaptés aux besoins de l’entreprise et des parties prenantes.

![image](https://github.com/Hadad-Ahmed-Ali/Business-Intelligence/assets/128106188/123ec3c3-b9a3-4a4e-a529-0e8cf23002b7)


                                Les Taleaux de bord
                                
Voici les tableaux de bord conçus pour répondre aux différents prototypes définis, chacun étant aligné avec les indicateurs de performance (KPI) spécifiques.

                           1- Taleaux de bord qui réponds au premier prototype
![image](https://github.com/Hadad-Ahmed-Ali/Business-Intelligence/assets/128106188/826ebe8e-b57f-47ed-b3de-4192672ff3ba)

Dans ce tableau de bord, nous avons créé un paramètre **"Top N States"** qui permet de classer les États en fonction du profit.

Ensuite, deux ensembles ont été définis :

- **Ensemble State**
- **Ensemble State 2**

Ces ensembles sont configurés en fonction du paramètre **"Top N States"**. Nous les appliquons ensuite comme filtres :

- Ensemble State affiche les N États générant le meilleur profit.
- Ensemble State 2 affiche les États avec les pires profits.

Dans les vues **"Top N Total Profit"** et **"Top N Perte"**, une **infobulle** est utilisée pour indiquer l'origine du profit de chaque État, en fonction des catégories de produits.

De même, dans la vue **"Total Profit par Catégorie et Région"**, une **infobulle** affiche l’origine du profit pour chaque catégorie, en détaillant les sous-catégories concernées.

                           2- Taleaux de bord qui réponds au deuxième prototype
![image](https://github.com/Hadad-Ahmed-Ali/Business-Intelligence/assets/128106188/4173913b-52f4-4bca-a775-44ff90e275c9)

On a fait un champ calculé temps de préparation en faisant la formule **[Order Date - Ship Date]** qui pert d’évaluer la performance logistique et la rapidité des opérations.

On a également fait un champ calculé des **ventes avec/sans remise**. Elle permet d’analyser l’impact spécifique des remises sur le chiffre d’affaire global en évaluant la contribution des remises à la croissance des ventes, en identifiant les produits ou les segments qui bénéficient le plus de remises.

Ici nous constatons qu’en général, c’est la catégorie **Office Supplies** qui est la plus vendue, avec un
total de 160 683 ventes. De manière générale, le mode d’expédition **Standard Class** est le plus utilisé.
Nous avons remarqué qu’il y a eu 1 209K ventes avec remise contre 1 088K ventes sans remises.

                             3- Taleaux de bord qui réponds au troisième prototype
![image](https://github.com/Hadad-Ahmed-Ali/Business-Intelligence/assets/128106188/37ac3000-31f9-4bf1-ad27-848fcbc7b99c)
                            
Nous avons créé un champ calculé intitulé **Chiffre d’affaires**, en utilisant la formule :
Somme des profits. Cet indicateur nous permet d’évaluer la performance financière globale de l’entreprise.

**Résultats clés:**

- Année la plus performante : L’année 2023 enregistre le meilleur chiffre d’affaires.
- Contribution régionale : Une grande partie de ce montant provient principalement de la région Ouest, soulignant son importance stratégique dans les performances globales.

                             4- Taleaux de bord qui réponds au quatrième prototype
![image](https://github.com/Hadad-Ahmed-Ali/Business-Intelligence/assets/128106188/306b3a3b-1dda-494e-b861-0d861343375b)

Nous avons créé un champ calculé Coût, en utilisant la formule :
**[Ventes - Profit]**, afin d’optimiser l’utilisation des ressources et d’évaluer l'efficacité des opérations.

**Infobulle de répartition des coûts**:

Nous avons également intégré une infobulle qui affiche la provenance du coût pour chaque région, répartie par catégorie de produits. Cette fonctionnalité permet :

- Une visualisation détaillée de la répartition des coûts par catégorie pour chaque région.
- Une analyse plus précise des zones géographiques et des catégories de produits les plus impactées par les coûts.


