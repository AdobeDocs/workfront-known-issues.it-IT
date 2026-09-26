---
title: 'Approvazioni: la delega di approvazione è impostata per un numero di giorni non corretto'
description: Quando un utente pianifica il proprio periodo di inattività e delega le approvazioni in base a tale momento, la delega di approvazione può includere giorni precedenti o successivi alle ferie programmate.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: b04e3dc0-3a59-45b1-aa02-b0b6d5f87eff
    internal-label: Approvals
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 100%
---
# Approvazioni: la delega di approvazione è impostata per un numero di giorni non corretto

<!--Live for workaround-->

>[!NOTE]
>
>Questa segnalazione è stata chiusa perché il problema non sussiste.

Quando un utente pianifica il proprio periodo di inattività e delega le approvazioni in base a tale momento, la delega di approvazione può includere giorni precedenti o successivi alle ferie programmate.

**Soluzione alternativa**

Questa discrepanza deriva da una differenza tra il fuso orario del profilo di un utente e il fuso orario della pianificazione assegnata all’utente.

Ti consigliamo di creare una pianificazione univoca per ogni fuso orario da cui lavorano gli utenti e assegnare ogni utente alla programmazione corrispondente al fuso orario del suo profilo.

_Segnalato per la prima volta il venerdì 24 marzo 2022._
