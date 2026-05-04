---
title: 'Bozze: viene creata una nuova fase perché la scadenza non può corrispondere a quella della fase esistente'
description: Durante la creazione di una bozza è possibile impostare la scadenza con incrementi d 15 minuti (10:00, 10:15, 10:30, 20:45, ecc.). Tuttavia, quando un utente viene aggiunto a una bozza dopo la sua creazione, la scadenza può essere impostata solo con incrementi di 30 minuti (10:00, 10:30, 11:00, ecc.).
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 44%

---

# Bozze: viene creata una nuova fase perché la scadenza non può corrispondere a quella della fase esistente

<!--Requested article-->

Quando viene creata una nuova bozza, la scadenza può essere impostata con un incremento di 15 minuti (10:00, 10:15, 10:30, 20:45, ecc.). Tuttavia, quando un utente viene aggiunto a una bozza dopo la sua creazione, la scadenza può essere impostata solo con incrementi di 30 minuti (10:00, 10:30, 11:00, ecc.). Pertanto, non è possibile aggiungere il nuovo utente a una fase con scadenza che termina in :15 o :45, perché le scadenze non corrispondono. Il nuovo utente viene quindi aggiunto a una nuova fase con scadenza impostata in incrementi di 30 minuti.

**Soluzione alternativa**:

* Se selezioni una scadenza per una nuova bozza, imposta la scadenza su un orario che termina in :00 o :30 (10:00, 10:30, 11:00, ecc.).
* Se la scadenza viene impostata automaticamente al momento della creazione della bozza, impostare manualmente la scadenza della bozza su un&#39;ora che termina in :00 o :30 (10:00, 10:30, 11:00, ecc.).
