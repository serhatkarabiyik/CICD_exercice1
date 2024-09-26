# CICD_exercice1

1-Commande pour construire l'image 
-docker build -t node-exercice-1

2-Commande pour démarré le conteneur
-docker run -p 3000:3000 node-exercice-1

3-Commande pour supprimer le conteneur:
Aficher les conteneurs
-docker ps

Recuperer l'id puis stopper le conteneur
-docker stop (id)

Supprimer le conteneur
-docker rm (id)

Recuperer l'id de l'image
-docker images
-docker rmi (id)


# CICD_exercice2
1-Commande pour construire l'image 
-docker build -t python-exercice-2

2-Commande pour démarré le conteneur
-docker run -p 5000:5000 python-exercice-2

3-Commande pour supprimer le conteneur:
Aficher les conteneurs
-docker ps

Recuperer l'id puis stopper le conteneur
-docker stop (id)

Supprimer le conteneur
-docker rm (id)

Recuperer l'id de l'image
-docker images
-docker rmi (id)
