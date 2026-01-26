---
title: 'Utenti: il badge “In attesa di approvazione” viene visualizzato per nuovi utenti'
description: I nuovi utenti in Workfront possono essere visualizzati nell’elenco di utenti con il badge “In attesa di approvazione". Il badge persiste per più di qualche minuto ed è visibile anche dopo che si aggiorna la pagina.
hidefromtoc: true
feature: People Teams and Groups
exl-id: 27db1155-f6aa-465d-a42b-1147cf5431e1
source-git-commit: 39a085b629d6d2afc5a198e47ca639d2bb431b0d
workflow-type: ht
source-wordcount: '245'
ht-degree: 100%

---

# Utenti: il badge “In attesa di approvazione” viene visualizzato per nuovi utenti

>[!NOTE]
>
>Questo problema può essere presente nelle organizzazioni che sono state migrate ad Adobe Admin Console.

I nuovi utenti in Workfront possono essere visualizzati nell’elenco utenti con il badge “Approvazione in sospeso”. Il badge persiste per più di qualche minuto ed è visibile anche dopo che si aggiorna la pagina.

Questo problema si aggrava quando gli utenti vengono caricati in batch di grandi dimensioni, ad esempio da un foglio di calcolo o da un Kick-Start di Workfront.

Il comportamento previsto prevede che il badge scompaia dopo pochi minuti e non sia più visibile una volta aggiornata la pagina.

## Soluzioni alternative

Questo si verifica quando gli utenti aggiunti a Workfront non vengono sincronizzati con Adobe Admin Console.

Consigliamo le seguenti soluzioni alternative:

### Risolvere i singoli utenti

Puoi risolvere singoli utenti nell’elenco Utenti.

1. Seleziona uno o più utenti nell’elenco Utenti.
1. Fai clic sul menu con i tre punti nell’intestazione dell’elenco.
1. Seleziona **Approva**.
1. Dopo alcuni minuti, aggiorna la pagina.

### Risolvere utenti aggiunti in un batch di grandi dimensioni

Per risolvere gli utenti aggiunti in un batch di grandi dimensioni, puoi aggiungere direttamente il batch di utenti ad Adobe Admin Console.

Per istruzioni, consulta [Gestire più utenti   Caricamento in blocco di CSV](https://helpx.adobe.com/it/enterprise/using/bulk-upload-users.html) nella documentazione di Adobe.


_Segnalato per la prima volta l’8 maggio 2025._
