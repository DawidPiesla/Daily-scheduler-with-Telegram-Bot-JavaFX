

PATonTS
Il progetto permette di visualizzare e modificare preferenze sui luoghi e date relative a determinati eventi.
L’applicazione sviluppata in JavaFX prevede una distinzione tra utente semplice e amministratore.  In base alla tipologia di utente si potranno eseguire diverse operazioni sulle preferenze, attività, workspaces…
Il Bot Telegram non prevede una distinzione tra user e admin, le operazioni sono limitate alla visualizzazione e modifica delle preferenze.

Prima di iniziare
Per utilizzare l’applicazione FX e il bot Telegram, nel caso in cui il file .jar si trovi al difuori della cartella con i file .json di default, è necessario importare il file utenti.json e worksapces.json tramite l’apposito bottone di import.
Non è possibile importare file senza estensione .json

Modalità d’uso
 Telegram
per poter utilizzare il bot Telegram l’utente deve accedere usando le proprie credenziali d’accesso separate da “ ; ”  {“Username”; “Password” }.
Non è possibile registrarsi dal bot, l’utente deve essere già presente all’interno del file “users.json”, l’aggiunta di nuovi utenti può essere effettuata da un admin tramite l’applicazione FX.
Dopo il login saranno possibili 3 operazioni:

•	/getActivity
Fornisce le informazioni sulle preferenze di tutte le attività a cui partecipa l’utente

•	/newPreference
Permette di modificare le preferenze di un’attività a scelta. L’utente dovrà scegliere la data e/o il luogo in cui desidera svolgere l’attività.

•	/deletePreference
Permette di “eliminare” una preferenza a scelta. I campi data e luogo verranno settati a “non selezionata/o”

Il bot non prevede altri comandi, la risposta a qualsiasi altro input diverso da quelli indicati sopra sarà uguale al testo contenuto nel file HELP.txt:
“Mi puoi controllare usando i seguenti comandi: /getActivity - Ti informo in quali attivity sei iscritto e le preferenze che hai scelto.
/newPreference puoi aggiungere una preferenza
/deletePreference puoi cancellare una preferenza”

Nota aggiuntiva
Solo gli utenti semplici possono accedere al bot telgram visto che sono gli unici a poter esprimere le prefrenze

Applicazione FX
Per utilizzare l’applicazione è necessario l’accesso dalla finestra di login
•	Utente amministratore
Dopo il login l'app permette di visualizzare i workspaces gestiti dall'amministratore, di crearne e modificarne di nuovi, e di aggiungere e modificare attività e relativi utenti.
Permette inoltre di visualizzare le preferenze date da ciascun utente nell'attività, in caso di omissione da parte di quest'ultimo, verrà visualizzata la dicitura “Non selezionato”.
•	Utente semplice
Dopo il login l’app ci permetterà di visualizzare i workspaces a cui partecipa l’utente e le relative attività.
Qualora l’utente volesse modificare una delle sue preferenze tramite l’apposito bottone “modifica data/ora” comparirà una finestra pop-up dalla quale non sarà possibile uscire prima di salvare o annullare le modifiche delle preferenze.

Credenziali
Qui di seguito vengono riportate le credenziali amministratore e utente per effettuare delle prove di funzionamento
Amministratore :
username : admin
password : admin
Utente semplice :
username : a
password : a

Autori
Dawid Nikodem Piesla
Enrico Valentini
