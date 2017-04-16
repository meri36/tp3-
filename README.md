#TP3 SIR réalisé par Meriem Machnache & Lydia Moussa

# MongoDB

 MongoDB est un système de gestion de base de données,qui a un mécanisme différent.
 Nous ne créons pas de tables relationnelles mais plutot des requetes sql complexes
 
 Le stockage des données est fait dans le même format qu'un document JSON.
 Nous pouvons le comparer à un dictionnaire composé de clés et de valeurs.
   
 Nous pouvons comparer une collection en MongoDB à une table, une collection est un ensemble de  documents.
 
# Limites d’une base données orientées document:

Dans une base de données relationnelle, le stockage de données est fait par lignes et colonnes.
Par contre,les bases de données comme que MongoDB proposent un mode de stockage dans un document, 
au format JSON.

Les limites d'une base de données orientées document sont :

- la modélisation en document ne permet pas la même flexibilité dans les requêtes et les chargements de données que la modélisation relationnelle. 

- Une base de données NoSQL n'utilise pas les propriétés ACID 
 (atomicité, cohérence, isolation et durabilité).

Les problèmes rencontrés avec MongoDb: Insérer des documents dépassant les 16 mo de limite.
La taille est limitée pour faire le stockage d'un gros nombre de données dans les documents.
La taille du document augmente très rapidement.



# Redis
Redis est un système de gestion de base de données (SGBD) fonctionnant sur le principe clé-valeur scalable. C'est en gros une grosse HashMap.

La force caractéristique de Redis consiste à stocker les données en mémoire vive (RAM).

## Types de données stockés dans Redis:

 Redis permet de manipuler différents types de données:
 	- chaînes de caractères: string peut etre du format JSON, valeur d'une image JPEG.
 	- hashs qui permet de stocker plusieurs clés et valeurs.
 	- listes de type linkedlist qui facilite l'insertion d'un élément, soit en tete ou en queue.
 	- sets
 	- sets triés

## Types de requetes
	-SET: ca permet de stocer l'information d'une facon permanente.
	-GET: ca permet de récupérer un résultat précis.
	-DEL: ca permet de supprimer la clé et sa valeur associée.
	-RPUSH: Met une nouvelle valeur dans la queue de la liste.
	-LPUSH: Met une nouvelle valeur dans le début de la liste.
	-LLEN: Retourne la longueur de la liste.
	-LRANGE: Renvoie un sous ensemble de la liste.
	-LPOP: Supprime le premier élément de la liste.
	-RPOP: Supprime le dernier élément de la liste.
	-SAAD: Ajoute la valeur courante à la liste.
	-SREM: Supprime une valeur donnée de la liste.
	
 	 
 


   
  .