---
title: 'Moduli personalizzati: i moduli personalizzati con più oggetti richiedono l’accesso Gestisci o Modifica per la modifica dei campi'
description: Quando un utente crea un modulo con più oggetti che consentono solo l’accesso Gestisci o Modifica e in seguito rimuove quel tipo di oggetto, il modulo personalizzato continua a richiedere l’accesso Gestisci o Modifica per la modifica dei campi. Non esiste alcuna indicazione visiva che i campi richiedano l’accesso Gestione o Modifica e non è possibile reimpostare il modulo in alcun modo.
feature: Custom Forms
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: d87de1f9-8e24-4c4d-aa4c-a403075091a1
    internal-label: Custom forms
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 92%
---
# Moduli personalizzati: i moduli personalizzati con più oggetti richiedono l’accesso [!UICONTROL Gestisci] o [!UICONTROL Modifica] per la modifica dei campi

<!--Won't fix, live for workaround-->

>[!NOTE]
>
>Questo problema è stato chiuso

Quando un utente crea un modulo con più oggetti che consentono solo l’accesso [!UICONTROL Gestisci] o [!UICONTROL Modifica] e in seguito rimuove quel tipo di oggetto, il modulo personalizzato continua a richiedere l’accesso [!UICONTROL Gestisci] o [!UICONTROL Modifica] per la modifica dei campi. Non esiste alcuna indicazione visiva che i campi richiedano l’accesso Gestione o Modifica e non è possibile reimpostare il modulo in alcun modo.

**Soluzione alternativa**

1. Aggiungere al modulo un’interruzione di sezione con valori predefiniti inseriti.
2. Spostare l’interruzione di sezione nella parte superiore del modulo.
3. Salvare il modulo.
4. Rimuovere l’interruzione di sezione appena aggiunta e salva nuovamente il modulo.

_Segnalato per la prima volta il giovedì 9 novembre 2022._
