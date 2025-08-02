# Portfolio Dell'Anna Francesco
Raccolta progetti in Excel, SQL, Tableau e R

link profilo Linkedin: 'www.linkedin.com/in/francesco-dellanna-fda'

---
# DASHBOARD_Analisi_Vendite.xlsx 📊
In questo progetto ho realizzato una dashboard interattiva con Excel per analizzare le vendite trimestrali di una catena distributiva fittizia, i dati sono presi da un dataset immaginario creato attraverso l'utilizzo dell'intelligenza artificiale.
## Obiettivi 🎯
- Visualizzare l’andamento delle vendite per mese, regione, manager, canale e categoria di prodotto;
- Applicare analisi esplorativa e visualizzazione dinamica;
- Semplificare l’interpretazione dei dati al fine di giungere all'assunzione di decisioni strategiche ottimali;
## Strumenti utilizzati 🔧
- Excel (tabelle pivot, grafici dinamici, segmentazioni);
- Dataset simulato;
## 📁 File presenti
- `DASHBOARD_Analisi_Vendite.xlsx` → File Excel con analisi e dashboard;

📥 Se vuoi vedere la dashboard o fornirmi un feedback, scrivimi su LinkedIn!

---

# RISTORANTE - analisi giornaliera.xlsx 📊
Questo è un progetto ideato e creato interamente da me durante la mia prima esperienza lavorativa. Il mio superiore mi aveva chiesto un modo in cui avremmo potuto tenere traccia dei costi e dei ricavi giornalieri del ristorante presente all'interno della struttura ricettiva. Riuscendo a calcolare i costi fissi annuali imputabili all'intera struttura, sono riuscito a separare quelli imputabili unicamente al ristorante e attraverso gli opportuni calcoli a trasformarli in giornalieri arrivando ad avere così un costo fisso medio giornaliero. Il file è suddiviso in più fogli, tutti collegati tra loro, secondo il seguente metodo:
## (1)Scheda generale costi e ricavi
Questa è la schermata principale ed è interamente autocompilativa. Al suo interno sono presenti tre diverse tabelle divise in righe, sulle quali sono presenti i mesi dell'anno, e colonne, con i giorni del mese. La prima tabella contiene la somma dei costi fissi medi giornalieri e dei costi medi variabili giornalieri, suddivisi in costo medio delle materie prime e costo medio del lavoro. La seconda tabella è contenente i ricavi medi giornalieri. Entrambe le tabelle si autocompilano attraverso l'immissione di dati in altre tabelle presenti in altri fogli che più avanti andremo ad esaminare. La terza e ultima tabella, denominata 'Reddito operativo', si autocompila basandosi sulle due tabelle precedenti effettuando una sottrazione tra ogni cella corrispendente della seconda e della prima tabella. Se il risulatato della sottrazione sarà positivo allora in quel giorno specifico andremo in contro ad un reddito operativo, al contrario se il risultato sarà negativo andremo in contro ad una perdita che sarà raffigurata da un valore colorato in rosso e preceduto dal segno '-'.
## (2)Posti occupati
In questo secondo foglio è presente una tabella strutturalmente identica alle precedenti ma, al contrario di esse, non è autocompilativa poichè al suo interno si vanno ad inserire il numero di ospiti che giornalmente consumano presso il ristorante.
## (3)Calendario costi
In questo foglio abbiamo i primi input che andranno in parte a compilare la tabella dei costi presente nel foglio principale. All'interno troveremo ben 12 tabelle, una per ogni mese dell'anno. Sulle colonne di ogni tabella troveremo sempre i giorni del mese e sulle righe, in questo caso, troveremo:
- il costo fisso medio, calcolato ed inserito manualmente da noi;
- il costo delle materie prime pasto, risultante da un calcolo, ovvero il prodotto tra il costo medio delle materie prime (valore che giornalmente è mediamente valutato dallo chef) e tra il numero degli occupati giornalieri (valore preso dalla tabella del foglio 2);
- il totale giornaliero, la somma delle due righe precedenti, i cui valori andranno a sommarsi a quelli del foglio 4 per andare a compilare la tabella principale;
## (4)Costo del lavoro
Questo foglio, in concomitanza con il precedente, andrà a completare l'input della tabella dei costi. Al suo interno troveremo le solite 12 tabelle mensili con le colonne suddivise per giorno del mese e con le righe così suddivise: 
- costo medio del lavoro, che è calcolato attraverso la somma del costo giornaliero di ogni collaboratore del ristorante e successivamente suddiviso per il numero di collaboratori;
- numero di collaboratori, il numero di lavoratori effettivamente presenti in quel giorno;
- costo totale, risultante dal prodotto tra la prima e la seconda riga, i cui valori andranno a sommarsi a quelli del foglio 3 per andare a compilare la tabella principale del foglio 1;
## (5)Calendario dei ricavi
Il quinto ed ultimo foglio è l'input utile alla compilazione della tabella ricavi presente nel foglio principale. In esso troviamo 12 tabelle, una per ogni mese, con i giorni mensili presenti sulle colonne e con le righe così suddivise:
- prezzo medio di vendita, il prezzo medio associato alla consumazione di ogni singolo cliente;
- numero di consumazioni, il numero di clienti che hanno consumato nel ristorante;
- totale giornaliero, risultante dal prodotto delle due righe precedenti, i cui valori andranno a compilare la tabella dei ricavi nel foglio 1.
## 📁 File presenti
'RISTORANTE - analisi giornaliera.xlsx' → File excel

---


