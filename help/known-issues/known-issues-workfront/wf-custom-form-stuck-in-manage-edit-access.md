---
title: "Moduli personalizzati: Per modificare i campi, i moduli personalizzati con più oggetti richiedono l’accesso a Gestione o Modifica"
description: "Quando un utente crea un modulo con oggetti incrociati che consentono solo l’accesso a Gestione o Modifica e quindi lo rimuove, il modulo personalizzato continua a richiedere l’accesso a Gestisci o Modifica per modificare i campi. Non esiste alcuna indicazione visiva che i campi richiedano l’accesso a Gestione o Modifica e non è possibile reimpostare il modulo."
hidefromtoc: true
source-git-commit: be498327ea7bb2a49be0fc65e53806ddb217aa8c
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 2%

---


# Moduli personalizzati: I moduli personalizzati multioggetto richiedono [!UICONTROL Gestisci] o [!UICONTROL Modifica] accesso alla modifica dei campi

>[!NOTE]
>
>Questo problema è stato chiuso

Quando un utente crea un modulo con oggetti incrociati che consentono solo [!UICONTROL Gestisci] o [!UICONTROL Modifica] accedere e quindi rimuovere tale tipo di oggetto, il modulo personalizzato continua a richiedere [!UICONTROL Gestisci] o [!UICONTROL Modifica] accedere per modificare i campi. Non esiste alcuna indicazione visiva che i campi richiedano l’accesso a Gestione o Modifica e che non è possibile reimpostare il modulo.

**Soluzione alternativa**

1. Aggiungi al modulo un’interruzione di sezione con valori predefiniti, se viene compilata con.
2. Spostare l’interruzione di sezione nella parte superiore del modulo.
3. Salvare il modulo.
4. Rimuovere l’interruzione di sezione appena aggiunta e salvare nuovamente il modulo.

_Segnalato per la prima volta il 9° novembre 2022._

