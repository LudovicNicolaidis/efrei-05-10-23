# cours Git EFREI
## GP01
### 05/10/23

ceci est notre permier fichier readme

## Points vus le 05/10/23
nous avons vu les commandes suivantes :
1. pwd : permet de savoir ou on se trouve
2. ls : (option -a, -l, -A) perdmet d'afficher la liste des dossiers
3. cd
4. mkdir
5. rmdir : permet de surprimer un dossier 
6. rm : permet de suprimmer un fichier / dossier 
7. cat = afficher le contenu d'un fichier 

pour commmande git suivantes : 
git --version
git init 
git config 
git status
git add [file]
git commit -m "message"
git commit --amend "message" = moddifer le message 
git restore --staged [file] = retire un ou plusieur fichier de l'hitorique de git 
git rm --cached [file] = retire un ou plusieur fichier 
git reset [-- soft, --hard] commitnuber = revenir à l'etat precend 
git log [oneline]
git branch -m nonacutal newname
git restore filename = annuler les modfis apporter à un fichier 
git diff [<commit-number>]
git ls-files