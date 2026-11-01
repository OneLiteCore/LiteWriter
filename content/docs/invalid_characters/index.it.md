---
ShowToc: true
title: Caratteri non validi nei nomi dei file
---

Questa app salva note, capitoli, romanzi e altri contenuti in file di testo. Abbiamo scelto il testo semplice per garantire un'ampia compatibilità e l'uso su piattaforme diverse. Così, anche se un giorno smetterai di usare l'app, potrai gestire e modificare facilmente i tuoi file con altre app e sistemi operativi.

## Caratteri non consentiti nei nomi dei file: `\/:*?"<>|`

Questi caratteri hanno funzioni speciali nei file system e in molti programmi di uso comune. Inserirli nel nome di un file può quindi impedire di crearlo, trovarlo o aprirlo in modo coerente su dispositivi diversi. Per esempio, `/` separa le cartelle in un percorso, mentre `\` è usato come separatore di percorso su alcuni sistemi e come carattere di escape in determinati formati di testo. Gli altri caratteri possono fungere da caratteri jolly, delimitatori o simboli di controllo. Per mantenere i tuoi file facilmente utilizzabili su più piattaforme, l'app non consente questi caratteri nei nomi.

## Perché un nome di file non può iniziare con `.` o `..`?

Android si basa sul kernel Linux. Nei percorsi in stile Linux, `.` indica la cartella corrente e `..` la cartella superiore. Inoltre, gli strumenti Linux e Android considerano generalmente nascosti i file e le cartelle i cui nomi iniziano con un punto. L'app impedisce di iniziare il nome con un punto per evitare confusione con gli elementi speciali dei percorsi e mantenere i file visibili e facili da trovare.
