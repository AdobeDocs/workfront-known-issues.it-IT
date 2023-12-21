---
title: Aggiornamenti di manutenzione per Workfront
description: Aggiornamenti di manutenzione per  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 704f5f9f7a460d13c7258df7865d84540e72fc6b
workflow-type: tm+mt
source-wordcount: '7697'
ht-degree: 98%

---

# Aggiornamenti di manutenzione per [!DNL Workfront]

I seguenti aggiornamenti di manutenzione sono stati effettuati nel 2023.

>[!NOTE]
>
>Tra gli aggiornamenti sono incluse anche altre correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

Per gli aggiornamenti di manutenzione precedenti al 2023, consulta [Aggiornamenti di manutenzione precedenti](#previous-maintenance-updates)

## Aggiornamenti di dicembre 2023

+++**Aggiornamento di manutenzione del venerdì 21 dicembre 2023**

**Problemi durante la visualizzazione dello stato delle sottoattività**

_Bacheche_

Sono stati segnalati i seguenti problemi relativi alla visualizzazione dello stato delle attività secondarie in una scheda in Bacheche:

* Lo stato viene visualizzato come “Seleziona stato” anche quando l’attività ha già uno stato. Questo stato può essere visualizzato quando si visualizza direttamente l’attività.
* Se l’utente cerca di selezionare uno stato, la schermata diventa vuota e deve essere aggiornata.

**Impossibile allegare un documento a una scheda**

_Bacheche_

Quando un utente tenta di allegare un documento a una scheda connessa, può selezionare il documento da allegare, ma il documento non viene visualizzato nell’area del documento della scheda e non è collegato all’oggetto a cui è connessa la scheda.

Questo problema è stato segnalato nelle schede collegate a problemi.

**Impossibile selezionare il modello da [!UICONTROL Preferiti] list**

_Modelli_

Quando un utente tenta di selezionare un modello dall’elenco [!UICONTROL Preferiti] , l’elenco dei modelli scompare quando l’utente sposta il mouse sull’elenco e non può selezionare un modello.

**Alcuni aggiornamenti non sono presenti nella nuova esperienza di commento**

_Aggiornamenti_

Quando un utente visualizza gli aggiornamenti nella nuova esperienza di commento, alcuni dei commenti da visualizzare non vengono visualizzati. Se l’utente passa all’esperienza di commento precedente, vengono visualizzati tutti i commenti.

+++

+++**[!DNL Adobe Workfront Fusion]Aggiornamento di manutenzione del giovedì 21 dicembre 2023**

L&#39;apertura del campo modulo richiede troppo tempo

_[!DNL Workfront Fusion]_

<!--no article-->

Quando un utente configura un modulo che richiede dati dall’account connesso (ad esempio per selezionare un record), il modulo non può recuperare i dati e la richiesta di dati scade.

+++

+++**Aggiornamento di manutenzione del venerdì 14 dicembre 2023**

**Le bozze in attesa di approvazione non vengono visualizzate nei rapporti**

_Bozze_

Quando un utente visualizza un rapporto per le approvazioni di bozze in sospeso, alcune approvazioni in sospeso non vengono visualizzate nel rapporto.
+++

+++**Aggiornamento di manutenzione del venerdì 7 dicembre 2023**

**Approvazione bloccata sul widget [!UICONTROL In attesa della mia approvazione]**

_Home_

Quando viene caricata una nuova versione di un documento e l’approvazione della versione precedente non è stata completata, la precedente versione del documento si blocca sul widget [!UICONTROL In attesa della mia approvazione] dell’approvatore. L’approvazione non può essere approvata perché è presente una nuova versione, né può essere rimossa dal widget.

**Problemi durante l’aggiunta di elementi di lavoro nella vista Bacheca di attività o problemi**

_Attività/problemi_

Quando un utente visualizza la vista Bacheca dell’area Attività o Problemi in un progetto e tenta di aggiungere un’attività o un problema, possono verificarsi i seguenti casi:

* La finestra a comparsa passa da uno stile di finestra all&#39;altro
* L’utente non può chiudere la finestra a comparsa

Questo problema è stato segnalato quando un utente seleziona un’area dalla navigazione a sinistra della finestra a comparsa prima di inserire eventuali informazioni.

+++

## Aggiornamenti di novembre 2023

+++**Aggiornamento di manutenzione del venerdì 30 novembre 2023**

**le attività non vengono visualizzate nel widget [!UICONTROL Il mio lavoro]**

_[!UICONTROL Home]_

Quando un utente visualizza il proprio widget [!UICONTROL Il mio lavoro] in [!UICONTROL Home], alcune delle attività che gli sono assegnate non vengono visualizzate nel widget. Ad esempio, un utente può accedere a un progetto e vedere che ha delle attività assegnate nel progetto, ma tali attività non vengono visualizzate nel suo widget [!UICONTROL Il mio lavoro].

**La pagina di accesso reindirizza alla pagina di destinazione per la disconnessione**

_Accedi_

Quando un utente cerca di accedere a [!DNL Workfront], anziché alla pagina di accesso, viene indirizzati alla pagina a che si aprirebbe se si disconnettesse.

**Errore 500 durante l’esportazione di un rapporto**

_Rapporti_

Quando un utente cerca di esportare un rapporto, l’esportazione non riesce e viene visualizzato il seguente errore:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Questo problema è stato segnalato nei rapporti che utilizzano un `valueexpression` per fare riferimento al testo della nota `lastNote`.

+++

+++**Aggiornamento di manutenzione del 16 novembre 2023**

**Le ore preventivate nel rapporto sull’utilizzo non corrispondono a quelle riportate tramite API**

_Rapporti_

Quando un utente effettua una chiamata API all’oggetto RPBGHR per un determinato progetto e confronta i risultati di tale chiamata con il rapporto sull’utilizzo del progetto, i risultati non corrispondono.

**Nella pagina Nuova richiesta viene visualizzata una valuta personalizzata errata**

_Richieste_

Quando un utente invia una richiesta ed effettua una selezione che cambia la logica di visualizzazione nel modulo della richiesta, la valuta visualizzata viene ripristinata alla valuta predefinita anziché alla valuta personalizzata impostata nel progetto rappresentato dalla coda di richieste.

Quando l’utente invia la richiesta, la valuta viene visualizzata come valuta personalizzata corretta per il progetto che la coda di richieste rappresenta

**Righe aggiuntive nel commento effettuato tramite API o[!DNL Workfront Fusion]**

_Aggiornamenti_

Quando un utente invia un commento tramite API o [!DNL Workfront Fusion], il commento visualizzato nell’area Aggiornamenti mostra righe aggiuntive. A volte le righe sono così numerose che l’utente deve scorrere verso il basso per vedere il contenuto del commento.

Questo problema è stato segnalato nella nuova esperienza di commento.

+++

+++**Aggiornamento di manutenzione del 9 novembre 2023**

**Oggetti mancanti nel widget Il mio lavoro quando non si trova nella parte superiore della pagina**

_Home_

Se il widget Il mio lavoro si trova nella parte superiore della nuova pagina Home, vengono recuperati tutti gli oggetti previsti. Tuttavia, se questo widget si trova al di sotto di qualsiasi altro widget sulla pagina, vengono estratti solo 10 oggetti.

**Impossibile generare la bozza**

_Bozze_

Quando un utente tenta di generare una bozza, l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

&quot;[!UICONTROL Errore durante la generazione della bozza]&quot;

Ciò si verifica quando l’impostazione del livello di accesso utente [!UICONTROL Visualizza informazioni di contatto] è impostata su Disattivata.

**I campi vengono cancellati quando un documento viene aggiunto a una richiesta**

_Richieste_

Quando un utente crea una richiesta, compila i campi in un modulo e poi aggiunge o rimuove un documento, alcuni campi del modulo vengono cancellati dai dati e l’utente deve compilarli nuovamente prima di inviare la richiesta.

**L’attività personale viene visualizzata nella scheda orario**

_Schede orario_

Quando un utente crea un’attività nel widget delle [!UICONTROL Cose da fare] della nuova esperienza [!UICONTROL Home], tale attività viene visualizzata nella scheda orario dell’utente. Ciò si verifica anche se l’attività non ha ore registrate e il progetto personale non è fissato.

+++

+++**Aggiornamento di manutenzione (Hot Fix) del 3 novembre 2023**

**Le attività secondarie non vengono ordinate quando vengono spostate nell’attività padre**

_Modelli_

Quando un utente crea delle attività su un modello e le sposta sotto un’attività principale, i numeri assegnati alle attività secondarie non vengono visualizzati nell’ordine previsto. Pertanto, quando la pagina si aggiorna, le attività secondarie vengono ordinate in base ai numeri delle attività impreviste e di conseguenza le attività secondarie non vengono ordinate.

+++

+++**Aggiornamento di manutenzione del 2 novembre 2023**

**Gli aggiornamenti privati vengono visualizzati nei campi dell’espressione di valore**

_Rapporti_

Quando un campo del rapporto include un’espressione di valore che fa riferimento a un aggiornamento privato, gli utenti non inclusi nell’aggiornamento privato possono visualizzarlo nel rapporto.

**L’utente viene visualizzato con un’assegnazione eccessiva a causa di una capacità imprecisa**

_Bilanciamento del carico di lavoro_

Nel Bilanciamento del carico di lavoro, un utente potrebbe essere visualizzato con un’assegnazione eccessiva. Passando il puntatore del mouse sull’assegnazione eccessiva, la capacità dell’utente è impostata su 0.

Se l’utente modifica l’intervallo di date, l’assegnazione è precisa. Tuttavia, se l’utente aggiorna la pagina, la capacità potrebbe di nuovo essere imprecisa.

+++

## Aggiornamenti di ottobre 2023

+++**Aggiornamento di manutenzione del 26 ottobre 2023**

**La ricerca non funziona**

_Bacheche_

Quando un utente esegue una ricerca sulle bacheche, la ricerca non restituisce tutte le schede che soddisfano i criteri di ricerca.

**Impossibile visualizzare la bozza interattiva nel visualizzatore Web**

_Bozze_

Quando un utente tenta di visualizzare una bozza nel proofing viewer basato sul Web, l’operazione ha esito negativo e viene visualizzato il messaggio di errore seguente:

“[!UICONTROL Parametro di query o valore cookie mancante per coppia di ID chiavi]”

**Impossibile creare una nuova versione di una bozza**

_Bozze_

Quando un utente tenta di creare una nuova versione di una bozza, l’operazione ha esito negativo viene visualizzato il messaggio di errore seguente:

&quot;[!UICONTROL Errore durante la generazione della bozza]&quot;

**L’utente viene duplicato durante la condivisione di una richiesta**

_Richieste_

Quando si condivide una richiesta, se il livello di accesso di un utente con cui viene condivisa la richiesta viene modificato, l’utente che si trova appena sopra l’utente nell’elenco diventa tale utente.

Ad esempio, se la richiesta viene condivisa con l’Utente A e l’Utente B e l’accesso dell’Utente B viene modificato, l’Utente A cambia in Utente B e nell’elenco sono ora presenti due Utenti B. Inoltre, è stato modificato solo l’accesso dell’utente B principale.

**“[!UICONTROL Errore]” errore nell’intestazione dell’attività**

_Attività_

Quando un utente visualizza un’attività, l’intestazione dell’attività non contiene informazioni. Invece, viene visualizzato il seguente messaggio di errore:

“[!UICONTROL Ops! Si è verificato un errore. Contatta Workfront per consentirci di individuare e risolvere il problema.]”

+++

+++**Aggiornamento di manutenzione del 19 ottobre 2023**

Gli utenti non ricevono notifiche sulle risposte in un thread di commenti

_Notifiche_

Quando un utente risponde a un commento, gli altri utenti che dovrebbero ricevere notifiche per la risposta non le ricevono. Alcuni utenti potrebbero ricevere la notifica, mentre altri no.

**Commento aggiuntivo vuoto durante la creazione di un commento su una bozza**

_Bozze_

Quando un utente crea un commento in una bozza, questa produce anche un altro commento vuoto.

Questo problema è stato segnalato nelle bozze video.

La scheda **[!UICONTROL Attività bozza] non si apre**

_Bozze_

Quando un utente visualizza una bozza e fa clic sulla scheda [!UICONTROL Attività bozza], la scheda lo riporta alla scheda [!UICONTROL Dettagli della bozza].

Quando un utente aggiuntivo viene assegnato a un’attività, le **[!UICONTROL Ore pianificate] vengono riallocate**

_Attività_

Quando un utente viene assegnato a un’attività con [!UICONTROL Ore pianificate] assegnate ad altri assegnatari dell’attività, tali [!UICONTROL Ore pianificate] vengono distribuite in modo uniforme a tutti gli assegnatari dell’attività.

Quando un problema viene convertito in un’attività, come nome utente negli aggiornamenti di sistema viene visualizzato **“[!UICONTROL Eliminato]”**

_Aggiornamenti_

Quando un utente che ha effettuato l’accesso come altro utente converte un problema in un’attività e il problema viene assegnato a un team, gli aggiornamenti di sistema mostrano l’utente che ha richiesto che il team lavori sull’attività come “[!UICONTROL Eliminato]”.

+++

+++**Aggiornamento di manutenzione del 12 ottobre 2023**

**Flussi di lavoro rimossi per account che non li utilizzano**

_Bacheche_

Per gli account che non hanno mai creato un flusso di lavoro nell’applicazione Bacheche, l’area Flussi di lavoro è stata rimossa dalla dashboard Bacheche. Gli account che utilizzano flussi di lavoro hanno ancora accesso a tali flussi.

**I campi calcolati non mantengono il valore quando il problema viene convertito in attività**

_Moduli personalizzati_

I campi calcolati che fanno riferimento a se stessi non mantengono i propri valori quando un problema viene convertito in un’attività.

Quando si converte un problema in un’attività, il valore desiderato viene visualizzato correttamente nella finestra di modifica. Tuttavia, al termine della conversione, nel campo calcolato viene visualizzato “N/d”.

**Errore durante la modifica dei filtri nella [!UICONTROL Home]**

_Home_

Quando un utente modifica i filtri nella [!UICONTROL Home], l’area della [!UICONTROL Home] non si carica e viene visualizzato il seguente errore:

“[!UICONTROL Si è verificato un errore. Stiamo lavorando per risolvere il problema. Per continuare con il tuo lavoro, prova ad aggiornare la pagina del browser]”.

+++

+++**Aggiornamento di manutenzione del 5 ottobre 2023**

**La bacheca si carica lentamente**

_Bacheche_

Quando un utente carica una bacheca, questa viene caricata molto lentamente. Ciò può verificarsi anche se la bacheca ha un numero limitato di schede.

Le schede archiviate, anche se non visualizzate, influiscono sul tempo di caricamento della bacheca.

**Impossibile spostare le schede tra le colonne**

_Bacheche_

Quando un utente tenta di spostare una scheda su una bacheca, la scheda non si sposta. Ciò si verifica nelle seguenti circostanze:

* Trascina e rilascia
* Spostamento opzione sulla scheda
* Modifica della scheda

**Impossibile spostare le schede dalla colonna acquisizione**

_Bacheche_

L’utente può trascinare una scheda fuori dalla colonna acquisizione in un’altra colonna sulla bacheca, ma le schede successive non possono essere spostate al di fuori della colonna acquisizione.

**La funzione di raggruppamento influisce sulle prestazioni della bacheca**

_Bacheche_

Quando l’utente tenta di raggruppare le schede per assegnatari o tag, la bacheca diventa molto lenta.

**Le e-mail di promemoria automatiche non vengono inviate**

_Notifiche_

Le e-mail di promemoria automatico non vengono inviate. È iniziato il 14 settembre 2023.

+++

## Aggiornamenti di settembre 2023

+++**Aggiornamento di manutenzione del 28 settembre 2023**

**Impossibile eliminare il campo personalizzato**

_Moduli personalizzati_

Il tentativo di eliminazione di un campo personalizzato risulta impossibile da parte dell‘utente, che visualizza il messaggio “[!UICONTROL Errore database dovuto alla violazione del vincolo].”

**I commenti creati nella nuova esperienza di commento non sono visibili nell’esperienza precedente**

_Aggiornamenti_

Quando un utente crea un commento nella nuova esperienza di commento e tale commento viene visualizzato nell’area Commenti della nuova esperienza, è possibile che lo stesso commento non venga visualizzato nell’esperienza precedente. Questo potrebbe causare la perdita di commenti per gli utenti che utilizzano l’esperienza precedente.

**La pagina dell’oggetto è priva di elementi**

_Workfront_

Quando un utente passa a una sezione personalizzata di un oggetto in [!DNL Workfront], la pagina che viene caricata potrebbe essere priva di alcuni elementi. Tali elementi possono includere:

* Pannello di navigazione a sinistra
* Nome dell’oggetto a cui appartiene la sezione personalizzata
* Campi e informazioni nell’intestazione

+++

+++**Aggiornamento di manutenzione del 21 settembre 2023**

**Impossibile assegnare l’utente a una bacheca in un flusso di lavoro**

_Bacheche_

Quando un utente cerca di assegnare un altro utente a un’attività da una bacheca che fa parte di un flusso di lavoro e inizia a digitare il suo nome, quest’ultimo non viene visualizzato nell’elenco a discesa degli utenti disponibili. Ciò si verifica anche quando l’utente è attivo ed è membro sia della bacheca che del flusso di lavoro.

L’utente può inoltre notare che gli utenti disattivati vengono visualizzati nel menu a discesa.

**Impossibile eliminare un elemento dell’elenco di controllo**

_Bacheche_

Quando un utente cerca di eliminare un elemento dell’elenco di controllo da una scheda di una bacheca, il pulsante [!UICONTROL Elimina] non risponde e l’elemento non viene eliminato.

**I moduli personalizzati vengono caricati lentamente**

_Moduli personalizzati_

Quando un utente tenta di caricare un modulo personalizzato, questo viene caricato lentamente.

**Impossibile spostare il documento in un’altra cartella**

_Documenti_

Quando un utente sposta un documento nella cartella di un oggetto, non può spostare l’oggetto in un’altra cartella.

**Errore XML durante il download**

_Documenti_

Quando un utente tenta di scaricare un documento, l’operazione ha esito negativo e l’utente visualizza una pagina con il messaggio seguente seguito da testo XML.

“[!UICONTROL Al file XML non sono associate informazioni sullo stile. La struttura del documento è riportata di seguito.]”

**Impossibile scaricare documenti da ambienti di anteprima/sandbox**

_Documenti_

Quando un utente tenta di scaricare un documento da un ambiente diverso da quello di produzione, il documento non viene scaricato e l’utente visualizza il seguente errore:

“[!UICONTROL Ops! Si è verificato un errore. Contatta Workfront per consentirci di individuare e risolvere il problema.]”

**Le bozze vengono visualizzate desaturate o ritagliate**

_Bozze_

I seguenti problemi sono stati segnalati durante la creazione di una bozza da un URL.

* La bozza viene visualizzata desaturata o sbiadita.
* La bozza è ritagliata.

Questo può rendere difficili le decisioni relative alle bozze, in quanto la bozza non viene rappresentata con precisione.

**La generazione delle bozze richiede un tempo eccessivo**

_Bozze_

Quando un utente tenta di generare una bozza, tale processo richiede un tempo eccessivo. La generazione della bozza può richiedere diversi giorni.

+++

+++**Aggiornamento di manutenzione del 14 settembre 2023**

**Errore “[!UICONTROL Nessuna factory]” durante l’aggiunta di un documento**

_Documenti_

Quando un utente tenta di aggiungere un documento da un’origine esterna, [!DNL Workfront] non può accedere all’origine e l’utente visualizza il seguente errore:

“[!UICONTROL Si è verificato il seguente errore: Nessuna factory trovata per il tipo di autenticazione null]”

**Errore “Ops” nei rapporti matrice**

_Rapporti_

Quando un utente cerca di aprire un rapporto matrice, questo non viene caricato e l’utente visualizza il seguente errore:

“[!UICONTROL Ops! Si è verificato un errore. Contatta Workfront per consentirci di individuare e risolvere il problema.]”

Ciò si verifica quando un rapporto viene raggruppato per intervalli di date.

+++

+++**Aggiornamento di manutenzione dell’11 settembre 2023**

**Le attività personali non vengono visualizzate nelle schede orario**

_Schede orario_

Le attività personali non vengono più visualizzate nella scheda orario per impostazione predefinita. Le attività personali vengono visualizzate nella scheda orario quando sono fissate o hanno ore registrate. Prima di questa modifica, le attività personali venivano visualizzate nelle schede orario per impostazione predefinita.

+++

+++**Aggiornamento di manutenzione del 7 settembre 2023**

**Il progetto è vuoto quando viene caricato da nuova esperienza [!UICONTROL Home]**

_Progetti_

Quando un utente fa clic su un progetto dalla pagina [!UICONTROL Home] nella nuova esperienza Home, la pagina del progetto non viene caricata correttamente.

Ciò si verifica quando l’utente ha effettuato l’accesso come altro utente, si è poi disconnesso come altro utente e ha ripristinato la propria pagina [!UICONTROL Home].

+++

## Aggiornamenti di agosto 2023

+++**Aggiornamento di manutenzione del 31 agosto 2023**

**i filtri non si applicano ai widget nella nuova esperienza [!UICONTROL Home]**

_[!UICONTROL Home]_

Quando un utente applica un filtro a un widget nella nuova esperienza [!UICONTROL Home], il widget mostra gli elementi che devono essere esclusi dal filtro.

Questo problema è stato segnalato nell’ambiente Sandbox personalizzata. Gli stessi widget negli ambienti di Anteprima e Produzione filtrano gli elementi nel modo previsto.

**Problemi durante il caricamento dei rapporti matrice**

_Rapporti_

Quando si tenta di caricare un rapporto matrice come grafico, può verificarsi una delle seguenti situazioni:

* Alcune informazioni nel rapporto non vengono caricate
* Il rapporto riporta l’errore “[!UICONTROL Impossibile caricare il contenuto dal server]”

**La pianificazione non viene caricata quando si applica il filtro**

_[!UICONTROL Pianificazione risorse]_

Quando un utente cerca di caricare la [!UICONTROL Pianificazione risorse], questa non viene caricata e l’utente visualizza il seguente messaggio di errore:

“[!UICONTROL Si è verificato il seguente errore: si è verificato un errore durante la connessione al servizio WorkPerDay]”

+++

+++**Aggiornamento di manutenzione del 24 agosto 2023**

**Impossibile selezionare il testo in elenchi o in elenchi puntati**

_Bozze_

Quando un utente visualizza una bozza nel Proofing Viewer e tenta di selezionare un testo incluso in un elenco o in un elenco puntato, lo strumento di selezione del testo non è efficace e non è possibile selezionare il testo.

**La creazione di una nuova versione della bozza comporta l’eliminazione di tutte le sue versioni**

_Bozze_

Quando un utente crea una bozza da un documento, la bozza viene creata. Tuttavia, se un utente crea un’altra versione della bozza, vengono eliminate sia la versione precedente che quella nuova. È presente un’opzione [!UICONTROL Crea bozza] nel documento originale e le versioni della bozza sono disponibili nel [!UICONTROL Cestino] dell’area [!UICONTROL Bozza] in [!DNL Workfront].

+++

+++**Aggiornamento di manutenzione del 17 agosto 2023**

**Impossibile accedere a un progetto con l’URL che utilizza l’[!UICONTROL ID di riferimento]**

_Progetti_

Quando un utente tenta di accedere a un progetto utilizzando un URL che include un numero [!UICONTROL ID di riferimento] viene reindirizzato a una pagina contenente un messaggio di errore. L’accesso a un’attività utilizzando un URL con un [!UICONTROL ID di riferimento] funziona come previsto.

L’impostazione **“[!UICONTROL Disabilita le notifiche e-mail delle bozze]” viene visualizzata in modo impreciso**

_Bozze_

Quando un utente visualizza le impostazioni della bozza in [!DNL Workfront], la casella di controllo “[!UICONTROL Disabilita le notifiche e-mail delle bozze]” non visualizza con precisione l’impostazione corrente corretta. Quando la casella è selezionata e indica che le notifiche e-mail delle bozze sono disabilitate, in realtà le notifiche sono abilitate. Vale anche il contrario.

**Impossibile regolare i markup della bozza**

_Bozze_

Quando un utente crea un commento nel Proofing Viewer e aggiunge un markup alla bozza, quindi fa clic in un altro punto, non può più regolare il markup.

+++

+++**Aggiornamento di manutenzione del 10 agosto 2023**

**Impossibile eliminare l’elemento [!UICONTROL Attività] nella nuova esperienza [!UICONTROL Home]**

_Home_

Quando un utente nella nuova esperienza [!UICONTROL Home] tenta di eliminare un elemento dal widget [!UICONTROL Attività], l’elemento non viene eliminato e l’utente visualizza il seguente errore:

“[!UICONTROL Si è verificato un problema durante la rimozione delle tue attività, riprova a breve.]”

Ciò può verificarsi quando sono presenti ore registrate in un elemento [!UICONTROL Attività].

**Un progetto fissato non presenta informazioni in alcune colonne**

_Progetti_

Quando un utente passa a un progetto fissato utilizzando il pin, gli elenchi di oggetti (come l’elenco delle attività) possono mostrare colonne vuote. Ad esempio, una colonna [!UICONTROL Assegnazioni] potrebbe non mostrare alcuna assegnazione, anche se sono state effettuate delle assegnazioni.

**Il modulo di sospensione provoca il blocco degli scenari**

_[!DNL Workfront Fusion]_

[!UICONTROL Strumenti] > Modulo di [!UICONTROL sospensione] in uno scenario può causare il blocco dell’esecuzione di uno scenario. Queste esecuzioni mostrano lo stato In esecuzione nella [!UICONTROL Cronologia scenario], e non si concludono.

+++

+++**Aggiornamento di manutenzione del 3 agosto 2023**

**Difficoltà a individuare gli elementi nella colonna acquisizione**

_Bacheche_

La colonna acquisizione su una bacheca era precedentemente ordinata in base alla priorità definita per attività e problemi, il che rendeva difficile individuare elementi specifici.

L’ordine predefinito è ora il seguente:

Attività:

* Ordine principale: nome progetto
* Ordine secondario: struttura dettaglio lavoro

Problemi

* Ordine principale: nome progetto
* Ordine secondario: numero di riferimento

**Il progetto non risolve correttamente il problema**

_Progetti/Problemi_

Quando un utente modifica lo stato di un progetto che è l’oggetto di risoluzione di un problema, lo stato del problema viene modificato in uno stato che non corrisponde alla stessa chiave dello stato del progetto.

**Errore “Ops” nei rapporti matrice**

_Rapporti_

Quando un utente cerca di aprire un rapporto matrice, questo non viene caricato e l’utente visualizza il seguente errore:

“[!UICONTROL Ops! Si è verificato un errore. Contatta Workfront per consentirci di individuare e risolvere il problema]”

Questo problema è stato segnalato per gli utenti dell’area EMEA.

+++

## Aggiornamenti di luglio 2023

+++**Aggiornamento di manutenzione del 27 luglio 2023**

**I tag e gli elementi di un elenco di controllo non funzionano correttamente nella vista bacheca del progetto**

_Bacheche_

I tag e gli elementi di un elenco di controllo sono stati rimossi dalla vista bacheca dei progetti perché non fanno parte delle attività di Workfront e non possono essere condivisi tra gli utenti.

**“[!UICONTROL Abilita a livello di sistema]” e “[!UICONTROL Visualizza a livello di sistema]” rappresentano funzionalità diverse**

_Filtri_

Se un utente condivide un filtro e abilita la funzione &quot;[!UICONTROL Visualizza a livello di sistema]&quot;, il filtro viene condiviso con ogni utente del sistema. Tuttavia, se un amministratore visualizza questo filtro in [!UICONTROL Configurazione], il filtro viene visualizzato come &quot;[!UICONTROL falso]&quot; nella colonna &quot;[!UICONTROL Visibile a livello di sistema]&quot;. Per impostare questo filtro come predefinito del sistema, l’amministratore deve abilitare &quot;[!UICONTROL Abilita a livello di sistema]&quot; in [!UICONTROL Configurazione]. Ciò può creare confusione a causa della formulazione simile di queste due opzioni.&quot;

+++

+++**Aggiornamento di manutenzione del 20 luglio 2023**

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione del 13 luglio 2023**

**La timeline non viene ricalcolata**

_Progetti / Attività / Problemi_

Quando si verifica un evento che deve attivare un calcolo della timeline, la timeline non viene ricalcolata. Questo influisce sui ricalcoli che si verificano sulle modifiche e sui ricalcoli pianificati. Può influire sulla precisione del Bilanciamento del carico di lavoro.

**Le approvazioni delle bozze bloccate vengono ancora visualizzate nell’Elenco lavori**

_Bozze_

Le approvazioni delle bozze che hanno superato la scadenza e sono bloccate vengono ancora visualizzate nell’Elenco lavori della Home dell’approvatore, invece di essere eliminate dall’elenco quando la scadenza viene superata.

**Il rapporto di utilizzo non viene caricato**

_Rapporti_

Quando si tenta di visualizzare un rapporto di utilizzo, viene visualizzato un indicatore di caricamento che ruota, ma il rapporto non si carica. Il rapporto restituisce un errore 500, ma all’utente non viene presentata alcuna indicazione di errore.

**La pagina Modifica utente è vuota**

<!--no article-->

_Utenti_

Quando un utente cerca di modificare un altro utente, la pagina Modifica utente è vuota e l’utente non può modificare l’altro utente.

+++

## Aggiornamenti di giugno 2023

+++**Aggiornamento di manutenzione del 29 giugno 2023**

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione del 22 giugno 2023**

**Errore “[!UICONTROL Ops]” durante la visualizzazione di un rapporto matrice**

_Rapporti_

Quando un utente visualizza un rapporto matrice, compare il seguente errore:

“[!UICONTROL Ops! Si è verificato un errore. Contatta Workfront per consentirci di individuare e risolvere il problema.]”

Questo problema è stato segnalato quando il rapporto è ordinato per data e l’opzione “[!UICONTROL Mostra settimane senza risultati]” è abilitata.

**Le date non vengono visualizzate correttamente nei rapporti matrice**

_Rapporti_

Quando un grafico o un rapporto matrice viene raggruppato per data, le date vicine ai limiti del raggruppamento possono essere visualizzate nel raggruppamento corretto, nel raggruppamento precedente/successivo o in entrambi.

+++

+++**Aggiornamento di manutenzione del 15 giugno 2023**

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**Aggiornamento di manutenzione dell’8 giugno 2023**

Questo aggiornamento contiene solo correzioni di bug minori o meno importanti. Il supporto di [!DNL Workfront] ti avvisa quando viene risolto un problema che hai segnalato.

+++

+++**[!DNL Adobe Workfront Fusion]Aggiornamento di manutenzione dell’8 giugno 2023**

[!DNL Fusion] ha implementato una correzione che impedisce la rimozione delle connessioni di un utente quando questo viene rimosso o disattivato in [!UICONTROL Adobe Admin Console].

Gli amministratori del team di [!DNL Fusion] sono ancora in grado di rimuovere le connessioni non necessarie dalla pagina [!UICONTROL Connessioni] in [!DNL Fusion].

+++

+++**Aggiornamento di manutenzione del 1° giugno 2023**

**Nessun messaggio di errore quando si cambia l’ordine di un’attività nello stato [!UICONTROL Approvazione in sospeso]**

_Attività_

Quando un utente tenta di riordinare, in un elenco di attività, un’attività in stato [!UICONTROL Approvazione in sospeso], questa sembra venire spostata nell’elenco delle attività. Dopo l’aggiornamento, l’utente vede che l’elemento non è stato spostato. L’elemento non può essere spostato perché è in stato [!UICONTROL Approvazione in sospeso], ma non è presente alcun messaggio che dà tale informazione all’utente e questo potrebbe creare confusione.

**Nessun messaggio di errore quando si sposta un’attività predecessore sotto un’attività dipendente**

_Attività_

Quando un utente tenta di riordinare, in un elenco di attività, un’attività in stato [!UICONTROL Approvazione in sospeso], questa sembra venire spostata nell’elenco delle attività. Dopo l’aggiornamento, l’utente vede che l’elemento non è stato spostato. L’elemento non può essere spostato perché un’attività predecessore non può essere spostata sotto un’attività di cui è predecessore; tuttavia l’utente non riceve alcun messaggio in merito e questo potrebbe creare confusione.

+++

## Aggiornamenti di maggio 2023

+++**Aggiornamento di manutenzione del 25 maggio 2023**

La bacheca **[!UICONTROL Kanban] rimane vuota durante la modifica delle schede**

_Agile_

Quando un utente cambia qualcosa in una scheda nella bacheca [!UICONTROL Kanban], la bacheca [!UICONTROL Kanban] diventa vuota invece di aggiornarsi con la modifica. Se l’utente ricarica la pagina manualmente, la bacheca [!UICONTROL Kanban] viene visualizzata con la modifica corretta.

Questo problema è stato segnalato nelle seguenti situazioni:

* Modifica di una scheda
* Spostamento di una scheda


+++

+++**Aggiornamento di manutenzione del 22 maggio 2023**

**Impossibile regolare la dimensione di un testo descrittivo**

_Moduli personalizzati_

Quando il Designer dei moduli personalizzati è stato rilasciato in versione beta, la la funzionalità per regolare le dimensioni del testo descrittivo non era disponibile. Questo problema è stato risolto e gli utenti possono ora regolare le dimensioni del testo descrittivo.

+++

+++**Aggiornamento di manutenzione del 18 maggio 2023**

**Se si ordina per un campo personalizzato, il rapporto non viene ordinato correttamente**

_Rapporti_
Quando un utente esegue un rapporto di attività, il rapporto sembra venire ordinato in modo corretto durante il caricamento, ma al termine dell’operazione l’utente visualizza che il rapporto non è ordinato correttamente.

Questo sembra accadere se sono soddisfatte tutte le seguenti circostanze:

* Il rapporto è un rapporto di attività
* Il rapporto è ordinato in base a un campo personalizzato
* Al rapporto è applicato un raggruppamento

+++

+++**Aggiornamento di manutenzione dell’11 maggio 2023**

**Impossibile passare da una versione della bozza all’altra durante la visualizzazione della bozza**

_Bozze_

Quando un utente visualizza una bozza nel [!UICONTROL Proofing Viewer] e passa a un’altra versione, il menu a discesa della versione viene disattivato e l’utente non può tornare alla versione originale che stava visualizzando, oppure a un’altra versione della bozza.

**[!DNL Workfront]Timeout della ricerca**

_Ricerca_

Timeout della ricerca di [!DNL Workfront]. La ricerca può restituire alcuni risultati o nessuno.

Questo problema influisce anche sulla funzionalità del modulo [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Ricerca].

+++

+++**[!DNL Adobe Workfront Fusion]Aggiornamento di manutenzione dell’11 maggio 2023**

**Errori di timeout in[!DNL Workfront Fusion]**

_Adobe Workfront Fusion_

Quando uno scenario è in esecuzione, potrebbe presentare un errore di timeout. Le informazioni del modulo con l’errore non raggiungono la relativa destinazione.

**[!DNL Workfront]Timeout della ricerca**

_Ricerca_

Timeout della ricerca di [!DNL Workfront]. La ricerca può restituire alcuni risultati o nessuno.

Questo problema influisce anche sulla funzionalità del modulo [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Ricerca].

+++

+++**Aggiornamento di manutenzione del 9 maggio 2023**

**Filtri salvati disponibili nella colonna di acquisizione della bacheca**

_Bacheche_

Ora si può utilizzare l’attività Workfront esistente e distribuire filtri durante la configurazione della colonna di acquisizione per una bacheca. Tuttavia, i filtri delle colonne di acquisizione esistenti ora sono di sola lettura nel pannello di configurazione. I filtri esistenti vengono comunque applicati alla colonna di acquisizione, ma, se si desidera modificarli, è necessario ricrearli.

+++

+++**Aggiornamento di manutenzione del 4 maggio 2023**

**Impossibile selezionare il modello da [!UICONTROL Modelli preferiti]**

_Modelli_

Quando un utente tenta di selezionare un modello dal menu Azioni (tre punti), l’elenco dei modelli scompare se l’utente sposta il mouse sull’elenco e non è possibile selezionare un modello. Questo perché la barra di scorrimento si trova tra il menu e l’elenco dei modelli, e il mouse si concentra sulla barra di scorrimento mentre si sposta all’elenco dei modelli.

+++

## Aggiornamenti di aprile 2023

+++**Aggiornamento di manutenzione del 27 aprile 2023**

**Impossibile passare da una bozza all’altra nel [!UICONTROL Proofing Viewer]**

_Bozze_

Quando un utente visualizza una bozza nel [!UICONTROL Proofing Viewer] e passa a un’altra bozza, il pulsante Cambia bozza non risponde. L’utente non può tornare alla bozza originariamente visualizzata o a un’altra bozza.

**Modificare le immagini allegate durante la modifica di un commento**

_Aggiornamenti_

È ora possibile modificare l’immagine allegata a un commento mentre lo si modifica. Questa funzione è disponibile nella sezione Aggiornamenti per gli obiettivi Workfront e in quella dei problemi quando si abilita l’esperienza beta dei commenti.

+++

+++**[!DNL Adobe Workfront Fusion]Aggiornamento di manutenzione del 25 aprile 2023**

I collegamenti della Guida in-app di **[!DNL Fusion]non portano a pagine di aiuto specifiche**

_[!DNL Workfront Fusion]_

Quando un utente visualizza una bozza nel [!UICONTROL Proofing Viewer] e passa a un’altra bozza, il pulsante Cambia bozza non risponde. L’utente non può tornare alla bozza originariamente visualizzata o a un’altra bozza.

+++

+++**Aggiornamento di manutenzione del 20 aprile 2023**

**Problemi nei campi a discesa personalizzati**

_Moduli personalizzati_

I campi a discesa personalizzati abilitati come campi con selezione multipla possono presentare i seguenti problemi:

* Il pulsante “+[!UICONTROL Aggiungi]” non è presente quando il modulo non è in modalità di modifica.
* I campi privi di valori presentano un’opzione “—[!UICONTROL nessuna etichetta]—”.

**Impossibile utilizzare lo strumento Polilinea quando si crea un commento su una bozza**

_Bozze_

Quando un utente visualizza una bozza nel Proofing Viewer e tenta di creare un commento utilizzando lo strumento Polilinea, lo strumento non contrassegna la bozza.

**La casella delle opzioni di testo mostra “textAnnotations”**

_Bozze_

Quando un utente visualizza una bozza, inizia ad aggiungere un commento e apre lo strumento Testo, accanto alle opzioni dello strumento viene visualizzata la dicitura “textAnnotation”. Lo strumento Testo continua a funzionare come previsto e “textAnnotation” scompare dopo la pubblicazione del commento.

**Mantieni le immagini come bozza quando ti sposti da un aggiornamento per gli obiettivi e per i problemi nell’esperienza beta dei commenti**

>[!NOTE]
>
>Questa funzione è stata rilasciata in anteprima il 19 aprile 2023 e in produzione il 20 aprile 2023.

_Aggiornamenti_

Ora, se esci dalla pagina Aggiornamenti mentre stai componendo un messaggio a cui è stata allegata un’immagine e quindi torni indietro, il messaggio e l’immagine vengono mantenuti. Prima di questo aggiornamento, il commento non inviato veniva mantenuto mentre l’immagine veniva eliminata. Questa funzione è disponibile nella sezione Aggiornamenti per gli obiettivi e in quella dei problemi quando si abilita l’esperienza beta dei commenti.

**Aggiornamenti in tempo reale e commenti eliminati nella sezione Aggiornamenti**

>[!NOTE]
>
>Questa funzione è stata rilasciata in anteprima il 19 aprile 2023 e in produzione il 20 aprile 2023.

_Aggiornamenti_

Ora, quando un utente aggiunge un commento o una risposta oppure elimina un commento dall’area Aggiornamenti, è possibile visualizzare il nuovo commento o un’indicazione che un commento è stato rimosso in tempo reale, senza alcun ritardo. Questa funzione è disponibile nella sezione Aggiornamenti per gli obiettivi e in quella dei problemi quando si abilita l’esperienza beta dei commenti.

**Livello di accesso modificato dal sistema senza record della modifica**

_Utenti_

Il livello di accesso di un utente può essere modificato in modo imprevedibile dal sistema. In questo caso, non vi è alcun aggiornamento visibile e la modifica non viene visualizzata nel registro di controllo.

+++

+++**Aggiornamento di manutenzione del 17 aprile 2023**

**Mostra nuovi commenti al di fuori dell’area visibile della schermata nella sezione [!UICONTROL Aggiornamenti] dei problemi (nuova esperienza beta dei commenti) e degli [!UICONTROL obiettivi]**

_Aggiornamenti_

È stato aggiunto un banner di notifica per la sezione [!UICONTROL Aggiornamenti] per informare gli utenti in caso di commenti più recenti su un elemento che potrebbe essere al di fuori dell’area visibile sulla schermata. Questo aggiornamento è attualmente disponibile nella sezione [!UICONTROL Aggiornamenti] degli obiettivi e in quella dei problemi quando la nuova esperienza beta dei commenti è stata abilitata per i problemi.

+++

+++**Aggiornamento di manutenzione del 13 aprile 2023**

**I filtri non vengono applicati all’elenco delle richieste**

_Richieste_

Quando un utente visualizza un elenco di richieste a cui è stato applicato un filtro, l’elenco include richieste che il filtro dovrebbe escludere.

**Impossibile selezionare [!UICONTROL Tipo di ora predefinito] o [!UICONTROL Tipi di ora disponibili]**

_Utenti_

Quando un amministratore sta modificando un utente e tenta di selezionare un [!UICONTROL Tipo di ora predefinito] o [!UICONTROL Tipo di ora disponibile], i menu a discesa per tali campi sono disattivati e non si possono effettuare selezioni.

+++

+++**Aggiornamento di manutenzione del 6 aprile 2023**

**I menu a discesa non si aprono quando un utente viene aggiunto a una bozza**

_Bozze_

Quando un utente aggiunge un altro utente a una bozza nel [!UICONTROL Proofing Viewer], è impossibile aprire i menu a discesa “[!UICONTROL Ruolo bozza]” e “[!UICONTROL Avvisi e-mail]”. L’utente non può assegnare un ruolo bozza o un avviso e-mail. Questo può verificarsi quando si aggiunge un utente tramite un commento o quando si condivide la bozza con l’utente.

+++

## Aggiornamenti di marzo 2023

+++**Aggiornamento di manutenzione del 30 marzo 2023**

**Impossibile passare da una versione della bozza all’altra durante la visualizzazione della bozza**

_Bozze_

Quando un utente visualizza una bozza nel [!UICONTROL Proofing Viewer] e passa a un’altra versione, il menu a discesa della versione viene disattivato e l&#39;utente non può tornare alla versione originale che stava visualizzando, oppure a un’altra versione della bozza.

**Errore 504 durante l’esportazione dei rapporti**

_Rapporti_

Quando un utente tenta di esportare un rapporto con un numero elevato di elementi, visualizzerà un errore 504 e non potrà esportare il rapporto.

**L’aggiornamento effettuato per conto di un utente viene visualizzato come effettuato direttamente dall’utente**

_Aggiornamenti_

Quando un amministratore effettua l’accesso come utente e crea un commento, il commento viene visualizzato come creato direttamente dall’utente, anziché dall’amministratore per conto dell’utente.

+++

+++**Aggiornamento di manutenzione del 23 marzo 2023**

I contenuti del pannello **[!UICONTROL Riepilogo] sono troppo ampi per il pannello**

_Documenti_

Quando un utente visualizza il pannello [!UICONTROL Riepilogo] per un documento, i contenuti sono troppo ampi per essere visualizzati nel pannello. Il pannello ora dispone di una barra di scorrimento orizzontale che l’utente deve utilizzare per visualizzare i contenuti del pannello [!UICONTROL Riepilogo]. Ciò si verifica perché il nome del file del documento non va a capo. Questo problema è limitato ai file con estensione HTML nel nome.

**Nuova versione di [!UICONTROL Desktop Proofing Viewer]**

_Bozza_

Per risolvere un problema relativo ai commenti in [!UICONTROL Desktop Proofing Viewer], ne è stata implementata una nuova versione.

Gli utenti che hanno già installato [!UICONTROL Desktop Proofing Viewer] riceveranno automaticamente questo aggiornamento.

Gli utenti possono anche scaricare manualmente la versione più recente. Per ulteriori informazioni, consulta [[!UICONTROL Installare Desktop Proofing Viewer]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=it).

* Versione precedente: 2.1.22
* Nuova versione: 2.1.23

+++

+++**Aggiornamento di manutenzione del 16 marzo 2023**

**Gli elementi di un elenco di controllo non vengono copiati quando si copia una scheda**

_Bacheche_

Quando si copia una scheda ad hoc (le schede collegate non possono essere copiate), gli elementi di un elenco di controllo non vengono copiati nella nuova scheda.

**Campo personalizzato mancante quando un problema viene convertito in progetto**

_Progetti_

Quando un utente converte un problema in un progetto utilizzando un modello, nel progetto non viene visualizzato un campo personalizzato presente nel problema. Questo problema riguarda solo gli utenti non amministratori.

**I messaggi personalizzati non vengono visualizzati nelle notifiche e-mail**

_Bozze_

Quando un utente condivide una bozza e aggiunge un messaggio personalizzato, questo non viene visualizzato nell’e-mail di notifica al destinatario. L’oggetto è il nome della bozza e il messaggio non viene visualizzato nell’e-mail.

+++

+++**Aggiornamento di manutenzione del 9 marzo 2023**

**Il livello di accesso non viene assegnato quando si riattiva l’utente**

_Utenti_

Quando un utente riattiva un utente disattivato e tenta di assegnargli un livello di accesso nella finestra [!UICONTROL Riattiva utente], il menu a discesa del livello di accesso non viene compilato quando l’utente digita e l’utente non può selezionare un livello di accesso. Se l’utente digita il livello di accesso e lo salva, tale livello di accesso non viene assegnato all’utente riattivato.

**Salvare la bozza di un commento nell’area [!DNL Goals]**

_[!DNL Workfront Goals]_

Ora, se esci dalla pagina [!UICONTROL Aggiornamenti] di un obiettivo mentre stai componendo un messaggio e quindi torni indietro, il messaggio viene mantenuto. Prima di questo aggiornamento, i commenti non inviati venivano eliminati.

+++

+++**Aggiornamento di manutenzione del 2 marzo 2023**

**Impossibile aggiungere schede quando viene applicato il raggruppamento**

_Bacheche_

Quando un utente visualizza una bacheca in cui è applicato un raggruppamento e tenta di aggiungere una scheda, può inserire solo il nome della scheda. Gli altri campi della scheda sono disabilitati, compreso il pulsante [!UICONTROL Salva].

Se si cambia il raggruppamento in [!UICONTROL Nessuno], il problema rimane. Per ripristinare la possibilità di aggiungere una scheda, l’utente deve cambiare il raggruppamento in [!UICONTROL Nessuno] e quindi aggiornare la pagina.

**Schede collegate non aggiunte alle colonne in base allo stato**

_Bacheche_

Anche se vengono applicati i criteri di colonna per lo stato, le nuove schede collegate vengono visualizzate nella colonna più a sinistra e non in quella corrispondente allo stato.


**Il collegamento a un commento reindirizzerà alla pagina [!UICONTROL Dettagli]**

_Aggiornamenti_

Quando un utente segue un collegamento a un commento su un oggetto in Workfront, il flusso di aggiornamento viene caricato brevemente e l’utente viene reindirizzato all’area [!UICONTROL Dettagli] dell’oggetto. Questo può verificarsi se l’utente fa clic sul collegamento da un’e-mail o lo incolla nel browser.

Attualmente, questa modifica interessa solo gli oggetti Documento.

**Stampa riepilogo non si carica**

_[!UICONTROL Workfront Proof]_

Quando un utente cerca di caricare la pagina Stampa riepilogo, questa risulta sempre in caricamento, senza essere mai caricata.

+++

## Aggiornamenti di febbraio 2023

+++**Aggiornamento di manutenzione del 23 febbraio 2023**

**Il collegamento a un commento reindirizzerà alla pagina [!UICONTROL Dettagli]**

_Aggiornamenti_

Quando un utente segue un collegamento a un commento su un oggetto in Workfront, il flusso di aggiornamento viene caricato brevemente e l’utente viene reindirizzato all’area [!UICONTROL Dettagli] dell’oggetto. Questo può verificarsi se l’utente fa clic sul collegamento da un’e-mail o lo incolla nel browser.

Attualmente, questa modifica interessa solo gli oggetti Documento.

**L’utente non può modificare le proprie impostazioni di notifica**

_Utenti_

Quando un utente con licenza [!UICONTROL Lavoratore] tenta di modificare le proprie impostazioni di notifica, le opzioni di [!UICONTROL Notifica] non sono visibili nella finestra [!UICONTROL Modifica] e l’utente non può modificare le impostazioni.

+++

+++**Aggiornamento di manutenzione del 16 febbraio 2023**

**Più assegnazioni di team sulle bacheche**

_Bacheche_

Ora si possono assegnare più team a un’attività o a un problema su una bacheca e alla bacheca stessa.

**Aumento del limite di decadenza della scheda**

_Bacheche_

I limiti di tempo per la decadenza della scheda sono stati portati a 8 settimane / 60 giorni invece di 4 settimane / 30 giorni.

**La disattivazione pianificata non disattiva l’utente**

_Utenti_

Quando è pianificata la disattivazione di un utente e vengono superate la data e l’ora pianificate, l’utente non viene disattivato.

+++

+++**Aggiornamento di manutenzione del 9 febbraio 2023**

Campo **[!UICONTROL Punti storia] aggiunto a rapporti ed elenchi di attività e problemi**

_Rapporti_

Il campo [!UICONTROL Punti storia] è ora disponibile per essere aggiunto a rapporti ed elenchi di attività o problemi. Si tratta di un campo modulo libero modificabile che non è legato alle ore pianificate o alle assegnazioni del team.

+++

+++**Aggiornamento di manutenzione dell’8 febbraio 2023**

**Pulsante Filtro nella colonna di acquisizione**

_Bacheche_

La colonna di acquisizione su una bacheca ora include un pulsante **[!UICONTROL Aggiungi un filtro]** quando la colonna è vuota e non sono stati creati filtri. Il pulsante apre l’area di configurazione, in cui è possibile aggiungere filtri per inserire attività e problemi nella colonna di acquisizione.

+++

+++**Aggiornamento di manutenzione del 2 febbraio 2023**

L’icona **[!UICONTROL Bacheche] viene visualizzata nel [!UICONTROL Menu principale] per impostazione predefinita**

_Bacheche_

L’icona [!UICONTROL Bacheche] ora appare nel [!UICONTROL Menu principale] per gli utenti che non dispongono di un modello layout. Per impostazione predefinita, le bacheche sono incluse anche nel menu principale per tutti i nuovi modelli di layout creati. I modelli di layout esistenti non sono stati modificati.

**Impossibile salvare i modelli e-mail**

_Configurazione_

Quando un utente tenta di creare o modificare un modello e-mail, il pulsante [!UICONTROL Salva] non risponde e l’utente non può salvare il modello.

+++

## Aggiornamenti di gennaio 2023

+++**Aggiornamento di manutenzione del 30 gennaio 2023**

**Sono state aggiunte scelte rapide da tastiera per le azioni comuni della scheda orario**

_Schede orario_

Le seguenti scelte rapide da tastiera sono state introdotte per le seguenti azioni frequenti all’interno di una scheda orario:

* Aggiungi riga (Comando+Opzione++ / Ctrl+Opzione++)
* Elimina riga (Comando+Opzione+- / Ctrl+Opzione+-)
* Fissa o sblocca un elemento di lavoro (Opzione+P / Opzione+P)
* Apri commento (Maiusc+F2 / Maiusc+F2)
* Salva commento (Comando+Invio / Ctrl+Invio)
* Espandi (Maiusc+Opzione+Freccia su/Maiusc+Alt+Freccia su)
* Comprimi (Maiusc+Opzione+Freccia giù/ Maiusc+Alt+Freccia giù)

L’area in cui vengono eseguite queste azioni deve essere evidenziata per poterle applicare.

**Icone delle informazioni nuove per schede orario, profili e preferenze della scheda orario**

_Schede orario_

>[!NOTE]
>
>Questo aggiornamento è stato rilasciato solo nell’ambiente di Anteprima il 3 novembre 2022 ed è ora disponibile in Produzione.

Sono state aggiunte diverse icone delle informazioni alle seguenti impostazioni:

* La casella di controllo “[!UICONTROL Può modificare l’ora]” durante la creazione o la modifica di una scheda orario o di un profilo della scheda orario per indicare, se abilitata, che gli approvatori possono anche inviare, riaprire o modificare la scheda orario, a meno che l’amministratore non limiti queste azioni nell’area [!UICONTROL Configurazione] delle [!UICONTROL Preferenze della scheda orario].
* “[!UICONTROL Limita la modifica della scheda orario a proprietari e amministratori]” nell’area [!UICONTROL Configurazione] delle [!UICONTROL Preferenze scheda orario e ora] per indicare che, se disabilitata, anche gli utenti seguenti possono modificare le schede orario: utenti con accesso amministrativo a schede orario e ore, approvatori di schede orario autorizzati a modificare l’ora e responsabili dei proprietari delle schede orario.

La funzionalità di queste impostazioni non è stata modificata e sono state aggiunte solo le icone delle informazioni per chiarire l’ambito delle impostazioni.

+++

+++**Aggiornamento di manutenzione del 26 gennaio 2023**

**Errore durante l’invio della richiesta da [!DNL Outlook]**

_Integrazioni_

Quando un utente cerca di inviare una richiesta con allegati da un indirizzo e-mail di [!DNL Outlook], uno o più allegati non vengono caricati e l’utente visualizza il seguente errore:

“[!UICONTROL Si è verificato il seguente errore: il file con handle xxxx non esiste.]”

Ciò si verifica solo quando viene eseguita un’assegnazione per la nuova richiesta, sia attraverso la coda di richieste che manualmente durante la creazione della richiesta.

**Nuova versione di Desktop Proofing Viewer**

_Bozza_

Per risolvere un problema di blocco in Desktop Proofing Viewer, ne è stata implementata una nuova versione. Gli utenti che hanno già installato Desktop Proofing Viewer riceveranno automaticamente questo aggiornamento.

Gli utenti possono anche scaricare manualmente la versione più recente. Per ulteriori informazioni, consulta [Installare Desktop Proofing Viewer](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=it).

* Versione precedente: 2.1.19
* Nuova versione: 2.1.20

**Gli utenti non possono modificare le proprie impostazioni**

_Utenti_

Quando un utente con una licenza Lavoro, Revisione oppure Richiesta tenta di modificare le proprie impostazioni, la finestra a comparsa visualizzata è vuota e l’utente non può apportare alcuna modifica. Per uscire dalla finestra a comparsa, l’utente deve aggiornare la pagina.

+++

+++**Aggiornamento di manutenzione del 19 gennaio 2023**

**È ora possibile condividere i filtri della colonna di acquisizione**

_Bacheche_

Quando la funzione della colonna di acquisizione è stata rilasciata in Bacheche, i filtri per la configurazione di tale colonna potevano essere visualizzati solo dall’utente che li aveva creati. Ora i filtri creati dall’utente possono essere condivisi con altri utenti o team.

**Funzionalità pin disponibile nel menu [!UICONTROL Altro]**

_Navigazione_

Le seguenti funzioni sono ora disponibili nel menu [!UICONTROL Altro] per i pin nell’ambiente Produzione:

* Ridenominazione dei pin
* Riordinamento dei pin all’interno del menu [!UICONTROL Altro]
* Spostamento di un pin dal menu [!UICONTROL Altro] (in questo modo, l’ultimo pin della barra di navigazione superiore viene spostato nel menu [!UICONTROL Altro])

+++

+++**Aggiornamento di manutenzione del 18 gennaio 2023**

**Espressioni con caratteri jolly non sono valide nei campi personalizzati**

_Moduli personalizzati_

Quando un utente utilizza un carattere jolly come \$$TODAY o $$NOW insieme a un modificatore (ad esempio “-30d”) in un campo personalizzato, la convalida non lo accetta come valido. I caratteri jolly senza modificatori sono considerati validi.

**[!UICONTROL Bilanciamento del carico di lavoro] mostra ore non associate a un/una progetto/attività/problema**

_[!UICONTROL Bilanciamento del carico di lavoro]_

Quando un utente visualizza il [!UICONTROL Bilanciamento del carico di lavoro], visualizza le ore registrate per utente che non sono associate ad alcun progetto, alcuna attività o alcun problema, né vengono registrate come ore [!UICONTROL Generali]. Queste ore possono essere visualizzate solo nella visualizzazione a 4 settimane o a 6 settimane.

+++

+++Aggiornamento di manutenzione per **[!DNL Adobe Workfront Fusion] (Hot Fix) del 12 gennaio 2023**

**Errori 404 nei moduli di [!DNL Workfront]**

_Workfront Fusion_

Quando è in esecuzione uno scenario, un modulo di [!DNL Workfront] restituisce un errore 404.

Questo problema è stato segnalato nei seguenti moduli:

* [!UICONTROL Leggi un record]

+++

+++**Aggiornamento di manutenzione (Hot Fix) del 12 gennaio 2023**

Errore **“[!UICONTROL Ops]” durante la configurazione di un campo calcolato**

_Moduli personalizzati_

Quando un utente crea o modifica un campo calcolato in un modulo personalizzato e include un campo personalizzato nell’espressione del campo calcolato, l’espressione viene considerata non valida. Il pulsante [!UICONTROL Salva] è disattivato e l’utente non può spostarsi dal campo personalizzato. Inoltre, l’utente visualizza il seguente messaggio sotto il campo:

“[!UICONTROL Ops! Si è verificato un errore. Contatta Workfront per consentirci di individuare e risolvere il problema.]”

La rimozione del campo personalizzato dall’espressione consente all’utente di salvare e spostarsi dal campo.

**Impossibile impostare i livelli di accesso**

_Utenti_

Quando un utente tenta di modificare il livello di accesso di un altro utente, i livelli di accesso sono disattivati e non possono essere modificati. Ciò si verifica anche quando l’utente che tenta di apportare la modifica è un amministratore di sistema.

+++

+++**Aggiornamento di manutenzione del 12 gennaio 2023**

**Ctrl+F o Comando+F non funziona come previsto nei campi a discesa**

_Moduli personalizzati_

Quando un utente compila un modulo personalizzato ed effettua una ricerca in un elenco a discesa utilizzando la scelta rapida Ctrl+F o Comando+F e poi tenta di passare all’istanza successiva della ricerca, l’elenco a discesa non passa a tale istanza ma ritorna all’inizio. Ciò si verifica se il menu a discesa è impostato per consentire selezioni multiple.

La schermata **[!UICONTROL Modifica rapporto] è vuota**

_Rapporti_

Quando un utente visualizza un rapporto e tenta di modificarlo, viene visualizzata una schermata vuota e non può modificarlo.

**Le attività con rientro non mantengono il rientro**

_Attività_

Quando un utente visualizza un elenco di attività e fa rientrare un’attività, questa torna immediatamente al suo stato originale (non rientrato).

+++

+++**Aggiornamento di manutenzione del 5 gennaio 2023**

**Funzionalità pin disponibile nel menu [!UICONTROL Altro]**

_Navigazione_

Le seguenti funzioni sono ora disponibili nel menu [!UICONTROL Altro] per i pin, solo nell’ambiente di Anteprima:

* Ridenominazione dei pin
* Riordinamento dei pin all’interno del menu [!UICONTROL Altro]
* Spostamento di un pin dal menu [!UICONTROL Altro] (in questo modo, l’ultimo pin della barra di navigazione superiore viene spostato nel menu [!UICONTROL Altro])

**È stata rimossa la limitazione del Gruppo di progetti per l’aggiunta di utenti al team di progetto**

_Team_

È stata rimossa limitazione che richiedeva che gli utenti da aggiungere a un team di progetto fossero nel Gruppo associato al progetto. Ora puoi aggiungere qualsiasi utente attivo a un team di progetto, indipendentemente dai gruppi di appartenenza.

**Icone delle informazioni nuove per schede orario, profili e preferenze della scheda orario**

>[!NOTE]
>
>Questo aggiornamento è stato rilasciato nell’ambiente di Anteprima il 3 novembre 2022 ed è ora disponibile in Produzione

_Workfront_

Sono state aggiunte diverse icone delle informazioni alle seguenti impostazioni:

* La casella di controllo “Può modificare l’ora” durante la creazione o la modifica di una scheda orario o di un profilo della scheda orario per indicare, se abilitata, che gli approvatori possono anche inviare, riaprire o modificare la scheda orario, a meno che l’amministratore non limiti queste azioni nell’area Configurazione delle Preferenze della scheda orario.
* Limita la modifica della scheda orario a proprietari e amministratori” nell’area Configurazione delle Preferenze scheda orario e ora per indicare che, se disabilitata, anche gli utenti seguenti possono modificare le schede orario: utenti con accesso amministrativo a schede orario e ore, approvatori di schede orario autorizzati a modificare l’ora e responsabili dei proprietari delle schede orario.

La funzionalità di queste impostazioni non è stata modificata e sono state aggiunte solo le icone delle informazioni per chiarire l’ambito delle impostazioni.

+++

## Aggiornamenti di manutenzione precedenti

Le informazioni sugli aggiornamenti di manutenzione precedenti sono disponibili qui:

* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2022](2022-updates.md)
* [Archivio aggiornamenti di manutenzione per [!DNL Workfront] - 2021](2021-updates.md)
