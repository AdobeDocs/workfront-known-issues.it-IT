---
title: '“Bozze: viene creata una nuova fase perché la scadenza non può corrispondere alla scadenza della fase esistente”'
description: Durante la creazione di una bozza è possibile impostare la scadenza con incrementi d 15 minuti (10:00, 10:15, 10:30, 20:45, ecc.). Tuttavia, quando un utente viene aggiunto a una bozza dopo la sua creazione, la scadenza può essere impostata solo con incrementi di 30 minuti (10:00, 10:30, 11:00, ecc.).
exl-id: b86c1c83-c647-4762-bc13-9687a7dada78
hidefromtoc: true
source-git-commit: 993b46816bed20ad7e75b7e0719f4b3b5442cabc
workflow-type: ht
source-wordcount: '197'
ht-degree: 100%

---

# Bozze: viene creata una nuova fase perché la scadenza non può corrispondere a quella della fase esistente

>[!NOTE]
>
>Questo problema è stato risolto.

Durante la creazione di una bozza è possibile impostare la scadenza con incrementi d 15 minuti (10:00, 10:15, 10:30, 20:45, ecc.). Tuttavia, quando un utente viene aggiunto a una bozza dopo la sua creazione, la scadenza può essere impostata solo con incrementi di 30 minuti (10:00, 10:30, 11:00, ecc.). Pertanto, il nuovo utente non può essere aggiunto in una fase che termina alle :15 o :45, perché le scadenze non possono coincidere. Il nuovo utente viene quindi aggiunto a una nuova fase con scadenza impostata in incrementi di 30 minuti.

**Soluzione alternativa**:

* Quando selezioni una scadenza per una nuova bozza, scegli un orario che termina con :00 o :30 (10:00, 10:30, 11:00, ecc.).
* Se la scadenza viene impostata automaticamente al momento della creazione della bozza, scegli manualmente un orario che termina in :00 o :30 (10:00, 10:30, 11:00, ecc.).
