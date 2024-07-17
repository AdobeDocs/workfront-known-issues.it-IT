---
title: 'Nuova pagina Home: le impostazioni predefinite del filtro e del raggruppamento widget non seguono il modello layout'
description: Quando un utente visualizza il widget I miei progetti, Le mie Attività o I miei problemi nella nuova esperienza della pagina Home, il filtro e il raggruppamento predefiniti per tale widget non sono l’impostazione predefinita nel modello layout assegnato a tale utente.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 100%

---

# Nuova [!UICONTROL Home]: le impostazioni predefinite del filtro e del raggruppamento widget non seguono il modello layout

>[!NOTE]
>
>Questo problema è stato chiuso perché il sistema funziona come previsto.

Quando un utente visualizza i widget [!UICONTROL I miei progetti], [!UICONTROL Le Mie Attività] o [!UICONTROL I miei Problemi] nella nuova esperienza [!UICONTROL Home], il filtro e il raggruppamento predefiniti per tale widget non sono l’impostazione predefinita nel modello di layout assegnato a tale utente.

**Soluzione alternativa**:

Quando si utilizza la nuova pagina Home, è importante ricordare che le impostazioni utente (preferenze) hanno la priorità. Di conseguenza, se imposti un filtro o un raggruppamento predefinito per un widget specifico utilizzando un modello di layout, potrebbe non avere effetto immediato a causa delle preferenze utente esistenti. Per applicare il nuovo filtro o raggruppamento, potrebbe essere necessario reimpostare le preferenze. Questa operazione può essere eseguita aggiungendo `/resetUser` all’URL.

_Segnalato per la prima volta il 3 gennaio 2024._
