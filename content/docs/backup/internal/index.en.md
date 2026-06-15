---
title: Internal backup service
date: 2026-06-14
ShowToc: true
copy_mark: src
---

The app provides an internal backup mechanism that periodically compresses your chapter data into a .zip file.

# Internal backup files will be lost if the app gets uninstalled

The built-in mechanism stores backup .zip files in an app-private folder. This folder, along with other app data, will be deleted if the app is uninstalled.

So do not rely on this mechanism alone to keep your data safe. It is not designed to be your only backup method.

# How it works

When you leave the app or at the scheduled time each day, the app checks whether there are any changes that have not been backed up. If so, the backup process is triggered. By default, there is at least an 8-hour interval between backup processes.

After a new zip file is created, the app checks for old backup data and deletes it if necessary. By default, the app keeps the latest 20 backup files, so you do not need to worry about backups taking up too much storage space.

If you have configured other backup services, such as Google Drive or device storage backup, the latest zip file will also be uploaded there.
