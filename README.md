Contexte de projet:

Le projet d'analyse de données sur le diabète consiste à allez explorer un ensemble de données contenant des informations sur différents aspects médicaux des patients. 
L'objectif est de réaliser plusieurs étapes d'exploration et d'analyse des données, suivies de visualisations pour mieux comprendre les caractéristiques des individus présents dans 
le jeu de données. Le jeu de données utilisé pour cette analyse provient à l'origine d’un échantillon publié par un Institut du diabète. Il contient plusieurs variables prédictives 
médicales et une variable cible, « Outcome ». Les variables prédictives comprennent le nombre de grossesses que le patient a eues, son IMC, son taux d'insuline, son âge, etc.

Chaque ligne représente un patient et les colonnes sont :

Grossesses: nombre de fois enceintes
Glucose: Concentration en glucose plasmatique 2 heures dans un test detolérance au glucose par voie orale
BloodPressure: pression artérielle diastolique (mm Hg)
SkinThickness: Épaisseur du pli cutané des triceps (mm)
Insuline: insuline sérique de 2 heures (mu U / ml)
IMC: indice de masse corporelle (poids en kg / (taille en m) ^ 2)
DiabetesPedigreeFunction: Fonction pedigree du diabète
Age: Age (ans)
Résultat: Variable de classe (0 ou 1).

Étape 1 : Lecture des données
Cette première étape consiste à effectuer plusieurs opérations sur les données pour les analyser et les comprendre. Voici les tâches que vous devez effectuer :

1. Faire une sélection des données qui ont leur glucose supérieur à 90 et les afficher.
2. Faire une sélection des données qui ont leur glucose entre 90 et 130, et les afficher.
les.
3. Sélectionner uniquement les colonnes: Outcome, BMI, and Age, et les afficher.
4. Sélectionner uniquement les 8 premières lignes de chaque affichage et les afficher.
les.
5. Sélectionner les données qui ont Outcome = 1 et Pregnancies>0, et les afficher.
6. Sélectionner uniquement les colonnes Glucose et BloodPressure, et les afficher.
7. Afficher les 3 premieres lignes du dataframe résultant.
8. Combien de personnes dans ce jeux de données sont atteintes du diabète et qui ont une tension artérielle (BloodPressure) supérieur à 70 ?
9. Quelle est la moyenne de "SkinThickness" lorsque le outcome est égal à 1 ?
10. Comment savoir si notre jeu de données possède des champs vides ?
11. Afficher le type de données des colonnes
12. Afficher le résumé statistique de notre data frame

Étape 2 : Visualisation des données
Cette étape, consiste à explorer visuellement les données en utilisant des graphiques pour mieux les comprendre. Voici les tâches à effectuer :
1. Examinons de plus près les données en dessinant un histogramme des valeurs des données pour chaque colonne.
2. Représenons graphiquement la répartition des âges des individus diabétiques par rapport à celle des individus non diabétiques à partir de ce jeu de donnéesen utilisant un
   histogramme.

Outils utilisés :
Éditeur de code : Jupeter-Notebook
Langage : Python
Librairies : Pandas, Matplotib et Seaborn
