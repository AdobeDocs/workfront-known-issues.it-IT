---
title: '“Bozze: viene creata una nuova fase perché la scadenza non può corrispondere alla scadenza della fase esistente”'
description: Durante la creazione di una bozza è possibile impostare la scadenza con incrementi d 15 minuti (10:00, 10:15, 10:30, 20:45, ecc.). Tuttavia, quando un utente viene aggiunto a una bozza dopo la sua creazione, la scadenza può essere impostata solo con incrementi di 30 minuti (10:00, 10:30, 11:00, ecc.).
hidefromtoc: true
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: tm+mt
source-wordcount: '223'
ht-degree: 100%

---

# Bozze: viene creata una nuova fase perché la scadenza non può corrispondere a quella della fase esistente

<!--Requested article-->

Durante la creazione di una bozza è possibile impostare la scadenza con incrementi d 15 minuti (10:00, 10:15, 10:30, 20:45, ecc.). Tuttavia, quando un utente viene aggiunto a una bozza dopo la sua creazione, la scadenza può essere impostata solo con incrementi di 30 minuti (10:00, 10:30, 11:00, ecc.). Pertanto, il nuovo utente non può essere aggiunto in una fase che termina alle :15 o :45, perché le scadenze non possono coincidere. Il nuovo utente viene quindi aggiunto a una nuova fase con scadenza impostata in incrementi di 30 minuti.

**Soluzione alternativa**:

* Quando selezioni una scadenza per una nuova bozza, scegli un orario che termina con :00 o :30 (10:00, 10:30, 11:00, ecc.).
* Se la scadenza viene impostata automaticamente al momento della creazione della bozza, scegli manualmente un orario che termina in :00 o :30 (10:00, 10:30, 11:00, ecc.).
