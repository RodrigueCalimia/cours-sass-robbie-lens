# COURS SASS - Mise en pratique P9 - Utilisez une fonction avec une mixin

## Instructions :

1. Dans les fichiers index.html, a-propos.html et portfolio.html, ajoutez la classe section__title--shadow à la balise h1
2. Dans le fichier style.scss,</br>
    2.1 Ajoutez une variable $title-shadow-percent avec une valeur à 35%</br>
    2.2 Ajoutez la mixin title-shadow qui applique un text-shadow de 0.50rem associée à la fonction darken qui récupère les variables $color-primary et $title-shadow-percent</br>
    2.3 Ajoutez le sélecteur section__title--shadow qui fait appel à la mixin title-shadow</br>
4. Enregistrez les modifications