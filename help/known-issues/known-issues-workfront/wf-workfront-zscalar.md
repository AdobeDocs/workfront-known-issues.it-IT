---
title: "Workfront: le impostazioni ZScalar possono causare una riduzione delle prestazioni"
description: "Il servizio web di ZScalar utilizza http/1.1 per impostazione predefinita, che può causare una riduzione delle prestazioni in Workfront."
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 77345937934851b8ebfdf257f44e25133eade971
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---


# Workfront: le impostazioni ZScalar possono causare una riduzione delle prestazioni

>[!NOTE]
>
>Questo è un problema relativo a ZScalar e non verrà risolto da Workfront.

Il servizio Web di ZScalar utilizza `http/1.1` per impostazione predefinita, che può causare una riduzione delle prestazioni in Workfront.

**Soluzione alternativa**

Configurare il software ZScalar per utilizzare `http/2`. Questo non può essere configurato in Workfront.

Puoi trovare informazioni su `http/2` nella documentazione di ZScalar.

_Segnalato per la prima volta il martedì 18 novembre 2024._
