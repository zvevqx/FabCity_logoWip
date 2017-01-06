# FabCity_logoWip
graphic research for fab city logo 


#getting started :
- githud 101  : https://guides.github.com/activities/hello-world/ 
                http://rogerdudler.github.io/git-guide/
                
- edit file   : inkscape (win / osx / linux) https://inkscape.org/en/


# demarer avec git 
installer ` git ` 
##### linux :
`sudo apt-get update`
`sudo apt-get install git`
##### windows :
https://git-scm.com/download/win
##### osx :
https://git-scm.com/download/mac

on cree un compte sur `github`
`https://github.com/`
___

### 1. on *Fork* le repo
* on click sur FORK ![alt text](https://github.com/zvevqx/FabCity_logoWip/blob/master/img_readme/fork.png?raw=true "fork btn")en haut a droite pour cree une copie personnel du repo 
### 2. avant tout recuperer le repo en local  (cloner les fichiers sur son ordinateur)
1. via le terminal naviger jusqu'a la destination souhaite 
`$ cd ~/dossier/de/desitnation`
2. recuperer les fichier depuis git avec `git clone`
`$git clone ADRESSE_DU_REPO_GIT`
cela va cree un dossier et telecharger les fichiers 

### 3. on travail sur les fichiers en local 
### 4. on *push* les changements sur le serveur git 
1. on verifie le statut des fichiers 
    `$cd /folder/du/repos/local` 
    `$git status`
2. on ajoute les fichiers modifie ou nouveau 
    `$ git add le_nom_du_fichier.ext`
    >tips:
    pour tout ajouter d'un coup `git add * `
    pour ajouter tout les fichiers d'une meme extension `git add *.extention` 
3. on *commit* les changements (on cree une version avec les nouveaux changements ) 
    `git commit -m "un message descriptif des changements"`
4. enfin on met a jour les fichiers sur **github**
    `git push origin master`
    >tips:
    `origin` correspond au server github (c'est une convention sur github)
    `master` a la branche a mettre a jour
5. profit...


### modifier le repo original 
pour soumettre les modifications sur le repo original il faut faire un *pull request* 
pour cela on clique depuis votre repo sur **new pull request** ![alt text](https://github.com/zvevqx/FabCity_logoWip/blob/master/img_readme/pullrequest.png?raw=true "pullrequest btn") 

## DONE 
**bravo** vous utilisez `git` et `github`









# Git Cheat Sheet
https://gist.github.com/akras14/3d242d80af8388ebca60

