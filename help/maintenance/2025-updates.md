---
title: Aggiornamenti di manutenzione di Workfront nel 2025
description: Aggiornamenti di manutenzione per [!DNL Adobe Workfront]
feature: Get Started with Workfront
source-git-commit: 28cc4e22ad9c05b1a3e2ecac5bca62ff8d6f4e49
workflow-type: ht
source-wordcount: '3668'
ht-degree: 100%

---

# Aggiornamenti di manutenzione di [!DNL Workfront] nel 2025

>[!NOTE]
>
>Per informazioni sulle interruzioni di manutenzione per tutti i prodotti Adobe, incluso Workfront, consulta la [pagina di stato Adobe](https://status.adobe.com/it/).

Questa pagina descrive i problemi risolti negli aggiornamenti settimanali di Workfront.

Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

Per gli aggiornamenti di manutenzione precedenti al 2025, consulta [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2025.

## Aggiornamenti di dicembre 2025

+++**Aggiornamenti di manutenzione della funzione Pianificazione di Workfront - Settimana dal 21 al 27 dicembre 2025**

### Aggiornamenti di manutenzione della funzione Pianificazione di Workfront - Settimana dal 21 al 27 dicembre 2025

#### Errore durante la rimozione del campo connesso

Quando un utente tenta di rimuovere un campo connesso nella funzione Pianificazione di Workfront, non può rimuoverlo e viene visualizzato il messaggio “Impossibile eliminare il campo. Riprova.”

+++

+++**Aggiornamenti di manutenzione - Settimana dal 21 al 27 dicembre 2025**

### Aggiornamenti di manutenzione - Settimana dal 21 al 27 dicembre 2025

#### Moduli personalizzati

**Impossibile modificare i campi formattati**

Quando un utente tenta di modificare un campo formattato all’interno di un modulo personalizzato, le modifiche non vengono salvate e il campo non viene aggiornato con le modifiche.

#### Attività

**Impossibile selezionare il ruolo utente durante la creazione di un’attività**

Quando un utente crea un’attività e vuole assegnare un ruolo utente, non può farlo perché manca l’opzione per l’assegnazione del ruolo utente.

+++

+++**Aggiornamenti di manutenzione della funzione Pianificazione di Workfront - Settimana dal 14 al 20 dicembre 2025**

### Aggiornamenti di manutenzione della funzione Pianificazione di Workfront - Settimana dal 14 al 20 dicembre 2025

#### Impossibile aggiungere un campo a una visualizzazione

>[!NOTE]
>
>* Questo problema è stato segnalato nella sandbox di aggiornamento personalizzata.

Quando si tenta di aggiungere un campo a una visualizzazione nella funzione Pianificazione di Workfront, questo non viene aggiunto e viene visualizzato il seguente messaggio:

“Impossibile creare la colonna del campo. Riprova.”

+++

+++**Aggiornamenti di manutenzione - Settimana dal 14 al 20 dicembre 2025**

### Aggiornamenti di manutenzione - Settimana dal 14 al 20 dicembre 2025

#### Approvazioni

**Collegamenti alle approvazioni non disponibili**

Quando un utente viene assegnato come approvatore a un oggetto, il collegamento a tale oggetto non viene visualizzato nell’area I miei aggiornamenti o nel widget Le mie approvazioni della pagina Home.

#### Assegnazioni

**Le assegnazioni del team non vengono salvate**

Quando un utente assegna un team a un elemento di lavoro in Workfront, l’assegnazione non viene salvata e il team non riceve alcuna notifica per tale lavoro.

#### Richieste

**Le autorizzazioni non vengono ereditate durante la creazione di una richiesta**

Quando un utente crea una richiesta, questa non eredita le autorizzazioni. L’utente potrebbe quindi non essere in grado di accedere alla richiesta.

#### Pianificazioni

**Le autorizzazioni per la pianificazione vengono revocate per un gruppo**

Quando un amministratore di un gruppo Workfront aggiunge un’eccezione di data a una pianificazione e salva le modifiche, le autorizzazioni per tale pianificazione vengono rimosse dal gruppo e l’amministratore di Workfront deve concedere l’accesso al gruppo.


#### Attività

**Le modifiche in linea apportate a un’attività non vengono salvate**

Quando, nella precedente esperienza per le attività, un utente apporta modifiche in linea a un’attività e le salva, tali modifiche non vengono salvate.

#### Schede orario

**Le schede orario non vengono generate**

Le schede orario non vengono generate in automatico come previsto. Questo può verificarsi anche se i profili delle schede orario sono accurati; le schede orario per altre settimane vengono generate correttamente.

#### Utenti

**Problemi di modifica del profilo bozza**

Sono stati segnalati i seguenti problemi in merito alla modifica del profilo bozza di un utente:

* Quando un utente assegna un profilo bozza diverso a un altro utente e lo salva, la modifica non viene salvata e l’utente mantiene il profilo bozza precedente.
* Il profilo bozza visualizzato per un utente potrebbe essere errato, anche se è stato assegnato il profilo bozza corretto.
* Quando si apportano altre modifiche a un utente, potrebbero cambiare anche le relative autorizzazioni di bozza.

**L’opzione per generare in automatico le bozze manca nel profilo utente**

Quando un utente visualizza un profilo utente, non è disponibile l’opzione “Genera automaticamente delle bozze quando vengono caricati i documenti”. Questo può verificarsi anche se sono stati soddisfatti tutti i prerequisiti per questa opzione.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 7 al 13 dicembre 2025**

### Aggiornamenti di manutenzione - Settimana dal 7 al 13 dicembre 2025

#### Richieste

**Impossibile caricare nella richiesta un documento da GDrive**

Quando, nella nuova esperienza di richiesta, un utente crea una richiesta e tenta di caricarvi un documento da GDrive, la finestra di GDrive non risponde. L’utente non può selezionare un file né chiudere la finestra.


#### Utenti

**La modifica in blocco degli utenti rimuove i pool di risorse e i riporti diretti**

Quando un utente modifica in blocco gli utenti, fa clic sul campo Pool di risorse e non immette un valore, vengono rimossi i pool di risorse per tutti gli utenti modificati.

La modifica in blocco può anche rimuovere i riporti diretti dagli utenti modificati.

**Errore durante l’apertura della pagina Utenti**

Quando un utente tenta di aprire la pagina Utenti dal menu principale, questa non si apre e viene visualizzato il seguente messaggio:

“Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova ad aggiornare la pagina del browser.”

+++

+++**Aggiornamenti di manutenzione - Settimana dal 30 novembre al 6 dicembre 2025**

### Aggiornamenti di manutenzione - Settimana dal 30 novembre al 6 dicembre 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

## Aggiornamenti di novembre 2025

+++**Aggiornamenti di manutenzione della funzione Pianificazione di Workfront - Settimana dal 16 al 22 novembre 2025**

### Aggiornamenti di manutenzione della funzione Pianificazione di Workfront - Settimana dal 16 al 22 novembre 2025

#### Moduli personalizzati

**Indicatore attivo/inattivo aggiunto all’elenco dei moduli personalizzati in cui viene utilizzato un campo**

Nel designer di moduli personalizzati puoi selezionare un campo e fare clic su **Visualizza moduli correlati** per ottenere un elenco di tutti gli altri moduli in cui è utilizzato tale campo. Vengono elencati i moduli che saranno interessati dalla modifica del campo in questione.

Questo elenco è stato migliorato con l’aggiunta di un indicatore attivo/inattivo per ogni modulo. È quindi possibile vedere subito se il campo è attualmente utilizzato in moduli attivi o inattivi.

+++

+++**Aggiornamenti di manutenzione della funzione Pianificazione di Workfront - Settimana dal 9 al 15 novembre 2025**

### Aggiornamenti di manutenzione della funzione Pianificazione di Workfront - Settimana dal 9 al 15 novembre 2025

#### Tipi di record

**Le opzioni Modifica e Impostazioni sono state rimosse dal menu Altro di un tipo di record**

Le opzioni Modifica e Impostazioni sono state rimosse dal menu Altro di un tipo di record globale aggiunto a un’area di lavoro secondaria da un tipo di record globale esistente. Prima di questo aggiornamento, i menu risultavano oscurati e non funzionanti.

+++

+++**Aggiornamenti di manutenzione della settimana dal 9 al 15 novembre 2025**

### Aggiornamenti di manutenzione - Settimana dal 9 al 15 novembre 2025

#### Attività

**L’aggiunta di predecessori non dipende più dalle impostazioni secondarie di Modifica delle attività nel livello di accesso**

Per poter aggiungere predecessori alle attività, l’accesso con autorizzazioni Modifica deve essere abilitato per le attività nel livello di accesso, a prescindere dalle impostazioni secondarie selezionate. Questo è ora coerente con la funzionalità API esistente.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 2 all’8 novembre 2025**

### Aggiornamenti di manutenzione - Settimana dal 2 all’8 novembre 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 26 ottobre al 1° novembre 2025**

### Aggiornamenti di manutenzione - Settimana dal 26 ottobre al 1° novembre 2025

#### Rapporti

**Problemi relativi ai menu a discesa nei grafici**

Sono stati segnalati i seguenti problemi relativi ai menu a discesa nei grafici:

* Quando un utente visualizza un rapporto con una colonna a discesa e utilizza la funzione Grafico, il menu a discesa nella finestra Grafico non funziona.
* Quando un utente tenta di assegnare gli utenti da un rapporto utilizzando un menu a discesa, l’assegnazione non viene salvata.

#### Utenti

**Impossibile utilizzare le opzioni avanzate durante la creazione di utenti**

Quando un amministratore di Workfront crea un utente e tenta di utilizzare l’opzione avanzata, non può utilizzare le opzioni e viene visualizzato il seguente messaggio:

```
Cannot read properties of undefined (reading 'sections')

Cannot read properties of undefined (reading 'sections')

Error fetching object details
```

+++

## Aggiornamenti di ottobre 2025

+++**Aggiornamenti di manutenzione - Settimana dal 19 al 25 ottobre 2025**

### Aggiornamenti di manutenzione - Settimana dal 19 al 25 ottobre 2025

#### Moduli personalizzati

**La logica di visualizzazione dei campi non viene seguita correttamente**

Quando un utente compila un modulo personalizzato che include una logica di visualizzazione (in cui alcuni campi sono visualizzati o meno in base ai valori di altri campi), i campi non vengono visualizzati seguendo tale logica.

#### Bozze

**Impossibile chiudere il visualizzatore bozza**

Quando un utente visualizza una bozza nel visualizzatore di bozze e tenta di chiuderla facendo clic sul pulsante X in alto a destra, la bozza non viene chiusa.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 12 al 18 ottobre 2025**

### Aggiornamento di manutenzione - Settimana dal 12 al 18 ottobre 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 5 all’11 ottobre 2025**

### Aggiornamento di manutenzione - Settimana dal 5 all’11 ottobre 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 28 settembre al 4 ottobre 2025**

### Aggiornamenti di manutenzione - Settimana dal 28 settembre al 4 ottobre 2025

#### Programmi

**Impossibile salvare durante la modifica di un programma**

Quando un utente modifica un programma e tenta di salvare le modifiche, queste non vengono salvate.

+++

## Aggiornamenti di settembre 2025

+++**Aggiornamenti di manutenzione - Settimana dal 21 al 27 settembre 2025**

### Aggiornamenti di manutenzione - Settimana dal 21 al 27 settembre 2025

#### Utenti

**Impossibile modificare le impostazioni delle notifiche per un altro utente**

Quando un utente tenta di modificare le impostazioni di notifica per un altro utente, non può modificarle e viene visualizzato il seguente messaggio:

“Non hai l’accesso necessario per modificare i dati finanziari.”

+++

+++**Aggiornamenti di manutenzione - Settimana dal 14 al 20 settembre 2025**

### Aggiornamenti di manutenzione - Settimana dal 14 al 20 settembre 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 7 al 13 settembre 2025**

### Aggiornamenti di manutenzione - Settimana dal 7 al 13 settembre 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++


+++**Aggiornamenti di manutenzione - Settimana dal 31 agosto al 6 settembre 2025**

### Aggiornamento di manutenzione - Settimana dal 31 agosto al 6 settembre 2025

#### API

**Nuovi guardrail per evitare di sovraccaricare le sottoscrizioni a eventi**

Le sottoscrizioni a eventi sono progettate per la distribuzione affidabile degli eventi per tutti gli utenti. A tal fine, sono state introdotte misure di salvaguardia per impedire una produzione eccessiva di eventi da parte di un singolo utente, con potenziali problemi di qualità del servizio per tutti gli utenti. Di conseguenza, un utente che produce troppi eventi con frequenza elevata in un breve arco temporale può essere soggetto a sandboxing e a ritardi nella consegna degli eventi.

#### Documenti

**Gli utenti aggiunti come approvatori non ricevono alcuna notifica una volta completata l’approvazione**

Se, dopo che un utente ha approvato un documento, vengono aggiunti altri utenti come approvatori, questi ultimi non ricevono notifiche in-app o e-mail della richiesta di approvazione.

+++

## Aggiornamenti di agosto 2025

+++**Aggiornamenti di manutenzione - Settimana dal 24 al 30 agosto 2025**

### Aggiornamento di manutenzione - Settimana dal 24 al 30 agosto 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 17 al 23 agosto 2025**

### Aggiornamento di manutenzione - Settimana dal 17 al 23 agosto 2025

#### Progetti

**Errore durante l’aggiunta di un progetto a un programma**

Quando un utente tenta di aggiungere un progetto esistente a un programma, il progetto non viene aggiunto e viene visualizzato il seguente messaggio di errore:

“Errore durante il caricamento del contenuto secondario...”

**I progetti esportati contengono ore effettive imprecise**

Quando un utente esporta un progetto in Excel, la colonna Ore effettive non mostra i dati corretti.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 10 al 16 agosto 2025**

### Aggiornamento di manutenzione - Settimana dal 10 al 16 agosto 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 3 al 9 agosto 2025**

### Aggiornamento di manutenzione - Settimana dal 3 al 9 agosto 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 27 luglio al 2 agosto 2025**

### Aggiornamenti di manutenzione - Settimana dal 27 luglio al 2 agosto 2025

#### Progetti

**Ora viene visualizzato un avviso quando la timeline non è stata ricalcolata**

Ora un’icona di avviso informa gli utenti quando la timeline del progetto non è stata ricalcolata. Quando si passa il puntatore su questa icona, viene visualizzato il seguente messaggio:

“La timeline del progetto non è corretta. I project manager potrebbero dover ricalcolare manualmente la timeline.”

A volte, la timeline non può essere ricalcolata se un progetto è estremamente complesso. Questo si verifica ad esempio se un progetto ha più dipendenze, un numero elevato di attività, più predecessori in progetti diversi o più rientri di attività.

In precedenza, non vi era alcuna indicazione che una timeline non fosse stata ricalcolata.

#### Attività

**L’area Approvazioni scompare dalla barra di navigazione a sinistra**

Quando un utente visualizza un’attività, l’area Approvazioni potrebbe non essere più visibile nella barra di navigazione a sinistra. Questo può essere risolto con la rimozione e quindi l’aggiunta dell’area Approvazioni al modello di layout, tuttavia il problema potrebbe ripresentarsi.

+++

## Aggiornamenti di luglio 2025

+++**Aggiornamenti di manutenzione - Settimana dal 20 al 26 luglio 2025**

### Aggiornamenti di manutenzione - Settimana dal 20 al 26 luglio 2025

#### Bozze

**Impossibile taggare gli utenti nei commenti di una bozza**

Quando si tenta di taggare un utente in un commento di una bozza e si inizia a digitare il nome dell’utente, questo non viene visualizzato nell’elenco e non può essere selezionato per essere taggato.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 13 al 19 luglio 2025**

### Aggiornamenti di manutenzione - Settimana dal 13 al 19 luglio 2025

### Integrazioni

**Problemi relativi all’integrazione di Workfront per Slack**

I seguenti problemi sono stati segnalati in relazione all’integrazione di Workfront per Slack:

* Gli utenti non ricevono alcuna notifica in Slack quando vengono apportati aggiornamenti in Workfront.
* Gli utenti non possono accedere a Workfront da Slack.
* Altri comandi nell’integrazione di Workfront per Slack non funzionano come previsto.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 6 al 12 luglio 2025**

### Aggiornamenti di manutenzione - Settimana dal 6 al 12 luglio 2025

### Progetti

**Impossibile spostare il progetto nel programma specificato**

Quando un utente tenta di spostare un progetto in un programma, l’operazione non viene eseguita. Questo può verificarsi anche se l’utente riceve un messaggio di tipo “Il progetto è stato spostato correttamente”.

+++

## Aggiornamenti di giugno 2025

+++**Aggiornamenti di manutenzione - Settimana dal 22 al 27 giugno 2025**

### Aggiornamento di manutenzione - Settimana dal 22 al 27 giugno 2025

#### Bozze

**Impossibile aprire una bozza dal collegamento diretto**

Quando un utente tenta di aprire una bozza da un collegamento diretto, la bozza non viene aperta. Questo può verificarsi anche se l’utente fa parte di un flusso di lavoro per la bozza o se è un amministratore di Workfront.

#### Rapporti

**L’approfondimento di un grafico include risultati errati**

Quando un utente visualizza un rapporto con grafici e tenta di approfondire un raggruppamento specifico, i dettagli includono risultati che non appartengono al raggruppamento selezionato.

Questo problema è stato segnalato nei rapporti raggruppati per data.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 15 al 21 giugno 2025**

### Aggiornamento di manutenzione - Settimana dal 15 al 21 giugno 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamenti di manutenzione - Settimana dall’8 al 14 giugno 2025**

### Aggiornamento di manutenzione - Settimana dall’8 al 14 giugno 2025

#### Pianificazione risorse

**Il pulsante Esporta è disabilitato**

Quando un utente tenta di esportare da Pianificazione risorse, il pulsante è disabilitato (non disponibile) e l’esportazione non può essere eseguita.

#### Schede orario

**Schede orario non generate correttamente**

Quando un utente tenta di generare le schede orario e l’operazione è impostata su “Ogni due settimane”, viene generata solo una settimana.

+++

+++**Aggiornamenti di manutenzione - Settimana dal 1° al 7 giugno 2025**

### Aggiornamento di manutenzione - Settimana dal 1° al 7 giugno 2025

### Ricerca

**La ricerca avanzata non restituisce i risultati previsti**

Quando un utente utilizza la ricerca avanzata, non vengono restituiti i risultati previsti. Questo può verificarsi anche se non sono stati applicati filtri alla ricerca avanzata.

+++

## Aggiornamenti di maggio 2025

+++**Aggiornamenti di manutenzione - Settimana dal 25 al 31 maggio 2025**

### Aggiornamento di manutenzione - Settimana dal 25 al 31 maggio 2025

Gli aggiornamenti di questa settimana includono solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione del 22 maggio 2025**

### Aggiornamento di manutenzione del 22 maggio 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione del 15 maggio 2025**

### Aggiornamento di manutenzione del 15 maggio 2025

#### Rapporti

**Errore durante la visualizzazione di un rapporto con una vista milestone**

Quando si tenta di visualizzare un rapporto in cui è presente una vista milestone da abilitare, il rapporto non viene caricato e viene visualizzato un errore.

+++

+++**Aggiornamento di manutenzione dell’8 maggio 2025**

### Aggiornamento di manutenzione dell’8 maggio 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione del 1° maggio 2025**

### Aggiornamento di manutenzione del 1° maggio 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

## Aggiornamenti di aprile 2025

+++**Aggiornamento di manutenzione del 24 aprile 2025**

### Aggiornamento di manutenzione del 24 aprile 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione del 17 aprile 2025**

### Aggiornamento di manutenzione del 17 aprile 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione del 10 aprile 2025**

### **Aggiornamento di manutenzione del 10 aprile 2025**

#### Dashboard

**La dashboard personalizzata non si apre**

Quando si visualizza un oggetto e si tenta di aprire una dashboard personalizzata associata all’oggetto, questa non si apre.

#### Rapporti

**Utenti in fusi orari diversi ottengono risultati diversi nei rapporti**

Gli utenti in fusi orari diversi che utilizzano il selettore data per ottenere un rapporto per una determinata data ottengono risultati diversi per tale rapporto.

+++

+++**Aggiornamento di manutenzione del 3 aprile 2025**

### Aggiornamento di manutenzione del 3 aprile 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

## Aggiornamenti di marzo 2025

+++**Aggiornamento di manutenzione del 27 marzo 2025**

### Aggiornamento di manutenzione del 27 marzo 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione del 20 marzo 2025**

### Aggiornamento di manutenzione del 20 marzo 2025

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. L’assistenza Workfront ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione del 13 marzo 2025**

### Aggiornamento di manutenzione del 13 marzo 2025

#### Rapporti

**Il numero di elementi in un grafico non è accurato**

In un rapporto della dashboard, se si fa clic su un risultato del grafico con più di 15 elementi e si seleziona di visualizzarne solo 15, tutto funziona come previsto. Tuttavia, se si apre lo stesso rapporto all’esterno della dashboard e si fa clic sullo stesso risultato del grafico, questo indica che sono visualizzati tutti gli elementi, ma ne vengono mostrati solo 15.

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

Quando un cliente visualizza il pannello Riepilogo di un’attività, i dati personalizzati che dovrebbero comparire nel pannello Riepilogo non sono presenti. Ciò può verificarsi anche se il modello layout per le attività include dei campi personalizzati.

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

+++**Aggiornamento di manutenzione del 23 gennaio 2025**

### Aggiornamento di manutenzione del 23 gennaio 2025

#### Rapporti

**I campi di valuta personalizzati causano un errore di rapporto**

Quando una visualizzazione di rapporto contiene due o più campi di valuta personalizzati, il rapporto restituisce un errore.

#### Utenti

**Il tag “Non registrato” persiste dopo l’accesso**

Nonostante l’accesso sia riuscito almeno una volta, il tag “non registrato” non scompare come previsto per i nuovi utenti.

+++

+++**Aggiornamento di manutenzione del 16 gennaio 2025**

### Aggiornamento di manutenzione del 16 gennaio 2025

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
