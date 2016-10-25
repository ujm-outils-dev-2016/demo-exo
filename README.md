# Exercice : Branches/merges

# Préambule
1. Vérifier la configuration de `git` (username, mail, mergetool, etc...)
* Cloner le dépôt (https://github.com/ujm-outils-dev-2016/demo-exo)

# Etape 1 :
1. Se positionner sur la branche `master` et créer une branche `develop`
* Créer une branche `votre_nom` à partir de `develop`
* Modifier `file1.txt`
* Créer un fichier `file4.txt` dans `dir1/` et supprimer `file2.txt`
* Faites vos commits (ajout à l'index + commit)
* **Call 911**

# Etape 2:
1. Revenir sur `develop`
* Modifier `file1.txt`
* Modifier `file2.txt`
* Modifier `file3.txt`
* Faites vos commits (ajout à l'index + commit)
* Afficher l'historique
* **Call 911**

# Etape 3:
1. Merger la branche `votre_nom` sur `develop`
* Gérer les conflits potentiels
* Utiliser votre "mergetool" pour résoudre le conflit
* Commiter le résultat du merge
* Afficher l'historique. L'historique vous parait-il "propre" ?
* **Call 911**

# Etape 4:
1. Annuler le commit de merge (`git revert HEAD`)
* Retourner sur `votre_nom`
* Mettre à jour `votre_nom` par rapport à `develop`
* Aller sur `develop`
* Merger la branche `votre_nom` sur `develop`
* Supprimer la branche `votre_nom`
* **Call 911**
