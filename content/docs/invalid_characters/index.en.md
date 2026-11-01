---
title: Invalid characters in file names
ShowToc: true
---

This app stores your notes, chapters, novels, and other content in text files. We use plain text so your data remains compatible across platforms: even if you stop using this app, you can easily manage and edit your files in other apps and operating systems.

## Characters not allowed in file names: `\/:*?"<>|`

These characters have special meanings in file systems and other common software, so using them in names can make files difficult to create, locate, or open consistently across devices. For example, `/` separates folders in a path, while `\` is used as a path separator on some systems and as an escape character in some text formats. Other characters in this set may act as wildcards, delimiters, or control symbols. To keep your files portable and easy to manage, the app does not allow these characters in file names.

## Why can't a file name start with `.` or `..`?

Android is based on the Linux kernel. In Linux-style paths, `.` refers to the current directory and `..` refers to its parent directory. Also, files and folders whose names begin with a dot are conventionally treated as hidden by Linux and Android tools. The app prevents names from starting with a dot to avoid confusion with these special path components and to keep your files visible and easy to find.
