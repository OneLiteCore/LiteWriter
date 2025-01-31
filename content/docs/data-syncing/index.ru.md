---
title: Как синхронизировать данные  
date: 2024-09-20  
ShowToc: true
copy_mark: src
---

Технически говоря, наше приложение не поддерживает синхронизацию данных между устройствами. Хотя вы можете использовать функцию резервного копирования для передачи данных с одного устройства на другое, это не может называться синхронизацией.

Тем не менее, у вас есть несколько способов синхронизировать данные вне приложения.

# Установите папку хранения в качестве домашней папки приложения

Вы можете выбрать папку в памяти устройства в качестве домашней папки приложения. В этом случае ваши книги и главы будут сохранены в виде подпапок и текстовых файлов внутри этой папки.

Поскольку они уже сохранены как файлы, вы можете использовать внешние инструменты для синхронизации файлов, чтобы синхронизировать данные между устройствами.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing — это широко используемый инструмент для синхронизации данных между различными платформами. Вы можете использовать его для синхронизации данных приложения между вашими мобильными устройствами, ПК, ноутбуком или домашним сервером.

Посмотрите официальный гид по Syncthing, чтобы узнать, как его настроить:

[Syncthing - Руководство по началу работы](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Сетевые диски

Некоторые сетевые диски предлагают двустороннюю синхронизацию файлов. Если установить домашнюю папку приложения в качестве папки для синхронизации, вы сможете синхронизировать данные между устройствами и использовать сетевой диск как сервер для резервного копирования.

# Git, SVN и Rsync

Для тех, кто разбирается в программировании, этот метод рекомендуется. Используя приложения, такие как Termux, можно выполнять командные строки для синхронизации данных.

Если вы знакомы с Git, SVN или Rsync, этот вариант предлагает большую гибкость. Однако, если вы не знакомы с этими инструментами, мы не рекомендуем этот метод, так как он требует технических знаний и не предназначен для обычных пользователей.

# Резюме

Основной принцип приложения — обеспечивать безопасность данных пользователей. Поскольку синхронизация данных между двумя клиентскими приложениями недостаточно безопасна, мы не разрабатываем встроенную функцию синхронизации. Вместо этого мы рекомендуем использовать проверенные и профессиональные инструменты для синхронизации данных.
