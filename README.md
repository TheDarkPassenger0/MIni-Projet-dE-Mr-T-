Explication du code :
HTML :

Le formulaire contient trois champs : un pour le titre (input), un pour l'adresse (input), et un pour la description (textarea). Un bouton permet de soumettre le formulaire.
Un conteneur div avec l'ID articlesContainer est utilisé pour afficher les articles créés.
CSS :

Le style est simple et léger, avec une mise en forme de base pour rendre le formulaire agréable à utiliser et pour afficher les articles de manière lisible.
Le bouton change de couleur au survol pour améliorer l'interactivité.
JavaScript :

Lorsqu'un utilisateur soumet le formulaire, le code intercepte l'événement de soumission (event.preventDefault()), récupère les valeurs des champs, puis crée un nouvel élément div pour l'article.
Chaque article est ajouté dynamiquement au conteneur des articles sur la page.
Le formulaire est réinitialisé après l'ajout de l'article.
Fonctionnement :
L'utilisateur remplit le formulaire (titre, adresse, description).
Lorsqu'il clique sur le bouton "Ajouter l'article", un nouvel article est ajouté à la page sous forme de div avec les informations qu'il a saisies.
Chaque nouvel article est affiché sous les précédents.
Améliorations possibles :
Ajouter une fonctionnalité de suppression des articles.
Permettre de modifier un article après sa création.
Ajouter une base de données pour persister les articles même après un rafraîchissement de la page (via un backend en PHP, Node.js, etc.).

YOU CAN USE THE CODE HERE ---> https://www.w3schools.com/js/tryit.asp?filename=tryjs_myfirst
