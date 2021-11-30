CE DEPOT EST UN DEPOT-TEST POUR COMMITER, MANIPULER, PUSH/PULL DES MODIFICATIONS...


# Avant propos 
Quelques suggestions pour faciliter le travail collaboratif et les gestions des changements

# Utiliser un outil de Gestion de versions : Git
Liens
* https://fr.wikipedia.org/wiki/Gestion_de_versions
* https://fr.wikipedia.org/wiki/Git
* Git :  https://git-scm.com/
* GitHub : https://github.com/

Principes : 
* Git est un logiciel de système de contrôle de versions (de codes)
* Github est le site où est stocké le code 
* GitHub Desktop est une application plus simple d'utilisation que Git

## Préparation
Tous:
* Créer un compte sur GitHub
* Se partager les identifiants (pas les mots de passe)
* Créer ou choisir un dépot pour tester - Ex : Mathias3303/Misc
* Créer ou choisir un dépot pour travailler - Ex : Mathias3303/ProjetInfo

Le collaborateur qui va héberger le dépôt (Mathias3303?) :
* Donner les accès aux projets 
`` GitHub > /Projet/ > Settings > Manage access

Autre collaborateurs : 
* Installer Git 
* Configurer Git (depuis une invite de commande)
```bash
    git config --global user.name "John Doe"
    git config --global user.email johndoe@example.com
```
* Installer GitHub Desktop (optionnel, mais plus intégré à GitHub)

## Cloner un dépot 

Cloner le dépot localement pour créer une copie de travail
* Avec GitHubDekstop
* 
![Capture écran](https://raw.githubusercontent.com/Mathias3303/Misc/main/docs/GitHub%20Desktop-clone.png)
* Avec Git, avec Explorer > Git GUI
* Avec Git, en ligne de commande  
```
git clone https://github.com/Mathias3303/Misc.git C:\users\jerome\Deskop\MesDepots\Misc 
```

Il doit y avoir un dossier avec 
* les fichiers du dépot 
* un dossier .git (fichiers de gestion de git)

## Utilisation
Cycle classique : 
* Modifier les fichiers - avec n'importe quel éditeur 
* Avec GitHub Desktop, 
    * vérifier les modifications
    * committer les modifications (localement) 
    * pousser les commits (vers le serveur)

Et le cycle reprend ...


Faire des tests pour vérifier le principe sur un depot de test
* Modifier, committer, pousser, synchroniser pour récupérer les modifications des collaborateurs ...
* Attention au début quand le fichier est petit, qu'il y a beaucoup de modification (conflits !?) 
* Renommer un fichier : via git (?)

# Etapes suivantes
Utiliser un IDE avec Version Control System intégré : VS Code
