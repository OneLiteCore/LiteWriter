---
ShowToc: true
date: 2026-10-31
title: Serviço de backup Samba
---

O Samba é um protocolo universal de compartilhamento de arquivos para redes locais (LAN) e funciona bem com uma grande variedade de dispositivos e sistemas.

# Entendendo os parâmetros de login

- **Nome do host ou endereço IP**: O endereço do dispositivo que executa o servidor Samba.
- **Porta**: A porta do servidor Samba. O padrão é **445**.
- **Nome do compartilhamento Samba**: Um servidor Samba pode ter várias configurações de compartilhamento, então você precisa indicar qual usar.
- **Caminho da pasta de armazenamento**: O caminho de armazenamento dentro do compartilhamento. Pode ficar vazio. Os backups são salvos neste caminho; se estiver vazio, o diretório raiz do compartilhamento é usado.
- **Nome de usuário**: O nome de usuário, que não pode ficar vazio.
- **Senha**: A senha, que não pode ficar vazia.
- **SSID de WiFi restrito**: Limita o backup a uma rede WiFi específica. Deixe vazio para permitir backups em qualquer WiFi, ou informe um SSID para que o backup só rode nessa rede. Como o Samba serve para compartilhar arquivos em uma rede local, isso mantém seus backups em um WiFi confiável.
