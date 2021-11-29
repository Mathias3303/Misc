# Avant propos 
Quelques suggestions pour faciliter le travail collaboratif et les gestions des changements

# Utiliser un outil de Gestion de versions : Git
Liens
* https://fr.wikipedia.org/wiki/Gestion_de_versions
* https://fr.wikipedia.org/wiki/Git
* Git :  https://git-scm.com/
* GitHub : https://github.com/

Principes : 
* Git is the version control system 
* Github is where you store your code and collaborate with the others 
* GitHub Desktop helps you work with GitHub locally 

## Préparation
Tous
* Créer un compte sur GitHub
* Se partager les identifiants (pas les mots de passe)
* Créer ou choisir un dépot pour tester - Ex : Mathias3303/Misc
* Créer ou choisir un dépot pour travailler - Ex : Mathias3303/ProjetInfo

Le collaborateur qui va héberger le dépôt (Mathias3303?)
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
* Cloner le dépot localement pour créer une copie de travail
** Avec Git, en ligne de commande  ``git clone https://github.com/Mathias3303/Misc.git C:\users\jerome\Deskop\MesDepots\Misc
** Avec Git, avec Git GUI
** Avec GitHubDekstop

Il doit y avoir un dossier avec 
* les fichiers du dépot 
* un dossier .git (fichiers de gestion de git)

## Utilisation
Faire des tests pour vérifier le principe sur un depot de test
* Modifier, committer, synchroniser ...
* Attention aux conflits
* Renommer VIA git

# Prochaine étape : Utiliser un IDE avec Version Control System intégré : VS Code
