---
title: Aggiornamenti di manutenzione per Workfront
description: Aggiornamenti di manutenzione per [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 9cd28fae4c6e1a3c6759353351de4b09a46984f3
workflow-type: tm+mt
source-wordcount: '1402'
ht-degree: 76%

---

# Aggiornamenti di manutenzione per [!DNL Workfront]

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2023.

>[!NOTE]
>
>Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. L’assistenza [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

Per gli aggiornamenti di manutenzione precedenti al 2023, vedi [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

## Aggiornamenti di febbraio 2023

+++**Aggiornamento di manutenzione del 2 febbraio 2023**

**Per impostazione predefinita, nel menu principale viene visualizzata l&#39;icona delle bacheche**

_Bacheche_

L’icona Bacheche ora viene visualizzata nel menu principale per gli utenti che non dispongono di un modello di layout. Per impostazione predefinita, le schede sono incluse anche nel menu principale per tutti i nuovi modelli di layout creati. I modelli di layout esistenti non sono stati modificati.

**Impossibile salvare i modelli e-mail**

_Configura_

Quando un utente tenta di creare o modificare un modello e-mail, il pulsante [!UICONTROL Salva] non risponde e l’utente non può salvare il modello.

+++

+++**Aggiornamento di manutenzione del 30 gennaio 2023**

**Sono state aggiunte scelte rapide da tastiera per le azioni comuni della scheda attività**

_Schede orario_

Sono state introdotte le seguenti scelte rapide da tastiera per le seguenti azioni eseguite di frequente all’interno di una scheda attività:

* Aggiungi riga (Comando+Opzione++ / Ctrl+Opzione++)
* Elimina riga (Comando+Opzione+- / Ctrl+Opzione+-)
* Fissare o sbloccare un elemento di lavoro (Opzione+P / Opzione+P)
* Commento aperto (Maiusc+F2 / Maiusc+F2)
* Salva commento (Comando+Invio / Ctrl+Invio)
* Espandi (Maiusc+Opzione+Freccia su/Maiusc+Alt+Freccia su)
* Comprimi (Maiusc+Opzione+Freccia giù/ Maiusc+Alt+Freccia giù)

L’area in cui vengono eseguite queste azioni deve essere evidenziata per poterle applicare.

**Icone nuove informazioni per schede orario, profili delle schede orario e preferenze della scheda orario**

_Schede orario_

>[!NOTE]
>
>Questo aggiornamento è stato rilasciato solo nell’ambiente Preview il 3 novembre 2022 ed è ora disponibile in Produzione.

Sono state aggiunte diverse icone di informazioni alle seguenti impostazioni:

* &quot;[!UICONTROL Può modificare il tempo]&quot; casella di controllo quando si crea o si modifica una scheda attività o un profilo di una scheda attività per indicare che, se attivato, gli approvatori possono anche inviare, riaprire o modificare la scheda attività, a meno che l&#39;amministratore non limiti queste azioni nel [!UICONTROL Preferenze foglio presenze] area [!UICONTROL Configurazione].
* &quot;[!UICONTROL Limita la modifica della scheda attività a proprietari e amministratori]&quot; nel [!UICONTROL Scheda attività e preferenze ora] area [!UICONTROL Configurazione] per indicare che, se disattivato, anche i seguenti utenti possono modificare i fogli presenze: utenti con accesso amministrativo a schede attività e ore, approvatori di schede attività autorizzati a modificare il tempo e responsabili dei proprietari delle schede attività.

La funzionalità di queste impostazioni non è stata modificata e sono state aggiunte solo le icone delle informazioni per chiarire l’ambito delle impostazioni.

+++

+++**Aggiornamento di manutenzione del 26 gennaio 2023**

**Errore durante l’invio della richiesta da[!DNL Outlook]**

_Integrazioni_

Quando un utente cerca di inviare una richiesta con allegati da un indirizzo e-mail di [!DNL Outlook], uno o più allegati non vengono caricati e l’utente visualizza il seguente errore:

“[!UICONTROL Si è verificato il seguente errore: il file con handle xxxx non esiste.]”

Ciò si verifica solo quando viene eseguita un’assegnazione per la nuova richiesta, sia attraverso la coda di richieste che sia manualmente durante la creazione della richiesta.

**Nuova versione del visualizzatore di correzione desktop**

_Verifica_

Per risolvere un problema di blocco nel visualizzatore per correzione desktop, è stata implementata una nuova versione del visualizzatore per correzione desktop. Gli utenti che hanno già installato il visualizzatore di correzione desktop riceveranno automaticamente questo aggiornamento.

Gli utenti possono anche disattivare manualmente la versione più recente. Per ulteriori informazioni, consulta [Installare il visualizzatore di correzione del desktop](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=en).

* Versione precedente: 2.1.19
* Nuova versione: 2.1.20

**L&#39;utente non può modificare le proprie impostazioni utente**

_Utenti_

Quando un utente con una licenza Lavoro, Revisione oppure Richiesta tenta di modificare le proprie impostazioni, la finestra a comparsa visualizzata è vuota e l’utente non può apportare alcuna modifica. Per uscire dalla finestra a comparsa, l’utente deve aggiornare la pagina.

+++

+++**Aggiornamento di manutenzione del 19 gennaio 2023**

**È ora possibile condividere i filtri della colonna di acquisizione**

_Bacheche_

Quando la funzione della colonna di acquisizione è stata rilasciata in Bacheche, i filtri per la configurazione di tale colonna potevano essere visualizzati solo dall’utente che li aveva creati. Ora i filtri creati dall’utente possono essere condivisi con altri utenti o team.

**Funzionalità pin disponibile nel menu [!UICONTROL Altro]**

_Navigazione_

Le seguenti funzioni sono ora disponibili nel menu [!UICONTROL Altro] per i pin, nell’ambiente Produzione:

* Rinominazione dei pin
* Riordinamento dei pin all’interno del menu [!UICONTROL Altro]
* Spostamento di un pin dal menu [!UICONTROL Altro] (in questo modo, l’ultimo pin della barra di navigazione superiore viene spostato nel menu [!UICONTROL Altro])

+++

+++**Aggiornamento di manutenzione del 18 gennaio 2023**

**Espressioni con caratteri jolly non sono valide nei campi personalizzati**

_Moduli personalizzati_

Quando un utente utilizza un carattere jolly come \$$TODAY o $$NOW insieme a un modificatore (ad esempio “-30d”) in un campo personalizzato, la convalida non lo accetta come valido. I caratteri jolly senza modificatori sono considerati validi.

**[!UICONTROL Bilanciamento del carico di lavoro] mostra ore non associate a un/una progetto/attività/problema**

_[!UICONTROL Bilanciamento del carico di lavoro]_

Quando un utente visualizza il [!UICONTROL Bilanciamento del carico di lavoro], visualizza le ore registrate per un utente che non sono associate ad alcun progetto, alcuna attività o alcun problema, né vengono registrate come ore [!UICONTROL Generali]. Queste ore possono essere visualizzate solo nella visualizzazione a 4 settimane o a 6 settimane.

+++

+++**[!DNL Adobe Workfront Fusion]Aggiornamento di manutenzione (Hot Fix) del 12 gennaio 2023**

**errori 404 nei moduli [!DNL Workfront]**

_Workfront Fusion_

Quando è in esecuzione uno scenario, un modulo [!DNL Workfront] restituisce un errore 404.

Questo problema è stato segnalato nei seguenti moduli:

* [!UICONTROL Leggi un record]

+++

+++**Aggiornamento di manutenzione (Hot Fix) del 12 gennaio 2023**

**“[!UICONTROL Ops]”, si è verificato un errore durante la configurazione di un campo calcolato**

_Moduli personalizzati_

Quando un utente crea o modifica un campo calcolato in un modulo personalizzato e include un campo personalizzato nell’espressione del campo calcolato, l’espressione viene considerata non valida. Il pulsante [!UICONTROL Salva] è disattivato e l’utente non può spostarsi dal campo personalizzato. Inoltre, l’utente visualizza il seguente messaggio sotto il campo.

“[!UICONTROL Ops! Si è verificato un errore. Contatta Workfront in modo che possiamo capire qual è stato il problema e risolverlo.]”

La rimozione del campo personalizzato dall’espressione consente all’utente di salvare e spostarsi dal campo.

**Impossibile impostare i livelli di accesso**

_Utenti_

Quando un utente tenta di modificare il livello di accesso di un altro utente, i livelli di accesso sono disattivati e non possono essere modificati. Ciò si verifica anche quando l’utente che tenta di apportare la modifica è un amministratore di sistema.

+++

+++**Aggiornamento di manutenzione del 12 gennaio 2023**

**Ctrl+F o Comando+F non funziona come previsto nei campi a discesa**

_Moduli personalizzati_

Quando si compila un modulo personalizzato e si cerca in un elenco a discesa utilizzando la scelta rapida Ctrl+F o Comando+F, quindi si tenta di passare all’istanza successiva della ricerca, l’elenco a discesa non passa a tale istanza ma ritorna all’inizio. Questo si verifica se il menu a discesa è impostato per consentire selezioni multiple.

La schermata **[!UICONTROL Edit Report] (Modifica report) è vuota**

_Report_

Quando un utente visualizza un report e tenta di modificarlo, viene visualizzata una schermata vuota e non può modificarlo.

**Le attività con rientro non mantengono il rientro**

_Attività_

Quando un utente visualizza un elenco di attività e fa rientrare un’attività, questa torna immediatamente al suo stato originale (non rientrato).

+++

+++**Aggiornamento di manutenzione del 5 gennaio 2023**

**Funzionalità pin disponibile nel menu [!UICONTROL Altro]**

_Navigazione_

Le seguenti funzioni sono ora disponibili nel menu [!UICONTROL Altro] per i pin, solo nell’ambiente Anteprima:

* Rinominazione dei pin
* Riordinamento dei pin all’interno del menu [!UICONTROL Altro]
* Spostamento di un pin dal menu [!UICONTROL Altro] (in questo modo, l’ultimo pin della barra di navigazione superiore viene spostato nel menu [!UICONTROL Altro])

**È stata rimossa la limitazione del Gruppo di progetti per l’aggiunta di utenti al team di progetto**

_Team_

Abbiamo rimosso la limitazione che richiedeva che gli utenti da aggiungere a un team di progetto fossero nel Gruppo associato al progetto. Ora puoi aggiungere qualsiasi utente attivo a un team di progetto, indipendentemente dai gruppi di appartenenza.

**Icone nuove informazioni per schede orario, profili delle schede orario e preferenze della scheda orario**

>[!NOTE]
>
>Questo aggiornamento è stato rilasciato nell’ambiente Anteprima il 3 novembre 2022 ed è ora disponibile in Produzione

_Workfront_

Sono state aggiunte diverse icone di informazioni alle seguenti impostazioni:

* Casella di controllo “Can edit time” (Può modificare l’ora) durante la creazione o la modifica di una scheda orario o di un profilo della scheda orario per indicare che, se abilitata, gli approvatori possono anche inviare, riaprire o modificare la scheda orario, a meno che l’amministratore non limiti queste azioni nell’area Timesheet Preferences (Preferenze della scheda orario) di Setup (Configurazione).
* “Restrict timesheet editing to owners and admins” (Limita la modifica della scheda orario a proprietari e amministratori) nell’area Timesheet &amp; Hour Preferences (Preferenze scheda orario e ora) di Setup (Configurazione) per indicare che, se disabilitata, anche i seguenti utenti possono modificare le schede orario: utenti con accesso amministrativo a schede orario e ore, approvatori di schede orario autorizzati a modificare l’ora e responsabili dei proprietari delle schede orario.

La funzionalità di queste impostazioni non è stata modificata e sono state aggiunte solo le icone delle informazioni per chiarire l’ambito delle impostazioni.

+++

## Aggiornamenti di manutenzione precedenti

Le informazioni sui precedenti aggiornamenti di manutenzione sono disponibili qui:

* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2022](2022-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2021](2021-updates.md)
