---
title: 'Schede orario: la scheda orario fissata passa a una pagina vuota'
description: Quando un utente fa clic su un pin in Workfront per passare alla scheda orario, il pin passa invece in una pagina vuota. È disponibile una soluzione alternativa.
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: ce22a157-dd2c-405f-b740-c2f204bb4c1a
    internal-label: Timesheets
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '126'
ht-degree: 100%
---
# Schede orario: la scheda orario fissata passa a una pagina vuota

<!--article live for workaround-->

Quando un utente fa clic su un pin in Workfront per passare alla scheda orario, il pin passa invece in una pagina vuota.

Questo perché l’URL della scheda orario è cambiato. Il `/own` alla fine dell’URL non è più l’URL corretto. Se l’utente ha fissato un URL che include `/own`, il pin porta a una pagina vuota.

**Soluzione alternativa**

1. Sblocca la scheda orario.
1. Rimuovi `/own` dalla fine dell’URL
1. Fissa nuovamente la scheda orario.

_Segnalato per la prima volta l’mercoledì 7 maggio 2024._
