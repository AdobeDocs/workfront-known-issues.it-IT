---
title: 'Workfront Fusion: il modulo di ricerca Jira restituisce un errore'
description: Il modulo di ricerca utilizzato dal connettore Jira legacy potrebbe causare un errore. È disponibile una soluzione alternativa
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 0f4dba4664f645920752cc0c346782c9582b0e54
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 4%

---


# Workfront Fusion: il modulo di ricerca Jira restituisce un errore

>[!NOTE]
>
>Questo problema è dovuto a una modifica apportata da Jira al suo prodotto.

Il modulo di ricerca utilizzato dal connettore Jira legacy può causare il seguente errore:

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

Ciò è dovuto a una deprecazione da parte di Jira.

Tieni presente che:

* È interessato solo il modulo di ricerca. Al momento, altri endpoint API Jira utilizzati dal connettore Fusion non sono interessati da questa rimozione.

* Il rollout geografico può causare incongruenze. Atlassian sta implementando questa modifica a livello regionale, il che significa che alcune istanze di Jira Cloud potrebbero ancora supportare temporaneamente gli endpoint precedenti. Questo può causare comportamenti non coerenti tra gli ambienti.

**Soluzione alternativa**

Se si verifica questo errore, è possibile sostituire il modulo di ricerca del connettore Jira legacy con il modulo di ricerca del nuovo connettore. Il nuovo connettore consente di selezionare la versione API utilizzata. Accertati di selezionare **V3** nel campo **Versione API** durante la creazione della connessione.

_Segnalato per la prima volta il martedì 15 settembre 2025._

