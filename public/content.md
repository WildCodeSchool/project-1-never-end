# Project 1 never ends!

## Pimp ton projet 1  

#### Introduction

Tu as réalisé en équipe ton plus beau projet web lors de ta deuxième semaine à la Wild Code School.
À présent, je te propose de dynamiser ton projet en utilisant les nouvelles notions que tu vas apprendre pendant les semaines à venir.


#### Installation

Lorsque tu as conçu le projet 1, tu faisais partie d'une équipe de contributeurs sur un *repository* Github.

Aujourd'hui, tu vas travailler individuellement sur le projet. 

Tu vas donc créer ton propre *repository* sur lequel tu mettras tes propres modifications. 

* Rends toi sur Github et créé un nouveau *repository* (n'ajoute pas de README)
* En **local**, rends toi dans le répertoire de ton projet 1 et suis les instructions ci-dessous pour modifier l'*origin* du *repository* par celui que tu viens de créer :

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

C'est bon ! maintenant, lorsque tu *push/pull/fetch*, ton environnement local est bien relié à ton environnement distant personnel. 

> Tu vas maintenant dynamiser ton site avec ce que tu sais maintenant faire ! Chaque semaine, une liste de challenge t'es proposé.
  Le but de ce projet 1 est de **mettre en pratique** tout ce que tu vois durant les enseignements
  (quêtes, cours, *livecoding*). 
  
> Mais tu es libre d'inventer tes propres challenges. Ce projet est un **bac à sable**, il ne faut pas que tu aies peur
  d'essayer, de casser pour mieux recommencer. Git est là pour t'éviter de perdre ton travail, pense donc bien à créer des branches
  pour chaque fonctionnalité tout en conservant un *master* fonctionnel ;-) 


#### Semaine 1

* **Factorise ton code** : Découpe ton code en plusieurs fichiers 
(par exemple `footer`, `navbar`, `header`) et utilise la fonction `include` pour les afficher. 
Si tu as un site multipage, cela va considérablement raccourcir ton code ([DRY](https://fr.wikipedia.org/wiki/Ne_vous_r%C3%A9p%C3%A9tez_pas "Don't Reapeat Yourself")).
* **Boucle tes items** : Si tu as une liste d'items sur ton projet (par exemple la liste des parfums de glace sur ton projet de glacier),
 créé un tableau en PHP contenant toutes les données de ta liste et affiche les avec une boucle. 
 
> C'est le moment de mélanger PHP et HTML ! Pour cela, n'écris pas de balises HTML dans les `echo`, 
 mais prends soin d'ouvrir et fermer les balises PHP à chaque fois que nécessaire. Tu intègres du dynamisme (le PHP) au sein
de ton HTML et non le contraire !
   

#### Semaine 2

* **Améliore ton formulaire** : Fais en sorte d'utiliser les bon types sur les champs de formulaire. S'il n'y sont pas déjà, ajoute des `labels` et `placeholder`.
Enfin, ajoute les vérifications nécessaires (`required` par ex). 

* **Réveille ton formulaire** : Récupère les informations saisies sur ton formulaire et utilise les ! 
Tu peux, par exemple, afficher sur une page suivante les éléments saisis, mis en forme dans une liste. 
Pense à utiliser une [fonction d'échappement du HTML](https://www.php.net/manual/fr/function.htmlentities.php)

* **Vérifie les données** : En PHP, réalise des vérifications simples des saisies de ton utilisateur. Tu peux par exemple vérifier si le champ saisi par l'utilisateur n'est pas vide.

* **BONUS Menu dynamique** : Si ton projet est multipage, dans ta navbar utilise du PHP pour modifier l'apparence de l'onglet actif (à l'aide de class CSS)

* **BONUS Menu dynamique** : Si ton projet est une [SPA](https://fr.wikipedia.org/wiki/Application_web_monopage "Single Page Application"), dans ta navbar utilise du JS pour modifier l'apparence de l'onglet cliqué (à l'aide de class CSS)

> Pour rappel, la sécurisation des formulaires est **primordiale**. Si la vérification côté client est utile, elle n'est pas suffisante.
 et il faut toujours privilégier la vérification en PHP (côté serveur). 


#### Semaine 3

* **Base de données** : Créé une base de données et au moins une table (mais tu peux en ajouter d'autres en fonction de ton projet et du temps disponible). 
Ensuite, en utilisant PDO, connecte toi à cette base de données. Remplis cette table avec des infos (l'idée est de reprendre les données que tu avais saisie "en dur" dans un tableau PHP lors de la semaine 1)
* **Récupère les informations** : Ajoute une requête dans ton PHP, pour récupérer les informations de ta table.
 Les résultats de ta requêtes vont être récupérées dans un tableau qui va remplacer le tableau de données préexistant.
 Tu ne devrais donc pas (ou très peu) modifier le reste de ton code, car tu continues de boucler sur un tableau PHP pour afficher les données sur ton site. 
 
* **Persiste les données** : Modifie ton formulaire (ou créé en un nouveau en fonction de ton projet). Les données de ce formulaire doivent être validées côté serveur, puis récupérées pour être insérée dans la table en base de données
(requête INSERT).
 
* **BONUS CRUD** : Pour le moment, tu récupères et insères des données, continue à améliorer ton site pour pouvoir mettre à jour et supprimer des données (réalisation d'un CRUD complet) ! À partir de fonctions natives ? ou bien en utilisant du JS ? 

* **BONUS Créé ton propre challenge** : Va encore plus loin en imaginant de nouvelles fonctionnalités ! À partir de fonctions natives ? ou bien en utilisant du JS ? 

