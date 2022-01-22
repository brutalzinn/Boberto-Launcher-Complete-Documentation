# Web Launcher Boberto part manual

### Française

Dans ce fichier, vous apprendrez les bases du fonctionnement de la partie web du lanceur boberto et une brève explication de chaque implémentation importante.


1. Clonez le projet https://github.com/brutalzinn/boberto-launcher-web
2. Changer le nom de .env.exemple en .env
3. Définissez la variable d'environnement selon vos paramètres. Ne vous inquiétez pas pour les mots de passe bancaires et autres. Docker téléchargera tous les services dont le projet a besoin pour fonctionner. Il suffit donc de configurer le fichier .env avec vos données.
4. Exécutez la commande docker-compose up
5. Allez sur http://127.0.0.1/ dans le navigateur
6. Voyez si vous obtenez un OK
7. Testez l'api http://127.0.0.1 avec l'outil postman. La collection est disponible dans ce même dépôt. Cette api sera utilisée par le gestionnaire de modpacks et, à l'avenir, par le lanceur.
8. Téléchargez un client Redis et vérifiez s'il fonctionne correctement.
9. Ouvrez le lanceur en mode développement et vérifiez si la console affiche des échecs.
10. Partie web cofigurée.