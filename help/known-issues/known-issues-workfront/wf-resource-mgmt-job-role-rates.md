---
title: "Gestione risorse: calcoli finanziari errati a causa di problemi di mansione"
description: "I calcoli relativi a ore e contabilità potrebbero non essere corretti e mostrare un costo pari a 0 anche se le ore sono registrate in una mansione che ha una tariffa."
hidefromtoc: true
feature: Resource Management
source-git-commit: e9a7ff289e7c9fcc9c9ff13b7c4b5b554e303c11
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 3%

---


# Gestione risorse: calcoli finanziari errati a causa di problemi di mansione

Le ore e i calcoli finanziari potrebbero non essere corretti, con un costo pari a 0 anche se le ore sono registrate in una mansione che ha una tariffa.

Questo perché i Ruoli creano automaticamente tassi duplicati senza date di inizio o di fine. Poiché non hanno date di inizio o di fine, vengono trattati come un valore pari a 0 quando vengono eseguiti i calcoli finanziari.

**Soluzione alternativa**

1. Assicurati di salvare i dati corretti passati.
1. Elimina le tariffe duplicate senza date di inizio o fine.
1. Ricalcolare i dati finanziari.

_Segnalato per la prima volta il 18 gennaio 2023._
