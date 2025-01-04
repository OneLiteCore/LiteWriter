---
title: Come sincronizzare i dati  
date: 2024-09-20  
ShowToc: true  
---

Tecnicamente parlando, la nostra app non supporta la sincronizzazione dei dati tra dispositivi. Sebbene tu possa usare la funzione di backup per trasferire i tuoi dati da un dispositivo a un altro, non può essere considerata una vera sincronizzazione.

Detto ciò, hai comunque alcune opzioni per eseguire la sincronizzazione al di fuori dell'app.

# Imposta una cartella di archiviazione come cartella principale dell'app

Puoi impostare una cartella nella memoria del dispositivo come cartella principale dell'app. In questo caso, i tuoi libri e capitoli verranno salvati come sottocartelle e file di testo all'interno della cartella.

Poiché i dati sono già memorizzati come file, puoi utilizzare strumenti di sincronizzazione esterni per sincronizzare questi dati tra dispositivi.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing è uno strumento di sincronizzazione dati multipiattaforma ampiamente utilizzato. Puoi usarlo per sincronizzare i dati dell'app tra i tuoi dispositivi mobili, PC, laptop o server domestico.

Consulta la guida ufficiale di Syncthing per sapere come configurarlo:

[Syncthing - Guida rapida](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Dischi di rete

Alcuni dischi di rete offrono una funzione di sincronizzazione bidirezionale. Impostando la cartella principale dell'app come cartella di sincronizzazione, puoi sincronizzare i dati tra dispositivi, con il vantaggio aggiuntivo di usare il disco di rete come backup.

# Git, SVN e Rsync

Per chi ha conoscenze di programmazione, questo metodo è altamente raccomandato. Usando app come Termux, puoi eseguire comandi per sincronizzare i tuoi dati.

Se hai familiarità con Git, SVN o Rsync, questa opzione offre grande flessibilità. Tuttavia, se non conosci questi strumenti, non ti consigliamo questo metodo poiché comporta un maggiore know-how tecnico e non è pensato per gli utenti comuni.

# Riassunto

L'obiettivo principale dell'app è mantenere i dati degli utenti al sicuro. Poiché la sincronizzazione dei dati tra due app client non è sempre sicura, abbiamo scelto di non sviluppare una funzione di sincronizzazione integrata. Invece, ti consigliamo di utilizzare strumenti professionali e affidabili per la sincronizzazione dei dati.
