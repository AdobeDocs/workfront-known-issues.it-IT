---
title: 'Workfront: le impostazioni ZScaler possono causare una riduzione delle prestazioni'
description: Il servizio web di ZScaler utilizza http/1.1 per impostazione predefinita, che può causare una riduzione delle prestazioni in Workfront.
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '83'
ht-degree: 100%
---
# Workfront: le impostazioni ZScaler possono causare una riduzione delle prestazioni

>[!NOTE]
>
>Questo problema è relativo a ZScaler e non verrà risolto da Workfront.

Il servizio Web di ZScaler utilizza `http/1.1` per impostazione predefinita, che può causare una riduzione delle prestazioni in Workfront.

**Soluzione alternativa**

Configura il software ZScaler per utilizzare `http/2`. Questo non può essere configurato in Workfront.

Puoi trovare informazioni su `http/2` nella documentazione di ZScaler.

_Segnalato per la prima volta il martedì 18 novembre 2024._
