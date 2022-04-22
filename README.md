


## DESCRIZIONE GIOCO
Qualsiasi esercizio, singolo o collettivo, a cui si dedichino bambini o adulti per passatempo o svago viene chiamato gioco.
Il gioco che noi abbiamo ideato, è un gioco che ha come obiettivo quello di formare delle parole, servendosi di lettere casuali poste in una griglia e provare a raggiungere il punteggio maggiore possibile. Il giocatore aprirà la schermata e si troverà subito davanti ad una scelta: giocare da solo,giocare con un avversario casuale scelto dal computer,o giocare magari con un proprio amico, dovendo però inserire il codice della partita.
Prima di iniziare la partita il giocatore può scegliere tra 3 livelli diverse: principante, intermedio e difficile.
Ciò che cambia in questi tre livelli,sarà la DIFFICOLTA'.
Nel livello principante il giocatore dovrà raggiungere una soglia di 20 punti per avanzare di livello.
In quello intermedio dovrà raggiungere i 50 punti, e in quello dificile 100 punti.
Qualsiasi siano le sue scelte, una volta premuto il tasto Inizio, scatterà automaticamente un timer di due minuti nel quale dovrà cercare di formare il maggior numero di parole di senso compiuto con le 16 lettere sviluppate dal gioco,situate nella griglia 4x4 in basso.
Nella griglia possono comparire delle lettere "arcobaleno" che ovviamente saranno in risalto rispetto alle altre: queste, se il giocatore riesce a inserirle in una parola guadagnerà il doppio dei punti di quanti ne avrebbe accumulati normalmente la parola inserita.
A ciascuna delle parole sviluppate è assegnato un punteggio diverso a seconda della difficoltà che c'era nel combinarla.

## REGOLE GIOCO
Se la parola formata ha 2 lettere il punteggio sarà di 3 punti.
Le parole,per essere accettate,devono essere costituite da almeno 2 lettere.
Se la parola formata ha 2 o 3 lettere il punteggio sarà di 5 punti.
Se ne ha 4 o 5 si otterranno 7 punti.
Se la parola formata ha da 6 a 9 lettere il giocatore avrà guadagnato 10 punti.
Se la parola è formata da 10 o più lettere il giocatore oltre a ottenere 12 punti, ha a disposizione 5 secondi nei quali ogni parola che formerà sarà valutata co un punteggio doppio.
Di conseguenza il punteggio aumenta in base alla difficoltà e alla lunghezza della parola.
Se la parola è ritenuta giusta, il display si illumina di vari colori e al centro verrà mostrato il punteggio ottenuto.
Se la parola è sbagliata, il giocatore perderà 2 punti, e il display si illumina di rosso.
Il gioco è composto da 3 round composti da 10 livelli, alla fine dei quali il giocatore, potrà accedere, al round successivo, che però avrà difficoltà maggiore.
Per ogni partita vinta, il giocatore riceverà dei punti premio speciali che gli possono permettere di giocare a delle modalità speciali del gioco.
Se il giocatore non supera il livello il numero dei punti che ha acquisito fino a quel momento rimarrà inavriato.
Alla fine della partita compare una schermata con il numero delle parole formate e il rispettivo punteggio ottenuto.


## SALVATAGGIO DATI
Per iniziare a giocare il giocatore si registrerà creando un proprio account. Il primo salvataggio che avviene è proprio questo: quello degli account creati. Inoltre il gioco da la possibilità di ricordare e salvare i dati. Questa funzione è utilizzabile sia nella partita attuale, memorizzando il punteggio, ma dà anche la possibilità di salvare informazioni legate al proprio account, come le partite giocate, i punti totali, le vittorie e il livello raggiunto. Nel caso in cui il giocatore si sta scontrando contro un avversario, si utilizza un'altro salvataggio che salva i dati in modo da essere confrontati e decretare un vincitore.


## BLOCCHI DIAGRAMMA DI FLUSSO
BLOCCO INIZIALIZZAZIONE: questo è il blocco che indica la creazione dell'interfaccia all'inizio di ogni round, che contiene la griglia, il timer, il numero dei punti fatto dal giocatore, una tabella con le parole trovate.

BLOCCHI MODALITA': singolo: il giocatore giocherà la partita in solitariamente
casuale: un'avversario viene selezionato casualmente dal computer
amico: la partita viene svolta contro un conoscente, che potrà accedere ad essa grazie ad un codice.

BLOCCHI DIFFICOLTA': principiante: il giocatore avrà 6 minuti per raggiungere il punteggio.
intermedio: il giocatore disporrà di 4 minuti.
difficile: il giocatore avrà a disposizione soli 3 minuti.

## CODING-MATEMATICA
Nella compresenza matematica-coding, quest'anno, abbiamo pensato questo gioco basandoci sulle competenze acquisite del calcolo combinatorio,
grazie alla professoressa Tripepi. Abbiamo poi pensato che Ruzzle fosse il gioco perfetto per mettere in pratica le competenze acquisite.

# CALCOLO COMBINATORIO
Il calcolo combinatorio, in matematica, fa parte dello studio della probabilità e si occupa dello studio dei metodi per raggruppare un numero finito di elementi, e che si pone l'obiettivo di contare il numero di possibili raggruppamenti degli elementi per ciascun metodo.
Il calcolocombinatorio studia i raggruppamenti che si possono fare con un dato numero( n )di oggetti disposti su un dato numero di (k) posti. 

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


## COLLEGAMENTO ALLA TEORIA
Possiamo notare quindi,come le regole del calcolo combinatorio e della probabilità vengono applicate al nostro gioco perchè :
-le lettere all’interno della griglia vengono generate tramite le regole di permutazioni, disposizioni e combinazioni. 
-la probabilità viene calcolata in base alle parole che si possono formare con le lettere che appaiono nella griglia.

