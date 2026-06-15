---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Internal backup service
---

L'application fournit un mécanisme de sauvegarde interne qui compresse régulièrement les données de vos chapitres dans un fichier .zip.

# Les fichiers de sauvegarde internes seront perdus si l'application est désinstallée

Le mécanisme intégré stocke les fichiers de sauvegarde .zip dans un dossier privé de l'application. Ce dossier, ainsi que les autres données de l'application, sera supprimé si l'application est désinstallée.

Ne comptez donc pas uniquement sur ce mécanisme pour protéger vos données. Il n'est pas conçu pour être votre seule méthode de sauvegarde.

# Fonctionnement

Lorsque vous quittez l'application, ou à l'heure planifiée chaque jour, l'application vérifie s'il existe des modifications qui n'ont pas encore été sauvegardées. Si c'est le cas, le processus de sauvegarde est lancé. Par défaut, il y a au moins 8 heures d'intervalle entre deux sauvegardes.

Une fois qu'un nouveau fichier zip est créé, l'application vérifie les anciennes données de sauvegarde et les supprime si nécessaire. Par défaut, l'application conserve les 20 fichiers de sauvegarde les plus récents, vous n'avez donc pas à vous inquiéter d'un espace de stockage occupé en excès par les sauvegardes.

Si vous avez configuré d'autres services de sauvegarde, comme Google Drive ou la sauvegarde du stockage de l'appareil, le dernier fichier zip y sera également envoyé.
