---
title: '“Gestione delle risorse: calcoli finanziari errati a causa di problemi relativi alla mansione”'
description: “Le ore e i calcoli finanziari potrebbero non essere corretti, mostrando un costo pari a 0 anche se le ore sono registrate in una mansione che prevede un tasso di costo.”
hidefromtoc: true
feature: Resource Management
source-git-commit: f8579e17458f702580e1a4cf3600c14376d7591b
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 100%

---


# Gestione delle risorse: calcoli finanziari errati a causa di problemi relativi alla mansione

>[!NOTE]
>
>Questo problema è stato risolto il venerdì 8 febbraio 2024.

Le ore e i calcoli finanziari potrebbero non essere corretti, mostrando un costo pari a 0 anche se le ore sono registrate in una mansione che prevede un tasso di costo.

Questo perché le mansioni creano automaticamente tariffe duplicate senza date di inizio o di fine. Poiché non dispongono di date di inizio o di fine, le tariffe vengono considerate come valori pari a 0 quando vengono eseguiti i calcoli finanziari.

**Soluzione alternativa**

1. Assicurati che i dati corretti passati siano salvati.
1. Elimina le tariffe duplicate senza date di inizio o di fine.
1. Ricalcola i dati finanziari.

_Segnalato per la prima volta il 18 gennaio 2023._
