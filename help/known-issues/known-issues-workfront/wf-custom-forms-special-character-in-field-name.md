---
title: '“Moduli personalizzati: impossibile utilizzare il campo nel calcolo se il nome del campo contiene virgolette o un apostrofo”'
description: “Quando un utente sta creando un’espressione di campo calcolato e tenta di includere un campo typeahead con un nome con un apostrofo o virgolette, il calcolo non viene accettato e l’utente visualizza il messaggio Questa è un’espressione personalizzata non valida. Riprovare”.
hidefromtoc: true
source-git-commit: 254339d1baa9d8d7825e851aeafc9b27b1a1b669
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 100%

---


# Moduli personalizzati: impossibile utilizzare il campo nel calcolo se il nome del campo contiene apostrofi o virgolette

>[!NOTE]
>
>Il team di prodotto sta attualmente valutando la risoluzione di questo problema, che potrebbe richiedere alcuni miglioramenti. I miglioramenti dei prodotti vengono comunicati negli annunci relativi al prodotto e non con gli aggiornamenti di manutenzione.I miglioramenti delle funzionalità del prodotto vengono comunicati nella sezione Annunci sui prodotti e non tramite gli aggiornamenti di manutenzione.

Quando un utente crea un’espressione di campo calcolato e tenta di includere un campo typeahead con un nome con un `'` o `"`, il calcolo non viene accettato e l’utente visualizza il messaggio “[!UICONTROL Questa è un’espressione personalizzata non valida. Riprovare”.]

Questo problema esiste solo con i campi typeahead. Campi di testo con `'` o `"` nel nome possono essere utilizzati nelle espressioni di campo calcolato senza alcun problema.

_Segnalato per la prima volta il 10° novembre 2022._

