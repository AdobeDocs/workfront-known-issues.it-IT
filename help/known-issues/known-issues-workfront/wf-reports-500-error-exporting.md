---
title: '“Rapporti: errore 500 durante l’esportazione di un rapporto”'
description: Quando un utente tenta di esportare un rapporto, l’operazione ha esito negativo e viene visualizzato un messaggio di errore. È disponibile una soluzione alternativa.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 100%

---

# Rapporti: errore 500 durante l’esportazione di un rapporto

>[!NOTE]
>
>Questo problema è stato risolto il sabato 5 aprile 2024.

Quando un utente tenta di esportare un rapporto, l’operazione ha esito negativo e viene visualizzato il seguente errore:

500: impossibile richiamare &quot;com.attask.biz.Parameter.getDisplayType()&quot; perché “parametro” è null /attask/api-internal/report/export

Ciò si verifica quando il rapporto fa riferimento a un campo valuta personalizzato a livello di progetto.

**Soluzione alternativa**

Rimuovi la colonna che fa riferimento al campo della valuta personalizzata ed esporta nuovamente il rapporto.

_Segnalato per la prima volta il venerdì 4 aprile 2024._
