---
title: '“Approvazioni: la delega di approvazione è impostata per un numero di giorni non corretto”'
description: Quando un utente pianifica il proprio periodo di inattività e delega le approvazioni in base a tale momento, la delega di approvazione può includere giorni precedenti o successivi alle ferie programmate.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
hidefromtoc: true
source-git-commit: 2a41264d6f477f51eaeda6ae3675b1a6d816249c
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 100%

---

# Approvazioni: la delega di approvazione è impostata per un numero di giorni non corretto

>[!NOTE]
>
>Questa segnalazione è stata chiusa perché il problema non sussiste.

Quando un utente pianifica il proprio periodo di inattività e delega le approvazioni in base a tale momento, la delega di approvazione può includere giorni precedenti o successivi alle ferie programmate.

**Soluzione alternativa**

Questa discrepanza deriva da una differenza tra il fuso orario del profilo di un utente e il fuso orario della pianificazione assegnata all’utente.

Ti consigliamo di creare una pianificazione univoca per ogni fuso orario da cui lavorano gli utenti e assegnare ogni utente alla programmazione corrispondente al fuso orario del suo profilo.

_Segnalato per la prima volta il giovedì 24 marzo 2022._
