---
title: 'Autorizzazioni: le autorizzazioni degli oggetti non vengono ereditate correttamente'
description: Le autorizzazioni ereditate non vengono applicate correttamente agli oggetti. Questo può verificarsi a causa della complessità delle autorizzazioni ereditate.
feature: Projects, Tasks, Work Management
exl-id: 589733a7-2bd6-4b73-afb8-a14cc1f5076a
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
    internal-label: Projects
  - id: b91c0848-76c4-4da4-8b81-3aade0518dd0
    internal-label: Tasks
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '146'
ht-degree: 100%
---
# Autorizzazioni: le autorizzazioni degli oggetti non vengono ereditate correttamente

>[!NOTE]
>
>Il team di prodotto sta attualmente valutando la risoluzione di questo problema, che potrebbe richiedere alcuni miglioramenti. I miglioramenti dei prodotti vengono comunicati negli annunci relativi al prodotto e non con gli aggiornamenti di manutenzione.I miglioramenti delle funzionalità del prodotto vengono comunicati nella sezione Annunci sui prodotti e non tramite gli aggiornamenti di manutenzione.

Le autorizzazioni ereditate non vengono applicate correttamente agli oggetti. Questo può verificarsi a causa della complessità delle autorizzazioni ereditate, che possono essere interessate dalle seguenti circostanze:

* L’oggetto è condiviso con un numero elevato di persone
* Un numero elevato di oggetti è interessato da una modifica delle autorizzazioni ereditata

**Soluzione alternativa**

Il problema può essere evitato limitando la dimensione o la complessità degli oggetti. Ogni oggetto principale non dovrebbe avere più di 10.000 oggetti secondari.

_Segnalato per la prima volta il 21 marzo 2025._
