


## DESCRIZIONE GIOCO
Il nostro è un gioco che ha come obiettivo quello di formare delle parole, con delle lettere casuali poste in una griglia e raggiungere il punteggio maggior.
Il giocatore ha due minuti a disposizione per formare il maggior numero di parole di senso compiuto con le sedici lettere a disposizione nella griglia 4×4. 
A ciascuna lettera è assegnato un punteggio in base alla difficoltà di inserirla all'interno di parole di senso compiuto.
Le parole devono essere costituite da almeno 2 lettere ed essere adiacenti.
Prima di iniziare la partita il giocatore può scegliere tra 3 difficoltà diverse.
Il punteggio aumenta in base alla difficoltà e alla lunghezza della parola, se la parola è giusta, il display si illumina di vari colori, e il giocatore guadagna 20 punti, se la parola è sbagliata il giocatore perde 15 punti, eil display si illumina di rosso.
Nella griglia possono comparire delle lettere che hanno un colore diverso rispetto alle altre, queste, se inserite in una parola faranno guadagnare al giocatore il doppio dei punti della parola in cui è stata inserita.
Il gioco è composto da 4 round, alla fine dei quali se il giocatore ha ottenuto un punteggio adeguato, potrà accedere al livello successivo.
Una volta superato un livello, si passa a quello successivo con una difficoltà maggiore, per ogni partita vinta, il giocatore riceverà dei punti premio speciali che gli possono permettere di giocare a delle modalità speciali del gioco. Se il giocatore non supera il livello il snumero dei punti che ha acquisito fino a quel momento rimane inavriato.
Alla fine della partita compare una schermata con il numero delle parole formate e il rispettivo punteggio 

## BLOCCHI DIAGRAMMA DI FLUSSO
BLOCCO INIZIALIZZAZIONE: questo è il blocco che indica la creazione dell'interfaccia all'inizio di ogni round, che contiene la griglia, il timer, il numero dei punti fatto dal giocatore, una tabella con le parole trovate.

BLOCCHI DIFFICOLTA': principiante: il giocatore avrà 6 minuti per raggiungere il punteggio
intermedio: il giocatore disporrà di 4 minuti
difficile: il giocatore disporrà di 3 minuti.

## CODING-MATEMATICA
Nella compresenza matematica-coding, quest'anno, abbiamo pensato questo gioco basandoci sulle competenze acquisite del calcolo combinatorio,
grazie alla professoressa Tripepi. Abbiamo poi pensato che Ruzzle fosse il gioco perfetto per mettere in pratica le competenze acquisite.

# CALCOLO COMBINATORIO
Il calcolo combinatorio, in matematica, fa parte dello studio della probabilità e si occupa dello studio dei metodi per raggruppare un numero finito di elementi, e che si pone l'obiettivo di contare il numero di possibili raggruppamenti degli elementi per ciascun metodo.
Nel calcolo combinatorio abbiamo: 

PERMUTAZIONI: sono i raggruppamenti realizzati quando il numero di oggetti è uguale al numero dei posti e differiscono per l'ordine con cui si dispongono. 
Le permutazioni possono essere con ripetizioni di oggetti o senza 

Pn = n!
Prn = n! / r1! r2!...

DISPOSIZIONI: sono i raggruppamenti realizzati quando il numero di oggetti è diverso dal numero dei posti e conta l'ordine con cui si dispongono, 
possono essere con  senza ripetizioni di oggetti.

Dn,k = n! / (n-k)!
DRn,k = n*k

COMBINAZIONI: sono i raggruppamenti realizzati quando il numero di oggetti è uguale al numero dei posti e differiscono per almeno un elemento ma non conta l'ordine.
Le permutazioni possono essere con ripetizioni di oggetti o senza.
le combinazioni con ripetizioni sono tutti i gruppi di k che si possono formare, nei quali, ogni elemento può essere ripetuto fino a k volte,
non interessa l'ordine con cui si dispongono ed è diverso il numero delle volte col quale un elemento compare

Cn,k = n! / k!(n-k)!
CRn,k = ( n + k -1 ) / k! (n-1)

## PROBABILITA'
La probabilità di un evento E è il rapporto fra il numero dei casi favorevoli F e quello dei casi possibili U quando sono tutti ugualmente possibili. 
Il numero dei casi favorevoli F è sempre minore o uguale al numero dei casi possibili, la probabilità di un evento è quindi sempre compresa tra 0 e 1.
Se F = U poichè il numero dei casi favorevoli è uguale al numero dei casi possbili : p(E) = 1, l'evento è certo
Se F = 0 poiche il numero dei casi favorevoli è nullo, p(E) = 0, l'evento è impossibile.