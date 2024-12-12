Projet "Dice" - Gestion de lancés de dés avec Spring Boot

-Création du projet Spring Boot et ajout des dépendances nécessaires : Spring Web, Spring Data JPA, H2 Database .
-Configuration du projet
-Création de la classe Dice
-Création de l'entité DiceRollLog
-Modélisation de l'entité JPA DiceRollLog 
-Utilisation des annotations JPA  @Entity, @Id, @GeneratedValue, etc.
-Implémentation de l'interface héritant de JpaRepository<DiceRollLog, Long> pour gérer les interactions avec la base de données.
-Création du contrôleur REST pour lancer les dés et du contrôleur REST annoté avec @RestController.
-Ajouts des endpoints GET /rollDice et GET /rollDices/{X} .
-Création du Service marqué avec @Service contenant une methode pour enregistrer l’historique des lancés dans la base via le Repository.
-Contrôleur pour afficher les historiques
-Ajouts du contrôleur REST permettant d'afficher l'historique des lancés; 
-Tests et validation
