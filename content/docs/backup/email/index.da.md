---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: E-mail-backuptjeneste
---

E-mail-backuptjenesten bruger din egen e-mailkonto til at sende backupfiler som vedhæftede filer til din egen postkasse. Det betyder, at backupfilerne bliver i en e-mailkonto, som du allerede selv kontrollerer, hvilket giver dig bedre privatliv og fuldt ejerskab over dine backupdata.

Vi går meget op i dit privatliv. Appen vil aldrig uploade din e-mailadresse, og den vil aldrig misbruge, indsamle eller stjæle din adgangskode.

# Hvorfor du skal bruge en app-adgangskode i stedet for din e-mailadgangskode

De fleste e-mailudbydere tillader ikke, at tredjepartsapps logger ind med din normale e-mailadgangskode. Det er en almindelig sikkerhedspolitik, som hjælper med at reducere risikoen for lækkede adgangskoder og misbrug af konti.

Derfor skal du som regel oprette en tredjeparts app-adgangskode eller en klientspecifik adgangskode i indstillingerne for din e-mailkonto og derefter bruge den adgangskode i appen i stedet for din almindelige e-mailadgangskode.

# Hjælpedokumenter for almindelige e-mailudbydere

- [Gmail-hjælpedokument](https://support.google.com/mail/answer/185833)
- [QQ Mail-hjælpedokument](https://wx.mail.qq.com/list/readtemplate?name=app_intro.html#/agreement/authorizationCode)

# Forstå loginparametrene

- **IMAP-serveradresse**: Serveren, der bruges til at modtage og læse e-mails.
- **IMAP-port**: Netværksporten, der bruges af IMAP. Standardporten for IMAP er normalt **993**.
- **SMTP-serveradresse**: Serveren, der bruges til at sende e-mails.
- **SMTP-port**: Netværksporten, der bruges af SMTP. Standardporten for SMTP er normalt **465** eller **587**.
- **STARTTLS**: En sikkerhedsfunktion, der opgraderer en almindelig forbindelse til en krypteret TLS-forbindelse, efter at forbindelsen er startet. Hvis SMTP-porten er sat til **587**, vil appen aktivere og kræve **STARTTLS** som standard.
- **E-mailadresse**: Den e-mailkonto, der sender backupmailen og også modtager den.
- **Tredjeparts app-adgangskode**: En adgangskode, som din e-mailudbyder opretter til eksterne apps. I de fleste tilfælde kan du ikke bruge din normale e-mailadgangskode her, fordi udbydere normalt blokerer direkte login med adgangskode fra tredjepartsapps af sikkerhedsmæssige årsager.
