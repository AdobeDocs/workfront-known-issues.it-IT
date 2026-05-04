---
title: 'Schede orario: la scheda orario fissata passa a una pagina vuota'
description: Quando un utente fa clic su un pin in Workfront per passare alla scheda orario, il pin passa invece in una pagina vuota. È disponibile una soluzione alternativa.
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
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
