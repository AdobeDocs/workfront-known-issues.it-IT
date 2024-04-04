---
title: "Workfront Fusion: RuntimeError con risposta 200 dal modulo Workfront"
description: Un modulo Workfront può restituire una risposta "RuntimeError [200]". Il valore 200 implica una risposta corretta, ma l’errore mostra che la richiesta non è riuscita.
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: 50f79121e0b027c3f0283cd43d19c885dde8268b
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 78%

---

# Workfront Fusion: RuntimeError con risposta 200 dal modulo Workfront

<!--

>[!NOTE]
>
>This issue was fixed on March 28, 2024.

-->

Un modulo Workfront può restituire una risposta `RuntimeError [200]`. Il valore 200 implica una risposta corretta, ma l’errore mostra che la richiesta non è riuscita.

Ciò può verificarsi se la risposta è estremamente lunga. I dati vengono restituiti a Fusion, ma non possono essere elaborati.

_Segnalato per la prima volta il giovedì 3 gennaio 2024._
