# Photo-Manager-Archiver

### 🟨Info🟨
Team members: Alessio Colautti [PROJECT MANAGER], Alex Troilo
School site: [ISIS Galilei](https://isisgo.it/)  
Program release date: 05/12/2025  

### 🟥Program description🟥
Photo Manager Archiver è un software realizzato in linguaggio Java, con l’ausilio del compilatore
Apache NetBeans, ideato per la gestione e l’organizzazione di un archivio di fotografie, con diverse
informazioni dettagliate disponibili all’inserimento per ognuna di esse. Successivamente, possono
essere visualizzate e analizzate per ogni scopo futuro.
Questo software è stato realizzato da Alessio Colautti e Alex Troilo, due studenti della classe 4B del
ramo delle materie informatiche della scuola ITI Galilei Fermi Pacassi di Gorizia. 

### 🟩Caratteristiche🟩
All’interno di Photo Manager Archiver, l’utente ha la possibilità, come precedentemente citato, di
inserire le informazioni descrittive di un archivio di fotografie e, successivamente, di un numero
indefinito di foto in modo da poterne tenere traccia e poterne visualizzare le caratteristiche principali
in modo semplice ed intuitivo.

L’utente, all’avvio del programma, può scegliere se interagire dal punto di vista comune, o
amministrativo, rendendo così possibile l’utilizzo del suddetto da parte sia dei clienti stessi, sia del
possessore dell’archivio. Nel primo caso, l’utente comune è in grado semplicemente di visualizzare
le informazioni e le caratteristiche di ogni fotografia, mentre nel secondo caso, all’amministratore è
richiesta l’autenticazione con la password (admin) che potrà essere cambiata in futuro dal medesimo
nel codice del programma stesso modificando il valore dell’attributo [password] all’inizio del codice.
Dopo essersi autenticato, l’amministratore dell’archivio potrà decidere se visualizzare semplicemente
le informazioni delle fotografie, aggiungere nuove informazioni di nuove fotografie, o cancellare il
file di salvataggio e ricominciare da capo l’archivio.

NB: Una volta inserite le informazioni generali sull’archivio, non potranno essere modificate fino a
quando non verrà cancellato il file di salvataggio e verrà ricominciato l’archivio.

Alla richiesta di inserimento delle informazioni, l’utente può decidere:
- Il tipo di soggetto presente nella foto
- Le informazioni riguardanti tale soggetto
- Nel caso il soggetto sia una persona, il ruolo della suddetta persona tra quelli proposti
- La descrizione del soggetto nel caso sia un paesaggio, un oggetto o un quadro
- Le informazioni dell’artista, del luogo e dell’anno di realizzazione del soggetto nel caso essosia un quadro
- Le condizioni della foto fisiche e le informazioni tecniche

Infine, verrà richiesto all’utente se esso vorrà inserire un’altra fotografia, ed in caso di risposta
negativa, verranno mostrate le informazioni inserite.

di ricostruire una fotografia: il metodo crea un nuovo Photo, inizializza Subject e Condition, e assegna
a ognuno i valori letti dal file, ripristinando così tutte le informazioni tecniche e descrittive.

