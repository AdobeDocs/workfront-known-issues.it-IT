---
title: 'Bozze: le bozze di acquisizione web non vengono generate'
description: Quando un utente tenta di creare una bozza di acquisizione web, la bozza non viene generata correttamente.
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 59%

---

# Bozze: le bozze di acquisizione web non vengono generate

>[!NOTE]
>
>Questo problema è stato chiuso perché il sistema funziona come previsto. Consulta la soluzione alternativa di seguito.

Quando un utente tenta di creare una bozza di acquisizione web, la bozza non viene generata correttamente.

**Soluzione alternativa**

Questo problema è causato dai lunghi tempi di generazione delle bozze per alcuni file PDF. Per aumentare il timeout di generazione dai 30 secondi predefiniti, modifica la proprietà seguente in Impostazioni di elaborazione a livello di account in Amministrazione bozze:

`WebCaptureNavigationTimeout -> 120`

_Segnalato per la prima volta il venerdì 3 ottobre 2024._
