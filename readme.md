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

## Commandes distant :

## Divers :
* **[Ctrl] + [J]** -> Ouvre le terminal de Visual Studio Code