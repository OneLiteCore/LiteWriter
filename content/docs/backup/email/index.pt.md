---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Serviço de backup por e-mail
---

O serviço de backup por e-mail usa a sua própria conta de e-mail para enviar arquivos de backup como anexos para a sua própria caixa de correio. Isso mantém os arquivos de backup em uma conta de e-mail que você já controla, oferecendo mais privacidade e total propriedade sobre seus dados de backup.

Nós nos importamos muito com a sua privacidade. O aplicativo nunca enviará o seu endereço de e-mail e nunca fará mau uso, coletará ou roubará a sua senha.

# Por que você precisa de uma senha de aplicativo em vez da senha do seu e-mail

A maioria dos provedores de e-mail não permite que aplicativos de terceiros façam login com a senha normal do seu e-mail. Essa é uma política de segurança comum que ajuda a reduzir o risco de vazamento de senhas e abuso de contas.

Por isso, normalmente você precisará criar uma senha de aplicativo de terceiros ou uma senha específica para cliente nas configurações da sua conta de e-mail e depois usar essa senha no aplicativo em vez da sua senha normal.

# Documentos de ajuda para provedores de e-mail comuns

- [Documento de ajuda do Gmail](https://support.google.com/mail/answer/185833)
- [Documento de ajuda do QQ Mail](https://wx.mail.qq.com/list/readtemplate?name=app_intro.html#/agreement/authorizationCode)

# Entendendo os parâmetros de login

- **Endereço do servidor IMAP**: O servidor usado para receber e ler e-mails.
- **Porta IMAP**: A porta de rede usada pelo IMAP. A porta IMAP padrão geralmente é **993**.
- **Endereço do servidor SMTP**: O servidor usado para enviar e-mails.
- **Porta SMTP**: A porta de rede usada pelo SMTP. A porta SMTP padrão geralmente é **465** ou **587**.
- **STARTTLS**: Um recurso de segurança que atualiza uma conexão comum para uma conexão TLS criptografada depois que a conexão é iniciada. Se a porta SMTP estiver definida como **587**, o aplicativo ativará e exigirá **STARTTLS** por padrão.
- **Endereço de e-mail**: A conta de e-mail que envia o e-mail de backup e também o recebe.
- **Senha de aplicativo de terceiros**: Uma senha gerada pelo seu provedor de e-mail para aplicativos externos. Na maioria dos casos, você não pode usar aqui a senha normal do seu e-mail, porque os provedores geralmente bloqueiam o login direto por senha para aplicativos de terceiros por motivos de segurança.
