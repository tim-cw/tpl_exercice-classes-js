# Semaine 02 - Exercice 02 - Introduction aux classes

## `ÉTAPE 4` - Une image aléatoire

### Voici ce qu'on cherche à faire avec cette étape:

Nous allons faire en sorte que ce soit une image aléatoire qui soit choisie lors de la création de la nouvelle image.

Il y a beaucoup de détails techniques à expliquer :

- **En premier**, nous allons créer une variable qui va contenir le nombre d'image total. Nous la mettrons dans le `Main` parce qu'encore une fois, elle n'a aucun lien avec la classe Image (qui sert seulement a créer une image).
- **Ensuite**, nous allons choisir une valeur aléatoire et créer un chemin (path) vers l'image. Pour ensuite, la passer en paramètre lors de l'instanciation de notre image.

### Dans la classe `Main`

- Dans le `constructeur`, créer une variable global pour le nombre total d'image `totalImage` et lui donner la valeur `51`
- Dans la méthode `addImage()` :
  - Créer une variable `imageId`
    - Faites en sorte d'avoir une valeur random entre `0` et le nombre total d'image (`totalImage`)
  - Créer une variable `path` :
    - Avec un template string créer une chaine de caractère qui donne quelque chose comme ça `assets/images/imageId.jpg` (imageId devrait être la valeur de la variable imageId)
- Il faut maintenant passer la variable `path` en paramètre à notre instance Image
  - Passer le paramètre lors de l'instanciation de votre nouvelle image
    - `new Image(path)`

### Dans la classe `Image`
Afin d'avoir accès au paramètre path qu'on passe avec `new Image(path)`, nous devons le récupérer.

  - Ajouter dans le constructeur de la classe `Image` un paramètre `path`
    - `constructor(path)`
  - Remplacer la source de l'image `img.src` par le contenu du paramètre `path`. 

<br><br><hr>

[Passer à l'étape suivante ▶](e.md)

<hr>

[◀ Retourner à l'étape précédente](c.md)
