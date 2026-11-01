---
ShowToc: true
title: Caractères non autorisés dans les noms de fichiers
---

Cette application enregistre vos notes, chapitres, romans et autres contenus dans des fichiers texte. Le texte brut garantit une large compatibilité et facilite l'utilisation sur différentes plateformes. Ainsi, même si vous cessez un jour d'utiliser l'application, vous pourrez facilement gérer et modifier vos fichiers avec d'autres applications et systèmes d'exploitation.

## Caractères interdits dans les noms de fichiers : `\/:*?"<>|`

Ces caractères ont une fonction particulière dans les systèmes de fichiers et de nombreux logiciels courants. Leur présence dans un nom peut donc empêcher la création, la recherche ou l'ouverture cohérente d'un fichier sur différents appareils. Par exemple, `/` sépare les dossiers dans un chemin ; `\` sert aussi de séparateur de chemin sur certains systèmes et de caractère d'échappement dans certains formats texte. Les autres caractères de cette liste peuvent notamment servir de joker, de délimiteur ou de symbole de contrôle. Pour que vos fichiers restent faciles à utiliser sur différentes plateformes, l'application n'autorise pas ces caractères dans les noms.

## Pourquoi un nom de fichier ne peut-il pas commencer par `.` ou `..` ?

Android repose sur le noyau Linux. Dans les chemins de type Linux, `.` désigne le dossier actuel et `..` le dossier parent. De plus, les outils Linux et Android considèrent généralement comme masqués les fichiers et dossiers dont le nom commence par un point. L'application interdit donc le point au début d'un nom afin d'éviter toute confusion avec les éléments spéciaux d'un chemin et de garder vos fichiers visibles et faciles à retrouver.
