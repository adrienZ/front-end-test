# Test Leetchi Front

Bonjour brave chevalier jedi.

Bienvenue sur le test technique front-end developer de Leetchi :)

Votre mission sera composer en 3 objectifs


### Objectif #1 (CSS)

Remplacer le contenu du JSON sur la page par un composant de votre création.

le composant devra afficher les données suivantes : 
- name
- height
- gender
- created (date) au format `DD/MM/YYYY`
- l'image: https://upload.wikimedia.org/wikipedia/commons/thumb/6/6c/Star_Wars_Logo.svg/2560px-Star_Wars_Logo.svg.png au **format carré**.
- un lien redirigant vers la proriété `url`

exemple de design attendu: ![](https://raw.githubusercontent.com/Leetchi-Front-End/front-end-test/master/wiki/card-example.png)

### Objectif #2 (API CALL)

à l'aide de l'api [swapi.dev](https://swapi.dev/), utiliser l'input `#search` afin de créer un champ de recherche affichant une liste de personnages, ou un message "Aucun résultat trouvé pour "XXX" (XXX étant la valeur de la recherche). L'utilisateur doit être capable d'utiliser la touche **enter** déclencher une recherche.

La liste de résultats doit s'afficher, chaque item doit être en rendu avec le composant que vous avez créer pendant l'objectif 1


### Obectif 3 (JS/TS - PAGINATION)

Certaines recherches ont un grande nombre de résulats qui nécessite d'implémenter une pagination.
exemple de query: `"a"`

Si une recherche contient plus de 10 items, affichier un bouton "Afficher plus" après votre liste d'items. Au click de bouton afficher la prochaine liste d'élements avec le composant que vous créer pendant l'objectif 1.
