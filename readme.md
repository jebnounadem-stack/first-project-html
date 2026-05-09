//inisialize git repository
git init
// add files to git reository
git add .
// check status of git repository
git status
//commit files to git repository
git commit -m "first commit"
1/Créer un dossier appelé learn_git.
//command : mkdir learn_git
2/Cd (changer de répertoire) dans le dossier learn_git.
//command : cd learn_git/
3/Créer un fichier appelé third.txt.
//command : touch third.txt
4/Initialiser un dépôt git vide.
//command : git init
5/Ajouter third.txt à la staging area.
//command : git add third.txt
6/Commiter avec le message "adding third.txt".
//command : git commit -m "adding third.txt"
7/Vérifiez votre validation avec git log.
//command : git log
8/Créez un autre fichier appelé fourth.txt.
//command : touch fourth.txt
9/Ajoutez fourth.txt à la staging area.
//command : git add fourth.txt
10/Vérifiez avec le message "adding fourth.txt"
//command : git commit -m "adding fourth.txt"
11/Enlevez le fichier third.txt.
//command : git rm third.txt
12/Ajoutez cette modification à la staging area. En utilisant la commande "git add ."
//command : git add .
13/Commiter avec le message "removing third.txt".
//command : git commit -m "removing therd.txt"
14/Vérifiez vos commits en utilisant git log.
//command : git log
15/Changez vos paramètres globaux pour core.pager=cat - vous pouvez en savoir plus ici.
//command : git config --global core.pager cat
16/Écrivez la commande appropriée pour lister toutes les configurations globales pour git sur votre machine.
//command : git config --global --list
17/Vous pouvez taper git config --global pour savoir comment faire.
//command :