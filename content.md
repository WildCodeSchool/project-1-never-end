# Project 1 never ends!

## Pimp ton projet 1  

#### Introduction

Tu as réalisé en équipe ton plus beau projet web lors de ta deuxième semaine à la Wild Code School.
À présent, je te propose de dynamiser ton projet en utilisant les nouvelles notions que tu vas apprendre pendant les semaines à venir.


#### Installation

Lorsque tu as conçu le projet 1, tu faisais partie d'une équipe de contributeurs sur le repository github.

Aujourd'hui, chacun travaillera individuellement sur le projet. 

Tu vas donc devoir avoir ton propre repository sur lequel tu mettras tes propres modifications. 

* Rends toi sur github et créé un nouveau repository (n'ajoute pas de Readme)
* En local, rends toi sur ton projet 1 et modifie l'origin en mettant l'adresse vers le repository que tu viens de créer.

```bash
# Rends toi dans le dossier où se trouve actuellement ton projet 1 
# et vérifie que tu es bien à jour avec le repository distant 
git status
git pull
# puis tape cette commande en indiquant la nouvelle adresse de ton repository :
git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
# Vérifie avec cette commande que tu es bien relié au nouveau repository :
git remote -v
```

C'est bon ! maintenant, lorsque tu push/pull/fetch, ton environnement local est bien relié à ton environnement distant personnel. 



#### Challenges

Dynamise ton site avec ce que tu sais maintenant faire !

Voici une liste de challenges. Réalise ceux qui t'inspirent. Invente de nouveaux challenges.

* **Factorise ton code** : Découpe ton code en plusieurs fichiers (par exemple `footer`, `navbar`, `header`) et utilise une fonction php pour les afficher. Si tu as un site multipage, cela va considérablement raccourcir ton code ([DRY](https://fr.wikipedia.org/wiki/Ne_vous_r%C3%A9p%C3%A9tez_pas "Don't Reapeat Yourself")).
* **Réveille ton formulaire** : Récupère les informations saisies sur ton formulaire et utilise les ! Tu peux par exemple afficher sur une page suivante les éléments saisis, mis en forme dans une liste.
* **Vérifie les données** : En php, réalise des vérifications simple des saisies de ton utilisateur. Tu peux par exemple vérifier si le champ saisi par l'utilisateur n'est pas vide.
* **Boucle tes items** : Si tu as une liste d'item sur ton projet (par exemple la liste des parfums de glace sur ton projet de glacier), créé plutôt un tableau en php contenant toutes les données de ta liste et affiche les avec une boucle.
* **BONUS Persiste les données** : Enregistre dans un fichier texte nommé avec la date du jour les données entrées via le formulaire.
* **BONUS Menu dynamique** : Si ton projet est multipage, dans ta navbar utilise du PHP pour modifier l'apparence de l'onglet actif (à l'aide de class CSS)
* **BONUS Menu dynamique** : Si ton projet est une [SPA](https://fr.wikipedia.org/wiki/Application_web_monopage "Single Page Application"), dans ta navbar utilise du JS pour modifier l'apparence de l'onglet cliqué (à l'aide de class CSS)
* **BONUS Créé ton propre challenge** : Va encore plus loin en imaginant de nouvelles fonctionnalités ! À partir de fonctions natives ? ou bien en utilisant du JS ? 

