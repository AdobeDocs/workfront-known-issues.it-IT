---
title: 'Workfront Fusion: formattazione dell’output per le date'
description: Quando le date vengono generate come stringhe, la data può essere generata come una stringa UTC o ISO. Questo dipende dalla logica all’interno di un pannello di mappatura.
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 92%
---
# Workfront Fusion: formattazione dell’output per le date

Quando le date vengono generate come stringhe, la data può essere generata come una stringa UTC o ISO. Questo dipende dalla logica all’interno di un pannello di mappatura:

* se una data all’interno di una funzione è unita a una stringa, quest’ultima verrà generata nel formato **UTC**.
* Se la Data non è unita all’interno di una funzione, verrà generata come **stringa ISO**.

Per assicurarsi che gli output siano nel formato richiesto, i clienti devono utilizzare le funzioni `toString` (per ISO) o `formatDate`.
