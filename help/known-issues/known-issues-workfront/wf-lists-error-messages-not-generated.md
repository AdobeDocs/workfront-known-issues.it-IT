---
title: '“Elenchi: gli errori di modifica in linea da parte dell’utente non generano messaggi di errore”'
description: “Quando un utente modifica in linea un oggetto e compie un errore che dovrebbe generare un messaggio di errore, non viene visualizzato alcun messaggio di errore. L’errore stesso non viene salvato in Workfront, pertanto i dati non vengono interessati, ma l’assenza di un messaggio di errore può causare confusione.”
hidefromtoc: true
source-git-commit: 2951a566384274e5f32544dd8be1872f3850af94
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 96%

---


# Elenchi: gli errori di modifica in linea da parte dell’utente non generano messaggi di errore

>[!NOTE]
>
>Questo problema è stato risolto il 1° dicembre 2022.

Quando un utente modifica in linea un oggetto e compie un errore che dovrebbe generare un messaggio di errore, non viene visualizzato alcun messaggio di errore. L’errore stesso non viene salvato in Workfront, pertanto i dati non vengono interessati, ma l’assenza di un messaggio di errore può causare confusione.

Questo problema è stato segnalato nelle seguenti situazioni:

* Predecessori: viene creato un ciclo predecessore, ad esempio con l’assegnazione di un’attività a se stessa
* Date: viene impostata una data impossibile, ad esempio una data di completamento anteriore alla data di inizio o successiva alla data di completamento del progetto

_Segnalato per la prima volta il 26 ottobre 2022._

