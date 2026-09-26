---
title: 'Workfront Fusion: il modulo di ricerca Jira restituisce un errore'
description: Il modulo di ricerca utilizzato dal connettore Jira precedente può causare un errore. È disponibile una soluzione alternativa
feature: Workfront Fusion
exl-id: 9502ffb3-f287-47b2-9b35-1a906345e924
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 100%
---
# Workfront Fusion: il modulo di ricerca Jira restituisce un errore

>[!NOTE]
>
>Questo problema è dovuto a una modifica apportata al prodotto Jira.

Il modulo di ricerca utilizzato dal connettore Jira precedente può causare il seguente errore:

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

Questo è dovuto alla rimozione di funzionalità da parte di Jira.

Nota:

* Solo il modulo di ricerca è interessato. Al momento, altri endpoint API Jira utilizzati dal connettore Fusion non sono interessati dalla rimozione di queste funzionalità.

* Il rollout su base geografica può causare incongruenze. Poiché Atlassian sta implementando questa modifica a livello regionale, è possibile che alcune istanze di Jira Cloud supportino ancora temporaneamente gli endpoint precedenti. Questo può causare comportamenti non coerenti in ambienti diversi.

**Soluzione alternativa**

Se si verifica questo errore, puoi sostituire il modulo di ricerca del connettore Jira precedente con il modulo di ricerca del nuovo connettore. Nota: il nuovo connettore consente di selezionare la versione API utilizzata. Accertati di selezionare **V3** nel campo **Versione API** durante la creazione della connessione.

_Segnalato per la prima volta il 15 settembre 2025._
