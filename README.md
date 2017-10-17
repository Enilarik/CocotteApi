# CocotteApi

### Visiteur
Note : Dans la description de chacune des pages qui vont suivre, si un ordre doit être choisi sur la façon de trier des données, l'ordre souhaité est un ordre chronologie inversé (du + récent au + vieux)

* Page de présentation :
Doit pouvoir accéder à une première page appelée "page de présentation", la forme est à décider mais l'idée est une première page présentant succinctement Cocotte Min'UTT et contenant, entre autres, une navbar permettant de naviguer entre plusieurs pages :
  - Actualités
  - Recettes
  - Contact
  - Photos & Vidéos
  - Partenaires
  - Nos événements

`Cette navbar devra être conservée sur les autres pages`

* Actualités :
"Blocs" contenant chacun un événement, sa description (+ d'autres propriétés (date-heure...)), il faut réfléchir à comment séparer les événements "à venir" des événements "déjà passés".
* Recettes :
Doit permettre l'affichage des recettes déjà effectuées par Cocotte Min'UTT -> "espèce de Marmiton like" avec possibilité de rechercher par date, événement, mot-clé...

`Une recette doit pouvoir être liée à un événement` -> Un lien dans l'événement doit renvoyer à la recette si elle existe

* Contact :
Un formulaire permettant l'envoi de mail à Cocotte Min'UTT.
* Photos & Vidéos :
Galerie de photos avec la possibilité d'afficher des photos plus grandes que d'autres en respectant le format et l'orientation (paysage/portrait) de la photo et éventuellement la possibilité de définir des photos "favories" qui seront mises en avant.
* Partenaires :
Doit afficher l'ensemble des partenaires de Cocotte Min'UTT, la forme est encore à discuter (il y a une idée de "onClick(partenaire) = afficher des informations en plus") ainsi que la possibilité d'accéder à un dossier de partenariat (un bouton "Devenons partenaires" par exemple).
* Nos événements :
Contient les "gros événements" de Cocotte Min'UTT, la présentation qui va avec (+ d'autres propriétés), cf Actualités.

### Membre
* -

### Administrateur
* Concernant le site vitrine, l'Administrateur doit pouvoir :
  - Ajouter, modifier et supprimer :
    - les actualités
    - les recettes
    - les photos & vidéos
    - les partenaires
    - les "gros événements" (nos événements)
  - Gérer les "gros événements" et les actualités
  - Gérer la page de présentation : être en mesure de modifier la photo et le texte
