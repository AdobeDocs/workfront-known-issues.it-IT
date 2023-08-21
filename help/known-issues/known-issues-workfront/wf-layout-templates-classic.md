---
title: "Modelli di layout: modelli di layout che causano incongruenze nei rapporti"
description: "I modelli di layout dell’esperienza Workfront classica non sono più disponibili nell’interfaccia di Workfront, ma possono comunque influire sui dati di Workfront. Questo può causare incoerenze nei campi interessati dai modelli di layout (ad esempio Condiviso con) nei rapporti o nelle dashboard."
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 045e2bd200aa2fffaf2e763a73eb8729517be197
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 0%

---


# Modelli di layout: modelli di layout che causano incoerenze nei rapporti

I modelli di layout dell’esperienza Workfront classica non sono più disponibili nell’interfaccia di Workfront, ma possono comunque influire sui dati di Workfront. Questo può causare incoerenze nei campi interessati dai modelli di layout (ad esempio Condiviso con) nei rapporti o nelle dashboard.

**Soluzione alternativa**

Elimina i modelli di layout Classic utilizzando una chiamata API. Devi aver effettuato l’accesso a Workfront.

>[!NOTE]
>
>Non è possibile eliminare i modelli di layout Globale e di sistema.

1. Individua il modello di layout da eliminare utilizzando la seguente chiamata API:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. Prendere nota dell&#39;ID del modello di layout che si desidera eliminare.
1. Individua l’ID sessione utilizzando la seguente chiamata API:
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >Non condividere mai il tuo ID sessione con nessuno.

1. Inserisci l’ID del modello di layout e l’ID della sessione nella seguente chiamata API:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. Incolla la chiamata API dal passaggio 4 nella barra URL del browser e premi Invio.

   Questo elimina il modello di layout.

