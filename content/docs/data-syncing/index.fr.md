---
title: Comment synchroniser les données  
date: 2024-09-20  
ShowToc: true
copy_mark: "src"
---

Techniquement parlant, notre application ne prend pas en charge la synchronisation des données entre appareils. Bien que vous puissiez utiliser la fonctionnalité de sauvegarde pour transférer vos données d’un appareil à un autre, cela ne peut pas être qualifié de synchronisation.

Cela dit, il existe encore quelques moyens de réaliser une synchronisation en dehors de l’application.

# Définir un dossier de stockage comme dossier principal de l'application

Vous pouvez définir un dossier dans le stockage de votre appareil comme dossier principal de l'application. Dans cette configuration, vos livres et chapitres seront enregistrés sous forme de sous-dossiers et de fichiers texte dans le dossier de stockage.

Puisqu'ils sont déjà enregistrés sous forme de fichiers, vous pouvez utiliser des outils externes de synchronisation de fichiers pour synchroniser ces données entre plusieurs appareils.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing est un outil de synchronisation de données multiplateforme largement utilisé. Vous pouvez l'utiliser pour synchroniser les données de votre application entre vos appareils mobiles, PC, ordinateur portable ou serveur domestique.

Consultez le guide officiel de Syncthing pour savoir comment le configurer :

[Syncthing - Prise en main](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Disques réseau

Certains disques réseau offrent une fonctionnalité de synchronisation bidirectionnelle des fichiers. En définissant le dossier principal de votre application comme dossier de synchronisation, vous pouvez synchroniser les données entre plusieurs appareils. Cela peut également servir de serveur de sauvegarde supplémentaire.

# Git, SVN et Rsync

Pour ceux qui ont des connaissances en programmation, cette méthode est fortement recommandée. En utilisant des applications comme Termux, vous pouvez exécuter des outils en ligne de commande pour synchroniser vos données.

Si vous êtes familiarisé avec Git, SVN ou Rsync, cette option offre une grande flexibilité. Cependant, si vous ne connaissez pas ces outils, nous ne vous recommandons pas cette méthode car elle nécessite des connaissances techniques approfondies et n'est pas destinée aux utilisateurs courants.

# Résumé

Le principal objectif de l'application est de garder les données des utilisateurs en sécurité. Comme la synchronisation des données entre deux applications clientes n'est pas toujours sécurisée, nous avons choisi de ne pas développer de fonctionnalité de synchronisation intégrée. À la place, nous recommandons d'utiliser des outils professionnels et fiables pour synchroniser les données.
