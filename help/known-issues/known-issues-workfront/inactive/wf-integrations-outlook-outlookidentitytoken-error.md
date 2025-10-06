---
title: 'Integrazioni: errore outlookIdentityToken durante l’utilizzo di Workfront per Outlook'
description: Quando un utente utilizza l’integrazione Workfront per Outlook, potrebbe visualizzare un errore.
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: 87c56abf4a5020632877263329f1455bbf4cc7f3
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 87%

---

# Integrazioni: errore outlookIdentityToken durante l’utilizzo di Workfront per Outlook

>[!NOTE]
>
>L&#39;integrazione di Workfront for Outlook non è più disponibile. Questo articolo verrà rimosso a breve.

Quando un utente utilizza l’integrazione Workfront per Outlook, potrebbe visualizzare il seguente errore:

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Soluzione alternativa**


Per risolvere questo errore, è necessario abilitare i token legacy di Microsoft 365 per l’organizzazione. Poiché questo deve essere fatto in Microsoft 365, Workfront non può abilitare questi token per l’organizzazione.

Per istruzioni sull’abilitazione dei token legacy di Microsoft 365, consulta [Attivare o disattivare i token legacy di Exchange Online](https://learn.microsoft.com/it-it/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) nella documentazione di Microsoft.

Per ulteriori informazioni sui token legacy, consulta [È possibile riattivare i token legacy di Exchange Online?](https://learn.microsoft.com/it-it/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) nella documentazione di Microsoft.


_Segnalato per la prima volta il 3 marzo 2025._
