---
title: "Report: errore 500 durante l’esportazione di un report"
description: '"Quando un utente tenta di esportare un rapporto, l’operazione ha esito negativo e viene visualizzato un errore. È disponibile una soluzione alternativa.”'
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 0dbb29f11088b5c963f7972f3ec9e64ee55d6263
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 16%

---


# Rapporti: errore 500 durante l’esportazione di un rapporto

Quando un utente tenta di esportare un rapporto, l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

500: impossibile richiamare &quot;com.attask.biz.Parameter.getDisplayType()&quot; perché &quot;parameter&quot; è null /attask/api-internal/report/export

Ciò si verifica quando il rapporto fa riferimento a un campo valuta personalizzato a livello di progetto.

**Soluzione alternativa**

Rimuovi la colonna che fa riferimento al campo della valuta personalizzata ed esporta nuovamente il rapporto.

_Segnalato per la prima volta il venerdì 4 aprile 2024._

