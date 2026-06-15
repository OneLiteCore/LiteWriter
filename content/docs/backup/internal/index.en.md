---
title: Internal backup service
date: 2026-06-14
ShowToc: true
copy_mark: src
---

The app provides an internal backup mechanism to zip all your chapters data into a .zip file from time to time.

# Internal backup files will LOSE if the app get uninstalled

The built-in mechanism will store the backup .zip files in an app-private folder, and the folder will be deleted together with other app data if the app itself get uninstalled.

So don’t just rely all your data safty on this, it is not designed to be used like this.

# How it works

When you leave the app or at the scheduled time each day, the app will check if there are any modifications that haven't been backed up, if so then the backup process will be triggered. By default there should be at least 8 hours between two backuo processes.

Once the latest zip file is made, the app will check and delete legacy data if there are any, by default the app will keep latest 20 backup files, so you don't need to worry about whether backup files woulc occupy too much storage space.

The latest zip file will be uploaded to other backup services, e.g. Google Drive or device storage backup, if you have already set it up.
