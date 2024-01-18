---
title: Aggiornamenti di manutenzione per Workfront
description: Aggiornamenti di manutenzione per  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 83d675f4ddbdf031b6737cf3e1101afc07d2f841
workflow-type: tm+mt
source-wordcount: '945'
ht-degree: 81%

---

# Aggiornamenti di manutenzione per [!DNL Workfront]

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2024.

>[!NOTE]
>
>Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

Per gli aggiornamenti di manutenzione precedenti al 2023, consulta [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

## Aggiornamenti di gennaio 2024

+++**Aggiornamento di manutenzione del venerdì 18 gennaio 2024**

### Aggiornamento di manutenzione dell’venerdì 18 gennaio 2024

#### Bacheche

**Impossibile allegare un documento a una scheda**

Quando un utente tenta di allegare un documento a una scheda connessa, può selezionare il documento da allegare, ma il documento non viene visualizzato nell’area del documento della scheda e non è collegato all’oggetto a cui è connessa la scheda.

Questo problema è stato segnalato nelle schede collegate a problemi.

**La scheda appare su più sprint**

Quando un utente sta visualizzando uno sprint su una bacheca, le schede che si trovano in sprint diversi appaiono sulla bacheca. Questo problema è intermittente.

**La scheda non si chiude quando si utilizza la vista Bacheche in un progetto**

Quando un utente crea una scheda durante la vista Bacheche in un elenco di attività di un progetto, la scheda non viene chiusa né salvata. Questo impedisce all’utente di tornare al progetto.

Per chiudere la scheda, l’utente deve modificare l’URL per rimuovere “scheda” e tutto ciò che si trova a destra di “scheda”.

**Le schede persistono quando si modifica l’iterazione**

Quando un utente visualizza un’iterazione su una bacheca e successivamente la modifica, le schede visualizzate per la nuova iterazione sono quelle di una che l’utente stava visualizzando in precedenza.

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

#### Moduli personalizzati nel mio gruppo

**Impossibile aggiungere o rimuovere in blocco moduli personalizzati nelle attività modello**

Se un utente cerca di aggiungere o rimuovere in blocco un modulo personalizzato in un’attività modello, il modulo non viene aggiunto o rimosso e l’utente visualizza il seguente errore:

[!UICONTROL Riproviamo. Parametro non valido: valore templateID “XXXXXXXXXXXXXXXX”]

Se l’utente individua il modello con il GUID specificato e cerca di aggiungere o rimuovere moduli personalizzati nelle altre attività modello, l’errore si verificherà nuovamente utilizzando un altro templateID.

I moduli personalizzati possono essere aggiunti o rimossi in un’unica attività modello. Questo errore vale solo per l’aggiunta o per la rimozione in blocco.

#### Portfolio

**La terminologia personalizzata non si applica alla pagina del gruppo**

Quando un utente imposta la terminologia personalizzata a livello di Portfolio, la terminologia non viene applicata alla pagina a livello di gruppo.

#### Configura

**Impossibile nascondere gli stati facoltativi**

Quando un utente cerca di nascondere gli stati facoltativi a livello di sistema e di gruppo, lo stato non viene nascosto. Se l’utente visualizza lo stato, l’opzione per nascondere lo stato non è abilitata, anche se l’utente l’ha abilitato e ha salvato le modifiche.

**Stati di problemi predefiniti mancanti in alcuni tipi di problemi in Configurazione**

Quando un utente visualizza gli stati dei problemi in Configurazione, nota che in alcuni tipi di problemi mancano gli stati predefiniti (Nuovo, In corso e Completato). Gli stati predefiniti non dispongono della possibilità di modificare il tipo di problema, pertanto l’utente non può configurare nuovamente gli stati da visualizzare per i tipi di problema interessati.

#### Team

**Problemi relativi all’impostazione degli stati del team per [!UICONTROL Fine] pulsante**

Sono stati segnalati i seguenti problemi relativi agli stati per il pulsante [!UICONTROL Fine] durante la modifica o la creazione di un team:

* Alcuni stati potrebbero non essere presenti nell’area del pulsante Fine della finestra [!UICONTROL Nuovo team] o nell’area [!UICONTROL Impostazioni team] di un team esistente.
* Se l’utente tenta di salvare il team, potrebbe visualizzare l’errore “È necessario selezionare almeno uno stato in ogni categoria.”

#### Modelli

**Errore durante l’associazione del modello al progetto**

Quando un utente cerca di allegare un modello a un progetto, riceve il seguente errore:

“Ops! Si è verificato un errore. Contatta Workfront per consentirci di individuare e risolvere il problema.”

Ciò si verifica quando l’utente non dispone dell’autorizzazione Visualizzazione per un modulo personalizzato allegato al modello.

#### Aggiornamenti

**I commenti non vengono trasferiti tra la vecchia e la nuova esperienza**

Un commento creato nell’esperienza di commento legacy potrebbe non essere visibile nella nuova esperienza di commento. Può anche verificarsi l’inverso.

+++

+++**Aggiornamento di manutenzione del giovedì 11 gennaio 2023**

### Aggiornamento di manutenzione dell’11 gennaio 2023

#### Bacheche

**Le schede completate non vengono caricate correttamente sulle bacheche dinamiche**

In precedenza, l’unico modo per includere il lavoro completato su una bacheca dinamica era caricare le schede come schede archiviate. In caso contrario, le schede completate non venivano affatto caricate sulla bacheca. Questo causava problemi nella possibilità di individuare le schede.

Ora, quando crei una bacheca dinamica, le schede completate vengono caricate per impostazione predefinita come schede archiviate, ma puoi selezionare Non archiviare le schede completate per caricare tutte le schede completate sulla bacheca come schede visibili nella colonna Completate.

+++

## Aggiornamenti di manutenzione precedenti

Le informazioni sugli aggiornamenti di manutenzione precedenti sono disponibili qui:

* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2023](2023-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2022](2022-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2021](2021-updates.md)
