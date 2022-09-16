---
title: "Prove: Nuova fase creata perché la scadenza non può corrispondere alla scadenza della fase esistente"
description: Quando viene creata una nuova bozza, la scadenza può essere impostata in un incremento di 15 minuti (10:00, 10:15, 10:30, 20:45, ecc.). Tuttavia, quando un utente viene aggiunto a una bozza dopo la creazione della bozza, la scadenza può essere impostata solo con incrementi di 30 minuti (10:00, 10:30, 11:00, ecc.).
exl-id: b86c1c83-c647-4762-bc13-9687a7dada78
hidefromtoc: true
source-git-commit: 993b46816bed20ad7e75b7e0719f4b3b5442cabc
workflow-type: tm+mt
source-wordcount: '197'
ht-degree: 0%

---

# Prove: Nuova fase creata perché la scadenza non può corrispondere alla scadenza della fase esistente

>[!NOTE]
>
>Questo problema è stato risolto.

Quando viene creata una nuova bozza, la scadenza può essere impostata in un incremento di 15 minuti (10:00, 10:15, 10:30, 20:45, ecc.). Tuttavia, quando un utente viene aggiunto a una bozza dopo la creazione della bozza, la scadenza può essere impostata solo con incrementi di 30 minuti (10:00, 10:30, 11:00, ecc.). Pertanto, il nuovo utente non può essere aggiunto a uno stadio con una scadenza che termina con :15 o :45, perché le scadenze non possono essere soddisfatte. Al contrario, il nuovo utente viene aggiunto a una nuova fase, con una scadenza impostata in incrementi di 30 minuti.

**Soluzione alternativa**:

* Se selezioni una scadenza per una nuova bozza, imposta la scadenza su un’ora che termina con :00 o :30 (10:00, 10:30, 11:00, ecc.).
* Se la scadenza viene impostata automaticamente al momento della creazione della bozza, imposta manualmente la scadenza della bozza su un&#39;ora che termina in :00 o :30 (10:00, 10:30, 11:00, ecc.).
