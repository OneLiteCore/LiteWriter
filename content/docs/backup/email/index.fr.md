---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Service de sauvegarde par e-mail
---

Le service de sauvegarde par e-mail utilise votre propre compte e-mail pour envoyer les fichiers de sauvegarde en pièces jointes vers votre propre boîte mail. Ainsi, les fichiers de sauvegarde restent dans un compte e-mail que vous contrôlez déjà, ce qui vous offre une meilleure confidentialité et une pleine maîtrise de vos données de sauvegarde.

Nous accordons une grande importance à votre vie privée. L'application n'enverra jamais votre adresse e-mail et n'utilisera, ne collectera ni ne volera jamais votre mot de passe.

# Pourquoi vous avez besoin d'un mot de passe d'application au lieu de votre mot de passe e-mail

La plupart des fournisseurs de messagerie n'autorisent pas les applications tierces à se connecter avec votre mot de passe e-mail habituel. Il s'agit d'une politique de sécurité courante qui aide à réduire le risque de fuite de mots de passe et d'abus de compte.

Pour cette raison, vous devrez généralement créer un mot de passe d'application tiers ou un mot de passe spécifique au client dans les paramètres de votre compte e-mail, puis utiliser ce mot de passe dans l'application à la place de votre mot de passe habituel.

# Documents d'aide pour les fournisseurs de messagerie courants

- [Document d'aide Gmail](https://support.google.com/mail/answer/185833)
- [Document d'aide QQ Mail](https://wx.mail.qq.com/list/readtemplate?name=app_intro.html#/agreement/authorizationCode)

# Comprendre les paramètres de connexion

- **Adresse du serveur IMAP** : Le serveur utilisé pour recevoir et lire les e-mails.
- **Port IMAP** : Le port réseau utilisé par IMAP. Le port IMAP par défaut est généralement **993**.
- **Adresse du serveur SMTP** : Le serveur utilisé pour envoyer les e-mails.
- **Port SMTP** : Le port réseau utilisé par SMTP. Le port SMTP par défaut est généralement **465** ou **587**.
- **STARTTLS** : Une fonction de sécurité qui fait passer une connexion simple à une connexion TLS chiffrée après le démarrage de la connexion. Si le port SMTP est défini sur **587**, l'application activera et exigera **STARTTLS** par défaut.
- **Adresse e-mail** : Le compte e-mail qui envoie l'e-mail de sauvegarde et qui le reçoit également.
- **Mot de passe d'application tiers** : Un mot de passe généré par votre fournisseur de messagerie pour les applications externes. Dans la plupart des cas, vous ne pouvez pas utiliser ici votre mot de passe e-mail habituel, car les fournisseurs bloquent généralement la connexion directe par mot de passe pour les applications tierces pour des raisons de sécurité.
