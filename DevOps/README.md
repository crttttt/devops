# Projet Git

## Description du Projet

Manipuler git & github, utiliser les branches, les commits et les merges

## Installation de git

https://gitforwindows.org/

Puis git --version

---

Documentations Utilisées : 

* https://git-scm.com/docs
* https://docs.github.com/fr

---

## Commande Utilisée

---

|-------------------------------|-----------------------------------------------|
|Commande : 			| Rôle de la commande : 			|
|-------------------------------|------------------------------------------------
|`git clone` 			| # Cloner un repository			|
|`git checkout -b develop` 	| # Créer une nouvelle branche			|
|`git add .` 			| # Ajouter tous les fichiers			|
|`git commit -m "message"` 	| # Sauvegarder les modifications en local	|
|`git push` 			| # Envoyer les modifications sur github	|
|`git pull` 			| # Récupérer les modifications			|
|`git merge develop` 		| # Fusionner une branche			|
|`git mv` 			| # Renommer un fichier				|
|`git rm` 			| # Supprimer un fichier			|
|--------------------------------------------------------------------------------
---

## Étapes réalisées

### 1. Création du repository

* Création d’un repo GitHub
* Clonage en local

### 2. Création de la branche develop

```
git checkout -b develop

```

### 3. Ajout des fichiers

* file1
* file2
* file3

### 4. Premier commit et push

```
git add .
git commit -m "Ajout des fichiers"
git push origin develop

```

### 5. Merge vers main

```
git checkout main
git merge develop

```

### 6. Modifications

* Création du README
* Renommage de file1 → file1.txt
* Suppression de file3

### 7. Commit final

```
git add .
git commit -m "Modifications finales"
git push

```

### 8. Merge final

```
git checkout main
git merge develop

```

---

## Workflow Git (merci gpt)

```
main -----------o-----------o
                \
develop ---------o-----o----o

```
