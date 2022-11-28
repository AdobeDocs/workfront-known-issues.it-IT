---
title: "Moduli personalizzati: Impossibile utilizzare il campo nel calcolo se il nome del campo contiene virgolette o un apostrofo"
description: "Quando un utente sta creando un'espressione di campo calcolata e tenta di includere un campo typeahead con un nome con un apostrofo o virgolette, il calcolo non viene accettato e l'utente visualizza il messaggio Si tratta di un'espressione personalizzata non valida, riprova."
hidefromtoc: true
source-git-commit: 0c260518bc0b268d734e309bef11b613fee90172
workflow-type: tm+mt
source-wordcount: '148'
ht-degree: 2%

---


# Moduli personalizzati: Impossibile utilizzare il campo nel calcolo se il nome del campo contiene apostrofi o virgolette

Quando un utente crea un&#39;espressione di campo calcolata e tenta di includere un campo typeahead con un nome con un nome `'` o `"`, il calcolo non viene accettato e l&#39;utente visualizza il messaggio &quot;[!UICONTROL Espressione personalizzata non valida. Riprovare.]&quot;

Questo problema esiste solo con i campi typeahead. Campi di testo con `'` o `"` nel nome può essere utilizzato nelle espressioni campo calcolate senza alcun problema.

_Segnalato per la prima volta il 10° novembre 2022._

