---
title: 'Utenti: il badge di approvazione in attesa viene visualizzato sui nuovi utenti'
description: I nuovi utenti in Workfront possono essere visualizzati nell’elenco di utenti con un badge di approvazione In attesa. Il badge persiste per più di qualche minuto ed è ancora presente quando la pagina viene aggiornata.
hidefromtoc: true
feature: People Teams and Groups
source-git-commit: 9c46f9006fa25481a012619a16d627e16f23c15e
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 1%

---


# Utenti: il badge &quot;In attesa di approvazione&quot; viene visualizzato sui nuovi utenti

>[!NOTE]
>
>Questo problema può essere presente nelle organizzazioni che sono state migrate a Adobe Admin Console.

I nuovi utenti in Workfront possono visualizzare nell’elenco utenti con un badge &quot;In attesa di approvazione&quot;. Il badge persiste per più di qualche minuto ed è ancora presente quando la pagina viene aggiornata.

Questo problema si aggrava quando gli utenti vengono caricati in batch di grandi dimensioni, ad esempio da un foglio di calcolo o da un Kick-Start di Workfront.

Il comportamento previsto prevede che il badge scompaia dopo pochi minuti e non sia presente quando la pagina viene aggiornata.

## Soluzioni alternative

Ciò si verifica quando gli utenti aggiunti a Workfront non eseguono la sincronizzazione con Adobe Admin Console.

È consigliabile adottare le seguenti soluzioni:

### Risolvi singoli utenti

È possibile risolvere singoli utenti nell&#39;elenco Utenti.

1. Selezionare uno o più utenti nell&#39;elenco Utenti.
1. Fai clic sul menu a tre punti nell’intestazione dell’elenco.
1. Seleziona **Approva**.
1. Dopo alcuni minuti, aggiorna la pagina.

### Risolvi gli utenti aggiunti in un batch di grandi dimensioni

Per risolvere gli utenti che sono stati aggiunti in un batch di grandi dimensioni, puoi aggiungere direttamente il batch di utenti a Adobe Admin Console.

Per istruzioni, vedere [Gestione di più utenti | Caricamento CSV in blocco](https://helpx.adobe.com/it/enterprise/using/bulk-upload-users.html) nella documentazione di Adobe.


_Segnalato per la prima volta il venerdì 8 maggio 2025._
