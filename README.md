# GUI1

Devoirs à rendre: GUI1 (https://www.notion.so/GUI1-67b42b7529d54d6b8550f3bfe121053f?pvs=21)

# Projet gui :

Idée de conception : 
Site d’office du tourisme axé sur les randonée/trek. Reservation de guide. Formulaire de contact. Carousel des images d’ancien marcheurs. Idée de balade pour l’hiver aussi.

Concevoir en pensant que la DB contiendrai : 
- Reservation
- Randonées
- Guides
- Dates disponible 
- etc…

### Les inspirations :

Nestlé : Le site est bien responsive, permet de naviguer simplement grace au menu et contient des bonnes polices

CFF: les couleur du site sont niquel et représente effectivement les couleurs de notre drapeau

Fontawesome : pour les icônes évidement 

Boostrap 5 : simple et éfficace

### Les + :

Contient : 

- Navbar (burger), mode sombre
- Une bannière de type carousel
- Des cards avec les différente pages du site
- Une sélection de produit en carousel (icon)
- Un formulaire pour proposer un changement
- Un footer contenant des liens verse les réseau sociaux et des information complémentaire

## Conception :

### Police :

Martian Mono : [https://fonts.google.com/specimen/Martian+Mono](https://fonts.google.com/specimen/Martian+Mono)

![Capture d’écran 2023-09-28 à 10.39.36.png](GUI1%20ad3001472f3947d98c234f21b6220091/Capture_decran_2023-09-28_a_10.39.36.png)

Latto : [https://fonts.google.com/specimen/Lato?query=lato](https://fonts.google.com/specimen/Lato?query=lato)

![Untitled](GUI1%20ad3001472f3947d98c234f21b6220091/Untitled.png)

### Couleur utilisé :

![Untitled](GUI1%20ad3001472f3947d98c234f21b6220091/Untitled%201.png)

## Les idées prisent ailleurs :

Nestlé : 

Le formulaire contient les champs nécessaire a une recherche de trek ainsi que les informations de région souhaité. Guide serait remplacer part “Guide” dans le cas ou les marcheurs connaissent ou on une préférence sur la personne.

La bannière et footer pour les cards et formulaire:

[https://www.figma.com/file/2FSj251ZflLkFNNggzIFC9/Modern-Id-Card-Design-(Community)?type=design&node-id=3-114&mode=design&t=PwnPt0L6spUbulXj-0](https://www.figma.com/file/2FSj251ZflLkFNNggzIFC9/Modern-Id-Card-Design-(Community)?type=design&node-id=3-114&mode=design&t=PwnPt0L6spUbulXj-0)

Le formulaire : 

SRC : [https://www.nestle.ch/fr](https://www.nestle.ch/fr)
Les formulaire de boostrap permettent aussi un bon management de l’espace entre les éléments et une facilité de mise en place

![Capture d’écran 2023-09-28 à 10.42.03.png](GUI1%20ad3001472f3947d98c234f21b6220091/Capture_decran_2023-09-28_a_10.42.03.png)

Liste de trek/rando proposé en card avec un jolie images du paysage rancontré : 

SRC : [https://www.nestle.ch/fr](https://www.nestle.ch/fr)

SRC 2 : [https://codepen.io/pascaloliv/pen/LVZaeE](https://codepen.io/pascaloliv/pen/LVZaeE) (carousel vertical → liste des trek ?)

SRC 3 :[https://codepen.io/yudizsolutions/pen/wvzrPoj](https://codepen.io/yudizsolutions/pen/wvzrPoj) 

SRC 4: [https://swiperjs.com/](https://swiperjs.com/) →→→→ la source choisie

Le carousel permet un réduction du texte lors du mouvement. Il est ergonomique : permet un scroll fluide et un défilement qui s’arrete pour afficher l’entier de la card lors de la lecture

![Capture d’écran 2023-09-28 à 11.12.37.png](GUI1%20ad3001472f3947d98c234f21b6220091/Capture_decran_2023-09-28_a_11.12.37.png)

Présentation des guides : simple et précis. Une courte présentation remplacera le titre actuel sur la card, les card de bootsrap sont plus facile d’utilisation, à voir si je fait Vanilla ou Bootsrap

Boostrap pour les card —> choix
SRC : [https://uiverse.io/abrahamcalsin/grumpy-ape-40](https://uiverse.io/abrahamcalsin/grumpy-ape-40)

Liste des guides officielles : [https://sbv-asgm.ch/fr/qui-sommes-nous/](https://sbv-asgm.ch/fr/qui-sommes-nous/)

![Capture d’écran 2023-09-28 à 10.48.58.png](GUI1%20ad3001472f3947d98c234f21b6220091/Capture_decran_2023-09-28_a_10.48.58.png)

Un potentiel carousel avec la liste des partenaire sur site ? Le carousel n’utilise que HTML/CSS ce qui justifie sont utilisation

SRC : 

[https://codepen.io/studiojvla/pen/qVbQqW](https://codepen.io/studiojvla/pen/qVbQqW)

![Capture d’écran 2023-09-28 à 10.52.12.png](GUI1%20ad3001472f3947d98c234f21b6220091/Capture_decran_2023-09-28_a_10.52.12.png)


## Fonctionnement du projet : 

CD dist/

npm run dev

ouvrir le serveur et changez manuellement le lien des pages
