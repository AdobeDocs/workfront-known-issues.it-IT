---
title: 'Workfront Proof: errore 500 durante l’accesso a Workfront Proof tramite API o Workfront Fusion'
description: 'Quando un utente accede all’azione getAllProofs dell’API di bozza, il server Workfront Proof restituisce il messaggio: Errore interno del server 500'
feature: Workfront Proof
exl-id: 3c968354-58e2-43fc-8c27-2670683ac862
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 69%
---
# [!DNL Workfront Proof]: errore 500 durante l’accesso a [!DNL Workfront Proof] tramite API o [!DNL Workfront Fusion]

>[!NOTE]
>
>Il team di prodotto sta attualmente valutando la risoluzione di questo problema, che potrebbe richiedere alcuni miglioramenti. I miglioramenti dei prodotti vengono comunicati negli annunci relativi al prodotto e non con gli aggiornamenti di manutenzione.I miglioramenti delle funzionalità del prodotto vengono comunicati nella sezione Annunci sui prodotti e non tramite gli aggiornamenti di manutenzione.

<!--This article is on Proof and Fusion TOCs-->

Quando un utente accede all’azione [!UICONTROL `getAllProofs`] dell’API [!DNL Workfront Proof], il server restituisce il messaggio seguente:

[!UICONTROL Errore server interno 500]

Dato che [!DNL Workfront Fusion] utilizza l’API [!DNL Workfront Proof] per moduli [!DNL Workfront Proof], questo errore può essere restituito in un modulo, interrompendo uno scenario.

_Segnalato per la prima volta il sabato 28 aprile 2023._
