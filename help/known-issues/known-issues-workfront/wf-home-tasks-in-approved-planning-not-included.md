---
title: "Home: le attività nei progetti con stato Approvato o Pianificazione non sono incluse in Le mie attività o nell’elenco di lavoro dell’area Home"
description: Le attività dei progetti con stato Approvato o Pianificazione non vengono visualizzate nella Home. È disponibile una soluzione alternativa.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: 5994508b-ee9f-40a9-bca3-e17d7a7708b5
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 82%

---

# Home: le attività nei progetti con stato Approvato o Pianificazione non sono incluse in Le mie attività o in Elenco di lavori dell’area Home

>[!NOTE]
>
>Il team di prodotto sta attualmente valutando la risoluzione di questo problema. Una volta avvenuta, la risoluzione del problema verrà comunicata negli annunci dei prodotti e non con gli aggiornamenti di manutenzione.

Le attività dei progetti con stato Approvato o Pianificazione non vengono visualizzate nelle aree seguenti:

* Home classica: Elenco lavori
* Nuova Home: widget Le mie attività

Ciò si verifica perché le attività provenienti da progetti con questi stati sono attualmente incluse nel limite di query di 2000 elementi, ma non sono visualizzate in Le mie attività o nell’Elenco lavori della Home. Questo può creare una situazione in cui un utente che dispone di meno di 2000 attività non le possa visualizzare.

**Soluzione alternativa**

Crea un rapporto delle assegnazioni personalizzato che includa i seguenti filtri in modalità testo:

Quando l’assegnazione è AWAITING_ACCEPTANCE, includi progetti CURRENT|APPROVED:

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

Quando l’assegnazione viene accettata, includi i progetti CURRENT|APPROVED|PLANNING:

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_Segnalato per la prima volta il 6 novembre 2023._
