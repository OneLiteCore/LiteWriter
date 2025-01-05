---
title: Como sincronizar dados  
date: 2024-09-20  
ShowToc: true
copy_mark: src
---

Tecnicamente, nosso aplicativo não suporta a sincronização de dados entre dispositivos. Embora você possa usar o recurso de backup para transferir seus dados de um dispositivo para outro, isso não pode ser chamado de sincronização.

Dito isso, ainda existem algumas maneiras de realizar a sincronização fora do aplicativo.

# Defina uma pasta de armazenamento como a pasta principal do aplicativo

Você pode definir uma pasta no armazenamento do seu dispositivo como a pasta principal do aplicativo. Nesse caso, seus livros e capítulos serão salvos como subpastas e arquivos de texto dentro dessa pasta.

Como eles já estão armazenados como arquivos, você pode usar ferramentas de sincronização de arquivos externas para sincronizar esses dados entre dispositivos.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing é uma ferramenta amplamente utilizada para sincronização de dados entre plataformas. Você pode usá-lo para sincronizar os dados do seu aplicativo entre seus dispositivos móveis, PC, laptop ou servidor doméstico.

Confira o guia oficial do Syncthing para saber como configurá-lo:

[Syncthing - Começando](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Discos de rede

Alguns discos de rede oferecem uma função de sincronização bidirecional de arquivos. Definindo a pasta principal do aplicativo como a pasta de sincronização, você pode sincronizar os dados entre os dispositivos e também usar o disco de rede como um servidor de backup.

# Git, SVN e Rsync

Para quem tem conhecimentos de programação, este é o método recomendado. Usando aplicativos como Termux, você pode executar ferramentas de linha de comando para sincronizar seus dados.

Se você estiver familiarizado com Git, SVN ou Rsync, essa opção oferece grande flexibilidade. No entanto, se não estiver familiarizado com essas ferramentas, não recomendamos este método, pois exige mais conhecimentos técnicos e não é indicado para usuários comuns.

# Resumo

O objetivo principal do aplicativo é manter os dados dos usuários seguros. Como a sincronização de dados entre dois aplicativos clientes não é suficientemente segura, optamos por não desenvolver um recurso de sincronização integrado. Em vez disso, recomendamos o uso de ferramentas confiáveis e profissionais para sincronização de dados.
