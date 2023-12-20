                                       Remarque
Sachez que je vous mets ci-joint le fichier tableau que vous pouvez ouvrir afin de bien visualiser mon travail dans le tableau, pour se faire vous devez avoir installer  tableau dans votre ordinateur.

                                       But du Projet

Pour répondre aux exigences de l’entreprise et fournir des informations stratégiques à différents niveaux de responsabilité, la direction a fait appel à son équipe de Data Analysts.
Sa mission consiste à mettre en place des tableaux de bord dynamiques permettant un suivi efficace des KPI et facilitant la prise de décisions stratégiques. 
L’entreprise de vente au détail fait face à des difficultés financières : 
                    Comment l’aider à suivre les ventes afin de maximiser son profit tout en minimisant ses coûts et en générant un chiffre d'affaires optimal ?

Les principales parties prenantes, notamment le Directeur Général, le Directeur de Région, le Directeur d’État, le Responsable de Ville, le Responsable Financier 
et le Responsable Import/Export, ont été identifiés comme cibles. Dans la suite de cette étude nous avons identifié quatre KPI (indicateurs clés de performance), 
qui semblent être les plus pertinents pour chaque cible.

                                  Les differents Users-Stories

hhhhhh

                                  Identifications des KPIs
Nous avons identifié quatre KPI à savoir le profit, les ventes, le chiffre d’affaires et le coût.

                                  Prototypage

Le prototypage émerge comme une étape importante dans notre approche pour répondre aux demandes des responsables. Nous utilisons cette méthode pour regrouper les User Stories en fonction
de KPI spécifiques. Cette méthode offre ainsi une vue structurée des exigences alignées sur les objectifs stratégiques de l’entreprise.
En identifiant les KPI tels que le Profit, les Ventes, le Chiffre d’affaires et les Coûts, nous organisons nos User Stories en quatres prototypes distincts.

                                Maquettages
                                
Le maquettage représente la troisième étape dans notre processus d’analyse. Il fournit une représentation visuelle préliminaire de l’interface utilisateur du tableau de bord. C’est une méthode rapide
et efficace pour donner forme à des idées conceptuelles et explorer diverses structures et mises en page
pour chaque prototype déjà établi. Cette pratique nous permet non seulement de recueillir des retours
précoces et d’itérer rapidement sur le design, mais également de nous assurer que la vision du produit
est alignée avec les attentes des responsables du métier.

Dans la suite, on présente les maquette qui représentent les tableaux de bords répondants aux différents Users-Storie selons la répartitions des prototypes 
c'est-à-dire selon les KPIs.


                           1- Maquette qui réponds au premier prototype

On a créé un paramètre top N states qui ordonne les States en fonction du profit.
Nous avons ensuite créé 2 ensembles : Ensemble State et Ensemble State 2 en leur fixant comme
paramètre le ’top N States’.
On les applique ensuite comme filtres : ‘Ensemble State’ affiche les N States avec le meilleur profit et
un ‘Ensemble State 2’ affiche les states avec les pires profits.
Dans les vues ’Top N Total Profit’ et ’Top N Perte’, nous avons utilisé une infobulle qui indique l’origine
du profit de chaque État en fonction des catégories.
De même, dans la vue ’Total Profit par Catégorie et Région’, une infobulle est utilisé pour montrer
l’origine du profit d’une catégorie en fonction des sous-catégories.

                           2- Maquette qui réponds au deuxième prototype
On a créé un champ calculé coût en faisant la formule [ventes-profit] afin d’évaluer la rentabilité,
l’efficacité des opérations, l’optimisation de l’utilisation des ressources et nous aider à prendre des
décisions.
On a également choisi un champ calculé temps de préparation en faisant la formule (order date ship date). Il nous a permis d’évaluer la performance opérationnelle de notre logistique. Il nous a
permis également de faire le suivi des tendances au fil du temps.
On a également fait un champ calculé des ventes avec/sans remise en faisant la formule si discount>0 (c’est un booléen). Elles nous ont permises d’analyser l’impact spécifique des remises sur le
chiffre d’affaire global en évaluant la contribution des remises à la croissance des ventes, en identifiant
les produits ou les segments qui bénéficient le plus de remises. Elles nous ont permises de segmenter
nos données.
Ici nous constatons qu’en général, c’est la catégorie ’Office Supplies’ qui est la plus vendue, avec un
total de 160 683 ventes. De manière générale, le mode d’expédition ’Standard Class’ est le plus utilisé.
Nous avons remarqué qu’il y a eu 1 209K ventes avec remise contre 1 088K ventes sans remises.

                             3- Maquette qui réponds au troisième prototype
                             
On a fait un champ calculé ’Chiffre d’affaire’ en effectuant la somme des profits afin d’évaluer la
performance financière de notre entreprise.
Nous constatons que c’est en 2023 qu’il y a eu le meilleur chiffre d'affaires, et une grande partie de ce  montant provient principalement de la région Ouest.

                             4- Maquette qui réponds au quatrième prototype

On a créé un champ calculé coût en faisant la formule [ventes-profit] afin d’optimiser l’utilisation des ressources.
On a créé une infobulle qui montre la provenance du coût pour chaque région dans chaque catégorie de
produits. Cela permet une meilleure visualisation de la répartition des coûts par catégorie pour chaque
région.


