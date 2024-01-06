+++
title = 'Les applications web progressive'
date = 2024-01-03T15:28:32+01:00
+++
## Introduction
Une fois de plus, il s'agit d'un sujet que j'ai pu apercevoir en cours et que j'ai revisité lors de ma veille technologique. Il s'agit des PWA, Progressive Web Apps, des applications qui sont, en essence, des sites web.

## L'article de web.dev
Les détails concernant ce qu'est une PWA sont expliqués en détail. Fondamentalement, il s'agit d'un site web que l'utilisateur peut "installer" comme une application à partir de son navigateur, s'il le souhaite. Elle sera donc capable de fonctionner sans connexion internet (sauf si les actions effectuées par l'utilisateur nécessitent une connexion), de stocker des informations en local et d'accéder facilement aux fonctionnalités natives de l'appareil sur lequel elle est installée, telles que l'accéléromètre sur un smartphone.

[lien de l'article](https://web.dev/articles/what-are-pwas?hl=fr)

Il est également expliqué la différence entre les applications natives et les applications web purement en ligne. Deux axes sont présentés, à savoir la capacité (capability) et la portée (reach). On comprend donc que les applications natives sont plus capables, tandis que les applications web touchent un plus grand nombre de personnes.

![Shéma qui montre les PWA](https://lchollet.github.io/lchollet/images/pwa.svg)
Les PWA se situent donc quelque part entre les deux.

### Les trois fonctionnalités
Dans cet article, les PWA mettent en avant les trois fonctionnalités suivantes :
- **Puissance** : Les applications web sont devenues puissantes récemment, et ce qui n'était pas réalisable il y a 10 ans est maintenant largement possible sur le web. Des applications de chat vidéo, la géolocalisation, les notifications push, tout est possible.
- **Fiabilité** : Peu importe le réseau, l'application doit et va fonctionner. Si la connexion est lente, les éléments principaux seront en mémoire, les menus seront déjà chargés, etc. Cela rend l'expérience utilisateur moins frustrante. La rétention d'utilisateurs s'améliore, selon eux, avec une augmentation de la probabilité de 123 % si l'utilisateur attend 1 seconde au lieu de 10 !
- **Installation** : Lorsqu'une PWA est installée, elle a sa propre fenêtre autonome, ce qui permet à l'utilisateur d'utiliser l'application sans le risque de quitter accidentellement son navigateur et donc l'application en même temps. Les raccourcis clavier ne sont plus réservés à la navigation standard et peuvent donc être réattribués.

## Conclusion
Les PWA sont, à mes yeux, un élément essentiel pour l'avenir du développement web et le développement d'applications en général. Les possibilités de créer une application avec un langage que je connais déjà, sans avoir à apprendre un langage spécifique à la plateforme ciblée, sont incroyables. Si un client me demande un jour de créer un outil interne pour son inventaire, nécessitant des fonctionnalités spécifiques et devant être compatible avec plusieurs types d'appareils, une PWA serait plus qu'idéale si le budget est limité. L'application n'aurait besoin d'être développée qu'une seule fois au lieu de deux, voire trois fois !






