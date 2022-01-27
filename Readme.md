# Projet reconnaissance facial
## But du projet
Le but de ce projet est la réalisation d'un modèle de reconnaissance facial se basant sur la base de donnée yalefaces qui compte un ensemble de 165 images réparti sur 15 personnes différentes (11 images par personne), dans différent cas de figure (expression du visage, lumonisité...) en utilisant deux descripteurs différents et comparant les performances. 
## Descripteurs utilisés
Les descripteurs utilisés dans ce projets sont : 
1. La transformée de Fourier en cosinus discrète de l'image (DCT)
2. La matrice des gradients orientés de l'image (HoG) 
## Modèles développés dans le projet
Les modèles utilisés avec chaque descripteur sont : 
1. Un modèle basé sur l'algorithme des K-plus proches voisins (KNN)
2. Un réseau de neurones multicouches simples (MLP)
## Fichiers utilisés
Le projet est constitué de : 
- 2 dossiers d'images : 
    - yalefaces : qui contient les images originales retrouvable dans la base de données sur internet
    - yalefacesgif : les images auxquelles on a ajouté l'extension appropriée (j'ai ajouté l'extension .bmp mais le projet est parfaitement faisable en ajoutant l'extension bmp)
- Le fichier ajoutbmp.py : qui permet de prendre toutes les images d'un dossier et de modifier les extensions des fichiers
- Le fichier Readme-yalefaces.txt : C'est le fichier Readme trouvable dans la base de données yalefaces
- Un Jupyter Notebook qui contient l'ensemble du projet