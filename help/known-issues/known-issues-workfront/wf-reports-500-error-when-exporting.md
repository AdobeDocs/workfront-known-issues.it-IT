---
title: '“Rapporti: errore 500 durante l’esportazione di un rapporto”'
description: Quando un utente cerca di esportare un rapporto, l’esportazione non riesce e viene visualizzato l’errore 500.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: ht
source-wordcount: '70'
ht-degree: 100%

---

# Rapporti: errore 500 durante l’esportazione di un rapporto

>[!NOTE]
>
>Questo problema è stato risolto il venerdì 30 novembre 2023.

Quando un utente cerca di esportare un rapporto, l’esportazione non riesce e viene visualizzato il seguente errore:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Questo problema è stato segnalato nei rapporti che utilizzano un `valueexpression` per fare riferimento al testo della nota `lastNote`.

_Segnalato per la prima volta l’8 novembre 2023._
