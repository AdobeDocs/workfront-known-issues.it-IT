---
title: "Report: errore 500 durante l’esportazione di un report"
description: "Quando un utente tenta di esportare un rapporto, l’esportazione non riesce e viene visualizzato l’errore 500."
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 8fcd13b3586664d7540e64fb855f7f84e6e7cdc7
workflow-type: tm+mt
source-wordcount: '59'
ht-degree: 0%

---


# Report: errore 500 durante l’esportazione di un report

Quando un utente cerca di esportare un rapporto, l’esportazione non riesce e viene visualizzato il seguente errore:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Questo problema è stato segnalato nei rapporti che utilizzano `valueexpression` per fare riferimento a `lastNote` testo della nota.

_Segnalato per la prima volta il 8 novembre 2023._
