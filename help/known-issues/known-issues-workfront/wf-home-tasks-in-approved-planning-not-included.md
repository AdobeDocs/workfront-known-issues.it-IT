---
title: '“Home: le attività nei progetti con stato Approvato o in Pianificazione non sono incluse in Le mie attività o nell’Elenco lavori della Home”'
description: “Le attività dei progetti con stato Approvato o in Pianificazione non vengono visualizzate nella Home. È disponibile una soluzione alternativa.”
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: ht
source-wordcount: '166'
ht-degree: 100%

---


# Home: le attività nei progetti con stato Approvato o Pianificazione non sono incluse in Le mie attività o in Elenco di lavori dell’area Home

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
