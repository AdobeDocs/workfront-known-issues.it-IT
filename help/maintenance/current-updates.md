---
title: Aggiornamenti di manutenzione per Workfront
description: Aggiornamenti di manutenzione per [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 244d9f48b2f63bf2b0b30259e42ca9317f5ad933
workflow-type: tm+mt
source-wordcount: '879'
ht-degree: 74%

---

# Aggiornamenti di manutenzione per [!DNL Workfront]

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2023.

>[!NOTE]
>
>Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. L’assistenza [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

Per gli aggiornamenti di manutenzione precedenti al 2023, vedi [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

## Aggiornamenti di gennaio 2023

+++**Aggiornamento di manutenzione del 19 gennaio 2023**

**È ora possibile condividere i filtri della colonna di input**

_Bacheche_

Quando la funzione della colonna di aspirazione è stata rilasciata a Bacheche, i filtri per la configurazione della colonna di assunzione potevano essere visti solo dalla persona che ha creato tali filtri. Ora il creatore può condividere i filtri con altri utenti o team.

**Funzionalità pin disponibile nel menu [!UICONTROL Altro]**

_Navigazione_

Le seguenti funzioni sono ora disponibili nel [!UICONTROL Altro] nell’ambiente Produzione:

* Rinominazione dei pin
* Riordinamento dei pin all’interno del menu [!UICONTROL Altro]
* Spostamento di un pin dal menu [!UICONTROL Altro] (in questo modo, l’ultimo pin della barra di navigazione superiore viene spostato nel menu [!UICONTROL Altro])

+++

+++**Aggiornamento di manutenzione del 18 gennaio 2023**

**Espressioni con caratteri jolly non valide nei campi personalizzati**

_Moduli personalizzati_

Quando un utente utilizza un carattere jolly come \$$TODAY o $$NOW insieme a un modificatore (ad esempio &quot;-30d&quot;) in un campo personalizzato, la convalida non accetta il carattere jolly come valido. I caratteri jolly senza modificatori sono considerati validi.

**[!UICONTROL Bilanciamento del carico di lavoro] mostra ore non associate a un progetto/task/problema**

_[!UICONTROL Bilanciatore dei carichi di lavoro]_

Quando un utente visualizza il [!UICONTROL Bilanciamento del carico di lavoro], visualizzano ore registrate per un utente che non sono associate ad alcun progetto, attività o problema, né vengono registrate come [!UICONTROL Generale] ore. Queste ore possono essere visualizzate solo nella visualizzazione a 4 settimane o a 6 settimane.

+++

+++**[!DNL Adobe Workfront Fusion]Aggiornamento della manutenzione (Hotfix) il 12 gennaio 2023**

**errori 404 nei moduli[!DNL Workfront]**

_Workfront Fusion_

Quando è in esecuzione uno scenario, un modulo [!DNL Workfront] restituisce un errore 404.

Questo problema è stato segnalato nei seguenti moduli:

* [!UICONTROL Leggi un record]

+++

+++**Aggiornamento della manutenzione (Hotfix) il 12 gennaio 2023**

**&quot;[!UICONTROL Whops]&quot; errore durante l&#39;impostazione di un campo calcolato**

_Moduli personalizzati_

Quando un utente crea o modifica un campo calcolato in un modulo personalizzato e include un campo personalizzato nell’espressione del campo calcolato, l’espressione viene considerata non valida. Il pulsante [!UICONTROL Salva] è disattivato e l’utente non può spostarsi dal campo personalizzato. Inoltre, l’utente visualizza il seguente messaggio sotto il campo.

“[!UICONTROL Ops! Si è verificato un errore. Contatta Workfront in modo che possiamo capire qual è stato il problema e risolverlo.]”

La rimozione del campo personalizzato dall’espressione consente all’utente di salvare e spostarsi dal campo.

**Impossibile impostare i livelli di accesso**

_Utenti_

Quando un utente tenta di modificare il livello di accesso di un altro utente, i livelli di accesso sono disattivati e l’utente non può modificarli. Ciò si verifica anche quando l&#39;utente che tenta di apportare la modifica è un amministratore di sistema.

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
