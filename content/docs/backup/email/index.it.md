---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Servizio di backup via email
---

Il servizio di backup via email utilizza il tuo account email per inviare i file di backup come allegati alla tua stessa casella di posta. In questo modo i file di backup restano in un account email che controlli già tu, offrendoti maggiore privacy e piena proprietà dei tuoi dati di backup.

La tua privacy ci sta molto a cuore. L'app non caricherà mai il tuo indirizzo email e non userà mai impropriamente, raccoglierà o ruberà la tua password.

# Perché ti serve una password per app invece della password della tua email

La maggior parte dei provider email non consente alle app di terze parti di accedere con la normale password della tua email. Si tratta di una politica di sicurezza comune che aiuta a ridurre il rischio di perdite di password e abuso degli account.

Per questo motivo, di solito dovrai creare una password per app di terze parti o una password specifica per client nelle impostazioni del tuo account email, e poi usare quella password nell'app al posto della tua normale password email.

# Documenti di aiuto per i provider email più comuni

- [Documento di aiuto di Gmail](https://support.google.com/mail/answer/185833)
- [Documento di aiuto di QQ Mail](https://wx.mail.qq.com/list/readtemplate?name=app_intro.html#/agreement/authorizationCode)

# Capire i parametri di accesso

- **Indirizzo del server IMAP**: Il server usato per ricevere e leggere le email.
- **Porta IMAP**: La porta di rete usata da IMAP. La porta IMAP predefinita è di solito **993**.
- **Indirizzo del server SMTP**: Il server usato per inviare le email.
- **Porta SMTP**: La porta di rete usata da SMTP. La porta SMTP predefinita è di solito **465** o **587**.
- **STARTTLS**: Una funzione di sicurezza che aggiorna una connessione semplice a una connessione TLS crittografata dopo l'avvio della connessione. Se la porta SMTP è impostata su **587**, l'app abiliterà e richiederà **STARTTLS** per impostazione predefinita.
- **Indirizzo email**: L'account email che invia l'email di backup e la riceve anche.
- **Password per app di terze parti**: Una password generata dal tuo provider email per le app esterne. Nella maggior parte dei casi, qui non puoi usare la normale password della tua email, perché i provider di solito bloccano l'accesso diretto con password per le app di terze parti per motivi di sicurezza.
