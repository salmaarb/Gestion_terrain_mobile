# Localisation des terrains
 Ce projet a pour but de mettre en place  une application mobile qui permet la localisation des terrains par zone et ville, la recherche d'un terrain, la reservation
  d'un terrain en precisant la date de reservation.Les terrains seront affiché dans une map avec la possibilité d'afficher la distance entre le client et un tel terrain ainsi que l'itinéraire.Il utilise spring boot côté serveur.
 
# Fonctionnalités

1. Affichage des terrains ainsi leurs informations.

3. Possibilité de filtrer les terrains.

4. Affichage de la distance entre le client et un tel terrain selectionné et l'itineraire.

5. Réservation d'un terrain.

# Mise en place du projet   

Pour mettre en place ce projet, vous aurez besoin des éléments suivants :

1. Android studio

2. Spring Boot backend : ce sera le côté serveur de notre application Web. Il traitera les demandes de l'interface, interrogez une base de données pour récupérer ou mettre à jour des données, et renvoyez des réponses à l'interface.

# Démarrage projet

Pour déployer ce projet  suivez les étapes suivantes :

Téléchargez le projet sur votre ordinateur.

Ouvrez-le dans votre android studio.

lancer le backend Spring boot.

Exportez le projet en tant qu'archive WAR.

remplacez les adresses ip avec votre propre adresse Ip.

# Architecture de l'application :

L'application mobile communiquera avec le backend à l'aide d'API.

Il utilisera l'architecture MVVM qui est un modèle architectural pour la mise en œuvre d'interfaces utilisateur qui sépare le développement de l'interface utilisateur en trois rôles distincts :

Modèle : le modèle représente les données avec lesquelles l'application fonctionnera. Il est responsable de la gestion de la logique métier et de la persistance des données.

Vue : la vue est l'interface utilisateur avec laquelle l'utilisateur interagit. Il est chargé d'afficher les données et de traduire les entrées de l'utilisateur en actions que le modèle peut comprendre.

ViewModel : le ViewModel est le ciment qui lie le modèle et la vue. Il est chargé de convertir les données du modèle en un formulaire que la vue peut afficher et de traduire les entrées de l'utilisateur dans la vue en actions que le modèle peut comprendre.

![156711399-b38e9f5c-10f9-49fe-b979-75cd5cb78989](https://user-images.githubusercontent.com/101585977/211149822-736f9621-6fcb-4c48-980a-e643c2c7c9af.png)
