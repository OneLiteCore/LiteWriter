---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Internal backup service
---

L'app fornisce un meccanismo di backup interno che comprime periodicamente i dati dei tuoi capitoli in un file .zip.

# I file di backup interni andranno persi se l'app viene disinstallata

Il meccanismo integrato salva i file di backup .zip in una cartella privata dell'app. Questa cartella, insieme agli altri dati dell'app, verrà eliminata se l'app viene disinstallata.

Perciò non fare affidamento solo su questo meccanismo per mantenere al sicuro i tuoi dati. Non è progettato per essere il tuo unico metodo di backup.

# Come funziona

Quando esci dall'app, oppure all'orario pianificato di ogni giorno, l'app controlla se ci sono modifiche che non sono ancora state sottoposte a backup. In tal caso, il processo di backup viene avviato. Per impostazione predefinita, tra due processi di backup passano almeno 8 ore.

Dopo la creazione di un nuovo file zip, l'app controlla i vecchi dati di backup e li elimina se necessario. Per impostazione predefinita, l'app conserva i 20 file di backup più recenti, quindi non devi preoccuparti che i backup occupino troppo spazio di archiviazione.

Se hai configurato altri servizi di backup, come Google Drive o il backup della memoria del dispositivo, anche il file zip più recente verrà caricato lì.
