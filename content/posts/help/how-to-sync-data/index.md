---
title: How to sync data
date: 2024-09-20
ShowToc: true
---

Technically speaking our app does not support syncing data between devices. Although you can use backup feature to transform your data from one device to another, it is still not convenient enough.

That being said, you still have some ways to perform syncing outside the app.

# Set a storage folder as the app's home folder

Setting a folder in your device storage as the app's home folder is supported in the first place, in this case your books and chapters will be saved as sub-folders and text files within the folder.

They are files already, therefore you can use tools which are for syncing files to syncing your data for the app.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing is a widely used cross-platform data synchronization tool, you can use it to sync your data between your phone devices and your PC/Laptop/Home server.

Check its official guide to know how to use it:

[Syncthing - Getting Started](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Network disks

Some network disks provide a bi-directional file syncing folder feature, making the app's home folder as the syncing folder would allow it to sync your data between devices. It could also perform an add-on backup server in this case.

# Git, Svn and Rsync

If you know programming well then this is the recommended way. You can use apps like Termux to run commands lines for data syncing.

You don't need a guide for it if you know what is talking about, but if you don't know then we would not recommend it for you as Git or Svn or command lines are never for common users.

# Summary

The first principle of the app is keeping users' data safe, and syncing data between 2 client apps isn't safe enough, therefore we do not develop a built-in syncing feature and leave this to thoes professional tools which are bound to it.

