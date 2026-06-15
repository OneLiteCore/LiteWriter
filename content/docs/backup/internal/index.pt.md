---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Serviço de backup interno
---

O aplicativo oferece um mecanismo de backup interno que compacta periodicamente os dados dos seus capítulos em um arquivo .zip.

# Os arquivos de backup interno serão perdidos se o aplicativo for desinstalado

O mecanismo integrado armazena os arquivos de backup .zip em uma pasta privada do aplicativo. Essa pasta, junto com os outros dados do aplicativo, será excluída se o aplicativo for desinstalado.

Por isso, não dependa apenas desse mecanismo para manter seus dados seguros. Ele não foi projetado para ser o seu único método de backup.

# Como funciona

Quando você sai do aplicativo, ou no horário programado de cada dia, o aplicativo verifica se existem alterações que ainda não foram salvas em backup. Se existirem, o processo de backup será acionado. Por padrão, há um intervalo mínimo de 8 horas entre os processos de backup.

Depois que um novo arquivo zip é criado, o aplicativo verifica se há dados de backup antigos e os remove, se necessário. Por padrão, o aplicativo mantém os 20 arquivos de backup mais recentes, então você não precisa se preocupar com backups ocupando espaço demais no armazenamento.

Se você configurou outros serviços de backup, como o Google Drive ou o backup do armazenamento do dispositivo, o arquivo zip mais recente também será enviado para lá.
