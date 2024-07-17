---
title: "Workfront Fusion: formattazione per le date"
description: Quando le date vengono generate come stringhe, la data può essere generata come una stringa UTC o ISO. Questo dipende dalla logica all’interno di un pannello di mappatura.
hidefromtoc: true
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
source-git-commit: 7aba3a4ce3e0436a8fd9850197bc44da9dafe347
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 87%

---

# Workfront Fusion: formattazione dell’output per le date

Quando le date vengono generate come stringhe, la data può essere generata come una stringa UTC o ISO. Questo dipende dalla logica all’interno di un pannello di mappatura:

* se una data all’interno di una funzione è unita a una stringa, quest’ultima verrà generata nel formato **UTC**.
* Se la Data non è unita all’interno di una funzione, verrà generata come **stringa ISO**.

Per assicurarsi che gli output siano nel formato richiesto, i clienti devono utilizzare le funzioni `toString` (per ISO) o `formatDate`.
