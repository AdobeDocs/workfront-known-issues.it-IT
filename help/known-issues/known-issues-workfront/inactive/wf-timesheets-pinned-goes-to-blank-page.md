---
title: '“Schede orario: la scheda orario fissata passa in una pagina vuota”'
description: Quando un utente fa clic su un pin in Workfront per passare alla scheda orario, il pin passa invece in una pagina vuota. È disponibile una soluzione alternativa.
hidefromtoc: true
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
source-git-commit: 1aed6a440155c99f8ce0b0f42c44dd9a3c660af4
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 100%

---

# Schede orario: la scheda orario fissata passa in una pagina vuota

<!--article live for workaround-->

Quando un utente fa clic su un pin in Workfront che deve passare alla scheda orario, il pin passa invece in una pagina vuota.

Questo perché l’URL della scheda orario è cambiato. Il `/own` alla fine dell’URL non è più l’URL corretto. Se l’utente ha fissato un URL che include `/own`, il pin porta a una pagina vuota.

**Soluzione alternativa**

1. Sblocca la scheda orario.
1. Rimuovi `/own` dalla fine dell’URL
1. Fissa nuovamente la scheda orario.

_Segnalato per la prima volta il mercoledì 7 maggio 2024._
