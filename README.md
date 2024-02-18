# COURS SASS - Mise en pratique P5 - Combinez BEM & Sass

## Instructions :

1. Activez **Watch Sass**
2. Remplacez les sélecteurs **navbar__link** par **&__link** dans le fichier **style.scss**
3. Enregistrez le fichier **style.scss**
4. Vérifiez le fichier **style.css** afin d'obtenir le code ci-dessous

```
.navbar {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}
.navbar__link {
  margin-left: 30px;
  color: #242424;
  text-decoration: none;
}
.navbar__link--purple {
  color: #a5b4fc;
}
```