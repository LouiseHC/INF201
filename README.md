# INF201
This is my first Java project in Eclipse

It is a runable .jar 

This small program interogate a specific database by using prepared SQL queries in Java.

The "patient" database is created through a SQL script that is not published here.



---------------------------

Ce projet a pour objectif de créer une application en Java afin de manipuler des données du PMSI stockées dans une base de données SQL.

Prérequis :
Création de la base de donnée SQL avec l'aide de DBeaver et du script "bd_projet.sql"

Création de l'application :
L'application a été développée en Java dans l'outil de développement intégré Eclipse.
La communication entre Java et SQL se fait grâce à un connecteur JDBC inclu dans les "referenced libraries" du projet livré
dont la version est "mysql-connector-java8.0.25.jar"
Ce connecteur permet la connection à la base de donnée ainsi que l'execution de requêtes.

L'application développée n'a pas d'interface graphique, l'interraction avec l'utilisateur se fait dans la console.


L'application permet à l'utilisateur d'obtenir des informations stockées dans la base de donnée grâce à un menu.
Ce menu renvoie 6 options préparées 


Difficultés rencontrées :
- gestion des entrées clavier (avant d'utiliser le script keyboard, j'ai tenté d'utiliser le scanner et le buffered reader)
- gestion des erreures et des exeptions, je n'ai pas réussi à résoudre certaines erreures qui entrainent une sortie de script.


