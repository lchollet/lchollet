+++
title = 'Expérimentation - Extention WordPress de prise de rendez-vous'
date = 2024-01-05T11:06:29+01:00
+++
## Introduction

Dans le cadre de cette veille technologique, j'ai découvert une extension WordPress permettant une gestion dynamique des rendez-vous, nommée Amelia. [Lien vers leur site ici](https://wpamelia.com/)

![Amelia](https://lchollet.github.io/lchollet/images/amelia.png)

L'extension propose une interface responsive, propre et facile d'utilisation, offrant diverses fonctionnalités telles que des notifications de rendez-vous avec rappel automatique, etc.

![Notifications](https://lchollet.github.io/lchollet/images/notif.png)

Dans cette expérimentation, je vais présenter un cas d'utilisation sur mon site dédié aux prises de rendez-vous pour le lavage automobile. [Lien du site de lavage auto](https://p-wash.ch)

## L'expérience

Après l'installation de l'extension, j'ai accédé à la page d'accueil regroupant toutes les informations sur les rendez-vous à venir, les gains générés par les rendez-vous précédents et la disponibilité des employés.

![Accueil](https://lchollet.github.io/lchollet/images/accueil.png)

J'ai créé un employé que j'ai nommé "P-wash lavage à domicile" (la gestion individuelle des employés ne m'intéresse pas ici). J'ai pu lui attribuer des horaires, des tarifs horaires, etc. Bien que je n'utilise pas toutes les fonctionnalités dans mon cas, je comprends leur utilité dans d'autres contextes.

Mon employé est associé à un calendrier Google, permettant l'ajout automatique des rendez-vous à son planning.

### Les services

Chaque employé peut offrir divers services. Dans mon cas, j'ai créé plusieurs services, un par région, avec des tarifs variant en fonction de la distance de Lausanne.

![Services](https://lchollet.github.io/lchollet/images/service.png)


### Les options

Chaque service comporte des options qui dynamiquement ajustent le prix et la durée allouée pour le lavage proposé.

![Options](https://lchollet.github.io/lchollet/images/option.png)

### Notifications

Une fois le rendez-vous effectué, le client reçoit automatiquement une notification par e-mail, personnalisée et automatisée. Tous les paramètres sont configurables depuis cette interface.

![Notifications](https://lchollet.github.io/lchollet/images/notification.png)

Chaque variable est affichable, comme le type de lavage, les options supplémentaires, l'emplacement du rendez-vous, etc. Du côté de l'employé, le même e-mail est reçu.

### Interface côté clients

Lors de la prise de rendez-vous, voici comment cela se présente du côté du client.

![Interface client - options](https://lchollet.github.io/lchollet/images/client1.png)

Et voici le calendrier, qui ajuste automatiquement les plages horaires en fonction de la durée du service demandé.

![Interface client - calendrier](https://lchollet.github.io/lchollet/images/client2.png)

## Conclusion

Cette expérience est un succès pour moi. L'extension Amelia a considérablement optimisé la gestion de mon business, permettant aux clients de prendre rendez-vous eux-mêmes sans avoir à décrocher le téléphone. À l'avenir, j'ai l'intention de personnaliser davantage l'outil, notamment en intégrant les employés de manière individuelle plutôt que de les regrouper sous un seul employé fictif. Dans tous les cas, la découverte de cette extension s'est avérée très bénéfique.

