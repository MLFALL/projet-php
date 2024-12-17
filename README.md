# projet-php
Création d'un Repository public sur GitHub et cocher readme.md
Au niveau de Git Bash, Création du dossier " pojet-php " et le fichier " index.php " en tapant ces commandes : " mkdir projet-php " ---- " cd projet-php " ---- " touch index.php "
Saisie du code " <?php   ..........              ?> " dans index.php
Initialisation d'un nouveau dépot avec " git init "
Ajout du fichier index.php avec " git add " et faire un commit " git commit -m "First commit" "
Création des 2 branches (develop et prod) et s'y positionner " git checkout -b develop " ---- " git checkout -b prod "
Ajout du repository Github comme remote : "   git remote add origin https://github.com/MLFALL/projet-php.git  " et pousser la branche develop sur GitHub " git push -u origin develop "
Création une nouvelle branche preprod à partir de develop. D'abord se placer sur develop et creer la nouvelle branche " git checkout develop
 " ---- " git checkout -b preprod  "
 Changement du texte dans indeex.php par "Hello, M. LO! Comment vous allez? "  et faire un  ajout et un commit dans la branche prepod avec " git add index.php " ---  "  git commit -m "Second commit"  "
 Pousser les modifications dans la branche preprod avec " git push -u origin preprod "
 Fusion de develop avec prepod: d'abord basculement dans develop et fusion avec les commandes " git checkout develop " --- " git merge preprod "
 Faire un commit et pousser les modifications sur GitHub " git commit -m "Third commit" " ---  " git push -u origin develop "
 Meme chose avec prod et prepod " git checkout prod" --- " git merge preprod " - " git commit -m "fourth commit" " --- " git push -u origin prod "
 Création d'un nouveau dossier nommé "laminefall" pour le clonage  " git clone -b prod https://github.com/MLFALL/projet-php.git "C:\Users\DJIBRIL FALL\Desktop\laminefall"   "
Vérification de la branche active avec " git branch "
Ajout du Collaborateur " issalo1998 " au niveau de GitHub


 
