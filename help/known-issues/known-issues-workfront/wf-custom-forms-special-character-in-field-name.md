---
title: '“Moduli personalizzati: impossibile utilizzare il campo nel calcolo se il nome del campo contiene virgolette o un apostrofo”'
description: “Quando un utente sta creando un’espressione di campo calcolato e tenta di includere un campo typeahead con un nome con un apostrofo o virgolette, il calcolo non viene accettato e l’utente visualizza il messaggio Questa è un’espressione personalizzata non valida. Riprovare”.
hidefromtoc: true
source-git-commit: 0c260518bc0b268d734e309bef11b613fee90172
workflow-type: ht
source-wordcount: '148'
ht-degree: 100%

---


# Moduli personalizzati: impossibile utilizzare il campo nel calcolo se il nome del campo contiene apostrofi o virgolette

Quando un utente crea un’espressione di campo calcolato e tenta di includere un campo typeahead con un nome con un `'` o `"`, il calcolo non viene accettato e l’utente visualizza il messaggio “[!UICONTROL Questa è un’espressione personalizzata non valida. Riprovare”.]

Questo problema esiste solo con i campi typeahead. Campi di testo con `'` o `"` nel nome possono essere utilizzati nelle espressioni di campo calcolato senza alcun problema.

_Segnalato per la prima volta il 10° novembre 2022._

