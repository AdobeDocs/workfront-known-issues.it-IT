---
title: 'Bozze: viene creata una nuova fase perché la scadenza non può corrispondere a quella della fase esistente'
description: Durante la creazione di una bozza è possibile impostare la scadenza con incrementi d 15 minuti (10:00, 10:15, 10:30, 20:45, ecc.). Tuttavia, quando un utente viene aggiunto a una bozza dopo la sua creazione, la scadenza può essere impostata solo con incrementi di 30 minuti (10:00, 10:30, 11:00, ecc.).
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '243'
ht-degree: 64%
---
# Bozze: viene creata una nuova fase perché la scadenza non può corrispondere a quella della fase esistente

<!--Requested article-->

Durante la creazione di una bozza è possibile impostare la scadenza con incrementi d 15 minuti (10:00, 10:15, 10:30, 20:45, ecc.). Tuttavia, quando un utente viene aggiunto a una bozza dopo la sua creazione, la scadenza può essere impostata solo con incrementi di 30 minuti (10:00, 10:30, 11:00, ecc.). Pertanto, il nuovo utente non può essere aggiunto a una fase con una scadenza che termina in :15 o :45, perché le scadenze non possono corrispondere. Il nuovo utente viene quindi aggiunto a una nuova fase con scadenza impostata in incrementi di 30 minuti.

**Soluzione alternativa**:

* Se selezioni una scadenza per una nuova bozza, imposta la scadenza su un orario che termina in :00 o :30 (10:00, 10:30, 11:00, ecc.).
* Se la scadenza viene impostata automaticamente al momento della creazione della bozza, impostala manualmente su un orario che termina in :00 o :30 (10:00, 10:30, 11:00, ecc.).
