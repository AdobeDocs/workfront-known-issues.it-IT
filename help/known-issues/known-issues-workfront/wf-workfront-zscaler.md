---
title: 'Workfront: le impostazioni ZScaler possono causare una riduzione delle prestazioni'
description: Il servizio web di ZScaler utilizza http/1.1 per impostazione predefinita, che può causare una riduzione delle prestazioni in Workfront.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: ht
source-wordcount: '81'
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
