# Notice GIT

1) Installer Git sur son poste : https://github.com/git-for-windows/git/releases/download/v2.43.0.windows.1/Git-2.43.0-64-bit.exe


2) Lancer Git Bash et réalisé la configuration initiale :

git config --global user.name "Votre Nom"

git config --global user.email "votre@email.com"


3) Créer un nouveau repository :

git init

ou en importer un

git clone "url du repository"


4) Ajouter des fichiers :

git add "nom du fichier"

git commit -m "texte de validation des changements"


5) Ajouter des branches :

git branch "nom de la branche"


6) Changer de branche :

git ckeckout "nom de la branche"


7) Fusionner les branches :

git merge "nom de la branche"


8) Récupérer dernière modif du repo

git pull origin "nom de la branche"


9) Récup vos modifs vers le repo

git push origin "nom de la branche"
