---
title: Aggiornamenti di manutenzione per Workfront
description: Aggiornamenti di manutenzione per  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: b74a577bc652f822b4ff9d835952f9b8145ae6dc
workflow-type: tm+mt
source-wordcount: '530'
ht-degree: 58%

---

# Aggiornamenti di manutenzione per [!DNL Workfront]

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2024.

>[!NOTE]
>
>Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

Per gli aggiornamenti di manutenzione precedenti al 2023, consulta [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

## Aggiornamenti di gennaio 2024

+++**Aggiornamento di manutenzione del sabato 12 gennaio 2024**

### Aggiornamento di manutenzione del giovedì 12 gennaio 2024

#### Bacheche

**Impossibile allegare un documento a una scheda**

Quando un utente tenta di allegare un documento a una scheda connessa, può selezionare il documento da allegare, ma il documento non viene visualizzato nell’area del documento della scheda e non è collegato all’oggetto a cui è connessa la scheda.

Questo problema è stato segnalato nelle schede collegate a problemi.

**La scheda appare su più sprint**

Quando un utente sta visualizzando uno sprint su una bacheca, le schede che si trovano in sprint diversi appaiono sulla bacheca. Questo problema è intermittente.

**La scheda non si chiude quando si utilizza la vista Bacheche in un progetto**

Quando un utente crea una scheda durante la visualizzazione Bacheche in un elenco di attività di un progetto, la scheda non viene chiusa né salvata. Questo impedisce all’utente di tornare al progetto.

Per chiudere la scheda, l’utente deve modificare l’URL per rimuovere &quot;scheda&quot; e tutto ciò che si trova a destra di &quot;scheda&quot;.

**Le schede persistono quando si modifica l’iterazione**

Quando un utente visualizza un’iterazione su una bacheca e successivamente la modifica, le schede visualizzate per la nuova iterazione sono quelle di un’iterazione che l’utente stava visualizzando in precedenza.

**Errore in [!UICONTROL Commenti] sezione di schede**

Quando un utente visualizza una scheda e scorre fino alla sezione [!UICONTROL Commenti], i commenti non vengono visualizzati e l’utente visualizza il seguente errore:

&quot;[!UICONTROL Si è verificato un errore. Riprova più tardi.]&quot;

**Problemi durante la visualizzazione dello stato delle attività secondarie**

Sono stati segnalati i seguenti problemi relativi alla visualizzazione dello stato delle attività secondarie in una scheda in Bacheche:

* Lo stato viene visualizzato come “Seleziona stato” anche quando l’attività ha già uno stato. Questo stato può essere visualizzato quando si visualizza direttamente l’attività.
* Se l’utente cerca di selezionare uno stato, la schermata diventa vuota e deve essere aggiornata.

**&quot;[!UICONTROL Non hai accesso]&quot; quando si visualizzano commenti su una scheda**

Quando un utente tenta di visualizzare i commenti su una scheda non connessa a un oggetto di [!DNL Workfront], viene mostrato il messaggio seguente:

“[!UICONTROL Non disponi del livello di accesso per visualizzare i commenti su questo oggetto]”

Ciò può verificarsi anche quando l’utente poteva vedere i commenti sulla scheda in precedenza.

+++

+++**Aggiornamento di manutenzione del giovedì 11 gennaio 2023**

### Aggiornamento di manutenzione dell’giovedì 11 gennaio 2023

#### Bacheche

**Le schede completate non vengono caricate correttamente sulle schede dinamiche**

In precedenza, l’unico modo per includere il lavoro completato su una bacheca dinamica era caricare le schede come schede archiviate. In caso contrario, le schede completate non venivano affatto caricate sulla bacheca. Questo causava problemi nella possibilità di individuare le schede.

Ora, quando crei una bacheca dinamica, le schede completate vengono caricate per impostazione predefinita come schede archiviate, ma puoi selezionare Non archiviare le schede completate per caricare tutte le schede completate sulla bacheca come schede visibili nella colonna Completate.

+++

## Aggiornamenti di manutenzione precedenti

Le informazioni sugli aggiornamenti di manutenzione precedenti sono disponibili qui:

* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2023](2023-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2022](2022-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2021](2021-updates.md)
