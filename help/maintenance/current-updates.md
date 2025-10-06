---
title: Aggiornamenti di manutenzione per Workfront
description: Aggiornamenti di manutenzione per  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 932556d1c72aa33e9169034f41f6250d249a228b
workflow-type: tm+mt
source-wordcount: '2314'
ht-degree: 48%

---

# Aggiornamenti di manutenzione per [!DNL Workfront]

>[!NOTE]
>
>Per informazioni sulle interruzioni di manutenzione per tutti i prodotti Adobe, incluso Workfront, consulta la [pagina di stato Adobe](https://status.adobe.com/it/).

Questa pagina descrive i problemi risolti negli aggiornamenti settimanali di Workfront.

Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

Per gli aggiornamenti di manutenzione precedenti al 2025, consulta [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2025.

## Aggiornamenti di ottobre 2025

+++**Aggiornamenti di manutenzione - settimana dal 28 settembre al 4 ottobre 2025**

### Aggiornamenti di manutenzione della settimana dal 28 settembre al 4 ottobre 2025

#### Programmi

**Impossibile salvare durante la modifica di un programma**

Quando un utente modifica un programma e tenta di salvare le modifiche, queste non vengono salvate.

+++

## Aggiornamenti di settembre 2025

+++**Aggiornamenti di manutenzione della settimana dal 21 al 27 settembre 2025**

### Aggiornamenti di manutenzione della settimana dal 21 al 27 settembre 2025

#### Utenti

**Impossibile modificare le impostazioni delle notifiche per un altro utente**

Quando un utente cerca di modificare le impostazioni di notifica per un altro utente, non può modificare le impostazioni e visualizza il seguente messaggio:

&quot;Non si dispone dell&#39;accesso sufficiente per modificare i dati finanziari.&quot;

+++

+++**Aggiornamenti di manutenzione - settimana dal 14 al 20 settembre 2025**

### Aggiornamenti di manutenzione della settimana dal 14 al 20 settembre 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione della settimana dal 7 al 13 settembre 2025**

### Aggiornamenti di manutenzione della settimana dal 7 al 13 settembre 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++


+++**Aggiornamenti di manutenzione - settimana dal 31 agosto al 6 settembre 2025**

### Aggiornamento di manutenzione della settimana dal 31 agosto al 6 settembre 2025

#### API

**Nuovi guardrail per evitare di sovraccaricare le sottoscrizioni eventi**

Abbonamenti eventi è progettato per fornire una distribuzione affidabile degli eventi per tutti gli utenti. A tal fine, sono state introdotte misure di salvaguardia per impedire la produzione di eventi eccessivi da parte di un singolo utente, che potrebbero causare potenziali problemi di qualità del servizio per tutti gli utenti. Di conseguenza, un utente che produce troppi eventi a una velocità elevata in un breve arco di tempo può riscontrare ritardi nella sandboxing e nella consegna degli eventi.

#### Documenti

**Gli utenti aggiunti come approvatori dopo il completamento dell&#39;approvazione non ricevono alcuna notifica**

Quando un utente ha approvato un documento e successivamente ne vengono aggiunti altri come approvatori, i nuovi approvatori aggiunti non ricevono le notifiche in-app o e-mail della richiesta di approvazione.

+++

## Aggiornamenti di agosto 2025

+++**Aggiornamenti di manutenzione della settimana dal 24 al 30 agosto 2025**

### Aggiornamento di manutenzione della settimana dal 24 al 30 agosto 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione della settimana dal 17 al 23 agosto 2025**

### Aggiornamento di manutenzione della settimana dal 17 al 23 agosto 2025

#### Progetti

**Errore durante l&#39;aggiunta di un progetto a un programma**

Quando un utente tenta di aggiungere un progetto esistente a un programma, l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

&quot;Errore durante il caricamento del contenuto secondario...&quot;

**I progetti esportati contengono ore effettive imprecise**

Quando un utente esporta un progetto in Excel, la colonna Ore effettive non mostra i dati corretti.

+++

+++**Aggiornamenti di manutenzione della settimana dal 10 al 16 agosto 2025**

### Aggiornamento di manutenzione della settimana dal 10 al 16 agosto 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione della settimana dal 3 al 9 agosto 2025**

### Aggiornamento di manutenzione della settimana dal 3 al 9 agosto 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione - settimana dal 27 luglio al 2 agosto 2025**

### Aggiornamenti di manutenzione della settimana dal 27 luglio al 2 agosto 2025

#### Progetti

**Viene visualizzato un avviso quando la sequenza temporale non è stata ricalcolata**

Ora gli utenti visualizzano un’icona di avviso quando la timeline del progetto non è stata ricalcolata. Quando passa il puntatore del mouse su questa icona, l’utente visualizza il seguente messaggio:

&quot;La timeline del progetto non è corretta. I project manager potrebbero dover ricalcolare manualmente la timeline.&quot;

A volte, le timeline non possono essere ricalcolate perché un progetto è estremamente complesso. Ad esempio, un progetto con più dipendenze, un numero elevato di attività, più predecessori di progetti incrociati o più rientri di attività potrebbero essere interessati.

In precedenza, non vi era alcuna indicazione che una sequenza temporale non fosse stata ricalcolata.

#### Attività

**L&#39;area Approvazioni scompare dal menu di navigazione a sinistra**

Quando un utente visualizza un’attività, l’area Approvazioni potrebbe non essere più visibile nel menu di navigazione a sinistra. La rimozione e l’aggiunta dell’area Approvazioni al modello di layout risolve il problema, ma il problema potrebbe ripresentarsi.

+++

## Aggiornamenti di luglio 2025

+++**Aggiornamenti di manutenzione della settimana dal 20 al 26 luglio 2025**

### Aggiornamenti di manutenzione della settimana dal 20 al 26 luglio 2025

#### Bozze

**Impossibile assegnare tag agli utenti nei commenti della bozza**

Quando un utente tenta di assegnare un tag a un altro utente in un commento della bozza e inizia a digitare il nome dell’utente, quest’ultimo non viene visualizzato nell’elenco e non può essere selezionato per l’assegnazione di tag.

+++

+++**Aggiornamenti di manutenzione - settimana dal 13 al 19 luglio 2025**

### Aggiornamenti di manutenzione della settimana dal 13 luglio al 192

### Integrazioni

**Problemi relativi all&#39;integrazione di Workfront per Slack**

Sono stati segnalati i seguenti problemi relativi all’integrazione di Workfront per Slack:

* Gli utenti non ricevono notifiche in Slack quando vengono apportati aggiornamenti in Workfront.
* Gli utenti non possono accedere a Workfront da Slack.
* Altri comandi nell’integrazione Workfront for Slack non funzionano come previsto.

+++

+++**Aggiornamenti di manutenzione - settimana 6-12 luglio 2025**

### Aggiornamenti di manutenzione - settimana del 6-12 luglio

### Progetti

**Impossibile spostare il progetto nel programma specificato**

Quando un utente cerca di spostare un progetto in un programma, il progetto non viene spostato. Ciò può verificarsi anche se l’utente ha ricevuto un messaggio che informa che il progetto è stato spostato correttamente.

+++

## Aggiornamenti di giugno 2025

+++**Aggiornamenti di manutenzione della settimana dal 22 al 27 giugno 2025**

### Aggiornamento di manutenzione della settimana dal 22 al 27 giugno 2025

#### Bozze

**Impossibile aprire la bozza dal collegamento diretto**

Quando un utente cerca di aprire una bozza da un collegamento diretto, la bozza non si apre. Ciò può verificarsi anche se l’utente fa parte di un flusso di lavoro per la bozza o se è un amministratore Workfront.

#### Rapporti

**L&#39;espansione del grafico include risultati imprecisi**

Quando un utente visualizza un rapporto grafico e tenta di eseguire un drill-down in un raggruppamento specifico, i dettagli includono risultati che non sono nel raggruppamento selezionato.

Questo problema è stato segnalato nei rapporti raggruppati per data.

+++

+++**Aggiornamenti di manutenzione - settimana dal 15 al 21 giugno 2025**

### Aggiornamento di manutenzione della settimana dal 15 al 21 giugno 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione della settimana 8-14 giugno 2025**

### Aggiornamento di manutenzione della settimana dall’8 al 14 giugno 2025

#### Pianificazione risorse

**Il pulsante Esporta è disabilitato**

Quando un utente tenta di esportare da Pianificazione risorse, il pulsante è disattivato (non disponibile) e l’utente non può eseguire l’esportazione.

#### Schede orario

**Schede orario non generate correttamente**

Quando un utente cerca di generare le schede orario e la generazione è impostata su &quot;A settimane alterne&quot;, viene generata solo una settimana.

+++

+++**Aggiornamenti di manutenzione, settimana 1-7 giugno 2025**

### Aggiornamento di manutenzione della settimana dal 1° al 7 giugno 2025

### Ricerca

**La ricerca avanzata non restituisce i risultati previsti**

Quando un utente utilizza la Ricerca avanzata, i risultati previsti non vengono restituiti. Ciò può verificarsi anche quando non sono presenti filtri applicati alla Ricerca avanzata.

+++

## Aggiornamenti di maggio 2025

+++**Aggiornamenti di manutenzione della settimana dal 25 al 31 maggio 2025**

### Aggiornamento di manutenzione della settimana dal 25 al 31 maggio 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione il venerdì 22 maggio 2025**

### Aggiornamento di manutenzione il venerdì 22 maggio 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione il venerdì 15 maggio 2025**

### Aggiornamento di manutenzione il venerdì 15 maggio 2025

#### Rapporti

**Errore durante la visualizzazione di un report con una vista milestone**

Quando un utente cerca di visualizzare un rapporto che ha una vista milestone disponibile da abilitare, il rapporto non viene caricato e viene visualizzato un errore.

+++

+++**Aggiornamento di manutenzione il venerdì 8 maggio 2025**

### Aggiornamento di manutenzione il venerdì 8 maggio 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione il venerdì 1 maggio 2025**

### Aggiornamento di manutenzione il venerdì 1 maggio 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

## Aggiornamenti di aprile 2025

+++**Aggiornamento di manutenzione il venerdì 24 aprile 2025**

### Aggiornamento di manutenzione il venerdì 24 aprile 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione il venerdì 17 aprile 2025**

### Aggiornamento di manutenzione il venerdì 17 aprile 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione il venerdì 10 aprile 2025**

### **Aggiornamento di manutenzione il venerdì 10 aprile 2025**

#### Dashboard

**Il dashboard personalizzato non si apre**

Quando un utente visualizza un oggetto e tenta di aprire un dashboard personalizzato associato all’oggetto, il dashboard non si apre.

#### Rapporti

**Utenti con fusi orari diversi ottengono risultati diversi**

Gli utenti in fusi orari diversi che utilizzano il selettore data per ottenere un rapporto per una determinata data ottengono risultati diversi per quel rapporto.

+++

+++**Aggiornamento di manutenzione il venerdì 3 aprile 2025**

### Aggiornamento di manutenzione il venerdì 3 aprile 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

## Aggiornamenti di marzo 2025

+++**Aggiornamento di manutenzione del venerdì 27 marzo 2025**

### Aggiornamento di manutenzione del venerdì 27 marzo 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione del venerdì 20 marzo 2025**

### Aggiornamento di manutenzione del venerdì 20 marzo 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione del venerdì 13 marzo 2025**

### Aggiornamento di manutenzione del venerdì 13 marzo 2025

#### Rapporti

**Il numero di elementi nel grafico non è accurato**

In un rapporto del dashboard, fare clic su un risultato del grafico con più di 15 elementi e selezionare la visualizzazione solo 15 funziona come previsto. Tuttavia, se si apre lo stesso report all&#39;esterno del dashboard e si fa clic sullo stesso risultato del grafico, questo indica che vengono visualizzati tutti gli elementi, ma solo 15.

+++

+++**Aggiornamento di manutenzione del 6 marzo 2025**

### Aggiornamento di manutenzione del 6 marzo 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

## Aggiornamenti di febbraio 2025

+++**Aggiornamento di manutenzione del 27 febbraio 2025**

### Aggiornamento di manutenzione del 27 febbraio 2025

#### Gruppi

**Impossibile condividere il livello di accesso amministratore**

Quando si tenta di condividere il livello di accesso amministratore con un gruppo, la casella di controllo per ciascun gruppo non risponde e il gruppo non ottiene il livello di accesso previsto.

+++

+++**Aggiornamento di manutenzione del 20 febbraio 2025**

### Aggiornamento di manutenzione del 20 febbraio 2025

#### Notifiche

**Ritardi nelle notifiche e-mail e in-app**

Quando si verifica un evento che dovrebbe attivare le notifiche e-mail o in-app, le notifiche non vengono inviate al momento dell’evento e richiedono invece alcune ore per essere inviate.

#### Attività

**Una volta spostata, l’ora registrata rimane sul progetto precedente**

Dopo lo spostamento delle attività in un nuovo progetto, il totale delle ore del progetto originale include anche le ore delle attività spostate. Le attività continuano a mantenere correttamente le ore registrate nel nuovo progetto.

#### Schede orario

**Ore totali non corrette**

Il calcolo delle ore totali delle schede orario mostra occasionalmente una somma non corretta.

+++

+++**Aggiornamento di manutenzione del 13 febbraio 2025**

### Aggiornamento di manutenzione del 13 febbraio 2025

#### Moduli personalizzati

**I dati personalizzati non vengono visualizzati nel pannello Riepilogo**

Quando un cliente visualizza il pannello Riepilogo di un’attività, i dati personalizzati che dovrebbero comparire nel pannello Riepilogo non sono presenti. Ciò può verificarsi anche se il modello di layout per le attività include i campi personalizzati.

#### Rapporti

**Problemi di visualizzazione del prompt**

Durante l’accesso a un rapporto richiesto con un numero elevato di prompt, la finestra di dialogo del prompt non consente lo scorrimento per accedere a tutti i prompt o al pulsante Esegui report.

+++

+++**Aggiornamento di manutenzione del 6 febbraio 2025**

### Aggiornamento di manutenzione del 6 febbraio 2025

#### Elenchi

**Impossibile modificare l’elenco delle attività dopo il caricamento della bozza**

Durante il caricamento di una bozza in un progetto, l’elenco delle attività per tale progetto non può essere modificato in linea fino a quando la pagina non viene aggiornata o il caricamento della bozza non è completato.

+++

## Aggiornamenti di gennaio 2025

+++**Aggiornamento di manutenzione del 30 gennaio 2025**

### Aggiornamento di manutenzione del 30 gennaio 2025

#### Pagina Home

**Le approvazioni non vengono visualizzate nel widget Home**

Le approvazioni inviate da un utente non vengono visualizzate nel widget Le mie approvazioni, anche se filtrate per visualizzarle in modo specifico.

#### Rapporti

**I filtri per i rapporti delle ore includono date errate**

Quando viene filtrato un rapporto delle ore in modo da visualizzare solo una data specifica, in realtà nel rapporto viene inclusa una data adiacente diversa. Questo problema sembra essere relativo alle impostazioni del fuso orario.

+++

+++**Aggiornamento di manutenzione il venerdì 23 gennaio 2025**

### Aggiornamento di manutenzione il venerdì 23 gennaio 2025

#### Rapporti

**I campi di valuta personalizzati causano un errore di rapporto**

Quando una visualizzazione di rapporto contiene due o più campi di valuta personalizzati, il rapporto restituisce un errore.

#### Utenti

**Il tag “Non registrato” persiste dopo l’accesso**

Nonostante l’accesso sia riuscito almeno una volta, il tag “non registrato” non scompare come previsto per i nuovi utenti.

+++

+++**Aggiornamento di manutenzione il venerdì 16 gennaio 2025**

### Aggiornamento di manutenzione il venerdì 16 gennaio 2025

#### Documenti

**Errore “Modifiche non salvate” durante l’aggiunta di un modulo a un documento**

Quando si aggiunge un modulo a un documento, viene visualizzato un errore “Modifiche non salvate” che non può essere chiuso e impedisce l’interazione con l’applicazione.

#### Bozze

**Il nome della bozza non viene visualizzato nella scheda del browser**

Quando un utente visualizza una bozza, il nome della bozza non è visibile nella scheda del browser. Nella scheda del browser viene invece visualizzato “Workfront”.

#### Richieste e problemi

**Errore con le assegnazioni avanzate di un utente**

Quando un utente cerca di effettuare un’assegnazione avanzata a un problema o a una richiesta, l’utente non viene assegnato e visualizza il seguente messaggio di errore:

“Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova ad aggiornare la pagina del browser.”

L’aggiornamento della pagina del browser non ha alcun effetto.

#### Richieste

**Impossibile creare richieste negli ambienti di Anteprima**

Quando si tenta di creare una nuova richiesta in un ambiente sandbox di anteprima, viene visualizzato un errore che indica che la coda richieste non è più disponibile e che non è possibile creare la richiesta.

+++

## Aggiornamenti di manutenzione precedenti

Le informazioni sugli aggiornamenti di manutenzione precedenti sono disponibili qui:

* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2024](2024-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2023](2023-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2022](2022-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2021](2021-updates.md)
