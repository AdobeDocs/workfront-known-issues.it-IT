---
title: "Workfront Fusion: formattazione di output per le date"
description: "Quando le Date vengono generate come Stringhe, la data può essere generata come una stringa UTC o ISO. Questo dipende dalla logica all’interno di un pannello di mappatura."
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# Workfront Fusion: formattazione di output per le date

Quando le Date vengono generate come Stringhe, la data può essere generata come una stringa UTC o ISO. Questo dipende dalla logica all’interno di un pannello di mappatura:

* Se una Data all’interno di una funzione è unita a una stringa, la stringa verrà generata in **UTC** formato.
* Se la Data non è unita in join all’interno di una funzione, verrà generata come **Stringa ISO**.

I clienti devono utilizzare `toString` (per ISO) o `formatDate` funzioni per garantire che le uscite siano nel formato richiesto.
