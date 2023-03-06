---
title: '“Moduli personalizzati: impossibile utilizzare il campo nel calcolo se il nome del campo contiene virgolette o un apostrofo”'
description: “Quando un utente sta creando un’espressione di campo calcolato e tenta di includere un campo typeahead con un nome con un apostrofo o virgolette, il calcolo non viene accettato e l’utente visualizza il messaggio Questa è un’espressione personalizzata non valida. Riprovare”.
hidefromtoc: true
source-git-commit: 3307a9be28555d0b9561e8ae96e3667cb1fee711
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 100%

---


# Moduli personalizzati: impossibile utilizzare il campo nel calcolo se il nome del campo contiene apostrofi o virgolette

>[!NOTE]
>
>Questo problema è stato risolto il martedì 2 marzo 2023.

Quando un utente crea un’espressione di campo calcolato e tenta di includere un campo typeahead con un nome con un `'` o `"`, il calcolo non viene accettato e l’utente visualizza il messaggio “[!UICONTROL Questa è un’espressione personalizzata non valida. Riprovare”.]

Questo problema esiste solo con i campi typeahead. Campi di testo con `'` o `"` nel nome possono essere utilizzati nelle espressioni di campo calcolato senza alcun problema.

_Segnalato per la prima volta il 10° novembre 2022._

