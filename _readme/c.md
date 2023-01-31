# Semaine 02 - Exercice 02 - Introduction aux classes

## `ÉTAPE 3` - Action sur le bouton

### Voici ce qu'on cherche à faire avec cette étape:

Nous allons maintenant faire en sorte qu'une image se créé chaque fois qu'on click sur le bouton de la page.

Le bouton de la page n'ayant pas de lien avec la classe `Image`, nous allons faire l'événement du click dans notre classe `Main`. Nous allons faire en sorte que l'action d'ajouter une image (new) se fasse lorsqu'on click sur le bouton.

<br>

1. Supprimer `l'instanciation de Image` que vous avez fait à l'étape précedente.
2. Dans la classe `Main` :
   - Créer une méthode `addImage`
     - Créer une instance de la classe `Image`
   - Dans la méthode `init` :
     - Créer une variable `button` qui sélectionne le bouton
     - Ajouter un `événement click` sur votre button qui appelle la méthode `addImage`
       - Si vous avez une erreur dans votre console, n'oubliez pas l'exception pour ajouter un évènement pour qu'il conserve son contexte

Vous devriez maintenant avoir une image qui s'ajoute lorsque vous cliquez sur le bouton.

`Il me semble que ça serait plus intéressant que l'image soit aléatoire`. _On est tanné de voir JayCobb_.

<br><br><hr>

[Passer à l'étape suivante ▶](d.md)

<hr>

[◀ Retourner à l'étape précédente](b.md)
