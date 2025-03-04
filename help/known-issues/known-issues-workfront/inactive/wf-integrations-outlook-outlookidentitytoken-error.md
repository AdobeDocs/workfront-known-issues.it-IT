---
title: 'Integrazioni: errore outlookIdentityToken durante l’utilizzo di Workfront per Outlook'
description: Quando un utente utilizza l’integrazione Workfront for Outlook, potrebbe visualizzare un errore.
hidefromtoc: true
feature: Workfront Integrations and Apps
source-git-commit: 19d438b3a368b076aa03a89fe6648ec4b225225f
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# Integrazioni: errore outlookIdentityToken durante l’utilizzo di Workfront per Outlook

Quando un utente utilizza l’integrazione Workfront for Outlook, potrebbe visualizzare il seguente errore:

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Soluzione alternativa**


Per risolvere questo errore, devi abilitare i token legacy di Microsoft 365 per la tua organizzazione. Poiché questo deve essere fatto in Microsoft 365, Workfront non può abilitare questi token per la tua organizzazione.

Per istruzioni sull&#39;abilitazione dei token legacy di Microsoft 365, consulta [Attivare o disattivare i token legacy di Exchange Online](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) nella documentazione di Microsoft.

Per ulteriori informazioni sui token legacy, vedere [È possibile riattivare i token legacy di Exchange Online?](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) nella documentazione di Microsoft.


_Segnalato per la prima volta il giovedì 3 marzo 2025, 2024._
