# Manuel du lanceur Web Boberto

### FRENCH

Dans ce fichier, vous apprendrez les bases du fonctionnement du composant WebPart Boberto Launcher et une brève explication de chaque implémentation importante


1. Clonez le projet https://github.com/brutalzinn/boberto-launcher-web
2. Changez le nom de .env.example en .env
3. Configurez une variable d'environnement avec vos paramètres. Ne vous inquiétez pas des mots de passe bancaires ou des choses comme ça. Docker télécharge tous les services dont le projet a besoin pour s'exécuter. Ne vous inquiétez donc que de la configuration du fichier .env avec vos données.
4. Exécutez la commande docker-compose up
5. Accédez à http://127.0.0.1/teste.php dans le navigateur
6. Voyez si vous avez un OK
7. Testez l'API http://127.0.0.1:5000 avec l'outil postman. La collection y est disponible. Cette api sera utilisée par le gestionnaire de modpack.
8. Téléchargez le client pour Redis et assurez-vous qu'il est correct.
9. Ouvrez le lanceur et voyez s'il répond.

