---
title: 'Documenti: errore 404 durante l’accesso a un documento collegato da SharePoint'
description: Quando un utente tenta di accedere a un documento collegato tramite SharePoint, viene reindirizzato a una pagina con un errore 404.
feature: Digital Content and Documents, Workfront Integrations and Apps
exl-id: b86ec92b-a27f-4ec3-acc2-0f0118014760
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a1f87682-0525-5459-aa06-3560bb4c3b2a
    internal-label: Workfront Integrations and Apps
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
    internal-label: Digital content and documents
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 91%
---
# Documenti: errore 404 durante l’accesso al documento collegato da [!DNL SharePoint]

<!--Requested article. This issue is on the WF and WFP TOCs.-->

Quando un utente tenta di accedere a un documento collegato tramite [!DNL SharePoint], viene reindirizzato a una pagina con il seguente errore:

“[!UICONTROL Errore 404: pagina non trovata. Questa pagina non è disponibile. Prova a controllare l’URL o visita una pagina diversa.]”

Questo è un problema noto di [!DNL SharePoint] che si verifica quando il sito contiene un simbolo “@” nel collegamento.

**Soluzione alternativa**

[!DNL SharePoint] consiglia di generare un URL breve e di utilizzarlo per il collegamento.

_Segnalato per la prima volta il mercoledì 14 marzo 2023._
