---
ShowToc: true
copy_mark: copied
date: 2024-05-25
title: Como usar o recurso Link remoto
---

O recurso "Link" permite mapear os dados do aplicativo como um diretório no PC, para que você possa usar software de PC para editar e gerenciar seus dados.

Esse recurso é baseado no protocolo geral **WebDav**. A maioria dos sistemas operacionais deve oferecer suporte nativo, mas talvez não seja tão fácil de usar. Então aqui vai uma forma mais fácil.

## Windows

Na plataforma Windows, recomendamos o software de terceiros **RaiDrive**. Você pode baixá-lo clicando no link abaixo:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(A versão 1.8.0 não é a mais recente, mas tem tudo o que precisamos e, mais importante, não tem anúncios)

Instale e abra-o; você pode ver um painel como este. Basta seguir as dicas:

![RaiDrive setup](/img/add_drive.webp)

1. Clique no botão "Add" no topo para entrar na configuração.
2. Vá para a guia "NAS" e selecione a opção WebDav
3. Insira o nome da unidade como preferir
4. Insira o endereço
    - ao lado do texto "address", você pode ver uma caixa de seleção; deixe-a **DESMARCADA** para que possamos usar URL http.
    - Insira o endereço IP e o número da porta, que você pode encontrar ao ativar o recurso de link no aplicativo.
5. Insira seu nome de usuário e senha personalizados, se tiver; caso contrário, apenas marque a caixa de seleção "Anonymous"
6. Clique no botão "OK" para iniciar o mapeamento

Se tudo correr bem, você verá isto:

![Done](/img/done.webp)

## Linux ou MacOS

### MacOS

No macOS, você pode usar o **Finder** integrado para se conectar ao serviço WebDav:

1. Abra o **Finder**.
2. Na barra de menus, clique em **Go** e escolha **Connect to Server…** (ou pressione `Command + K`).
3. Insira no campo de endereço o endereço mostrado no aplicativo, por exemplo `http://192.168.1.100:8080`.
4. Clique em **Connect**.
5. Se solicitado, insira seu nome de usuário e senha, ou conecte-se como convidado.
6. Uma vez conectado, o serviço WebDav aparecerá no Finder como uma unidade de rede, e você poderá acessar e gerenciar seus dados como uma pasta local.

### Linux

No Linux (usando o desktop do Ubuntu como exemplo), você pode usar o gerenciador de arquivos integrado para se conectar:

1. Abra o aplicativo **Files**.
2. Clique em **Other Locations** na barra lateral esquerda.
3. Encontre o campo **Connect to Server** na parte inferior.
4. Insira o endereço no formato `dav://IP:porta`, por exemplo `dav://192.168.1.100:8080`.
5. Clique em **Connect**.
6. Se solicitado, insira seu nome de usuário e senha, ou conecte-se anonimamente.
7. Uma vez conectado, o serviço WebDav aparecerá no gerenciador de arquivos como uma localização de rede.
