---
ShowToc: true
date: 2026-10-31
title: Service de sauvegarde Samba
---

Samba est un protocole universel de partage de fichiers utilisé au sein d'un réseau local (LAN) et fonctionne bien avec une grande variété d'appareils et de systèmes.

# Comprendre les paramètres de connexion

- **Nom d'hôte ou adresse IP** : L'adresse de l'appareil qui exécute le serveur Samba.
- **Port** : Le port du serveur Samba. La valeur par défaut est **445**.
- **Nom du partage Samba** : Un serveur Samba peut avoir plusieurs configurations de partage, vous devez donc préciser celle à utiliser.
- **Chemin du dossier de stockage** : Le chemin de stockage dans le partage. Il peut être laissé vide. Les sauvegardes sont stockées sous ce chemin ; s'il est vide, le répertoire racine du partage est utilisé.
- **Nom d'utilisateur** : Le nom d'utilisateur, qui ne peut pas être vide.
- **Mot de passe** : Le mot de passe, qui ne peut pas être vide.
- **SSID WiFi restreint** : Limite la sauvegarde à un réseau WiFi donné. Laissez le champ vide pour autoriser les sauvegardes sur n'importe quel WiFi, ou saisissez un SSID pour ne les exécuter que sur ce réseau. Samba servant à partager des fichiers sur un réseau local, cela maintient vos sauvegardes sur un WiFi de confiance.
