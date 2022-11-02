---
title: "Elenchi: Gli errori di modifica in linea per utente non causano messaggi di errore"
description: "Quando un utente modifica in linea un oggetto e compie un errore che dovrebbe creare un messaggio di errore, non viene visualizzato alcun messaggio di errore. L’errore stesso non viene salvato in Workfront, pertanto i dati non vengono interessati, ma la mancanza di un messaggio di errore può causare confusione."
hidefromtoc: true
source-git-commit: ed5bd591f4be66631dba19d666b7d280eda1e1ab
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 2%

---


# Elenchi: Gli errori di modifica in linea per utente non causano messaggi di errore

Quando un utente modifica in linea un oggetto ed esegue un errore che dovrebbe creare un messaggio di errore, non viene visualizzato alcun messaggio di errore. L’errore stesso non viene salvato in Workfront, pertanto i dati non vengono interessati, ma la mancanza di un messaggio di errore può causare confusione.

Questo è stato segnalato per le seguenti situazioni:

* Predecessori: Viene creato un ciclo predecessore, ad esempio l&#39;assegnazione di un&#39;attività a se stessa
* Date: Viene impostata una data impossibile, ad esempio una data di completamento precedente alla data di inizio o successiva alla data di completamento del progetto

_Segnalato per la prima volta il 26 ottobre 2022._

