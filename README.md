# mini-projet

Introduction :
Pour qu’aujourd’hui l’informatique s’élève vers les nuages, qu’elle devienne « Cloud Computing » : le cloud computing consiste a exploiter la puissance de calcule ou de stockage de serveurs informatiques distants par l’intermédiaire d’un réseau, généralement l’internet.
Dans notre projet, nous volons réaliser une application de conversion de document qui sera prête à être déployer pour le cloud.

1-	a) l’architecture globale de l’application :
![1](https://user-images.githubusercontent.com/44180360/51027193-86a5d680-1590-11e9-8189-98076f0cb4a3.PNG)
![2](https://user-images.githubusercontent.com/44180360/51027205-8efe1180-1590-11e9-8187-7a722e8dacbc.PNG)


b) l’architecture de la couche de données :
![3](https://user-images.githubusercontent.com/44180360/51027215-93c2c580-1590-11e9-8b50-36210dcaa7db.jpg)

c)la manière de gestion des demandes de client :
Après l’authentification de client ou leur inscription ,il choisi la conversion voulu à travers l’application , La demande sera enregistrée dans une base, Un message sera envoyé lors de l’enregistrement de la demande là ou il trouvera sa demande s’il elle est en attente ou en cours ou bien terminé et la conversion de document effectuer ensuite ,il peut répétée l’opération de conversion d’autre document (soit fichier html , JPG , png …) et la même opération effectuer pour un autre client pour la conversion de leur document.

4) les technologies choisies pour le développement de l’application :
Le Cloud computing, plateforme JAVA EE, Le modèle MVC, JSP
 1/Cloud computing : pour notre application on va utiliser une plateforme Cloud  sur laquelle elle sera déployée et exécutée.
En effet, le Cloud computing offre un moyen simple d’accéder a des serveurs, a des stockages et a des bases de donnés, ainsi qu’une large gamme de service applicative sur internet, en plus de ca offre une vitesse et souplesse accrues pour notre application.
  2/JAVA EE : Java Entreprise Edition, c’est une norme qu’à une « plateforme » pour développer  notre application  rapidement, de façon performante, et…à moindre coût !
3/Le modèle MVC :
Ce modèle nous permet  de séparer notre structure en multiple calques. et offre une meilleure maintenance de notre projet et nous facilite la tâche durant les tests unitaires 
Un autre avantage est le fait qu’il y a peu d’accrochage entre les vues, les modèles et les contrôleurs, ce qui nous permet d’avoir un code propre où les fonctions & les classes peuvent être facilement réécrite & optimisé…
Notre application sera conçue en utilisant les servlets,
En utilisant les servletes a causes de leurs offres pour notre application comme l’extensibilité, l’intégrité dans des environnements plus larges, la performance, Sécurisées : exécutées dans une JVM.
Ainsi Les servlets ont de nombreux avantages par rapport aux autres technologies côté serveur. Tout d'abord, étant donné qu'il s'agit d'une technologie Java, les servlets fournissent un moyen d'améliorer les serveurs web sur n'importe quelle plateforme (et surtout pour la plateforme de notre application), d'autant plus que les servlets sont indépendantes du serveur web (contrairement aux modules apache ou à l'API Netscape Server). En effet, les servlets s'exécutent dans un moteur de servlet utilisé pour établir le lien entre la servlet et le serveur web. 
4/ le Java Server Pages oui JSP est une technique basée sur java qui permet aux développeurs de créer dynamiquement du code HTML ,XML ou tout autre type de page web .cette technique permet au code java et a certaine actions prédéfinies  d’être ajoutés dans un contenu statique .Cette technique permet la création de bibliothèque de balises JSP qui agissent comme des extensions au HTML ou XML .les bibliothèques de balise offrent une méthode indépendante de la plate forme pour étendre les fonctionnalités d’un serveur HTTP .les JSP sont compilées par un compilateur JSP pour devenir des servlets java .

Conclusion 
Alors, nous souhaitons que notre application prête pour uploader dans le cloud et fournir les objectifs attendus en utilisant les technologies choisies pour  le développement quand à déjà parler.
