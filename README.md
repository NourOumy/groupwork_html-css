# groupwork_html-css

## **position : sticky**

La position CSS sticky a deux parties principales, l'élément sticky et le conteneur sticky.
- L'élément sticky.
  
L'élément sticky — est l'élément que nous avons défini avec la propriété position : sticky. L'élément flottera lorsque la position de la fenêtre correspond à la définition de la position, par exemple :
`.header {
    position: sticky;
    top: 0px;
}`
- Le conteneur sticky.
  
Le conteneur sticky — est l'élément HTML qui enveloppe l'élément sticky. Il s'agit de la zone maximale dans laquelle l'objet collant peut flotter.

![Illustration](https://storage.gra.cloud.ovh.net/v1/AUTH_5159edadfde2413fb43128c1fef06fbf/zerofiltre-object-container/sticky%20img.png)

- Exemple :
## **shape-outside**
La propriété shape-outside définit une forme (qui peut ne pas être un rectangle) autour de laquelle le contenu en ligne (texte) évoluera.
Par défaut, le contenu en ligne évolue autour de la boîte de marge de l'élément flottant.
La propriété shape-outside permet de personnaliser ce contour et d'obtenir un texte qui s'écoule autour d'objets plus complexes que des rectangles.

[Pour les détails, Mozilla fait le bail](https://developer.mozilla.org/fr/docs/Web/CSS/shape-outside)

- Exemple :
  
## **filter**
La propriété CSS filter permet d'appliquer des filtres et d'obtenir des effets graphiques de flou, de saturation, etc. Les filtres sont généralement utilisés pour ajuster le rendu d'une image, d'un arrière-plan ou des bordures.
- filter: blur(px)

  Applique un effet flou
  
- filter: brightness
  
  Rend l'image plus claire ou plus sombre en utilisant un coefficient multiplicateur. L'effet est linéaire : 0% créera une image complètement noire, 100% ne modifiera pas l'image et les valeurs supérieures à 100% rendront l'image plus claire.
  
- filter: drop-shadow

  Applique une ombre portée suivant les contours de l'image.
  Tous les filtres appliqués après drop-shadow() sont appliqués à l'ombre portée également.

- filter: opacity

  Applique un niveau de transparence. Un coefficient de 0% rendra l'image complètement transparente tandis qu'un coefficient de 100% laissera l'image inchangée.
  
## **datalist**
