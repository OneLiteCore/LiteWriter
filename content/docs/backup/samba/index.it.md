---
ShowToc: true
date: 2026-10-31
title: Servizio di backup Samba
---

Samba è un protocollo universale per la condivisione di file all'interno di una rete locale (LAN) e funziona bene con un'ampia varietà di dispositivi e sistemi.

# Comprendere i parametri di accesso

- **Nome host o indirizzo IP**: L'indirizzo del dispositivo che esegue il server Samba.
- **Porta**: La porta del server Samba. Il valore predefinito è **445**.
- **Nome della condivisione Samba**: Un server Samba può avere più configurazioni di condivisione, quindi devi indicare quale usare.
- **Percorso della cartella di archiviazione**: Il percorso di archiviazione all'interno della condivisione. Può essere lasciato vuoto. I backup vengono salvati in questo percorso; se è vuoto, si usa la directory principale della condivisione.
- **Nome utente**: Il nome utente, che non può essere vuoto.
- **Password**: La password, che non può essere vuota.
- **SSID WiFi limitato**: Limita il backup a una rete WiFi specifica. Lascia vuoto il campo per consentire i backup su qualsiasi WiFi, oppure inserisci un SSID per eseguirli solo su quella rete. Samba serve a condividere file in una rete locale, così i backup restano su un WiFi affidabile.
