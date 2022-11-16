---
title: '“Elenchi: gli errori di modifica in linea da parte dell’utente non generano messaggi di errore”'
description: “Quando un utente modifica in linea un oggetto e compie un errore che dovrebbe generare un messaggio di errore, non viene visualizzato alcun messaggio di errore. L’errore stesso non viene salvato in Workfront, pertanto i dati non vengono interessati, ma l’assenza di un messaggio di errore può causare confusione.”
hidefromtoc: true
source-git-commit: ed5bd591f4be66631dba19d666b7d280eda1e1ab
workflow-type: ht
source-wordcount: '165'
ht-degree: 100%

---


# Elenchi: gli errori di modifica in linea da parte dell’utente non generano messaggi di errore

Quando un utente modifica in linea un oggetto e compie un errore che dovrebbe generare un messaggio di errore, non viene visualizzato alcun messaggio di errore. L’errore stesso non viene salvato in Workfront, pertanto i dati non vengono interessati, ma l’assenza di un messaggio di errore può causare confusione.

Questo problema è stato segnalato nelle seguenti situazioni:

* Predecessori: viene creato un ciclo predecessore, ad esempio con l’assegnazione di un’attività a se stessa
* Date: viene impostata una data impossibile, ad esempio una data di completamento anteriore alla data di inizio o successiva alla data di completamento del progetto

_Segnalato per la prima volta il 26 ottobre 2022._

