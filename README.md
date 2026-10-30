# Analyse_donnees_medicales_synthetiques

Ce fichier détaille les commandes à exécuter pour tester notre code.

- main.c : fichier principal, il utilise les fonctions des autres fichiers
- getData.c (et getData.h) : fonctions pour lire les fichiers patients.pengu et livestyle.pengu et stocker les données dans une structure de données
- sampling.c (et sampling.h) : fonctions pour échantilloner les données (les patients) en deux jeux de données distincts (entraînement et test)
- perceptron.c (et perceptron.h) : fonctions pour entraîner le perceptron, tester les données, calculer l'accuracy et afficher les résultats
- perceptronBonus.c (et perceptronBonus.h) : entraînement du perceptron a 7 dimensions, test et calcul de l'accuracy
- kmeans.c (et kmeans.h) : algorithme des k-means

Ainsi, pour tester le code, il suffit de télécharger ces fichiers puis exécuter les commandes suivantes dans un terminal :
gcc main.c getData.c sampling.c perceptron.c perceptronBonus.c kmeans.c -o programme -lm
./programme
