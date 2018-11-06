# TPNo-01










Rapport De Projet


Realiser par :
                          *Rebbouh Lyes.
                          *Nasri zine eddine 
 

1.	ARCHITECTURE GLOBALE:

Le Model MVC :

MODEL
Dans notre cas le model est chargé de gérer les données
des clients comme par exemple dans l’opération de l’authentification
et aussi les définitions des formats des conversation qui utilisée dans 
notre service cloud et l’ensemble des règles des gestions de 
l’utilisateur.

VIEW
La vue est chargée de la mise en forme de notre service c’est l’interface qui utiliser par l’utilisateur pour 
Uplode les ficher et la conversation et Ilya aussi les interface comme par exemple le système authentification

CONTROLLER
Le contrôleur est chargé de gérer l’ensemble de l’opération entre le model et le view et aussi l’ensemble de l’opération de la conversion.












2.	L’architecture de la couche données

Description Générale des données

Les données de notre client :
•	Email
•	Username
•	 Password
•	Ensemble des permissions des client
L’ensemble d’informations des fiches :
•	Format (MP3, MP4, DOCX, PDF)
•	Les tailles des fiches

Diagramme de classe :



Passage relationnel (Base De données) :















La maniére de la gestion des clients :
En utilisant des threads avec un serveur concurrent par création de processus fils pour les échanges de chaque requête 













La technologie JAVA EE :
Java Platform, Enterprise Edition, Java EE ou Jakarta EE est une spécification pour la plate-forme Java d'Oracle, destinée aux applications d'entreprise2.
La plate-forme étend Java Platform, Standard Edition (Java SE) en fournissant une API de mapping objet-relationnel, des architectures distribuées et multitiers, et des services web3. La plate-forme se fonde principalement sur des composants modulaires exécutés sur un serveur d'applications.
Pour ce faire, Java EE définit les éléments suivants :
•	une plate-forme (Java EE Platform), pour héberger et exécuter les applications, incluant outre Java SE des bibliothèques logicielles additionnelles du Java Development Kit (JDK) ;
•	une suite de tests (Java EE Compatibility Test Suite) pour vérifier la compatibilité ;
•	une réalisation de référence (Java EE Reference Implementation), dénommée GlassFish ;
•	un catalogue de bonnes pratiques (Java EE BluePrints) ;
•	un code script.
À chaque version de Java EE correspond notamment, comme toutes les éditions Java :
•	les Java Specification Requests (JSR), constituant les spécifications de la version considérée ;
•	un Java Development Kit (JDK), contenant les bibliothèques logicielles ;
•	un Java Runtime Environment (JRE), contenant le seul environnement d'exécution (compris de base dans le JDK).
