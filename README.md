Première étape : 
Créer et lancer le projet ReactJS dans PowerShell à l'aide des commandes suivantes 
    - npx create-react-app mon-app 
    - cd mon-app 
    - npm start

Deuxième étape : 
Modifier le fichier index.html pour afficher Hello world avec mon nom et prénom

Troisième étape : 
Créer un fichier ci.yml dans les dossiers .github/workflows/ dans lequel on retrouve le script qui va build et installer les dépendances nécessaires au projet

Quatrième étape : 
Pour déployer le projet sur github page, il faut le push sur un nouveau repositorie dans lequel on va créer une nouvelle branche que l'on appelle gh-pages qui va permettre de compiler le code. Ensuite, dans les settings on va dans pages où l'on change la branche pour celle que l'on vient de créer. Et il n'y a plus qu'à récupérer le liens qui s'affiche lorsque l'on valide les changements pour avoir accès à notre projet sur github page. Attention à ne pas oublié de rajouter /public à la fin du lien pour afficher le fichier index.html, sinon se sera le fichier README qui s'affiche.
