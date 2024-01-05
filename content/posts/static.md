+++
title = 'Les générateur de Sites Statiques'
date = 2024-01-03T15:21:25+01:00
+++
# Introduction

Au cours de mes études à l'HEIG, j'ai fait une découverte significative concernant les Générateurs de Sites Statiques (Static Site Generators ou SSG). Ces outils de création de sites web statiques, qui affichent le même contenu à chaque visiteur, cherchent à combler le fossé entre les CMS tels que WordPress (connus pour leur personnalisation et leur facilité d'utilisation, mais souvent handicapés par une performance réduite due à la prolifération de nombreux plugins) et la création manuelle en HTML, CSS et JS.

## L'article de CloudFlare
![image article](/posts/cloud.png)

Dans le cadre de mes études à l'HEIG, j'effectue une veille technologique centrée sur mon domaine de prédilection : le développement web. L'article que j'ai repéré lors de ma veille est rédigé par CloudFlare, le service de cloud. [Lien vers l'article](https://www.cloudflare.com/learning/performance/static-site-generator/)
J'ai choisi cet article car il explique de manière claire la distinction entre un CMS et un SSG, en mettant en avant les avantages pratiques de l'un par rapport à l'autre.

## CMS ou SSG ?

Selon CloudFlare, il est essentiel de comprendre qu'à l'origine, chaque page web était écrite manuellement. Les CMS ont été introduits pour résoudre ce problème en générant les pages à partir d'une base de données et d'un modèle avant de les servir aux utilisateurs sur demande. En revanche, les SSG se distinguent par leur extrême rapidité, car ils éliminent cette étape, évitant ainsi les requêtes à une base de données et l'application de modèles à chaque demande utilisateur.
Les pages sont générées à l'avance, bien qu'un modèle soit toujours utilisé, ce qui accélère le processus de développement. Une fois générées, les pages ne nécessitent aucun traitement avant d'être envoyées à l'utilisateur, ce qui se traduit par une expérience instantanée !

### Les avantages des SSG

- **Rapidité exceptionnelle** 
- **Possibilité de personnalisation**
- **Faible charge côté serveur** en comparaison avec les CMS traditionnels

### Les inconvénients des SSG

- **Options de modèle limitées**
- **Gestion complexe** pour les non-initiés, la maintenance peut être plus difficile

## Conclusion 

Cet article se révèle très instructif et résume judicieusement les avantages des sites statiques. Le retour à une infrastructure plus légère est à mon sens très gratifiant, notamment face à la lourdeur de WordPress, qui peut parfois être contraignante. Le développement manuel d'un site web en HTML serait une tâche beaucoup trop chronophage.
Je prévois d'utiliser de plus en plus les SSG et de me former davantage pour les maîtriser. Je pense qu'ils présentent un fort potentiel pour les sites vitrines des petites entreprises. La rapidité d'affichage est toujours un atout précieux, tandis que l'utilisation de WordPress dans certaines situations peut entraîner un gaspillage de ressources.
