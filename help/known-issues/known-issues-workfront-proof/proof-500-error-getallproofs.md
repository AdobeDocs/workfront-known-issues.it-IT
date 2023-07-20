---
title: '“Workfront Proof: errore 500 durante l’accesso a Workfront Proof tramite API o Workfront Fusion”'
description: '“Quando un utente accede all’azione getAllProofs dell’API Proof, il server Workfront Proof restituisce il messaggio: errore server interno 500”'
hidefromtoc: true
feature: Workfront Proof
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: tm+mt
source-wordcount: '102'
ht-degree: 100%

---


# [!DNL Workfront Proof]: errore 500 durante l’accesso a [!DNL Workfront Proof] tramite API o [!DNL Workfront Fusion]

>[!NOTE]
>
>Il team di prodotto sta attualmente valutando la risoluzione di questo problema, che potrebbe richiedere alcuni miglioramenti. I miglioramenti dei prodotti vengono comunicati negli annunci relativi al prodotto e non con gli aggiornamenti di manutenzione.I miglioramenti delle funzionalità del prodotto vengono comunicati nella sezione Annunci sui prodotti e non tramite gli aggiornamenti di manutenzione.

<!--This article is on Proof and Fusion TOCs-->

Quando un utente accede all’azione [!UICONTROL `getAllProofs`] dell’API [!DNL Workfront Proof], il server restituisce il messaggio seguente:

[!UICONTROL Errore server interno 500]

Dato che [!DNL Workfront Fusion] utilizza l’API [!DNL Workfront Proof] per moduli [!DNL Workfront Proof], questo errore può essere restituito in un modulo, interrompendo uno scenario.

_Segnalato per la prima volta il 28 aprile 2023._

