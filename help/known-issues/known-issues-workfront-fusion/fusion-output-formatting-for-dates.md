---
title: '“Workfront Fusion: formattazione dell’output per le date”'
description: “Quando le date vengono generate come stringhe, la data può essere generata come una stringa UTC o ISO. Questo dipende dalla logica all’interno di un pannello di mappatura”.
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: ht
source-wordcount: '120'
ht-degree: 100%

---


# Workfront Fusion: formattazione dell’output per le date

Quando le date vengono generate come stringhe, la data può essere generata come una stringa UTC o ISO. Questo dipende dalla logica all’interno di un pannello di mappatura:

* se una data all’interno di una funzione è unita a una stringa, quest’ultima verrà generata nel formato **UTC**.
* Se la Data non è unita all’interno di una funzione, verrà generata come **stringa ISO**.

Per assicurarsi che gli output siano nel formato richiesto, i clienti devono utilizzare le funzioni `toString` (per ISO) o `formatDate`.
