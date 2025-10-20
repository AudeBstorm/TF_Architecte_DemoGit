# [GIT](https://git-scm.com/)
## Avant de commencer :
* Voir la version git installée sur votre machine :
```
git version
```
* Pour configurer le nom de l'utilisateur de git sur votre machine :
```
git config --global user.name “Beurive Aude”
```
* Pour configurer l'email de l'utilisateur sur la machine
```
git config --global user.email “aude.beurive@bstorm.be”
```
* Initialise le dossier dans lequel la commande est effectuée comme étant un repository git 
```
git init
```
> [!NOTE] 
> Un dossier caché .git apparait alors dans votre dossier. C'est ce dossier qui contient toutes les informations de votre repository local (ex: le lien vers le repository distant, vos différents commit, etc)

## Commandes de base (local) :
* Permet de savoir quel est le statut de votre repository git
```
git status
```
> [!NOTE]
> Cette commande vous affichera les fichiers qui ne sont pas suivis (untracked), les fichiers suivis mais qui ne sont pas encore commit,...

* Permet d'ajouter les fichiers qui ont été modifiés/créés/supprimés dans la zone de staging
```
git add nomFichier
git add nomDossier
git add . 
```
> [!Note]
> git add . permet de directement ajouter au stating, tous les fichiers changed (modifiés, créés, supprimés)

* Permet de faire une version à l'instant T avec tous les fichiers actuellement dans la zone de staging
```
git commit -m "description de ce que vous commitez"
```
> [!Note]
> Vos messages de commit doivent être clairs, expliquer ce que vous faites (ajout d'une fonctionnalité, réglage d'un bug, etc) et on essaie au max de les faire en anglais

* Permet d'afficher un résumé de tous les commits
```
git log 
git log --graph (pour afficher un graphique avec les différentes banches)
git log --oneline (pour afficher les commits sur une seul ligne)
```

## Commandes distant :

## Divers :
* **[Ctrl] + [J]** -> Ouvre le terminal de Visual Studio Code