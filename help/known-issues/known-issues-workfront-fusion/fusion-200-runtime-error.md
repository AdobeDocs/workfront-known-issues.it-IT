---
title: '“Workfront Fusion: RuntimeError con risposta 200 dal modulo Workfront”'
description: Un modulo Workfront può restituire una risposta “RuntimeError [200]”. Il valore 200 implica una risposta corretta, ma l’errore mostra che la richiesta non è riuscita.
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: d88a785bb980ad4dcbb5ccb6b1b1bfb0cb61a161
workflow-type: tm+mt
source-wordcount: '96'
ht-degree: 100%

---

# Workfront Fusion: RuntimeError con risposta 200 dal modulo Workfront

>[!NOTE]
>
>Questo problema è stato risolto il venerdì 25 luglio 2024.

Un modulo Workfront può restituire una risposta `RuntimeError [200]`. Il valore 200 implica una risposta corretta, ma l’errore mostra che la richiesta non è riuscita.

Ciò può verificarsi se la risposta è estremamente lunga. I dati vengono restituiti a Fusion, ma non possono essere elaborati.

_Segnalato per la prima volta il giovedì 3 gennaio 2024._
