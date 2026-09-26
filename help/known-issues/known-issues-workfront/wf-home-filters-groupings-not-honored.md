---
title: 'Nuova Home: le impostazioni predefinite del filtro widget e del raggruppamento non seguono il modello di layout'
description: Quando un utente visualizza il widget I miei progetti, Le mie Attività o I miei problemi nella nuova esperienza della pagina Home, il filtro e il raggruppamento predefiniti per tale widget non sono l’impostazione predefinita nel modello layout assegnato a tale utente.
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c042179c-157b-516d-b27c-e3bf303e8567
    internal-label: Get Started with Workfront
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 93%
---
# Nuova [!UICONTROL Home]: le impostazioni predefinite del filtro e del raggruppamento widget non seguono il modello layout

>[!NOTE]
>
>Questo problema è stato chiuso perché il sistema funziona come previsto.

Quando un utente visualizza i widget [!UICONTROL I miei progetti], [!UICONTROL Le mie attività] o [!UICONTROL I miei problemi] nella nuova esperienza [!UICONTROL Home], il filtro e il raggruppamento predefiniti per tale widget non sono l’impostazione predefinita nel modello layout assegnato a tale utente.

**Soluzione alternativa**:

Quando si utilizza la nuova pagina Home, è importante ricordare che le impostazioni utente (preferenze) hanno la priorità. Di conseguenza, se imposti un filtro o un raggruppamento predefinito per un widget specifico utilizzando un modello layout, potrebbe non avere effetto immediato a causa delle preferenze utente esistenti. Per applicare il nuovo filtro o raggruppamento, potrebbe essere necessario reimpostare le preferenze. Questa operazione può essere eseguita aggiungendo `/resetUser` all’URL.

_Segnalato per la prima volta il 3 gennaio 2024._
