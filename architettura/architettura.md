Architettura sw/hw di ASD-AS

L'architettura ASD-AS è completamente open source al fine di permetterne il libero sviluppo nel rispetto del codice di condotta.
Il progetto è soggetto a GNU General Public License v3.0.

L'architettura di ASD-AS si basa su n livelli:

- SGE server gestionale
- BCG browser client per il server gestionale
- CDN server dei contenuti
- C1 client all-in-one
- CST client stratificato

SGE e BCG. 
Il server gestionale SGE è acceduto dal personale medico e dagli altri soggetti interessati, tramite un browser client BCG.
SGE consente di gestire ed utilizzare il sistema in base a un dato livello di permessi.

CDN. 
Il server dei contenuti centralizza i file criptati relativi alle registrazioni e ai loro metadati.

C1. 
Il client all-in-one è un dispositivo mobile Android capace di registrazione audiovideo e di accesso a rete internet.
Su C1 viene installata una app gratuita, priva di advertisings, disponibile su https://play.google.com/apps
Tramite l'app è possibile gestire l'invio degli audiovideo corredati di commenti (vedi sezione nel folder "standard" di questo progetto).

CST. 
Il client stratificato è un insieme di dispositivi organizzato in una rete domestica, adatto a registrazione audiovideo e avente accesso alla rete internet.
Il CST può essere composto da apparati quali ipcamera, minipc Linux, altri dispositivi basati su Linux o Android.
Sul minipc è installato il software per la gestione dell'invio degli audiovideo corredati di commenti (vedi sezione nel folder "standard" di questo progetto).
Nella configurazione tipica il dispositivo dotato di apparato di registrazione comunica con il minipc Linux per la gestione delle registrazioni e l'invio al server.


