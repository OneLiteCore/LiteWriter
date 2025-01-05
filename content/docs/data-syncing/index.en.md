---
title: How to sync data  
date: 2024-09-20  
ShowToc: true
copy_mark: "src"
---

Technically speaking our app does not support syncing data between devices. Although you can use backup feature to transform your data from one device to another, it couldn't be called as syncing.

That being said, you still have some ways to perform syncing outside the app.

# Set a Storage Folder as the App's Home Folder

You can set a folder in your device's storage as the app's home folder. In this setup, your books and chapters are saved as sub-folders and text files in the storage folder.

Since they are already stored as files, you can use external file-syncing tools to sync this data across devices.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing is a widely-used, cross-platform data synchronization tool. You can use it to sync your app's data between your mobile devices, PC, laptop, or home server.

Check out Syncthing's official guide to learn how to set it up:

[Syncthing - Getting Started](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Network Disks

Some network disks offer a bi-directional file-syncing feature. By setting your app's home folder as the syncing folder, you can sync data across devices, with the added benefit of using the network disk as a backup.

# Git, SVN, and Rsync

For those with programming knowledge, this method is highly recommended. Using apps like Termux you can run command-line tools for syncing your data.

If you're familiar with Git, SVN, or Rsync, this option provides great flexibility. However, if you're not familiar with these tools, we wouldn't recommend this method, as they involve more technical know-how and are not intended for common users.

# Summary

The app's primary goal is to keep users' data safe. Since syncing data between two client apps isn't always secure, we've chosen not to develop a built-in syncing feature. Instead, we recommend using reliable, professional tools for data syncing.
