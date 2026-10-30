---
ShowToc: true
date: 2024-05-25
title: Comment utiliser la fonction de lien distant
---

La fonction « Lien » vous permet de mapper les données de l'application en tant que répertoire PC, afin de pouvoir utiliser un logiciel PC pour modifier et gérer vos données.

Cette fonction repose sur le protocole général **WebDav**. La plupart des systèmes d'exploitation devraient le prendre en charge nativement, mais il n'est peut-être pas si facile à utiliser. Voici donc une méthode plus simple.

## Windows

Sur Windows, nous vous recommandons le logiciel tiers **RaiDrive**. Vous pouvez le télécharger en cliquant sur le lien ci-dessous :

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(La version 1.8.0 n'est pas la plus récente, mais elle a tout ce dont nous avons besoin et, surtout, elle ne contient aucune publicité)

Installez-la et ouvrez-la ; vous verrez peut-être un panneau comme celui-ci, suivez simplement les conseils :

![RaiDrive setup](/img/add_drive.webp)

1. Cliquez sur le bouton « Add » en haut pour accéder à la configuration.
2. Allez dans l'onglet « NAS » et sélectionnez l'option WebDav
3. Saisissez le nom du lecteur comme vous le souhaitez
4. Saisissez l'adresse
    - à côté du texte « address », vous verrez peut-être une case à cocher ; laissez-la **DÉCOCHÉE** afin de pouvoir utiliser une URL http.
    - Saisissez l'adresse IP et le numéro de port, que vous pouvez trouver lorsque vous activez la fonction de lien dans l'application.
5. Saisissez votre nom d'utilisateur et votre mot de passe personnalisés si vous en avez ; sinon, cochez simplement la case « Anonymous »
6. Cliquez sur le bouton « OK » pour démarrer le mappage

Si tout se passe bien, vous verrez peut-être ceci :

![Done](/img/done.webp)

## Linux ou MacOS

### MacOS

Sur macOS, vous pouvez utiliser le **Finder** intégré pour vous connecter au service WebDav :

1. Ouvrez le **Finder**.
2. Dans la barre de menus, cliquez sur **Go** puis choisissez **Connect to Server…** (ou appuyez sur `Command + K`).
3. Saisissez dans le champ d'adresse l'adresse affichée dans l'application, par exemple `http://192.168.1.100:8080`.
4. Cliquez sur **Connect**.
5. Si demandé, saisissez votre nom d'utilisateur et votre mot de passe, ou connectez-vous en tant qu'invité.
6. Une fois connecté, le service WebDav apparaîtra dans le Finder comme un lecteur réseau, et vous pourrez accéder à vos données et les gérer comme un dossier local.

### Linux

Sur Linux (en prenant Ubuntu desktop comme exemple), vous pouvez utiliser le gestionnaire de fichiers intégré pour vous connecter :

1. Ouvrez l'application **Files**.
2. Cliquez sur **Other Locations** dans la barre latérale gauche.
3. Trouvez le champ **Connect to Server** en bas.
4. Saisissez l'adresse au format `dav://IP:port`, par exemple `dav://192.168.1.100:8080`.
5. Cliquez sur **Connect**.
6. Si demandé, saisissez votre nom d'utilisateur et votre mot de passe, ou connectez-vous de manière anonyme.
7. Une fois connecté, le service WebDav apparaîtra dans le gestionnaire de fichiers comme un emplacement réseau.
