---
title: '“Workfront Fusion: impossibile creare una connessione a Google”'
description: Quando un utente tenta di creare una connessione in uno dei connettori Google (ad esempio Google Sheets o Google Drive), la connessione non viene creata e l’utente visualizza vari messaggi di errore.
hidefromtoc: true
exl-id: 068793be-63e5-40b5-bf10-c01d76c1b6e7
source-git-commit: dd093aff6103901898c561c9f6f544c1648682a3
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# [!DNL Workfront Fusion]: impossibile creare la connessione a [!DNL Google]

>[!NOTE]
>
>Questo problema è stato risolto il 9 gennaio 2023.

Quando un utente tenta di creare una connessione in uno dei connettori [!DNL Google] (come [!DNL Google Sheets] o [!DNL Google Drive]), viene visualizzata una finestra con il seguente errore:

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

Quando l’utente chiude questa finestra, la connessione non riesce e viene visualizzato il seguente errore all’interno di [!DNL Fusion]:

“[!UICONTROL Errore: richiesta non riuscita a causa di un errore di una richiesta precedente. Nessun token di accesso specificato]”.

_Segnalato per la prima volta il 21 novembre 2022._
