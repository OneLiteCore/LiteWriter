---
ShowToc: true
date: 2024-05-25
title: Come usare la funzione Link remoto
---

La funzione "Link" ti consente di mappare i dati dell'app come una directory del PC, così puoi usare software PC per modificare e gestire i tuoi dati.

Questa funzione si basa sul protocollo generale **WebDav**. La maggior parte dei sistemi operativi dovrebbe supportarlo nativamente, ma forse non è così facile da usare. Ecco quindi un modo più semplice.

## Windows

Su Windows ti consigliamo il software di terze parti **RaiDrive**. Puoi scaricarlo facendo clic sul link qui sotto:

[RaiDrive 1.8.0 https://raidrive.en.uptodown.com/windows/download/2114805](https://raidrive.en.uptodown.com/windows/download/2114805)

(La versione 1.8.0 non è l'ultima, ma ha tutto ciò che ci serve e, cosa più importante, non ha pubblicità)

Installalo e aprilo; potresti vedere un pannello come questo, segui semplicemente i suggerimenti:

![RaiDrive setup](/img/add_drive.webp)

1. Fai clic sul pulsante "Add" in alto per accedere alla configurazione.
2. Vai alla scheda "NAS" e seleziona l'opzione WebDav
3. Inserisci il nome dell'unità come preferisci
4. Inserisci l'indirizzo
    - accanto al testo "address" potresti vedere una casella di controllo; lasciala **NON SELEZIONATA** così possiamo usare un URL http.
    - Inserisci l'indirizzo IP e il numero di porta, che trovi quando attivi la funzione link nell'app.
5. Inserisci nome utente e password personalizzati, se li hai; altrimenti seleziona la casella "Anonymous"
6. Fai clic sul pulsante "OK" per avviare il mapping

Se tutto va bene, potresti vedere questo:

![Done](/img/done.webp)

## Linux o MacOS

### MacOS

Su macOS puoi usare il **Finder** integrato per connetterti al servizio WebDav:

1. Apri il **Finder**.
2. Nella barra dei menu, fai clic su **Go** e scegli **Connect to Server…** (oppure premi `Command + K`).
3. Inserisci nel campo indirizzo l'indirizzo mostrato nell'app, ad esempio `http://192.168.1.100:8080`.
4. Fai clic su **Connect**.
5. Se richiesto, inserisci nome utente e password, oppure connettiti come ospite.
6. Una volta connesso, il servizio WebDav apparirà nel Finder come unità di rete e potrai accedere ai tuoi dati e gestirli come una cartella locale.

### Linux

Su Linux (prendendo come esempio Ubuntu desktop), puoi usare il file manager integrato per connetterti:

1. Apri l'app **Files**.
2. Fai clic su **Other Locations** nella barra laterale sinistra.
3. Trova il campo **Connect to Server** in basso.
4. Inserisci l'indirizzo nel formato `dav://IP:porta`, ad esempio `dav://192.168.1.100:8080`.
5. Fai clic su **Connect**.
6. Se richiesto, inserisci nome utente e password, oppure connettiti in modo anonimo.
7. Una volta connesso, il servizio WebDav apparirà nel file manager come posizione di rete.
