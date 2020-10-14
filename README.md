
# Tutoriel Git étape par étape

## Créer un repository distant (remote) sur GitHub

- Après s'être inscrit sur Github ([Lien](https://github.com/join?source=login)), se connecter et se rendre sur [la page pour créer un nouveau repository](https://github.com/new)

![Screenshot](images/create_repo_github.png)


## Créer un repository en local

- Aller dans le dossier choisi avec le terminal (sur Linux / Mac OS) ou avec Git Bash (Windows) :

```bash
cd git_step_by_step/ 
```

- Initialiser le repository local : 

```bash
cd git init
```


## Faire un premier commit en local


- Créer un fichier texte "file_1.txt", par exemple en tapant :

```bash
touch file_1.txt
open file_1.txt # le fichier va s'ouvrir, écrire quelque chose et enregistrer
```


- Vérifier ce qu'on a modifié

```bash
git status # vérifier ce qu'on a modifié
```

- Ajouter les modifications faites (c'est dire à Git ce qu'on va sauvegarder dans l'étape d'après). Il faut avoir enregistré à l'étape d'avant ! 

```bash
git status # vérifier ce qu'on a modifié
git add file_1.txt 
```


- Commit (c'est faire une photo de notre dossier en ne photographiant que ce qu'on a ajouté dans l'étape d'avant)

```bash
git commit -m "file_1.txt créé, on a écrit dedans"
```

##