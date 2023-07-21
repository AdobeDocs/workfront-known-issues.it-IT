---
title: "Moduli personalizzati: impossibile utilizzare il campo nel calcolo se il nome del campo contiene virgolette o un apostrofo"
description: Quando un utente crea un’espressione di campo calcolato e tenta di includere un campo typeahead con un nome con un apostrofo o virgolette, il calcolo non viene accettato e l’utente visualizza il messaggio Questa è un’espressione personalizzata non valida. Riprovare.
hidefromtoc: true
feature: Custom Forms
exl-id: 7caa6b7a-87ab-40e8-aea2-05b41583a375
source-git-commit: 2a41264d6f477f51eaeda6ae3675b1a6d816249c
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 59%

---

# Moduli personalizzati: impossibile utilizzare il campo nel calcolo se il nome del campo contiene apostrofi o virgolette

>[!NOTE]
>
>Questo problema è stato risolto il 2 marzo 2023.

Quando un utente crea un’espressione di campo calcolato e tenta di includere un campo typeahead con un nome con un `'` o `"`, il calcolo non viene accettato e l’utente visualizza il messaggio “[!UICONTROL Questa è un’espressione personalizzata non valida. Riprovare”.]

Questo problema esiste solo con i campi typeahead. Campi di testo con `'` o `"` nel nome possono essere utilizzati nelle espressioni di campo calcolato senza alcun problema.

_Segnalato per la prima volta il 10° novembre 2022._
