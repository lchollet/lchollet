+++
title = 'CMS Headless: le guide complet'
date = 2024-01-04T09:37:24+01:00
+++
## Introduction

Aujourd'hui, j'ai trouvé un article intéressant sur les headless CMS (Content Management System). L'article, *"CMS Headless: le guide complet"* , rédigé par StoryBlock, une entreprise spécialisée dans les solutions CMS headless, présente de manière approfondie les avantages et les inconvénients de ce type d'outils. J'avais déjà brièvement aperçu ce sujet lors de mon cours de marketing digital.
Vous pouvez consulter l'article [ici](https://www.storyblok.com/fr/tp/headless-cms-explique).

## Headless ? CMS ? Définitions
L'article commence par définir ce qu'est un headless CMS. *"Un CMS headless est un système de gestion de contenu qui n'utilise que le backend et qui est conçu dès le départ comme un répertoire de contenu."* Le contenu est rendu via des API RESTful. L'affichage (la tête) est séparé des données (le corps) et le tout est lié via des APIs. Voici un schéma tiré de l'article.
![Alt text](/posts/hCMS.webp)
*On voit au centre les données distribuées par l'API*

## Différences avec un CMS ordinaire ? Pourquoi besoin d'autre chose ?
Je vais encore une fois prendre un des schémas de l'article qui résume bien le fonctionnement d'un CMS classique.
![Alt text](/posts/CMS.webp)
L'affichage et les données sont pris en charge par le même "bloc", l'affichage front-end est pris en charge par le CMS également. La demande à laquelle répond le CMS headless est lorsque l'on souhaite communiquer sur plusieurs canaux, tels qu'une application mobile, un site web, une interface VR, peu importe. Dans les cas où l'on souhaite communiquer sur plus d'un canal, le CMS traditionnel ne sera pas capable.

## Avantages d'un Headless CMS
Plusieurs avantages sont mis en avant :
1. **Capacité omnicanal** : Comme cité précédemment, en headless, on est capable de communiquer facilement depuis plusieurs canaux de communication de manière unifiée. L'interface admin permet de modifier des données et de les publier simultanément sur tous les canaux.
2. **Plus de support pour les développeurs** : Grâce aux API, on peut utiliser n'importe quel front-end, ce qui signifie que si on a des besoins spécifiques au niveau technologique, cela ne sera pas un problème.
3. **Plus de sécurité pour les opérations** : Les API mettent de la distance entre les interfaces utilisateurs et le backend où se trouvent les données sensibles. Cela rend le système plus résistant aux attaques.
4. **À l'épreuve du temps** : Le point le plus important selon moi est que la solution headless est facile à maintenir. Les API peuvent facilement être redirigées vers un autre front-end lorsque vient le moment de changer de design ou de technologie, ou lorsque celui-ci devient obsolète.

## Les usages adaptés
L'article se termine ensuite avec une FAQ, faisant remonter quelques points intéressants. Il explique que le headless n'est pas fait pour tout le monde. Toutes les entreprises n'ont pas besoin d'autant de flexibilité dans le choix des technologies, de sécurité des informations et de canaux de communication.
Il liste ensuite le nom de grandes entreprises qui utilisent des headless CMS :
- Tesla
- Adidas
- T-Mobile
- Oatly
- Claro
- Netflix
- Deliveroo

## Conclusion
Pour conclure, je suis content d'en avoir appris plus sur ce sujet. Je suis en train de suivre un cours sur la création d'une API, et faire le lien avec un outil comme les headless CMS est intéressant pour se rendre compte à quel point la segmentation de l'information en plusieurs canaux peut être pratique. Les avantages de communiquer le fond détaché de la forme sont évidents. Je pense qu'à l'avenir, les grandes et moyennes entreprises adopteront de plus en plus ces solutions, car pouvoir unifier sa communication et choisir les technologies utilisées sont des avantages tant pour le personnel de marketing que pour les développeurs. Je pense que connaître mieux les technologies en matière de CMS me sera vraiment utile à l'avenir, car les employeurs risquent de demander de plus en plus aux développeurs de les maîtriser.
