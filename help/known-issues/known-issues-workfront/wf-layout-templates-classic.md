---
title: '“Modelli layout: i modelli layout causano incongruenze nei rapporti”'
description: “I modelli layout dell’esperienza Workfront classica non sono più disponibili nell’interfaccia di Workfront, ma possono comunque influire sui dati di Workfront. Questo può causare incongruenze nei campi interessati dai modelli stessi (ad esempio Condiviso con), nei rapporti o nelle dashboard.”
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 045e2bd200aa2fffaf2e763a73eb8729517be197
workflow-type: ht
source-wordcount: '195'
ht-degree: 100%

---


# Modelli layout: i modelli layout causano incongruenze nei rapporti

I modelli layout dell’esperienza Workfront classica non sono più disponibili nell’interfaccia di Workfront, ma possono comunque influire sui dati di Workfront. Questo può causare incongruenze nei campi interessati dai modelli stessi (ad esempio Condiviso con), nei rapporti o nelle dashboard.

**Soluzione alternativa**

Elimina i modelli layout classici utilizzando una chiamata API. È necessario aver effettuato l’accesso a Workfront.

>[!NOTE]
>
>Non è possibile eliminare i modelli layout di sistema e globali.

1. Individua il modello layout da eliminare utilizzando la seguente chiamata API:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. Prendi nota dell’ID del modello layout che desideri eliminare.
1. Individua l’ID sessione utilizzando la seguente chiamata API:
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >Non condividere mai il tuo ID sessione con nessuno.

1. Inserisci l’ID del modello layout e l’ID sessione nella seguente chiamata API:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. Incolla la chiamata API dal passaggio 4 nella barra degli URL del browser e premi Invio.

   Questa azione eliminerà il modello layout.

