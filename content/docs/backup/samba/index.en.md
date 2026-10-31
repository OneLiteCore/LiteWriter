---
title: Samba backup service
date: 2026-10-31
ShowToc: true
---

Samba is a universal file-sharing protocol used within a local area network (LAN). It works well with a wide range of devices and systems.

# Understanding the login parameters

- **Host name or IP address**: The address of the device running the Samba server.
- **Port**: The port of the Samba server. The default is **445**.
- **Samba share name**: A Samba server can have multiple share configurations, so you need to specify which one to use.
- **Storage folder path**: The storage path inside the share. It can be left empty. Backup files are stored under this path; if it is empty, the root directory of the share is used.
- **Username**: The user name, which cannot be empty.
- **Password**: The password, which cannot be empty.
- **Restricted WiFi SSID**: Limits backup to a specific WiFi network. Leave it empty to allow backups on any WiFi, or enter an SSID to run backups only when connected to that network. Samba is used to share files over a local network, so this keeps your backups on a trusted WiFi.
