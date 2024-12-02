Première étape : <br>
Créer et lancer le projet ReactJS dans PowerShell à l'aide des commandes suivantes <br>
    - npx create-react-app mon-app <br>
    - cd mon-app <br>
    - npm start<br>
<br>
Deuxième étape : <br>
Modifier le fichier index.html pour afficher Hello world avec mon nom et prénom<br>
<br>
Troisième étape : <br>
Créer un fichier ci.yml dans les dossiers .github/workflows/ dans lequel on retrouve le script qui va build et installer les dépendances nécessaires au projet<br>
<br>
Quatrième étape :<br> 
Pour déployer le projet sur github page, il faut le push sur un nouveau repositorie dans lequel il faut modifier les settings pour donner la permission aux Workflows de lire et écrire et dans Pages, on doit choisir gh-pages comme branche pour Github Page permettant de compiler le code. Il n'y a plus qu'à récupérer le liens qui s'affiche lorsque l'on valide les changements pour avoir accès à notre projet sur github page.