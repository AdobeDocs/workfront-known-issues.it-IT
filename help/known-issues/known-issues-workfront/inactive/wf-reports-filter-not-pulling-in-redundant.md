---
title: 'Rapporto: il filtro del rapporto non restituisce i risultati previsti'
description: Un filtro in un rapporto potrebbe non restituire tutti i risultati previsti. È disponibile una soluzione alternativa.
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
    internal-label: Reports and dashboards
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '100'
ht-degree: 100%
---
# Rapporto: il filtro del rapporto non restituisce i risultati previsti

>[!NOTE]
>
>Questo problema è stato chiuso.

Un filtro in un rapporto potrebbe non restituire tutti i risultati previsti.

Ciò può verificarsi quando il filtro è configurato per restituire risultati con determinati criteri e include una regola OR che restituisce risultati che sono un sottoinsieme degli stessi criteri.

**Soluzione alternativa**

Assicurati che i blocchi OR del filtro non includano criteri di valutazione identici.

_Segnalato per la prima volta il martedì 11 marzo 2024._
