<h2><a href="https://t.me/joinchat/6Y0dlxqHN5o0MTk0">PRIMA DI MODIFICARE, ENTRARE NEL GRUPPO TELEGRAM DI GESTIONE DELLA WIKI, GRAZIE :)</a></h2>
<h2>Informazione, computer e dati</h2>
<h3>Storia degli strumenti di calcolo&nbsp;</h3>
<p>Un primo strumento di calcolo fu l'abaco (romano o cinese), originariamente utilizzato con sassolini su scanalature. Col tempo divenne più sofisticato fino ad arrivare a quelli moderni.&nbsp;</p>
<p>Già nel 1500 Leonardo da Vinci ebbe un'intuizione su come potesse essere una macchina da calcolo, abbozzando l'idea su un disegno (molto simile a quella poi progettata da Pascal).</p>
<p>Infatti nel 1642 Pascal riuscì a realizzare una prima automatizzazione degli strumenti di calcolo (una macchina), importante passo sia per velocizzare che per ridurre le probabilità d’errore. Nello stesso periodo nasce anche il regolo calcolatore. La
    scala è logaritmica, questo permette di trasformare prodotti in somme. Il regolo calcolatore rimase in mercato fino agli anni ’70, era uno strumento facile da trasportare, non necessitava di batterie e dava risultati abbastanza accurati.</p>
<p>Nel 1600 si sviluppa il commercio a livello di navigazione oceanica, quindi navi che non avevano sempre la costa in vista in mezzo all’oceano necessitavano di sapere longitudine e latitudine. Per la longitudine si utilizzavano orologi con l’ora di Greenwich
    confrontati poi con l'altezza del sole.</p>
<p>Ci furono altri precursori di strumenti automatici: calcolatrice binaria di Leibniz, il telaio programmabile di Jaquard, macchina alle differenze e macchina analitica di Babbage, sistemi di analisi di scheda perforata di Hollerit.</p>
<p>Uno dei primi veri antenati del computer moderno è l’IBM Mark (1943), il primo calcolatore elettromeccanico digitale (numeri rappresentati sotto forma di cifre binarie). Macchina abbastanza voluminosa, ma in grado di compiere tre addizioni o sottrazioni
    al secondo.</p>
<p>L’ENIAC (1946) è il primo computer elettronico, ingombrante e costoso per necessità di elettricità.</p>
<p>IC, che sta per "integrated circuit", è un altro grande passo in avanti per i calcolatori elettronici, essendo infatti il primo processore che utilizza un semiconduttore anzichè le valvole termoioniche molto in voga fino ad allora. Nasce così la microelettronica
    (anni '50)</p>
<p>Con il tempo lo sviluppo è sempre più veloce e la potenza di calcolo cresce esponenzialmente (Legge di Moore 1965).</p>
<p>Come conseguenza delle scoperte e sviluppi tecnologici nasce la fisica computazionale. Fermi, Pasta e Ulam in “<em>Studies of non linear problems</em>” (pubblicato nel 1955) mostrano l’utilità dell’ambito computazionale per la fisica: con un approccio
    intermedio tra teoria ed esperimento si rivela uno strumento utile nella ricerca e un modo per "dialogare" con la natura.</p>
<p>&nbsp;</p>
<h3>Come funziona un computer?</h3>
<p>Un computer immagazzina informazioni tramite transistor.</p>
<p>Un transistor è una componente dell'elettronica in grado di controllare il livello della tensione in&nbsp; uscita, tra due valori possibili: alto e basso, che si possono far corrispondere a qualsiasi coppia di simbolii, ma è di particolare interesse la
    coppia \( (1;0) \).</p>
<p>Questo non è l'unico modo di immagazzinare informazione: un DVD lo fa annerendo più o meno delle regioni della sua superficie o un nastro magnetico mediante magnetizzazione diversa della sua superficie.</p>
<h3>Perché l'elettronica?</h3>
<p>Un sistema elettronico è molto più veloce e durevole di qualsiasi sistema elettromeccanico.</p>
<p>L'ingegneria elettronica ci dà un sistema fisico (computer) con molti elementi in grado di assumere degli stati binari.</p>
<p>Ogni elemento può assumere \( 2 \) stati, quindi \( n \) elementi possono assumere \( 2^n \) stati. Un computer moderno ha un \( n \) che si aggira intorno ai milioni di miliardi.</p>
<p>La quantità di informazione data dallo stato di un elemento corrisponde a un <strong>bit</strong>. 8 bit, cioè l'informazione data da 8 elementi, sono <strong>1 Byte</strong>.</p>
<p>I multipli del bit sono Kb (kilo-bit, \( 10^3 \) bit), Mb (mega-bit, \( 10^6 \) bit), Gb (giga-bit, \( 10^9 \) bit), Tb (tera-bit, \( 10^{12} \) bit), Pb (peta-bit, \( 10^{15} \) bit).</p>
<p>I multipli del Byte sono KB (kilo-byte, \( 10^3 \) byte), MB (mega-byte, \( 10^6 \) byte), GB (giga-byte, \( 10^9 \) byte), TB&nbsp;(tera-byte, \( 10^{12}) \) byte), PB&nbsp;(peta-byte, \( 10^{15} \) byte).</p>
<p>Inizialmente si dava a questi prefissi un significato binario, ossia si andava alla potenza di \( 2 \) più vicina, ad esempio Kilo significava \( 2^{10}=1024 \). Questo creava naturalmente confusione.</p>
<p>Il problema è stato risolto introducendo i prefissi Ki (kibi, binary kilo, \( 2^{10} \)), Mi (mibi, binary mega, \( 2^{20} \)), Gi (gibi, binary giga, \( 2^{30} \)), etc., mentre i prefissi del S.I. hanno riacquistato il loro significato originale.</p>
<h3>Rappresentazione dei numeri</h3>
<p>La <strong>base 2 (binaria)</strong>&nbsp;è chiaramente la scelta di base naturale se vogliamo rappresentare un numero intero su un sistema di dispositivi fisici (transistor) che possono trovarsi esclusivamente in due stati \( (1;0) \).</p>
<p>\( 237 \) è un numero che sottintendiamo essere in base \( 10\). Si indica esplicitamente con \( 237_{10} \) e significa che si può scrivere \( 237=2\cdot10^2+3\cdot10^1+7\cdot10^0 \).</p>
<p>Nota: gli interi sul computer non sono gli interi di Peano. Sul computer esiste un massimo intero rappresentabile.</p>
<p>Notare l'importanza dello zero per la fattibilità di questa rappresentazione.</p>
<p>La base 10 non è l'unica possibile, ma è la più naturale per il fatto che abbiamo 10 dita. I Babilonesi probabilmente usavano la base 60.</p>
<p>Un'altra base molto utilizzata in ambito informatico è la <strong>base 16 (esadecimale)</strong>. Per rappresentare un intero in questa base, abbiamo bisogno di 16 cifre diverse (così come per la rappresentazione in base 10 necessitiamo di 10 cifre).
    Convenzionalmente, si scelgono le cifre \( 0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F \). Questa base si rivela particolarmente comoda poiché 16 è una potenza di 2. Infatti, si ha che ogni "blocco" di quattro cifre in base 2 è rappresentabile univocamente come
    un'unica cifra in base 16.</p>
<h4>Esempi</h4>
<p>\( 211_3 \to 2\cdot 3^2 +1\cdot 3^1 + 1\cdot 3^0 \)</p>
<p>\( 101_2 \to 1\cdot 2^2 +0\cdot 2^1 + 1\cdot 2^0 = 5_{10} \)</p>
<p>Per scrivere \(37_{10}\) in base \( 2\) posso costruire una tabella di potenze di \(2\) e scriverlo come somme di tali potenze:</p>
<table>
    <tbody>
        <tr>
            <th scope="row">\(n\)</th>
            <td>0</td>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
            <td>5</td>
            <td>6</td>
            <td>7</td>
            <td>8</td>
            <td>9</td>
            <td>10</td>
        </tr>
        <tr>
            <th scope="row">\(2^n\)</th>
            <td>1</td>
            <td>2</td>
            <td>4</td>
            <td>8</td>
            <td>16</td>
            <td>32</td>
            <td>64</td>
            <td>128</td>
            <td>256</td>
            <td>512</td>
            <td>1024</td>
        </tr>
    </tbody>
</table>
<p>Osservo che \(37=32+5=32+4+1=100101_2\) <br><br></p>
<p>Un altro modo, più algoritmico e applicabile più facilmente anche nel caso di numeri più grandi, è come segue:</p>
<table>
    <tbody>
        <tr>
            <td>37</td>
            <td>1</td>
            <td>(37-1)/2=</td>
        </tr>
    </tbody>
    <tbody>
        <tr>
            <td>18</td>
            <td>0</td>
            <td>(18-0)/2=</td>
        </tr>
        <tr>
            <td>9</td>
            <td>1</td>
            <td>(9-1)/2=</td>
        </tr>
        <tr>
            <td>4</td>
            <td>0</td>
            <td>(4-0)/2=</td>
        </tr>
        <tr>
            <td>2</td>
            <td>0</td>
            <td>(2-0)/2=</td>
        </tr>
        <tr>
            <td>1</td>
            <td>1</td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
</table>
<p>Trascrivendo dal basso in alto ottengo \(37_{10}=100101_{2}\)</p>
<p>La base 16 risulta anche molto utile, specie in informatica: la conversione tra "binario" ed "esadecimale" è particolarmente semplice e rende più compatta e leggibile la notazione numerica:</p>
<table>
    <tbody>
        <tr>
            <td>0000</td>
            <td>0001</td>
            <td>0010</td>
            <td>0011</td>
            <td>0100</td>
            <td>0101</td>
            <td>0110</td>
            <td>0111</td>
            <td>1000</td>
            <td>1001</td>
            <td>1010</td>
            <td>1011</td>
            <td>1100</td>
            <td>1101</td>
            <td>1110</td>
            <td>1111</td>
        </tr>
        <tr>
            <td>0</td>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
            <td>5</td>
            <td>6</td>
            <td>7</td>
            <td>8</td>
            <td>9</td>
            <td>a</td>
            <td>b</td>
            <td>c</td>
            <td>d</td>
            <td>e</td>
            <td>f</td>
        </tr>
    </tbody>
</table>
<p><br><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/NUMERI%20BASE10216.png" alt="Numeri in base 10, 2, 16" width="260" height="700">&nbsp;</p>
<p><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/potenze%20del%202.png" alt="potenze del 2" width="200" height="382">&nbsp;&nbsp; &nbsp;</p>
<p>&nbsp;</p>
<h3>Operazioni per il cambio di base</h3>
<p>&nbsp;</p>
<h4>Da base 10 a base b: metodo delle divisioni successive</h4>
<p>Per passare da un numero in base 10 a un numero in base b si applica il metodo delle divisioni successive: si divide il numero per la base desiderata, tenendo conto dei resti fino ad ottenere zero; il numero convertito è dato dai resti, presi partendo
    dal basso.</p>
<p><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/metodo%20delle%20divisioni%20successive.png" alt="metodo delle divisioni successive" width="588" height="382"></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<h4>Da base b a base 10: metodo polinomiale</h4>
<p>Per passare da un numero in base b ad un numero in base 10 occorre moltiplicare ogni cifra, partendo da quella meno significativa arrivando a quella più significativa, per la base elevata alla n, con n che vale inizialmente 0 e viene incrementato di uno
    finché le cifre del numero non sono finite. La somma dei numeri ottenuti è il numero nella nuova base.</p>
<p>&nbsp;</p>
<p><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/metodo%20polinomiale%20%281%29.png" alt="metodo polinomiale" width="497" height="136"></p>
<p>&nbsp;</p>
<h4>Da base a a base b</h4>
<p>Per passare da una base generica a ad un'altra b occorre convertire il primo numero in base a in base 10 attraverso il metodo polinomiale e successivamente si converte il numero in base 10 in quella b utilizzando il metodo delle divisioni successive.</p>
<p><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/da%20basa%20a%20a%20basa%20b.png" alt="da base a a base b" width="617" height="517"></p>
<h4>Metodo delle potenze del 2</h4>
<p>Per passare da una base 2&nbsp; ad una base sua potenza o viceversa, si prende il numero in base 2 si divide, partendo da destra in gruppi di 2,3,4 ecc... cifrein base al numero dell'esponente di 2 che da come risultato la base di arrivo, (per esempio
    16 è 2 alla 4 quindi dividiamo il numero in gruppi da 4 cifre). Successivamente si converte ogni gruppo di cifre. Le cifre ottenute sono il risultato.</p>
<p><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/metodo%20delle%20potenze%20del%202.png" alt="metodo delle potenze del 2" width="585" height="410"></p>
<p>&nbsp;</p>
<h3>Distinguere pezzi di informazione</h3>
<p>Come si fa a distinguere un intero da un altro? Sul foglio posso separarli con uno spazio, ma nel computer non posso. Infatti, ogni stringa di caratteri binari "separatrice" che posso inventare, non sarebbe interpretabile in modo univoco.</p>
<p>Per ovviare a questo problema, si attribuisce ad ogni <strong>tipo</strong> di informazione, ad esempio "numero intero" un numero standard di bit (p.es. 8 bit per un intero). In questo modo, posso "spezzettare" lo spazio di archiviazione a disposizione
    e quindi identificare ogni blocco di 8 bit con un numero intero specifico. Se da un lato questa convenzione è funzionale alla risoluzione di questo problema, l'utilizzo di un numero standardizzato di bit costituisce uno spreco per la rappresentazione
    di numeri piccoli e d'altro canto mi pone un limite al massimo numero intero rappresentabile che dovrà poter "stare" in solo 8 bit.</p>
<p>Nel caso invece io volessi rappresentare in binario una stringa di testo, avrò bisogno di <strong>codificare</strong>&nbsp;ogni carattere con una specifica sequenza di bit.</p>
<p>La prima soluzione in tal senso fu la codifica ASCII, che con 8 bit riusciva a codificare tutti i caratteri della tastiera anglosassone. Per estendere a tutti i caratteri possibili e immaginabili si è sviluppato il sistema Unicode a 21 bit. Esso si propone
    di fornire una codifica per tutti i simboli di tutti gli alfabeti mai esistiti nel mondo, oltre a tutti i simboli utilizzati in linguaggi di altro genere quale simboli musicali e della matematica. Per la scrittura di documenti con esclusivamente simboli
    codificati anche nel sistema ASCII, tuttavia, la scelta del sistema Unicode non si rivela efficace, poiché mi porta a un dispendio di risorse di archiviazione quasi triplo. Il sistema UTF (UTF-8 e UTF-16) risulta un grande passo avanti per ovviare
    a questo problema poiché distingue in modo automatico tra caratteri "standard" che possono essere rappresentati da solo 8 bit mediante sistema ASCII (UTF-8) e caratteri piú rari che invece vengono codificati con un sistema a 16 bit (UTF-16).</p>
<h3>File e dimensione</h3>
<p>Un file di testo (codifica ASCII) con dentro solo il carattere <code>a</code> "pesa" 1 byte (8 bit), ossia occupa 1 byte di informazione. Un analogo file <code>.docx</code>&nbsp; prodotto da un elaboratore di testo come Microsoft Word, corrisponde a 12KB.
    Perché? Il primo file contiene soltanto gli 8 bit necessari alla rappresentazione del carattere ''a'' nella codifica ASCII/UTF-8, mentre il secondo contiene anche tutte le informazioni di formattazione e impaginazione, chiamati <strong>metadati</strong>.
    Infatti questi dati aggiuntivi, tipici degli elaboratori di testo complessi, costituiscono una parte cospicua della dimensione del file.</p>
<h3>Archiviazione</h3>
<p>256GB sono molti o pochi? Dipende. A seconda dei file che ho bisogno di salvare può bastarmi poco spazio o potrei necessitarne di più. Ad esempio per salvare file di testo (30 righe con 80 caratteri circa fanno 2.4KB per pagina) dell'ordine del centinaio
    di pagine ci si trova intorno al centinaio di KB. Un dizionario arriva al MB. Un disco da 256GB potrebbe tenere 100'000 dizionari, quindi sembra tanto spazio, ma questo se vogliamo salvare solo file di solo testo.</p>
<p>Per codificare un'immagine bisogna codificare il colore di ogni pixel. Ad esempio consideriamo un'immagine 640x426px a colori. Ci sono 3 colori fondamentali (RGB) che possiamo codificare con un buon compromesso con 256 valori ciascuno. Ciò dà 3 Byte per
    pixel e un totale di circa 817KB, che non si discosta molto dagli 819 effettivi di un'immagine del genere in codifica <code>.tiff</code>. La stessa immagine in formato <code>.jpg</code> può arrivare a pesare 79KB. Ciò si spiega con il fatto che la
    codifica <code>JPEG</code> raggruppa insiemi di pixel che hanno lo stesso colore, descrivendoli in modo collettivo.</p>
<p>Quanto descritto prima vale per le immagini "rasterizzate", ossia che vengono descritte pixel per pixel nella loro archiviazione. Un modo completamente diverso di descrivere immagini è il formato "vettoriale", che non descrive pixel ma le forme dei contorni.</p>
<p>Un film è una sequenza di immagini con una traccia audio. Se anche mi bastasse un byte per descrivere la pressione dell'aria ad un istante, un campionamento decente per l'orecchio umano è intorno ai 20'000 Hz, corrispondenti a&nbsp; 20KB al secondo, da
    raddoppiare per una traccia stereo. In questo modo la quantità di informazione necessaria aumenta molto rapidamente.</p>
<h3>Il modello di Von Neumann</h3>
<p>Il modello di Von Neumann schematizza il funzionamento di un computer, dando un riferimento generale, in modo simile a una descrizione anatomica. Va da sé che i computer moderni hanno un grado di complessità molto maggiore in confronto a questo modello.</p>
<h4>Periferiche e circuiti I/O</h4>
<p>Le periferiche sono tutti quegli accessori che ampliano le funzioni del computer vero e proprio: il computer è il processore, tutto il resto sono periferiche: mouse, tastiera, schermo, scheda di rete, audio, USB, Hard Disk, ...</p>
<p>I/O (input-output) sono i circuiti che creano collegamento diretto tra esterno (periferiche) e interno (computer secondo Von Neumann).</p>
<h4>Processore, RAM e ROM&nbsp;</h4>
<p>La CPU (Central Processing Unit) contiene tutti i circuiti il cui incarico è di elaborare le informazioni. Le informazioni arrivano alla CPU attraverso il BUS (di comunicazione), dal punto di vista funzionale equiparabile ad un insieme di cavi che portano
    i segnali.&nbsp;</p>
<p>RAM (Random Access Memory, memoria ad accesso casuale) è, insieme alla ROM (Read-Only Memory), il luogo dove viene immagazzinata l'informazione che il processore elabora, o i risultati di tale elaborazione.</p>
<p>La ROM contiene i programmi essenziali per il funzionamento della CPU, i quali devono essere sempre disponibili e di norma non vengono modificati. La RAM può essere pensata come un grande nastro, partizionato in tanti blocchi di una certa lunghezza (1
    o più byte di norma). Ognuno di questi blocchi viene identificato dal programmatore tramite un indirizzo. Spegnendo il computer si cancella tutta la RAM.</p>
<p>NOTA: I dati salvati nella RAM hanno un indirizzo, ma, a differenza del foglio con le caselle con cui la rappresento, non può accadere che non ci sia niente nelle caselle della RAM. Ogni casella di RAM ha un contenuto, anche se noi non diciamo nulla al
    programma, quindi accedere a locazioni dove non abbiamo scritto noi può risultare in comportamenti imprevedibili!</p>
<h5>CPU</h5>
<p>I dati vengono dalla RAM e devono essere "parcheggiati" all'interno della CPU nei cosiddetti <strong>registri dati</strong>. Ci sono anche altri registri, come il registro di stato PSW, che contiene lo stato del processore. Il PC (Program Counter) contiene
    l'indirizzo della prossima istruzione. L'unità di controllo decifra l'istruzione e aggiorna il PC, eventualmente attivando la ALU (Arithmetic and Logic Unit) che effettua operazioni sui dati (per es. confrontando, sommando, ecc.). Tutto ciò avviene
    sotto il controllo del Clock, che dà un segnale periodico per passare all'unità elementare successiva delle elaborazioni. L'ingegnere elettronico decide quali sono le unità elementari e come strutturare il clock. Un'elaborazione è una transizione
    da una sequenza di 0 e 1 a un'altra per un segnale dato dal clock.</p>
<p>Più alta è la frequenza del Clock, più è rapida l'elaborazione, ma c'è anche più dissipazione di calore. Un'altra limitazione fisica è il tempo che ci mette il silicio a modificare la tensione al suo interno (l'arseniuro di gallio sarebbe più efficiente
    e darebbe performance migliori, ma è un materiale molto più raro e costoso).</p>
<p><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/ram.png" alt="pc" width="556" height="386"></p>
<h2>L'elaborazione dei dati</h2>
<p>Una volta la CPU si faceva carico di tutte le operazioni, ma ora alcune operazioni sono delegate a specifiche componenti dedicate, o unità di Input/Output (I/O). Ad esempio, l'interazione con lo schermo è gestita dalla GPU (scheda grafica). Questa è la
    strategia principale per gestire la complessità dei computer moderni.</p>
<p>Ogni elaboratore ha delle sequenze di bit corrispondenti a delle operazioni (es. somma due numeri). Un programma complesso ha una sequenza di tali sequenze che vengono caricate in RAM ed eseguite, per dare un bellissimo risultato scientificamente rilevante.
    Tipiche operazioni: - copia in un registro un dato che viene da una periferica - esegui come prossima istruzione quella alla locazione x della ram - esegui come prossima operazione quella contenuta in x se un registro n è negativo ecc. Ciclo Fetch
    Decode Execute:</p>
<p>&nbsp;</p>
<ol>
    <li>Registro PC azzerato</li>
    <li>Caricata l'istruzione presente dove indicato da PC</li>
    <li>Decodificata l'istruzione</li>
    <li>Eseguita</li>
    <li>Si torna al punto 2 finché nel PSW non viene scritto HALT.</li>
</ol>
<p>&nbsp;</p>
<p>Si può programmare direttamente scrivendo in RAM i vari 0 e 1 (<strong>linguaggio macchina</strong>). Però ci sono vari problemi: bisogna conoscere molto bene le istruzioni ed è difficile vedere se ci sono errori, o anche solo capire cosa faccia.</p>
<p>Il <strong>linguaggio assembler</strong> permette di scrivere programmi in linguaggio simbolico, più simile a quello umano, che poi tramite il programma assembler vengono tradotti in linguaggio macchina. Ogni istruzione in linguaggio assembler corrisponde
    a un'istruzione in linguaggio macchina. C'è inoltre la possibilità di inserire <em>"commenti"</em> che non vengono interpretati ma servono soltanto per spiegare che cosa facciano le varie istruzioni.</p>
<p>Assembler ha il vantaggio della leggibilità e permette di avere uno stesso linguaggio per varianti diverse di un processore, ma dipende comunque dalle istruzioni che il processore è in grado di eseguire. Per avere un linguaggio più universale si sono
    introdotti i cosiddetti <strong>linguaggi di alto livello</strong>, dove le istruzioni non corrispondono più alle singole elaborazioni elementari che il processore esegue, ma sono scritte in un linguaggio comune a tutti i processori.</p>
<p>L'utilizzo diretto dell'hardware comporta notevoli problemi di efficienza. I sistemi operativi automatizzano:</p>
<p>&nbsp;</p>
<ol>
    <li><strong>multitasking</strong> (eseguire più compiti in sequenza in modo automatico)</li>
    <li><strong>multiuser</strong> (gestione di più utenti, onde evitare che qualcuno sovrascriva il lavoro di qualcun altro)</li>
    <li><strong>time-sharing</strong> (suddivisione del tempo di esecuzione tra programmi diversi).</li>
</ol>
<p>&nbsp;</p>
<p>1GHz di frequenza di Clock corrisponde a un miliardo di operazioni al secondo, contro il decimo di secondo di tempo di reazione umano: 8 ordini di grandezza!! Questo permette di dare l'impressione che il computer lavori su più problemi contemporaneamente:
    l'uomo ha l'impressione che il suo programma continui ad essere eseguito</p>
<h2>Sistemi operativi</h2>
<p>Un <strong>sistema operativo (SO)&nbsp;</strong>è un programma che ha il particolare compito di gestire il computer da quando viene acceso fino a quando viene spento. Tale programma deve restare in RAM durante tutta l’elaborazione.</p>
<p>Il SO controlla tutto l’hardware del computer (nei computer moderni non è possibile utilizzare l’hardware se non passando attraverso il sistema operativo). Quindi tutti i programmi dell’utente o le applicazioni che l’utente ha scaricato, vengono trattati
    dal SO come dei dati, alcuni dei quali corrispondono ad istruzioni che vengono eseguite con il “permesso” del SO.</p>
<p>Attualmente ci sono due grandi famiglie di sistemi operativi: la linea di Microsoft Windows e quella di UNIX (GNU/Linux, BSD, MacOSX, ...).</p>
<h3>Interfaccia utente (UI)</h3>
<p>L'interfaccia utente è quella che mette in relazione utente e sistema operativo. La più comune è di tipo grafico a finestre (GUI, <em>Graphical User Interface</em>). Un altro tipo è l'interfaccia di linea (CLI, <em>Command Line Interface</em>, o anche
    Terminale), composta da solo testo. In realtà tutti i sistemi hanno, a qualche livello, un'interfaccia di linea, che è quella che si usa poi per interazioni di livello più manutentivo.</p>
<p>&nbsp;</p>
<h4>GUI</h4>
<p>Sono oggi le più diffuse per computer di uso personale.</p>
<p>Le GUI sono normalmente basate sulla metafora della scrivania, con icone "cliccabili" rappresentative di cartelle e file.</p>
<p>Le interazioni con le GUI avvengono con strumenti diversi: puntatori, audio, tastiera, periferiche di output.&nbsp;</p>
<p>Al "disopra" della scrivania si aprono le <strong>finestre</strong>, che hanno dei sottoelementi detti <strong>widget</strong>, tra cui:</p>
<ul>
    <li>Cornici</li>
    <li>Bottoni (tra cui i tre bottoni per ridimensionare, nascondere o chiudere la finestra)</li>
    <li>Campi di immissione di testo</li>
    <li>Menu</li>
    <li>Canvas</li>
    <li>Etichette</li>
</ul>
<p>Le GUI sono intuitive, hanno una curva di apprendimento lieve e un maggior disaccoppiamento da OS. Per contro non eseguono in modo efficiente compiti ripetitivi o massicci, la distanza tra macchina e chi vuole capire è maggiore e le applicazioni sono
    monolitiche.</p>
<h4>CLI</h4>
<p>Le interazioni con le CLI sono di tipo testuale, quindi l'unico meccanismo di input è a tastiera e l'unico di output lo schermo. Tuttavia la maggior povertà di interazione con una CLI non ne ha comportato la scomparsa per ragioni che risulteranno evidenti
    analizzando i pro e contro delle due tipologie di interfaccia.&nbsp;</p>
<p>Un grande vantaggio delle CLI è sicuramente la potenza dei meccanismi di automazione e composizione di funzionalità senza dimenticare la facilità di interazione col computer anche in situazioni critiche o non programmate. Per contro è necessario memorizzare
    i comandi.&nbsp;</p>
<p>Quindi, un vantaggio delle CLI è sicuramente quello di avere una visione abbastanza precisa di quello che succede (per esempio durante l'esecuzione di un programma) al di là delle GUI, che al contrario tendono a nascondere e rendere poco chiari alcuni
    passaggi.</p>
<p>Nei sistemi Unix attualmente la CLI più diffusa è la cosiddetta <em>shell bash</em>.</p>
<p>&nbsp;<img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/tabella%20gui%20e%20cli.jpg" alt="" width="660" height="328"></p>
<p>&nbsp;</p>
<p><br>&nbsp;</p>
<h3>Processi</h3>
<p>Ogni applicazione è fatta da dati, risorse hardware utilizzate, metadati (proprietario, spazio di RAM utilizzabile, ecc.) e stato del programma. Il sistema operativo deve tener traccia di tutto ciò. L'insieme di questi dati forma un processo. Si possono
    anche avere centinaia di processi in RAM, a ognuno dei quali il sistema operativo dedicherà una parte del tempo del processore. Il sistema operativo gestisce la creazione e l'eliminazione di processi e fa sì che non si crei confusione tra i processi.
    I processi più complessi possono essere suddivisi in <em>thread</em>.</p>

<h2>I comandi da CLI</h2>
<h3>Finestra Terminal</h3>
<p>La <strong>finestra terminal</strong> corrisponde all'interfaccia di linea (CLI), la quale è a sua volta un'applicazione, detta anche <em>shell bash</em>in ambiente Unix. Ciò che viene digitato nella finestra è sostanzialmente un input di comando indirizzato
    alla <em>shell bash</em>. Il primo elemento che appare all'apertura del terminal è il <em>prompt,</em>una scritta che informa l'utente dell'applicazione con cui sta interagendo e a cui sta inviando gli input digitati. I comandi della shell bash consentono
    di effettuare le stesse operazioni che si hanno nell'interfaccia grafica a patto che si conosca la collocazione della cartella in questione. A tal fine, l'applicazione di <strong>interprete comandi</strong> completa qualunque nome di file non lungo
    (che non inizia con "/") con la <em>cartella di login</em> (quella con cui ci si collega all'interprete dei comandi) ed è caratteristica di ogni utente. Digitando il comando <code>pwd</code> ("print working directory") è possibile conoscere la cartella
    di completamento del nome di un file e sarà del tipo <code>/Users/nome utente</code>. Questo elemento, detto anche <em>home directory,</em> verrà quindi anteposto a ogni nome di file incompleto inserito nella finestra terminal.</p>
<h3>Comandi</h3>
<p>Un comando è una qualunque sequenza di caratteri che va dal primo carattere al primo spazio. Quest'ultimo è, dal punto di vista della<em> shell bash</em>, l'elemento separatore fra comandi diversi.<br>I comandi vengono inseriti nella finestra di terminal
    e inviati all'unità di elaborazione sotto forma di un segnale codificato nella corrispettiva sequenza di bit. Premendo "invio" l'utente sta quindi chiedendo alla shell bash di analizzare il comando ed eventualmente di eseguirlo nel caso in cui si
    tratti di un comando noto e facente parte della shell stessa, ossia un comando <em>"<span>built in</span>".</em>&nbsp;In alternativa, la shell cerca tale comando in una serie di cartelle e in caso di non ritrovamento invia alla finestra terminal un
    messaggio di errore (<em>command not found</em>).</p>
<p>Per avere maggiori informazioni riguardo a un comando qualsiasi è sufficiente digitare nella finestra terminal il comando <code>man</code>&nbsp;seguito dalla dicitura del comando stesso; si apre quindi una schermata contenente il nome scritto per esteso,
    la modalità di utilizzo e la descrizione delle funzionalità.</p>
<p>Inoltre, è possibile lasciare un comando incompleto e premere successivamente il tasto di tabulazione. Il comando verrà completato automaticamente se non ci sono ambiguità, altrimenti verrà visualizzata una lista dei possibili comandi tra cui scegliere.</p>
<p>In una shell bash UNIX, il comando <code>ls</code> elenca tutti i contenuti di una cartella. Se vogliamo informazioni sul tipo di ogni contenuto si può scrivere <code>ls -F</code>. In questo modo vengono visualizzate tramite caratteri le informazioni
    che vedremmo graficamente come icone: se si tratta di una cartella vedremo un carattere <code>/</code> comparire in fondo al nome. Un carattere <code>*</code> indica un file con permessi di esecuzione.</p>

<p>Dal punto di vista del <em>file system</em>, il <em>desktop</em> corrisponde a un livello dell'albero gerarchico all'interno dei file del sistema che è immediatamente successivo alla <em>home directory</em>. Il comando che conferma l'esistenza del <em>desktop</em>    sotto forma di cartella è <code>ls -d Desktop</code>. Volendo aggiungere la cartella <em>desktop</em> al completamento dei nomi dei file è necessario digitare <code>cd Desktop</code>, (dove cd sta per "change directory"). Inserendo poi il comando
    <code>pwd</code>, è possibile verificare che il completamento dei nomi dei file è ora stato modificato in <code>/Users/nome utente/Desktop</code> che diventa la cartella corrente. Dando infatti il comando <code>ls</code> ("list") e premendo invio
    è possibile visualizzare nella finestra terminal gli elementi del desktop. Per aprire il contenuto di una specifica cartella del desktop basterà cambiare nuovamente la <em>directory</em> attraverso il comando <code>cd</code> inserendo il nome della
    cartella in questione, per poi visualizzarne il contenuto con il comando <code>ls</code>.</p>
<p>La scorciatoia che permette di vedere il contenuto di un file di testo sulla finestra terminal è <code>cat NomeFile</code>. Esiste anche il comando <code>less NomeFile</code> il quale consente la visualizzazione del file utilizzando un numero di righe
    corrispondente all'ampiezza della finestra. Premendo la barra spaziatrice è possibile visionare le pagine successive fino ad arrivare alla fine del file.</p>
<p>Per tornare invece a un livello superiore dell'albero del&nbsp;<em>file system</em>&nbsp;esiste il comando&nbsp;<code>cd ..</code></p>
<p>Se invece si volesse aprire un file attraverso un'applicazione come&nbsp;<em>Word</em>&nbsp;basterebbe digitare <code>open "nome file"</code>.</p>

<h3>Caratteri universali</h3>
<p>Nella finestra terminal è possibile utilizzare dei caratteri universali come l'asterisco "<strong>*</strong>" e il punto interrogativo "<strong>?</strong>". Questi non rappresentano se stessi ma una qualunque sequenza di caratteri.</p>
<p>L'inserimento nella finestra di un comando del tipo <code>ls *.c</code> equivale alla richiesta di trovare tutti i file che finiscono con .c, qualunque siano i caratteri antecedenti. L'asterisco può essere inserito in una qualunque posizione: analogamente,
    una scorciatoia della forma <code>ls f*</code> fornirà una lista di tutti i file che iniziano per f, indipendentemente da quali siano i caratteri successivi.</p>
<p>Per comprendere come il punto interrogativo si differenzia dall'asterisco può essere utile prendere in esame un esempio di comando come <code>ls f?1</code>: diversamente dall'asterisco, la richiesta in questo caso è quella di elencare tutti i file che
    iniziano per f e terminano con 1, aventi però un <em>unico</em> carattere compreso tra quello iniziale e finale. Inserendo quindi comandi come <code>a*</code> e <code>a?</code> posso ottenere un file intitolato "a" tramite il primo, nessuno utilizzando
    il secondo. L'asterisco ammette infatti qualunque carattere dopo "a" ma anche nessuno, mentre il punto interrogativo richiede l'esistenza di un unico carattere dopo "a" che però deve esserci.</p>
<h3>Creazione di File e Cartelle</h3>
<p>Per la creazione di una cartella, il comando da inserire in seguito al <em>prompt </em>è <code>mkdir nuova_cartella</code>, dove "nuova_cartella" rappresenta una cartella qualsiasi. Premendo "invio", la comparsa del <em>prompt </em>senza ulteriori scritte
    è indice del fatto che la cartella è stata creata correttamente; in caso contrario, compare invece un messaggio di errore.</p>
<p>Nonostante il <em>file system</em> riconosca lo spazio come un carattere facente parte della denominazione del file, per la <em>shell</em> questo rappresenta invece un separatore di comandi: una dicitura del tipo <code>quat copy.f90</code> viene dunque
    interpretata come un insieme di due file da analizzare separatamente. Le espressioni che consentono al terminal di interpretare una dicitura dotata di spazio come un unico file sono le seguenti:</p>
<ul>
    <li><code>"quat copy f.90"</code>&nbsp;</li>
    <li><code>'quat copyf.90'</code>&nbsp;</li>
    <li><code>quat\ copy.f90</code></li>
</ul>
<p>Risulta quindi evidente la comodità nell'inserire il simbolo di <em>underscore </em>"_" al posto degli spazi per ovviare a queste ambiguità.</p>
<p>Per la creazione di un file è utile avvalersi un editor di testo come <em>jedit</em>. Il comando da inserire nel prompt può essere del tipo <code>jedit es_file.est</code>, dove "es_file" rappresenta un file qualsiasi e "est". Si apre quindi il programma
    jEdit all'interno del quale è possibile digitare il contenuto del file e salvarlo tramite il tasto "Save". A ogni nuovo salvataggio il programma sovrascrive la nuova versione a quella precedente del file. Come misura precauzionale, il programma crea
    inoltre un file secondario del tipo <code>"es_file~"</code> che contiene la versione del file antecedente all'ultimo salvataggio per poterla recuperare nel caso in cui questo fosse stato sovrascritto erroneamente.</p>
<h3>stdin, stdout, stderr</h3>
<p>Ci sono tre processi fondamentali della shell: <code>stdin</code>,<code>stdout</code>,<code>stderr</code>, che sono lo <b>standard input</b>, <b>output</b> ed <b>error</b>. L'input di default è impostato alla tastiera, mentre output ed error sono impostati
    per stampare sulla schermata della CLI. Si può "deviare" l'output scrivendo <code>comando &gt; nomefileout </code>. Per deviare anche lo standard error sullo stesso file, si può scrivere <code> comando &gt;&amp; nomefileouterr </code>. Per deviare
    l'input basta scrivere <code>comando &lt; nomefilein</code>. Si possono anche combinare: <code> comando &lt; infile &gt; outfile</code>.</p>
<p>Si può anche usare direttamente l'output di un programma come input di un altro programma immediatamente successivo, scrivendo <code>primoprogramma | secondo programma</code>. Si crea così una <i>pipeline</i><span>, ovvero un insieme di componenti software collegati tra loro in cascata.</span>&nbsp;Ad
    esempio, il comando <code>wc</code>&nbsp;(<i>web counting</i>) conta in ordine le righe, le parole e i caratteri di un file. <code>wc -l</code> conta solo le righe, per cui <code> ls | wc -l</code> conta il numero di file nella pwd (<i>print work directory</i>).</p>
<h2>Dischi e file</h2>
<p>L'informazione nella RAM non è permanente: quando il computer si spegne, viene persa. Il <strong>disco rigido</strong> è la periferica che si occupa di salvare informazioni in modo permanente. Bisogna poter leggere e scrivere dati su disco e l'interazione
    con il disco è:</p>
<ol>
    <li>Simile come struttura a quella con la RAM: il disco è diviso in blocchi di Byte accessibile tramite indirizzo</li>
    <li>Molto più lenta che quella con la RAM</li>
</ol>
<p>Per questi motivi la scrittura su disco avviene tramite un <strong>buffer di scrittura</strong>: una zona di RAM dove il SO concentra i dati da scrivere su disco, riversandoli tutti in una sola operazione quando il buffer si riempie. In questo modo si
    guadagna efficienza.</p>

<h3>File</h3>
<p>Per facilitare l'accesso all'informazione risulta comodo (se non necessario) suddividerla in <strong>file</strong>, in cui salvare anche una <a href="https://it.wikipedia.org/wiki/Serie">serie</a> di metadati, quali</p>
<ul>
    <li>Nome</li>
    <li>dimensione</li>
    <li>localizzazione sul disco</li>
    <li>informazioni sull'ultimo accesso</li>
    <li>utente "proprietario"</li>
    <li>Permessi di accesso</li>
    <li>...</li>
</ul>
<p>Ovviamente i metadati devono essere permanenti, come i dati stessi, ma sono anche presenti in RAM (per essere utilizzati del SO durante il funzionamento del computer).</p>
<p>Esempio con i permessi di accesso: drwxr-xr-x &nbsp;--&gt; "d" indica che il file considerato è una cartella; "rwx" indica che l'utente può leggere (<em>read</em>), scrivere (<em>write</em>) ed eseguire (<em>execute</em>) il file; "r-x" indica che lo
    staff può leggere ed eseguire il file; infine, il secondo "r-x" indica che tutti possono leggere ed eseguire il file.</p>
<h4>Filesystem</h4>
<p>La parte del SO che si occupa della gestione dei dati e metadati relativi ai dischi è il <em>filesystem</em>.</p>
<p>In un <em>filesystem</em> gerarchico, il nome di un file riflette direttamente una struttura logica ad albero.</p>
<p>Nei sistemi Windows si utilizza una organizzazione a più <a href="https://it.wikipedia.org/wiki/Albero" target="_blank" rel="noreferrer noopener">alberi</a> (a foresta), gli alberi vengono individuati da una lettera maiuscola seguita da <code>:</code>    ( esempio <code>C:/</code>)</p>
<p>Nei sistemi Unix l'organizzazione è sempre ad albero singolo con partenza da un livello detto root e indicato del simbolo <code>/</code> iniziale.</p>
<p>La struttura viene poi riflessa da un "nome lungo" o "nome completo" che è caratterizzato da parole separate da un carattere speciale costituito da:</p>
<ul>
    <li><code>\</code> nei sistemi Windows&nbsp; &nbsp; &nbsp; <code>D:\Dati\Testi\Tesi\Capitolo1\Figure\Figura1.png</code></li>
    <li><code>/</code> nei sistemi Unix&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<code>/Dati/Testi/Tesi/Capitolo1/Figure/Figura1.png</code></li>
</ul>
<p>Per visualizzare i metadati relativi a un file, si può scrivere al terminale <code>ls -l nomefile</code>. Dando il nome corto (ovvero l'ultimo segmento prima dell'ultimo slash che appare nel nome), il file viene cercato nella <em>directory</em> in cui
    si trova la <em>shell bash</em>. Altrimenti, si può dare il nome lungo per accedere a qualsiasi file.</p>
<h2>Linguaggi di programmazione</h2>
<p>Permettono di esprimere un algoritmo in modo non ambiguo senza dipendere dalla particolare architettura dell'<em>hardware</em>. I loro vantaggi sono:</p>
<ul>
    <li><strong style="font-weight:bold;">portabilità</strong><strong>: </strong>ovvero, i programmi scritti possono essere portati facilmente da un computer all'altro anche se gli <em>hardware</em> sono molto diversi. Il programmatore, quindi, non si deve
        preoccupare di problemi legati allo specifico computer (rallenta l'obsolescenza del programma: infatti, un <em>hardware</em> può diventare obsoleto anche in soli cinque anni, mentre un programma, invece, può così "sopravvivere" per tempi più lunghi);</li>
    <li><strong>espressività</strong>: ricalcano al massimo il livello di astrazione proprio del mondo del problema (ci si esprime con un linguaggio che ricalca di più quello comune, che non è necessariamente vicino a quello dello specifico mezzo che si sta
        usando).</li>
</ul>
<p>Esempio in linguaggio C ("il più basso dei linguaggi di programmazione di alto livello"):</p>
<pre>#include &lt;stdlib.h&gt;
#include &lt;stdio.h&gt;<br>
#define RI 4
#define CL<br>
int main()
    {
    int i,j,k;
    double A[RI][CL],B[RI][CL],C[RI][RI];<br>
    for (i=0; i&gt;
</pre>
<p>Riassumendo: in C un programma può risultare più o meno comprensibile. Se si scrive lo stesso programma in altri linguaggi (C++, Fortran), esso si può compattare e può aumentare la sua espressività.</p>
<p>Diversi linguaggi di programmazione hanno estetiche diverse, alcune più intuitive di altre. Inoltre, non esiste il "miglior" linguaggio di programmazione. Ciascuno si adatta meglio a contesti differenti e possiede diversi punti di forza. Possono essere
    considerati come degli "strumenti", per cui, intuitivamente, più se ne hanno, più si guadagna in efficienza.</p>
<p>I linguaggi si possono dividere, per esempio, sulla base dei seguenti criteri:</p>
<p><strong>1)</strong>&nbsp;G<span>rammatica:</span>&nbsp;ovvero su quali siano gli elementi del linguaggio e come questi si possano combinare. Questi, a loro volta, possono essere classificati in:&nbsp;</p>
<ul>
    <li><strong>imperativi </strong>(la maggior parte: <em>C</em>, <em>C++</em>, <em>Python</em>, <em>Java</em>, <em>Fortran</em>, <em>Ada</em>, <em>Pascal</em>, <em>Visual Basic</em>, <em>PHP</em>, ...) -&gt;&nbsp;sono basati sulla separazione tra dati e
        istruzioni: l'elaborazione procede per continue modifiche al contenuto dei dati fino ad arrivare a un risultato finale.&nbsp;Le istruzioni sono nella forma di verbi imperativi come "scrivi", "leggi", "assegna un valore a una variabile", ...</li>
    <li><strong>funzionali</strong> (<em>Lisp</em>, <em>Haskell</em>, <em>Lua</em>, <em>Erlang</em>, <em>Scheme</em>, ...) -&gt; si basano sull'inserimento di funzioni che poi il computer valuta;</li>
    <li><strong>logici</strong> (<em>Prolog</em>) -&gt; ogni elaborazione è l'analogo della dimostrazione di un teorema (c'è un ipotesi e la costruzione di una serie di proposizioni logiche).</li>
</ul>
<p><strong>2)</strong>&nbsp;Supporto: ovvero i linguaggi imperativi possono essere suddivisi sulla base del problema che sono in grado di risolvere, in altre parole il supporto che possono fornire. Infatti, per risolvere un problema bisogna prima analizzarlo,
    il che va fatto a prescindere dal linguaggio (esempio: se non so di avere davanti un'equazione di secondo grado, non so di dover usare la sua formula di risoluzione!) Una possibile classificazione dei linguaggi in questo caso è la seguente:</p>
<ul>
    <li>procedurali o a oggetti;</li>
    <li>di programmazione a eventi;</li>
    <li>parallela;</li>
</ul>
<p><strong>3)</strong><span> T</span>raduzione: oltre alle differenze strutturali a livello grammaticale i linguaggi di programmazione possono essere catalogati sulla base di altri parametri, come la modalità con cui le istruzioni scritte nel linguaggio
    ad alto livello vengono tradotte in linguaggio macchina.</p>
<p>Si può distinguere tra linguaggi:</p>
<ul>
    <li><strong>interpretati</strong>: l'interprete (un'applicazione) traduce ogni istruzione in linguaggio macchina e la esegue appena possibile, mostrando subito i risultati parziali (es. linea di comando);</li>
    <li><strong>compilati</strong>: il compilatore (un'applicazione) traduce un intero programma, scritto su un file, in un file binario eseguibile, cioè contenente istruzioni in linguaggio macchina.&nbsp;
        <p>La programmazione nel caso di linguaggi compilati passa per diversi cicli di:</p>
        <p>·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Modifica del file sorgente</p>
        <p>·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Compilazione</p>
        <p>·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Esecuzione del file binario eseguibile</p>
        <p>Occorre ricordare che le modifiche al (file) sorgente non si propagano automaticamente all’eseguibile. Occorre ricompilare il (file) sorgente.</p>
    </li>
    <li>con <strong>codifica neutra intermedia (bytecode)</strong>: l'applicazione non crea istantaneamente le istruzioni macchina corrispondenti. Invece, viene prodotto un file intermedio indipendente dall'architettura del computer e che non viene eseguito
        direttamente dal processore ma viene interpretato da una <em>Virtual Machine</em>.</li>
</ul>
<h2>Fortran parte1</h2>
<h3>Compilatore e Applicazione</h3>
<p>Un <strong>compilatore </strong>è sostanzialmente un'applicazione ma ciò non implica che tutte le applicazioni siano necessariamente dei compilatori: tale distinzione risulta ancora più evidente nell'interfaccia di linea. Un'applicazione corrisponde infatti
    a un programma che è rappresentato da un'icona nel contesto dell'interfaccia grafica. Quest'ultima ha il vantaggio di agevolare l'utilizzo da parte dell'utente, ma non permette di comprendere come l'oggetto selezionato sia effettivamente correlato
    al computer.</p>
<p>Aprire un file significa far eseguire all'interno della CPU del computer un'applicazione che opera sui dati contenuti in esso al fine di generare uno specifico output. Tale risultato non si ottiene necessariamente tramite l'esecuzione di una sola applicazione
    ma è possibile richiedere ad applicazioni diverse di operare sugli stessi dati.</p>
<p>Come applicazione è possibile utilizzare anche un <strong>editor di testo</strong> che rappresenta delle sequenze di caratteri corrispondenti a delle istruzioni. Nel caso in cui il file selezionato sia di tipo grafico, i dati che rappresentano i pixel
    non hanno un'interpretazione diretta e l'editor di testo cercherà di tradurre la sequenza binaria assumendo che questi siano in realtà dei caratteri visualizzabili, ottenendo però un risultato pressoché illeggibile.&nbsp;</p>
<h3>Esecuzione di programmi</h3>
<p>Per creare un programma eseguibile a partire dalle istruzioni contenute in un file scritto in linguaggio di programmazione come Fortran è necessario utilizzare un'applicazione specifica (in questo caso <em>gfortran</em>) in quanto il computer non è in
    grado di eseguire direttamente tali istruzioni. Per eseguire l'applicazione nell'interfaccia di linea, il comando da inserire è <code>gfortran "nome file"</code>&nbsp;dove "nome file" è l'input per l'applicazione gfortran. Ricorda: per essere letto
    da gfortran il nome del file deve terminare con f90. Segue quindi un'analisi del file da parte dell'interprete comandi e la creazione di un nuovo file contenente la traduzione delle istruzioni in linguaggio macchina. Il comando per eseguire il file
    appena creato&nbsp; è <code>./"nome file"</code>&nbsp; dove "./" indica che il file si trova nella directory corrente. Il ciclo di creazione, modifica, compilazione ed esecuzione del file di testo è alla base di qualsiasi lavoro di programmazione.</p>
<h3>Compilazione</h3>
<p>La compilazione di un file comporta l'utilizzo di un programma come <em>gfortran </em>che funge da compilatore: questo legge il file scritto in istruzioni di alto livello e le traduce in istruzioni di linguaggio macchina eseguibili dal processore. Il
    comando da inviare alla shell per l'esecuzione del compilatore è <code>gfortran es_file</code>&nbsp;.</p>
<h2>Gnuplot</h2>
<p>Per quanto riguarda la creazione di grafici, un'applicazione utile risulta essere <em>gnuplot ,&nbsp;</em>che è possibile lanciare dalla finestra terminal digitando <code>gnuplot</code></p>
<p>Si ha quindi la comparsa di un nuovo <em>prompt,&nbsp;</em>diverso da quello della shell e della forma <code>gnuplot&gt;</code>&nbsp;; qualunque comando digitato viene ora interpretato come input indirizzato a tale applicazione. Per creare un grafico
    è sufficiente digitare <code>gnuplot&gt; plot</code>&nbsp;seguito dall'equazione di cui l'applicazione fornirà poi una rappresentazione grafica. Vi sono diversi comandi che permettono di terminare il programma:&nbsp;</p>
<ul>
    <li><code>gnuplot&gt; exit</code>&nbsp;</li>
    <li><code>gnuplot&gt; quit</code>&nbsp;</li>
    <li><code>gnuplot&gt; q</code>&nbsp;</li>
</ul>
<h2>Fortran</h2>
<p>Probabilmente uno dei primi linguaggi che siano stati messi appunto, nato negli anni '50 è un linguaggio di alto livello, nel senso che è sganciato dalle particolarità della macchina. Nasce come linguaggio specializzato per quelli che sono i calcoli numerici.
    Oggi "Fortran" è il nome, ma in origine è nato come un acronimo di "Formula Translation". Quindi fin dall'inizio è nato come linguaggio specializzato per poter dare una descrizione in un linguaggio simbolico di alto livello di quella che è una soluzione
    di problemi matematici (non solo matematica numerica, ma tutti i campi applicativi che utilizzano l'analisi numerica tipo Fisica e Ingegneria). Si è evoluto molto nel tempo.&nbsp;</p>
<p>Fortran è un linguaggio imperativo, quindi i comandi saranno composti da verbi all'imperativo che indicano le azioni da svolgere.<br></p>
<p>Un programma inizia da:&nbsp;<code>program NOME</code>&nbsp;</p>
<p>e finisce con:&nbsp;<code>end program</code></p>
<p><code>NOME</code>: si possono usare solo caratteri numerici, dell’alfabeto e il simbolo <code>_</code>. Il nome deve sempre iniziare con un carattere dell’alfabeto. Il nome è univoco. Non si deve utilizzare lo stesso nome per entità diverse. Sono accettate
    sia maiuscole che minuscole ma dal compilatore non sono riconosciute (ad esempio &lt;code&gt;NomeProgramma&lt;/code&gt;,&lt;code&gt;NoMePrOgRaMmA&lt;/code&gt; e &lt;code&gt;nomeprogramma&lt;/code&gt; indicano la stessa entità).</p>
<p>A differenza di altri linguaggi, non bisogna mettere un carattere per segnare la fine della linea: questo perché la scrittura è orientata alle linee. Quindi andando a capo, in un’altra linea, in automatico inizia un nuovo comando. Ma se il comando dovesse
    essere così lungo da necessitare più di una riga si utilizza il simbolo <code>&amp;</code>&nbsp;alla fine di una riga per segnalare al compilatore che il comando continua nella riga successiva.</p>
<p>Le istruzioni all'interno del programma sono di due tipi: le istruzioni eseguibili e le istruzioni non eseguibili. Le prime sono trasformate in linguaggio macchina mentre le seconde sono fondamentali per permettere al compilatore di comprendere il programma.
    Un esempio di istruzione non eseguibile è il comando&nbsp;<code>program</code>&nbsp;che indica al compilatore l'inizio del programma. Anche la dichiarazione delle variabili è un tipo di istruzione non eseguibile, su cui torneremo dopo. Fondamentale
    però ricordarsi che dopo la prima istruzione eseguibile non possono essere più inserite istruzioni non eseguibili.</p>
<h3>Costanti letterali numeriche</h3>
<p>Numeri interi 34</p>
<p>Numeri decimali 1.34</p>
<p>Numeri negativi -34</p>
<p>Numeri in notazione scientifica 1.054e-34</p>
<p>Numeri complessi (2.3,3.1)</p>
<p>I numeri vengono identificati come real o complex mentre le parole vengono identificate come characters.</p>
<p>I <strong>valori </strong><strong>logici </strong>true e false sono sempre preceduti e seguiti da un punto:<code>.true.</code> e <code>.false.</code>&nbsp;.</p>
<h3>Dichiarazione delle variabili</h3>
<p>Nella parte iniziale del codice vanno dichiarate tutte le variabili del programma. Per "dichiarare" si intende associare ai nomi un determinato tipo di valori. Una variabile dichiarata come numero intero, ad esempio, non potrà contenere una stringa.</p>
<p>&nbsp;Per dichiarare una o più di tipo intero bisogna scrivere&nbsp;<code>integer :: x,y</code>&nbsp;dove le variabili dichiarate sono separate da una virgola.</p>
<p>Se si hanno delle variabili di tipo real, ovvero dei numeri con la virgola, il meccanismo è analogo e si scrive il comando:&nbsp;<code>real :: a, nuova_variabile</code></p>
<p>Per i numero complessi si usa il comando <code>complex :: ww, psi</code></p>
<p>Per i valori logici si scrive&nbsp;<code>logical :: In, out</code></p>
<p>Per un carattere si utilizza&nbsp;<code>character :: q, p</code>&nbsp;ma in questo caso la variabile può contenere un unico carattere (insomma, un po' triste come cosa).</p>
<p>Per ottenere una serie di caratteri bisogna, quindi, aggiungere il numero di caratteri assegnato, ad esempio si può scrivere</p>
<p>&nbsp;<code>character (len=60) :: q, p</code>&nbsp;</p>
<p>per dare una lunghezza di 60 caratteri alle due variabili.</p>
<p>Nelle versioni passate di Fortran esisteva la convenzione implicita ma questa risulta svantaggiosa perché non segnala errori di scrittura. Ad esempio se io ho una variabile ll e per sbagli scrivo l1 in un punto del codice il sistema anziché dirmi che
    la variabile l1 non esiste le assegna un tipo di variabile sulla base della convenzione implicita. Questo ovviamente è causa di molti errori, motivo per il quale è vietato l'utilizzo di tale convenzione in questo corso. Per disattivarla bisogna inserire
    il comando&nbsp; <code>implicit none</code>&nbsp;come prima istruzione all'interno del programma.</p>
<p>Quindi un programma di base inizia con&nbsp;<code>program nomeprogramma</code>&nbsp;alla prima riga,&nbsp;<code>implicit none</code>&nbsp;alla seconda e la dichiarazione delle variabili nelle righe successive. Finite le istruzioni non eseguibili possono
    iniziare quelle eseguibili ed infine il programma si conclude con&nbsp;&nbsp;<code>end program nomeprogramma</code></p>
<h3>Comandi eseguibili</h3>
<p>Un tipo di comando eseguibile può essere <code>x=3</code> in cui viene assegnato il valore 3 alla variabile x. Un altro esempio può essere <code>y = x**2 + 3</code> . Ma il segno di uguale non ha il significato di equazione, ma di assegnazione: in matematica
    scrivere <code>x = x +1</code> è un abominio ma programmando questo significa che viene assegnato alla variable x quello che era il precedente valore di x aumentato di uno.&nbsp;</p>
<p>Una volta svolti tutti i calcoli risulta fondamentale poterli comunicare all'utente. Per farlo si usa il comando <code>print*, x</code> dove x è la variabile di cui voglio stampare il valore.&nbsp;</p>
<p>Un altro passaggio importante in tutti i programmi è l'inserimento di alcuni parametri da tastiera, perché altrimenti dovrei andare a modificare ogni volta il codice sorgente per cambiare un solo numero. Un programma infatti ha l'obiettivo di risolvere
    una classe di problemi e non un unico e specifico caso. Per permettere al programma di leggere i valori da tastiera il comando è <code>read*, x</code> che chiede all'utente di assegnare un valore alla variabile x. Si possono anche chiedere più valori
    in input con lo stesso comando che in questo caso sarà del tipo <code>read*, x, y, ...</code> . L'utente potrà inserire uno alla volta i vari valori da tastiera premendo invio o potrà separarli con degli spazi.&nbsp;</p>
<p>Errore comune: se dichiaro la variabile x come intero e per errore scrivo 2t, che sicuramente non è un intero il compilatore protesta ed interrompe il programma. Se però un numero viene dichiarato come tipo REAL e l'utente inserisce un numero senza virgola
    non ci sono problemi perché il compilatore risolve la cosa assegnando a tutti i valori dopo la virgola lo zero (del resto 3 e 3.00000 indicano entrambi 3 unità, anche se con precisioni diverse).</p>
<h4>Operatori logici</h4>
<p><code>print*, in .and. out</code> usa l'operatore logico "and" e fornisce un risultato sulla base del valore delle due variabili su cui opera l'operatore logico .and.&nbsp; Se voglio confrontare dei numeri invece i simboli sono <code>==</code> per richiedere
    l'uguaglianza, <code>/=</code> per la disuguaglianza, ed i segni di <code>&lt;</code>, <code>&lt;=</code>, <code>&gt;</code>, <code>&gt;=</code> che indicano rispettivamente il minore, minore o uguale, maggiore e maggiore o uguale.</p>
<h3>Cicli e condizioni</h3>
<p>Esistono degli strumenti che ci permettono di eseguire ripetutamente certe istruzioni e di eseguirne altre solo sotto certe condizioni. Per eseguire una serie di istruzioni si adopera la struttura <code>if (condizione) then</code> seguita dalla parte
    di codice da eseguire se la condizione risulta vera. Finita la parte di codice si può inserire il comando <code>else</code> per dire al programma cosa fare se la condizione non è risultata vera. Infine va inserita l'istruzione <code>end if</code>    per concludere il "ciclo" if.&nbsp;</p>
<p>Per eseguire istruzioni ripetutamente si può usare il ciclo do.</p>
<p>il ciclo inizia con <code>do z=a, b, c</code> dove a è il valore iniziale del contatore z, b è il valore finale e c è l'incremento che subisce z dopo ogni ciclo. Se non viene specificato il terzo elemento verra considerato uguale ad 1 (l'incremento può
    essere anche un numero negativo, in tal caso il valore iniziale del contatore deve essere maggiore di quello finale. Dopo il DO si inserisce il codice che va ripetuto e per indicare dove finisce tale codice si scrive <code>end do</code>.&nbsp;</p>
<p>Il numero di cicli è calcolato in maniera tale che, se uno scrivesse un ciclo come <code>do i=1, 10, -1</code> in cui il contatore i non arriverà mai al valore finale allora il ciclo non verrà eseguito.</p>
<p>In particolare la formula per il numero di volte che viene eseguito un ciclo do è: <code>MAX{0, (valore finale + incremento - valore iniziale)/incremento}</code></p>
<h3>Commentare il codice</h3>
<p>Può tornare molto utile inserire dei commenti all'interno dei codici, per ricordarci a cosa servivano determinati pezzi o per aiutare una persona che guarda il nostro codice a capire cosa abbiamo fatto. Per inserire un commento basta usare il <code>!</code>    e tutto ciò che lo seguirà in quella riga sarà considerato commento ed ignorato dal compilatore.</p>
<h3>Variabili</h3>
<p>Le variabili possono essere pensate come dei cassetti con un contenuto e un'etichetta: dichiarando una variabile si assegna a un cassetto un'etichetta e il tipo del suo contenuto. Assegnando un valore a una variabile si riempie il cassetto (attenzione:
    siccome la RAM non può essere vuota, il cassetto non è mai vuoto, ma contiene inizialmente dei valori sconosciuti. Assegnando il valore in realtà si <em>cambia</em> il contenuto). Esempio:</p>
<pre>integer :: a,b,c
read*, a,b
c=a/b
print*, a b</pre>
<p>Le variabili che non ricevono l'istruzione <code>print</code> sono in&nbsp; RAM fino alla fine del programma, ma ovviamente non vengono visualizzate.</p>
<h3>Array</h3>
<p>Per gestire molti dati (cioè delle variabili scalari/singole) in successione diventa scomodo trovare un nome per ciascuno. Molto più pratico è assegnare un <strong>indice</strong> a ciascuno e trattarli come un insieme. Gli <strong>array</strong>, a volte
    chiamati vettori (ma ricordiamo che delle entità per essere dei vettori devono verificare i numerosi assiomi di spazio vettoriale), sono variabili con indici, o "contenitori" per variabili di un certo tipo (integer, real, complex, logical, characters).
    Dal momento che questi oggetti sono composti da più variabili, occupano più di una allocazione di memoria.</p>
<p>Il numero di indici di un array è il suo <strong>rango</strong>. Le variabili normali, o scalari, sono implicitamente degli array di rango 0 o, equivalentemente, con zero indici.</p>
<p>Gli array possono essere ad allocazione <strong>statica</strong> o <strong>dinamica</strong>: se l'allocazione è statica, il compilatore assegna la memoria all'array ("a priori"), mentre nell'allocazione dinamica la memoria viene assegnata durante l'esecuzione
    del programma ("sul momento"). Per l'allocazione statica bisogna specificare subito nel codice quanti elementi ci sono nell'array. Si può arrivare a un numero massimo di 15 indici per lo standard (alcuni compilatori Intel arrivano anche a 30) ma il
    numero di componenti su ciascuno di essi dipende da quanta memoria si ha a disposizione.</p>
<p>Attenzione: uno stesso array <span style="text-decoration:underline;">non</span> può essere contemporaneamente ad allocazione statica e dinamica.</p>
<p>Normalmente gli indici di un array con \(N\) elementi partono da \(1\) e arrivano fino a \(N\), ma si può fare anche diversamente. Si dichiarano come:</p>
<pre>integer, dimension(3)      :: p,q        !array di 3 interi indiciato da 1 a 3
integer, dimension(0:2)    :: p1,q1      !array di 3 interi indiciato da 0 a 2
integer, dimension(3,3)    :: X          !matrice 3x3 a entrate intere indiciata da (1,1) a (3,3)
integer, dimension(0:2,4)  :: Y          !matrice 3x4 a entrate intere indiciata da (0,1) a (2,4)
</pre>
<p>In generale, la virgola separa indici diversi mentre il doppio punto riguarda il singolo indice.</p>
<p>Si possono anche usare delle variabili (purché <strong>costanti</strong>!) per definire i limiti di un array:</p>
<pre>integer,parameter :: LYR=0, UYR=2, CY=4
integer,dimension(LYR:UYR, CY) :: Y
</pre>
<p>Si può accedere agli elementi di un array tramite il nome dell'array e l'indice tra parentesi tonde:</p>
<pre>p(1)=45
p(2)=21
read*,p(3)
print*,p(1),p(2),p(3)

do i = 1,3000
    print*, p(i)    ! Questo darà un errore: sto cercando valori di p per indici troppo grandi! 
                    ! tuttavia il compilatore non protesterà
end do
</pre>
<p>Alcune istruzioni, applicate ad un array nella sua interezza, vengono applicate elemento per elemento. Ad esempio, l'istruzione <code>p=q**5</code> è equivalente a</p>
<pre>do i = 1:N
   p(i)=q(i)**5
end do
</pre>
<p>ovvero una singola istruzione corrisponde a un intero ciclo do.</p>
<p>Si noti che Array non è un nuovo tipo dati, ma un attributo dei tipi esistenti. Di conseguenza, i tipi dati delle componenti dell'array devono essere omogenei, in altre parole essere dello stesso tipo (integer, real, complex, ...). Inoltre, i tipi dati
    in questione devono essere dichiarati tutti con la stessa precisione (per esempio, non è possibile dichiarare una variabile a 64 bit e la successiva a 32 bit, anche se sono entrambe di tipo real).</p>
<p>Gli elementi di un array possono essere inizializzati velocemente tutti insieme con un <strong>costruttore</strong>:</p>
<p><code>q = [ 2, 4, 19 ]</code></p>
<p>Quando si lavora per componenti (accedendo direttamente agli elementi dell'Array), <strong>sta al programmatore porre attenzione</strong> a come lo si fa: si può incorrere in errori quali accesso ad indici troppo grandi, ecc...</p>
<p>Si noti che non sempre il compilatore è in grado di riconoscere questi errori: nel caso di accesso a variabili non inizializzate, non c'è speranza (verrà letto <span style="text-decoration:underline;">qualsiasi</span> valore presente in RAM in quel momento
    in quella determinata allocazione di memoria), ma neanche per accesso ad indici troppo grandi, se questo viene fatto in maniera sufficientemente subdola. Leggendo (o, peggio, scrivendo su) un indice troppo grande si va ad accedere a memoria che non
    era assegnata a quell'array, con il rischio di sovrascrivere informazioni preziose del vostro programma. Per fortuna, il sistema operativo riserva a ogni programma la sua fetta esclusiva di RAM (chiamata <strong>segmento di memoria</strong>), oltre
    la quale non può accedere. In caso di accessi troppo esuberanti, il programma verrà bloccato brutalmente con un errore del tipo <code>SIGSEGV: Segmentation fault</code>&nbsp;chiamato appunto "<strong>errore di segmentation fault</strong>".</p>
<p>Perché tutto ciò? Quando si accede a un elemento di un Array, Fortran prende l'indirizzo del primo elemento e si sposta nella memoria di tante caselle quante l'indice a cui si accede. Pertanto, non c'è garanzia di dove si andrà a finire con indici strani.
    Per evitare del tutto questi errori, si può compilare il programma aggiungendo il tag <code>-fcheck=bounds</code>, che in caso di accessi proibiti darà un errore più chiaro ed esaustivo. Lo svantaggio è che si aggiungono molte istruzioni in più (a
    ogni accesso a un elemento di un array), che quindi rallentano l'esecuzione.</p>
<p>I costruttori sono molto utili, ma come fare per array di grandi dimensioni, ad es. 30000? Sarebbe alquanto scomodo dover scrivere <code>a=[0, 1, 2, 3, 4, 5, 6, ...]</code> e scrivere un intero ciclo <code>do</code> solo per inizializzare un array a volte
    può essere poco pratico o anche impossibile (p.es. nel caso di inizializzazione contestuale alla dichiarazione). Per questo Fortran implementa i cosiddetti <strong>cicli do impliciti</strong>. Di seguito alcuni esempi:</p>
<pre>integer, dimension(30000) :: pbig = [ (i , i=1,30000) ]
real, dimension(3) :: Z = [ (0.1*i , i=1,3) ]
</pre>
<p>Attenzione: come già anticipato, nei costruttori di array, tutte le componenti devono essere omogenee: <code>real, dimension(3):: a=[1.0, 2.0, 3]</code> darà errore perché 3 è integer.</p>
<p>All'interno di un programma, non si è costretti a usare l'intero array. Infatti, si possono stampare <strong>sezioni di array,</strong>&nbsp;ossia intervalli di elementi, con il costrutto <code>pbig(1001:1030)</code> restituirà 30 elementi, dal 1001 al
    1030 compresi. Si può andare a salti: <code>pbig(1001:1030:2)</code>. Omettendo il primo elemento si parte dall'inizio, mentre omettendo l'ultimo si arriva fino in fondo. <code>pbig(::2)</code> restituisce una componente ogni 2, per tutta la lunghezza
    dell'array. <code>p(:)</code> è perfettamente equivalente a <code>p</code>, ma può essere utile per ricordarsi che si sta manipolando un array, differenziandolo dalle variabili scalari.</p>
<p>Per manipolare gli array nel linguaggio Fortran, esistono numerose funzione intrinseche. Il numero di elementi di un array si può ottenere con <code>size(p)</code>. Si può usare anche nel caso di una matrice <code>X</code></p>
<p>Per stampare tutte le righe di una matrice si può usare:</p>
<pre>do i=1,size(X,1)
    print*, X(i,:) ! intera riga i-esima
end do
</pre>

<h4>Allocazione dinamica</h4>
<p>A volte può non essere un'ottima scelta prenotare subito e per sempre tutta la memoria di cui si potrebbe aver bisogno: rischiano di risentirne altri processi e la priorità con cui il nostro programma verrà eseguito dal sistema operativo. Spesso risulta
    più comodo decidere in runtime di quanta memoria abbiamo bisogno, magari in modo automatizzato. Per questo esiste l'<strong>allocazione dinamica</strong>, che in Fortran si implementa così: <code>integer,dimension(:),ALLOCATABLE :: a,b</code></p>
<p>L'unica informazione da fornire al compilatore è il numero di indici dell'array. Infatti, un array non può essere definito con un numero ignoto di indici.</p>
<p>Attenzione: accedere ad un elemento di un array non ancora allocato è peggio che accedere a una variabile non inizializzata: oltre a non sapere che valore andiamo a pescare, non sappiamo neanche <strong>dove</strong> lo andiamo a pescare: nessuno lo sa!
    Tuttavia un indirizzo verrà utilizzato e potrebbe corrispondere ad una regione del nostro programma che contiene altri dati o anche ad una regione esterna a quella assegnata al processo. In tal caso il programma termina con un errore di segmentation
    fault.</p>
<p>Per allocare memoria a un array si può usare il comando <code>allocate(p(N))</code> con <code>p</code> Array <code>allocatable</code> e <code>N</code> variabile o costante intera.</p>
<p>Nel caso di una matrice si può procedere in questo modo</p>
<pre>integer :: N
integer,dimension(:,:),allocatable :: p, q
print*, " N? "
read*, N
allocate(p(N,N))
p= reshape( [ (i , i=1,N**2 ) ], shape(p), order=[2,1]) ! spezza un array e lo riassembla incolonnando, o affiancando, a seconda dell'order

q=p ! q viene allocato automaticamente esattamente come p e poi i valori vengono copiati.

! Risultato con N=3 e order=[2,1]
!  1   2   3
!  4   5   6
!  7   8   9
! Risultato con N=3 e order=[1,2] (equivalente a non mettere order)
!  1   4   7
!  2   5   8
!  3   6   9
</pre>
<p>Si può tener traccia del fatto che l'allocazione sia andata a buon fine grazie alla variabile <code>stat</code>:</p>
<pre>integer :: N, alloc_fail
integer,dimension(:,:),allocatable :: p

do
    print*, "N?"
    read*, N
    allocate(p(N,N), stat=alloc_fail) ! su alloc_fail verrà salvato 0 se tutto è andato bene, qualcos'altro altrimenti.
    if (alloc_fail /= 0) then
        print*, "Non c'è memoria"
        read *, N
    else
        exit
    end if
end do

p(N,N)= 23
print*, "p(N,N)= ", p(N,N)
</pre>
<p> Capita che inserendo un valore di <code>N=1000000</code> il computer non dia errore, anche se non ha a disposizione i 4TB di RAM necessari a tenere tanti <code>integer</code>. Ci sono due meccanismi che entrano in gioco qui: il computer è in grado di
    usare la memoria di storage come RAM (con grande rallentamento dell'esecuzione) ed è inoltre in grado di fare un "overbooking" di memoria. In pratica, fa finta di avere a disposizione tutta quella memoria, sperando che noi avremo bisogno solo di una
    piccola parte di quella memoria.</p>
<p>La memoria allocata da un array si può recuperare con <code>deallocate</code>.</p>
<p>Un esempio di costruttore abbastanza utile in molte occasioni, è <code>spread</code>:</p>
<pre>real,dimension(2) :: X=[0.1, 0.3]
real,dimension(3,2) :: A
real,dimension(2,3) :: W
A= spread(X, 1, 3)              ! spread (vettore, righe/colonne, quantità)
W= spread(X, 2, 3)

! A:
! 0.1    0.3
! 0.1    0.3
! 0.1    0.3

! W:
! 0.1    0.1    0.1
! 0.3    0.3    0.3</pre>
<p> Si possono moltiplicare matrici con la funzione <code>mathmul</code>.</p>

<h3>Funzioni</h3>
<p>Le funzioni sono un esempio di sottoprogramma: scrivendo un programma, tutti i calcoli sono esplicitamente scritti da noi, tranne quei blocchi di operazioni che servono, ad esempio, a calcolare l'esponenziale, che evitiamo di riscrivere ogni volta e troviamo
    comodamente impacchettati nell'espressione <code>exp(x)</code>. "Impacchettare" il codice in questo modo ha i seguenti vantaggi:</p>
<p>
</p>
<ol>
    <li>Minore probabilità di errori (non serve ricopiare il codice)</li>
    <li>Maggiore facilità di correzione e miglioria all'algoritmo (si può anche cambiare completamente algoritmo senza problemi)</li>
    <li>Maggiore leggibilità del codice</li>
    <li>Programmi meno voluminosi</li>
</ol>
I due tipi di sottoprogrammi principali sono le <code>function</code> e le <code>subroutine</code>. Un esempio di subroutine è <code>random_number</code>:
<p></p>
<pre>call random_number(x)
print*, x
</pre>
<p>Nota: una funzione da sola <b>non costituisce un'istruzione!</b> Può essere usata solo in un'assegnazione o all'interno di un'espressione.</p>
<p> Il luogo suggerito per scrivere funzioni e subroutine è un <strong>modulo</strong>. Un modulo è un contenitore, che può tenere funzioni, variabili, subroutine, in quantità arbitrarie. Un modulo può essere usato dal program o da un altro modulo. Lo standard
    richiede che il modulo utilizzato preceda tutti i moduli e il program che lo utilizzano. se si trova nel loro stesso file.</p>
<p>Una funzione si dichiara indicando il nome, le variabili argomento e la variabile risultato. L'ultimo valore della variabile risultato sarà il valore restituito dalla funzione:</p>
<pre>function norma2(x,y,z) result(res)
    real,intent(in) :: x,y,z
    real            :: res
    res=sqrt(x**2+y**2+z**2)
end function norma2
</pre>
<p><a href="https://github.com/marcellofonda/labcalc/blob/master/Programmi/10_05_2021/10_05_2021.f90" target="_blank" rel="noreferrer noopener">Esempio di utilizzo di moduli, funzioni e subroutine</a></p>
<p>Lo spazio delle variabili di una funzione è completamente separato da quelle del programma principale: anche se una variabile dichiarata e usata in una funzione ha lo stesso nome di una variabile del program, queste non possono comunque interagire in
    nessun modo. Gli unici punti di contatto tra function e program sono gli argomenti e il risultato.</p>
<p>Generalmente, è buona pratica non dichiarare variabili globali in un modulo, quanto piuttosto dei parameter. Il motivo è che le variabili globali possono essere modificate da qualunque programma abbia accesso al modulo, con il rischio di avere comportamenti
    imprevedibili: bisogna sempre essere in grado di rispondere alla domanda "quando è stata modificata l'ultima volta questa variabile?"</p>
<h4>La subroutine random_number</h4>
<p>È necessario dedicare un paragrafo alla suboutine random_number che, come anticipato, fornisce numeri assolutamente casuali compresi tra 0 e 1. Nonostante possa essere molto utile generare casualmente una serie di numeri in modo da ottimizzare i tempi
    di verifica del corretto funzionamento di un programma (invece di scrivere 100 componenti di un array a mano e una alla volta, si lascia fare al computer), in un contesto scientifico è molto importante la riproducibilità. Affidarsi completamente a
    random_number potrebbe comportare delle situazioni inaspettate, nelle quali diventa quasi impossibile ma sicuramente sfiancante trovare l'errore, situazioni dovute proprio all'assoluta casualità dei numeri che vengono generati. Di conseguenza, è ragionevole
    implementare una subroutine ausiliaria, chiamata <b>random_seed</b>, per alterare in modo controllato e riproducibile le sequenze generate da random_number. Il <b>seed</b> è generalmente un insieme di numeri interi che, successivamente, vengono usati
    negli algoritmi di generazione di numeri casuali. Il sottoprogramma random_seed possiede tre argomenti, che rappresentano i possibili modi per controllare le sequenze di numeri randomici:</p>
<p></p>
<ul>
    <li><b>size</b>: indica l'estensione dell'array di numeri interi che costituisce il seed;</li>
    <li><b>get</b>: richiede il seed che verrebbe usato di default dal sistema operativo;</li>
    <li><b>put</b>: modifica concretamente il seed di default con quello voluto.</li>
</ul>
<h3>Programmi di più file</h3>
<p>Per vari motivi può essere utile dividere un programma su più file: parti di codice da riutilizzare frequentemente, programmi complessi e lunghi, ecc.</p>
<p>Il modo più naturale è di costruire un file separato che contenga dei moduli. Per tener conto di questo, <code>gfortran</code> ha un sottoprogramma detto <b>linker</b> che gestisce le cosiddette dipendenze.</p>
<p>Il modo più semplice è spostare di blocco uno o più moduli in altro un file <code>.f90</code> e di esplicitare a <code>gfortran</code> anche il nuovo file in fase di compilazione: <code>gfortran modulo.f90 programma.f90</code>. Questo crea un eseguibile
    unico, come se i diversi file fossero uno unico. <strong>ATTENZIONE!</strong> Come in un programma i moduli vanno messi in ordine di "dipendenza", così i file utilizzati devono essere scritti prima dei file utilizzatori nel comando a <code>gfortran</code>.</p>
<p>Compilare contemporaneamente tutti i file è comodo quando i file sono pochi, ma diventa impegnativo a livello di tempo e risorse macchina se i file sono molti (anche centinaia!). Un modo per velocizzare il processo è compilare separatamente i diversi
    file, lasciando alla fine solo il processo di linking e di <b>pre-loading</b> (dove le richieste di memoria dei diversi eseguibili vengono affiancate in modo che non confliggano). Basta eseguire la compilazione sui singoli file con l'argomento <code>-c</code>    seguito dal nome del file: <code>gfortran -c modulo.f90</code>. Questo genererà dei file con estensione <code>.o</code>: sono file di istruzioni macchina, ma non sono ancora eseguibili. Per costruire l'eseguibile basta eseguire <code>gfortran</code>    su questi file tutti insieme, esattamente come se fossero i classici <code>.f90</code> del caso precedente. Comandi del genere sono anche perfettamente supportati: <code>gfortran modulo.o programma.f90</code></p>
<h3>Interazione tra funzione e programma</h3>
<p>Gli argomenti dei sottoprogrammi vengono messi nello <b>stack</b>, uno spazio della RAM che contiene informazioni su come usare gli argomenti. Queste informazioni possono essere di diverso tipo: si dice <b>passaggio per valore</b> se viene specificato
    il valore dell'argomento, <b>passaggio per riferimento</b> se invece viene scritto il suo indirizzo di memoria, oppure può anche non essere dichiarato nulla e in tal caso il compito è lasciato al programmatore.</p>
<p>È possibile controllare gli argomenti e come questi vengono usati attraverso gli intent:</p>
<p></p>
<ul>
    <li>intent(in): argomento in entrata, di sola lettura, non modificabile successivamente dalla procedura;</li>
    <li>intent(out): argomento in uscita, il valore viene definito all'interno della procedura;</li>
    <li>intent(in out): argomento in entrata e in uscita, l'argomento reale deve essere una variabile il cui valore in entrata (e nel programma chiamante) viene modificato all'interno della procedura.</li>
</ul>
<p>La <b>corrispondenza</b> tra gli argomenti dichiarati all'interno di un modulo e quelli nel programma principale quando si implementa un sottoprogramma può essere <b>per posizione</b> oppure <b>per nome</b>. La differenza è che per la seconda non è necessario
    rispettare l'ordine degli argomenti.</p>
<p><u>Nota</u>: "allocate" non è una subroutine perché non la si chiama con "call", né una function perché può stare "da sola". Tuttavia, è sicuramente molto simile a entrambe.</p>
<p>Ora è utile chiedersi che cosa succeda quando un argomento di un sottoprogramma è un array.</p>
<p>Innanzitutto è possibile esprimere gli argomenti in due modi:</p>
<p></p>
<ul>
    <li><b>Forma esplicita</b> (<i>explicit shape</i>):</li>
</ul>
<p style="text-align:center;"><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/Schermata%202021-05-14%20alle%2017.35.08%20%282%29.png" alt=""><br></p>
<p style="text-align:left;">Da notare che all'interno del programma principale è <b>assolutamente VIETATO</b> indicare le dimensioni di un array con una variabile perché è necessario specificare quale tipo di allocazione di memoria si sta usando. Nel caso di quella statica bisogna
    usare un numero, per quella dinamica i doppi punti. Questo fatto permette di capire che nella subroutine non avviene alcuna allocazione. Quindi, facendo riferimento all'esempio sopra, N, N1, N2 servono solo per avere un certo numero di componenti
    per l'array.</p>
<ul>
    <li><b>Forma presunta</b> (<i>deferred shape</i>): non è necessario portarsi dietro il numero di componenti come argomento del sottoprogramma. L'unica cosa che non può passare in automatico è l'indice da cui si parte.</li>
</ul>
<p style="text-align:center;"><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/Schermata%202021-05-14%20alle%2017.38.29%20%281%29.png" alt=""><br></p>
<p style="text-align:left;">In entrambe le situazioni, se si vuole allocare un argomento bisogna aggiungere l'attributo "allocatable" nella dichiarazione e, quindi, usare "allocated" per verificare che l'argomento sia stato effettivamente allocato.</p>
<p style="text-align:left;">...</p>
<p style="text-align:left;">Le variabili locali sono variabili introdotte nel sottoprogramma e completamente separate dal programma principale. Se a esse attribuisco un valore, non è detto che questo venga mantenuto a ciascuna chiamata del sottoprogramma. Affinché ciò non accada,
    si usa l'attributo <b>save</b> che, in realtà viene inserito automaticamente dal compilatore Fortran al momento di dichiarazione della variabile, ma che potrebbe dover essere scritto manualmente in altre situazioni.</p>
<h3>Algoritmi ricorsivi</h3>
<p>Un algoritmo ricorsivo è un algoritmo che si riconduce a se stesso. Un tipico esempio è il fattoriale, che ha una definizione <strong>iterativa</strong> come \( \displaystyle n!=\prod_{i=1}^ni \) e una <strong>ricorsiva</strong>, come \( n! = \begin{cases}n\cdot
    (n-1)!&amp;n\neq 0\\1&amp;n=0.\end{cases} \) Notare che un algoritmo non può fare indefinitamente riferimento a se stesso, ossia avvalersi esclusivamente della chiamata ricorsiva: bisogna uscire dalla ricorsione, ed essere sicuri che questa uscita
    verrà raggiunta. Nel caso del fattoriale, la condizione (esplicita) di uscita si ottiene per \( n=0.\) </p>
<p>In Fortran, il fatto che la funzione sia ricorsiva va esplicitato. Una funzione ricorsiva avrà una struttura di questo tipo:</p>
<pre>recursive function nome(...) result(...)
    ...
    variabile = nome(...)
    ...
end function</pre>
<p>Da notare che la chiamata ricorsiva risulta una vera e propria chiamata di funzione: gli argomenti vengono copiati in una nuova zona di memoria e, in pratica, la memoria allocata da una funzione viene moltiplicata tante volte quante le chiamate ricorsive
    (più la chiamata originale). Un algoritmo ricorsivo può così diventare rapidamente inefficiente dal punto di vista della gestione della memoria. Tuttavia questi possono essere ottimali per alcune operazioni, ad esempio per visitare tutti i nodi di
    una struttura ad albero.</p>
<p>Da non dimenticare che per avere significato, una function deve contenere almeno un'istruzione.</p>
<p>Oltre al fattoriale, anche la successione di Fibonacci si presta bene ad un'implementazione ricorsiva: \( a_{n+2}=a_{n+1}+a_n \), ma tale implementazione sdoppia i calcoli e risulta molto inefficiente, sia a livello di tempo che di memoria. Infatti, si
    vengono a formare due <b>cascate di ricorsione</b>, con il risultato di aver duplicato un processo che già di base può potenzialmente occupare molta memoria.</p>
<h3>Funzioni pure ed elementali</h3>
<p>Una funzione è <strong>pura</strong> se l'unica cosa che fa è prendere degli input e dare un risultato. In altre parole:
</p>
<ul>
    <li>non deve aggiungere cosa non deve fare;</li>
    <li>è l'oggetto Fortran più vicino al mondo matematico.</li>
    <li>non deve aggiungere eventuali passaggi, come un <i>print*,</i>.</li>
</ul>
<p>Queste funzioni sono utilizzate da sole per convincere il compilatore di certe ottimizzazioni. Infatti, di fronte a un ciclo do nel quale, per esempio, viene ripetuta l'istruzione x=3 per un totale di 1000 volte, il compilatore è un minimo "furbo" e non
    esegue il ciclo realmente 1000 volte, ma restituisce direttamente il risultato x=3. Nel caso, invece, di una situazione analoga ma come istruzione l'applicazione di una funzione, il compilatore non è generalmente autorizzato a fare alcuna ottimizzazione
    perché potrebbero presentarsi spiacevoli effetti collaterali. Altrimenti, il programmatore può spiegare al compilatore che, al contrario, tali ottimizzazioni sono possibili attraverso l'attributo&nbsp;<code>pure</code>.</p>
<p>Per avere una funzione che accetti indifferentemente come argomento uno scalare o un array, questa deve essere necessariamente pura (altrimenti gli effetti collaterali potrebbero moltiplicarsi indefinitamente). Una tale funzione si dichiara con l'attributo
    <code>elemental</code>:</p>
<pre>elemental function perdue(x) result(res)
    real, intent(in) :: x
    real :: res

    res= x * 2
end function
</pre>
<h3>Tipi dati derivati</h3>
<p>Per trattare oggetti complessi con molte proprietà potrebbe essere comodo raggruppare più variabili sotto un unico nome. Siccome queste variabili possono essere eterogenee, gli array non sono adatti a tal scopo. Conviene definire un nuovo tipo dati, un
    <strong>tipo dati derivato</strong>, ottenuto combinando tra loro i tipi dati primitivi (integer, real, complex, logical, character).</p>
<p>Come esempio pratico si può immaginare di voler scrivere un comando per descrivere una molecola. Le informazioni di cui, intuitivamente, si avrà bisogno sono il nome della molecola, la distanza interatomica, il numero atomico e altre ancora. È chiaro
    come queste informazioni siano rappresentate da tipi dati tra loro non omogenei (un character, un integer e un real, rispettivamente).</p>
<p>Di seguito, è riportato un altro esempio, concettualmente simile:</p>
<pre>type :: atomo
    real :: amass
    integer :: natom
    real,dimension(3) :: pos
end type atomo

type(atomo) :: w

read*, w    ! legge tutte le componenti di w
print*, w%amass ! stampa la massa atomica di w
</pre>
<p></p>
<p><span style="color:inherit;font-family:inherit;">dove "amass" si riferisce alla massa atomica, "natom" al numero atomico e "pos" alla posizione dell'atomo in un dato sistema di riferimento. Come si può notare dal codice, l</span><span style="color:inherit;font-family:inherit;">e informazioni riguardanti il tipo dati derivato si indicano tramite il costrutto:</span></p>
<p
    style="text-align:center;"><span style="color:inherit;font-family:inherit;"><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/Schermata%202021-05-22%20alle%2015.41.24%20%281%29.png" alt=""><br></span></p>
    <p style="text-align:left;"><span style="color:inherit;font-family:inherit;">e dal momento che sono indirizzate al compilatore, non sono eseguibili da sole. Inoltre, il simbolo di percentuale <b>%</b> serve per selezionare uno dei campi che costituiscono il tipo dati derivato, in questo esempio la massa atomica.</span></p>
    <p
        style="text-align:left;">Similmente ai tipi dati primitivi, anche per quelli derivati è possibile l'assegnazione, la costruzione di operazioni e di nuovi operatori.</p>
        <p style="text-align:left;"><br></p>
        <h4>Le interfacce</h4>
        <p>Le interfacce costituiscono un blocco di istruzioni non eseguibili necessarie per definire un sottoprogramma generico. Per fare un esempio, le funzioni generalmente non accettano come argomento un'altra funzione o una subroutine. È possibile modificare
            questo aspetto tramite un'interfaccia, il cui costrutto è:</p>
        <p style="text-align:center;"><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/Schermata%202021-05-22%20alle%2016.23.05.png" alt=""><br></p>
        <p style="text-align:left;">Un sottoprogramma può in questo modo avere una funzione come input:</p>
        <pre style="text-align:left;">subroutine stampainzero(f)
    interface
        function f(x) result(res)
            use modulo
            real,intent(in) :: x
            real            :: res
    end interface
    print*, f(0.)
end subroutine</pre>
        <p style="text-align:left;">Questo oggetto di Fortran risulta essere molto utile anche per definire nuovi <b>operatori</b>, al fine di avvicinarsi il più possibile alla simbologia usata quotidianamente in un corso di studio in Fisica. Facciamo l'esempio del prodotto vettoriale:</p>
        <p
            style="text-align:center;"><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/Schermata%202021-05-22%20alle%2016.30.18.png" alt=""><br></p>
            <p style="text-align:left;">È molto importante definire il nuovo operatore tra due punti bassi (.x. oppure .pluto.) e usare il costrutto "interface operator ...".</p>

            <h3>L'interazione con il Filesystem</h3>
            <p>Fortran salva le informazioni sui file con cui interagire in strutture dette <b>unità logiche</b>, con cui si interagisce attraverso dei numeri, es. <code>write(unit=1,fmt=*)"ciao"</code>. Di default un'unità fa riferimento a un file che su
                sistemi UNIX normalmente si chiama <code>fort.1</code>. Per modificare il nome del file si può usare il comando <code>open</code>:</p>
            <p><code>open(unit=10,file='pippo.dat')</code>. Da questo comando in poi ogni comando del tipo <code>write(unit=10,fmt=*)"ciao"</code> scriverà nel file <code>pippo.dat</code>. Per sciogliere questa associazione tra unità logica e file si usa
                il comando:</p>
            <p><code>close(10)</code></p>
            <p>Si può anche specificare in runtime il file da aprire:</p>
            <pre> character,dimension(100) :: input
read*, input
open(unit=4, file=input)
do i=1,N
    read(4,*) x(i)
end do
rewind 4       !La prossima lettura riprende dall'inizio del file
read(4,*) pluto
close(4)
</pre>
            <p>L'argomento <code>fmt</code> dice al programma come interpretare i caratteri dell'input. Sfruttando questo argomento si ottiene il cosiddetto <b>input/output formattato</b>. Ad esempio, l'input <code>1.32</code> può essere interpretato come
                un numero o come una sequenza di 4 caratteri. Un numero reale a 64 bit può occupare 22 caratteri (15 cifre+ 1 segno della mantissa + 1 punto + 1 segno dell'esponente + e + 3 cifre di esponente) . Da 8 byte si passa quindi a 22, cioè le
                dimensioni in termini di spazio su disco aumentano quasi di un fattore 3. Per evitare questo aumento di dimensioni si può specificare di salvare i dati direttamente, senza convertirli in carattere. Ovviamente il file che ne risulta sarà
                illeggibile e non è detto che un altro computer lo sappia interpretare correttamente. Ciò si specifica nel comando <code>open</code> con l'argomento <code>form</code>, con valori <code>'formatted'</code> o <code>unformatted</code>.</p>
            <p>L'accesso a un file è di default <b>sequenziale</b> (si ha accesso a un dato solo dopo aver avuto accesso al precedente; di default è formattato), ma può anche essere di tipo <b>stream</b> (utile ad esempio nel caso di strumentazione che invia
                dati continuamente; unformatted di default) o <b>diretto</b> (si può accedere direttamente a ogni dato; sostanzialmente, è un ampliamento del concetto di array, con memoria molto maggiore ma accesso circa 1000 volte più lento; unformatted
                di default). L'argomento di <code>open</code> che controlla l'accesso è <code>access</code> con valori <code>sequential</code>, <code>stream</code>, <code>direct</code>.</p>
            <p><span>Al parametro</span>&nbsp;<code>fmt</code>&nbsp;<span>sono&nbsp;<span>associati diversi </span><span><b>descrittori di formato</b></span><span>. Il più usato è&nbsp;&nbsp;<code>ESw.d</code>&nbsp;, che scrive<span> i dati sotto forma di numeri reali in notazione scientifica, con la mantissa che comincia con una cifra diversa da </span><span>0</span><span>.</span>&nbsp;</span>
                </span><br></p>
            <p></p>
            <ul>
                <li><span><span>&nbsp;<code>w</code>&nbsp;&nbsp;<span>indica il numero di caratteri totali del campo</span></span>
                    </span>
                </li>
                <li>&nbsp;<code>d</code><span style="font-size:14.44px;">&nbsp;&nbsp;<span>indica il numero di cifre dopo il punto decimale</span></span>
                </li>
            </ul>
            <p><span>Ciascun descrittore può essere preceduto da un intero che indica il numero di dati a cui va applicato quel descrittore, ad es.&nbsp;<code>write(unit=1, fmt=(3ES16.6)) a,b,c</code>&nbsp; scrive tre reali con un campo di 16 caratteri, di cui 6 dedicati alla parte decimale della mantissa del numero.</span><br></p>
            <p><span><span>Nelle istruzioni di lettura è sconsigliabile usare formati, poiché non si può sempre garantire che il file in lettura contenga solo dati di quel specifico formato</span><br></span>
            </p>
            <p></p>
            <p><br></p>
            <h3>Il puntatore</h3>
            <p>Il puntatore è una variabile che contiene l'indirizzo di una zona di memoria. Gli array allocabili svolgono sostanzialmente lo stesso compito, per questo il puntatore ha una necessità di utilizzo abbastanza bassa nel linguaggio Fortran. Nel
                linguaggio C, invece, viene usato, per esempio, nella manipolazione delle matrici (operazione che in Fortran viene effettuata tramite array di più indici).</p>
            <p>Tuttavia, questo oggetto può essere molto utile quando si vuole manipolare tipi dati derivati che contengono array molto grandi, come i dati relativi a diversi esperimenti. Se si volesse ordine questi dati con un meccanismo di <i>bubblesort</i>,
                a ogni scambio si dovrebbero spostare potenzialmente milioni di dati! Con il puntatore, invece, ci si limita a scambiare gli indirizzi di memoria corrispondenti.</p>
            <p>Inoltre, ci sono situazioni in cui gli array risultano un po' scomodi. Se, infatti, si volesse passare da un array a N componenti a uno a N-1 componenti, l'operazione in sé non risulterebbe troppo complicata ma sarebbe estremamente inefficiente
                dal punto di vista del movimento dei dati. Infatti, si dovrebbe fare un numero totale di operazioni generalmente pari al numero di componenti dell'array. Se, al contrario, si considera il puntatore, si possono strutturare i dati in tante
                celle composte dal dato i-esimo e dal puntatore che fa riferimento alla cella successiva. Così facendo, per eliminare un dato è sufficiente reindirizzare il corrispondente puntatore al dato immediatamente successivo.</p>
            <h2><span style="color:inherit;font-family:inherit;">Aritmetica del computer</span></h2>
            <h3>La rappresentazione degli interi</h3>
            <p>Abbiamo visto come l’implementazione aritmetica su un computer può differire dall’aritmetica di Peano per la presenza di numeri negativi generati da somme di interi postivi che superano una certa soglia. Ciò è dovuto al numero finito di bit
                che caratterizzano i registri del computer ed è indipendente dal linguaggio di programmazione utilizzato. Avendo a disposizione <em>n</em> bit&nbsp; possiamo dunque rappresentare al massimo <em><strong>2<sup>n</sup></strong></em>&nbsp;numeri
                diversi.</p>
            <p><span style="font-size:14.44px;">L’aritmetica con cui ci troviamo a operare è conseguentemente di tipo <strong>modulare</strong>: se avessimo a disposizione una rappresentazione a 4 bit e quindi 2<sup>4 </sup>numeri possibili, il numero 16 corrisponderebbe allo zero in aritmetica a classe di resto pari a <em>mod 2<sup>4</sup></em>&nbsp;.</span></p>
            <p><span style="font-size:14.44px;">Si pone ora il problema della rappresentazione dei numeri negativi in sistema binario. Si potrebbe pensare di simboleggiare il segno meno con l’aggiunta di un bit, ma in questo caso si avrebbero due rappresentazioni diverse per lo zero (00000000=+0 e 1000000=-0 in un sistema a 8 bit), in contraddizione con il teorema dell’unicità dell’elemento neutro.&nbsp;</span></p>
            <p><span style="font-size:14.44px;">Utilizzando l’aritmetica modulare possiamo tuttavia identificare degli <em>inversi additivi</em>. Sempre nell’esempio della rappresentazione a 4 bit ( e quindi in aritmetica&nbsp;<em>mod 2<sup>4</sup></em>&nbsp;), notiamo che:</span></p>
            <p>1 + 15 = 0</p>
            <p>2 + 14 = 0</p>
            <p>. . .</p>
            <p><span style="font-size:14.44px;">15 è dunque l’inverso additivo di 1 e corrisponde a -1, 14 corrisponde a -2 e così via. Notiamo che gli inversi additivi costituiscono la seconda metà dei numeri a disposizione e che zero è l'inverso additivo di se stesso. In questo caso i numeri positivi vanno da 0 a 7 e quelli negativi da 8 a 16.</span></p>
            <p>Prendiamo a titolo d'esempio il numero 5 scritto in una sequenza di 32bit. Avremo&nbsp;</p>
            <p>0...0 1 0 1 = 5<sub>10</sub>&nbsp; &nbsp; (lo zero è ripetuto 29 volte)</p>
            <p>Per scrivere il suo inverso additivo in sequenza binaria è necessario scambiare tutti gli zero e gli uni della sequenza sopra riportata per poi sommare un 1. Si ha quindi</p>
            <p>1.....1 0 1 1 = - 5<sub>10</sub>&nbsp;</p>
            <p>Sommando le due sequenze e tenendo conto del fatto che 1 + 1 = 0 con riporto di uno, il risultato è infatti pari a zero.</p>
            <h4>Rappresentazione del Complemento 2</h4>
            <p>Se nell’aritmetica di Peano l’insieme dei numeri reali è rappresentato da una retta illimitata sia inferiormente che superiormente, nell'aritmetica modulare il numero limitato di byte disponibili comporta l'esistenza di un massimo e di un
                minimo evidenziati dalla rappresentazione qui sotto riportata (<em>rappresentazione del complemento 2</em>):</p>
            <p style="text-align:center;"><img class="img-responsive" style="vertical-align:text-bottom;margin:0px .5em;" src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/Schermata%202021-04-12%20alle%2009.56.21.png" alt="Rappresentazione del complemento 2"
                    width="200" height="190"></p>
            <p>Vediamo come questo cerchio risulta essere costituito da due metà: la prima (da 0 a 2<sup>n-1</sup>&nbsp;-1) è quella dei numeri positivi, mentre la seconda (da -2<sup>n-1&nbsp; (errore nella figura!)&nbsp; </sup>a &nbsp; -1) è quella dei
                numeri negativi, in cui si trovano appunto gli interi additivi. 2<sup>n-1</sup>&nbsp;-1 rappresenta il più grande numero positivo, mentre -2<sup>n-1&nbsp; </sup>è il più piccolo numero negativo.</p>
            <p>Si possono quindi riscontrare delle anomalie nel caso in cui due numeri postivi generino una somma il cui valore supera quello di 2<sup>n-1</sup>&nbsp;-1, andando a ricadere nel settore negativo del nostro cerchio. Si spiega così il motivo
                per cui somme di numeri positivi (ma anche numeri elevati al quadrato) danno luogo a valori negativi.</p>
            <p>Alcuni software segnalano in questo caso il cosiddetto “errore di <em>overflow</em>”, anziché svolgere il calcolo in aritmetica modulare. Risulta però più efficiente mantenere quest’ultimo in quanto permette la generazione di numeri <em>pseudocasuali</em>,
                ossia di numeri che pur essendo generati da un approccio deterministico hanno tutte le caratteristiche dei numeri casuali (numeri di cui è impossibile determinare il valore prima della loro estrazione). La rappresentazione del complemento
                2 è quindi la codifica più frequentemente utilizzata per la rappresentazione degli interi.</p>
            <p><span style="font-size:14.44px;">Il problema può infatti essere aggirato fornendo interi con un numero sufficientemente alto di bit, come 64 bit anziché 32: in questo caso, il massimo intero positivo sarebbe 2<sup>63 </sup>- 1.</span></p>
            <p><span style="font-size:14.44px;">Infine un altro modo per lavorare con interi sempre più grandi è quello di utilizzare dei software che rappresentano gli interi con un numero variabile e potenzialmente molto elevato di bit, in modo da superare le limitazioni poste dal numero di bit dei registri e avere come unico confine la dimensione della RAM.</span></p>
            <p>&nbsp;</p>
            <p>&nbsp;</p>
            <h4><span style="font-size:14.44px;">Rappresentazione con Bias</span></h4>
            <p><span style="font-size:14.44px;">La rappresentazione di tipo <em>bias</em> attribuisce alle sequenze di bit il valore fornito dalla rappresentazione complemento 2 ma sottratto di una costante (detta appunto <em>bias</em>).</span></p>
            <p style="text-align:center;"><img class="img-responsive" style="vertical-align:text-bottom;margin:0px .5em;" src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/Schermata%202021-04-12%20alle%2013.10.03.png" alt="Confronto fra le due rappresentazioni"
                    width="500" height="294"></p>
            <p>In questo caso, notiamo che il <em>bias</em> è uguale a 127 e lo zero in complemento 2 corrisponde quindi a -127 nella rappresentazione <em>bias</em>. Tale codifica è utilizzata soprattutto per la rappresentazione di esponenti interi di numeri
                con virgola (numeri "<em>floating point"</em>).</p>
            <h3>Rappresentazione di numeri con virgola</h3>
            <p><span style="font-size:14.44px;">Nella rappresentazione decimale, la virgola (o il punto decimale in notazione anglosassone) separa le cifre ottenute dalla moltiplicazione per esponenti positivi da quelli ottenuti dalla moltiplicazione per esponenti negativi. I numeri possono essere rappresentati da una parte intera e una decimale separate dalla virgola (<em>notazione a</em>&nbsp;<em>virgola fissa; </em>es. 0.0003247) oppure da una componente detta "mantissa" e l'esponente (<em>notazione a virgola mobile; </em>es. 0.3247*10<sup>-3</sup>&nbsp;).&nbsp;</span></p>
            <p><span style="font-size:14.44px;">Il punto decimale assume lo stesso significato in rappresentazione binaria, dove una sequenza del tipo:</span></p>
            <p><span style="font-size:14.44px;">1 0 1 . 1 1 0 1</span></p>
            <p>avrà come parte intera 1*2<sup>2&nbsp;</sup>+ 0*2<sup>1</sup>&nbsp;+<sup>&nbsp;</sup>&nbsp;1*2<sup>0&nbsp;</sup>&nbsp;=&nbsp; 5<sub>10</sub>&nbsp; &nbsp; &nbsp; e come parte decimale&nbsp; &nbsp; 1*2<sup>-1</sup> + 1*2<sup>-2</sup>&nbsp;+
                0*2<sup>-3</sup>&nbsp;+ 1*2<sup>-4&nbsp;</sup>&nbsp;=&nbsp; 0.8125<sub>10</sub></p>
            <p>abbiamo quindi che&nbsp;1 0 1 . 1 1 0 1&nbsp; =&nbsp; &nbsp;5.8125<sub>10</sub></p>
            <p>&nbsp;</p>
            <p>Per passare invece da una notazione in base 10 a una in base 2, la parte intera si calcola con il sistema delle divisioni successive già precedentemente illustrato, mentre per la parte decimale:</p>
            <ul>
                <li>si moltiplica la parte a destra della virgola per 2;</li>
                <li>si considera la parte intera (1 o 0) del numero ottenuto come cifra utile;</li>
                <li>si prende la parte decimale del nuovo numero e la si moltiplica per 2;</li>
                <li>si ripete il procedimento finché la parte a destra diventa zero.</li>
            </ul>
            <p>La figura seguente riporta un esempio di applicazione di tale algoritmo a un numero la cui parte decimale è 0.3.</p>
            <p style="text-align:center;"><img class="img-responsive" style="vertical-align:text-bottom;margin:0px .5em;" src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/download.png" alt="numeri con virgola in sistema binario" width="248" height="203"></p>
            <p style="text-align:left;">&nbsp;Applicando l'algoritmo a questo numero (finito) otteniamo una sequenza che in base 2 è invece periodica: il blocco 0011 si ripete infatti all'infinito dopo un antiperiodo 01 e siccome il blocco si ripete infinite volte segue che la rappresentazione
                del numero sarà approssimata.</p>
            <p>La rappresentazione dei numeri&nbsp;<em>floating point&nbsp;</em>è stata recentemente standardizzata in modo che, lavorando con compilatori diversi, fosse comunque possibile ottenere dei risultati compatibili a prescindere dal computer in
                uso. Ciò significa che ci sono comitati internazionali che si mettono d'accordo sulle caratteristiche che devono essere soddisfatte per essere considerati aderenti allo standard, senza però &nbsp;precludere la possibilità di aggiungere
                determinate caratteristiche che rendono un compilatore più o meno vantaggioso dal punto di vista commerciale.</p>
            <p>Secondo lo standard attuale ogni computer ha a disposizione 3 diverse quantità di bit per poter rappresentare i numeri floating point:</p>
            <ol>
                <li>Numeri floating point a 32 bit</li>
                <li>Numeri floating point a 64 bit</li>
                <li>Numeri floating point a 128 bit</li>
            </ol>
            <p>Il singolo compilatore può presentare anche solamente due delle rappresentazioni standard.</p>
            <p>Chiaramente, come già indicato sopra, questo non preclude la presenza di numeri floating point con ''taglie'' diverse, inoltre per un computer che dispone di un &nbsp;processore Intel, Gfortran ed altri compilatori mettono a disposizione un
                ulteriore rappresentazione ad 80 bit.</p>
            <p><strong>Rappresentazione standard dei numeri Floating Point in notazione scientifica.</strong></p>
            <p>Consideriamo dapprima la rappresentazione a 32 bit, abbiamo quindi a disposizione 32 caselle per poter rappresentare il numero. Il primo bit verrà utilizzato per rappresentare il segno del numero, in particolare utilizzeremo uno <strong>zero </strong>se
                il numero è positivo, altrimenti utilizzeremo un <strong>1</strong>. I successivi bit saranno utilizzati per la rappresentazione della mantissa e dell'esponente, sarà necessario riservare un numero equilibrato di bit per poter visualizzare
                in modo abbastanza preciso la mantissa e riuscire ad ottenere un numero con esponente molto elevato. Lo standard mette a disposizione di 8 caselle per la rappresentazione dell'esponente e le restanti 23 caselle per la mantissa.&nbsp;</p>
            <p><em>Occorre ricordare che la rappresentazione della mantissa binaria di un numero standardizzato comincia sempre con 1.&nbsp;</em>Se il numero è standardizzato, possiamo quindi evitare di scriverlo nel campo della mantissa concentrandoci sulla
                scrittura di un certo numero di cifre binarie.</p>
            <p>Il campo esponente è un intero che viene rappresentato tramite la notazione <strong>BIAS 127.</strong></p>
            <p>&nbsp;</p>
            <table border="1" cellspacing="0" cellpadding="0">
                <tbody>
                    <tr>
                        <td valign="top" width="64">
                            <p>0/1 -segno</p>
                        </td>
                        <td valign="top" width="64">
                            <p><strong>exp</strong></p>
                        </td>
                        <td valign="top" width="64">
                            <p><strong>&nbsp; &nbsp; &nbsp;...</strong></p>
                        </td>
                        <td valign="top" width="64">
                            <p><strong>…</strong></p>
                        </td>
                        <td valign="top" width="64">
                            <p><strong>exp (8)</strong></p>
                        </td>
                        <td valign="top" width="64">
                            <p><strong>mantissa</strong></p>
                        </td>
                        <td valign="top" width="64">
                            <p><strong>&nbsp; &nbsp; &nbsp;...</strong></p>
                        </td>
                        <td valign="top" width="64">
                            <p><strong>&nbsp; &nbsp; &nbsp; ...</strong></p>
                        </td>
                        <td valign="top" width="64">
                            <p><strong>&nbsp; &nbsp; &nbsp; ...&nbsp;</strong></p>
                        </td>
                        <td valign="top" width="64">
                            <p><strong>mantissa (32)</strong></p>
                        </td>
                    </tr>
                </tbody>
            </table>
            <p>&nbsp;</p>
            <p>Sorgono alcuni problemi: stiamo supponendo che tutti i numeri siano normalizzabili, ovvero che tutti i numeri la cui mantissa comincia con 1. Se consideriamo per esempio lo zero, è evidente che la sua mantissa non avrà al primo posto la cifra
                1, per cui suddivideremo i numeri normalizzati da quelli non normalizzati in modo che questi siano distinguibili facilmente. Useremo il campo esponente come criterio di distinzione vedendo che se esso è composto da 8 zeri oppure &nbsp;da
                8 uni, allora sappiamo di avere un numero non normalizzato, altrimenti siamo in presenza di un numero normalizzato.&nbsp;</p>
            <ul>
                <li><strong>Zero: </strong>E = 0, 0, 0, 0, 0, 0, 0, 0 &nbsp;- M = 0, 0, ... 0.&nbsp;</li>
            </ul>
            <p>Per cui daremo ai numeri non normalizzati la seguente rappresentazione:</p>
            <ol>
                <li>Il primo bit indica il segno del numero non normalizzato</li>
                <li>Dal secondo bit al nono bit una sequenza di zeri che mi indicano l'esponente di un numero non normalizzato</li>
                <li>Dal decimo bit al trentaduesimo bit la rappresentazione della mantissa, sottintendendo però in questo caso che al primo posto anziché trovare un 1 (come accadeva per i numeri normalizzati) troveremo uno zero che non verrà scritto nelle
                    caselle&nbsp;</li>
            </ol>
            <p>La scrittura del numero non normalizzato quindi avverà in questo modo:</p>
            <p>&nbsp; &nbsp; &nbsp;± 0. x<sub>1</sub>,x<sub>2</sub>, . . ., x<sub>23</sub>&nbsp;• 2<sup>-126&nbsp;</sup></p>
            <p>La giustificazione della presenza del termine 2<sup>-126</sup>&nbsp;è data dal fatto che stiamo lavorando con la rappresentazione con BIAS 127. Infatti usando la rappresentazione con BIAS abbiamo visto in precedenza che al termine:</p>
            <p>0 0 0 0 0 0 0 0 corrisponde a -127 in codifica BIAS&nbsp;</p>
            <p>0 0 0 0 0 0 0 1 corrisponde a -126 in codifica BIAS</p>
            <p>...</p>
            <p>...</p>
            <p>...</p>
            <p>1 1 1 1 1 1 1 0 corrisponde a +127 &nbsp;in codifica BIAS</p>
            <p>1 1 1 1 1 1 1 1 corrisponde a +128 &nbsp;in codifica BIAS</p>
            <p>Vediamo che il più piccolo esponente per i normalizzati è -126 (0 0 0 0 0 0 0 1), se quindi vogliamo avere il gruppo dei non normalizzati diversi da zero tale che sia contiguo al più piccolo dei normalizzati, la scelta è quella di scegliere
                un'esponente -126. Se ragioniamo sui positivi &nbsp;e considerando il più grande numero non normalizzato:</p>
            <p>(0. 1 1 1 1 1 1 1 1) • 2<sup>-126 </sup>&nbsp;sommando un 1 a questo questo numero otterremo 1. 0 0 0 0 0 0 0 0 • 2<sup>-126</sup>&nbsp;approdando nel campo dei normalizzati ( si noti che il primo numero della mantissa questa volta è 1).</p>
            <p>In conclusione un numero non normalizzato lo si scrive in questo modo:</p>
            <p>se E = 0 e M ≠ 0&nbsp;→ 0. X<sub>1</sub>, . . . , x<sub>23</sub>&nbsp;• 2<sup>-126</sup></p>
            <p>Consideriamo infine il campo esponente 1 1 1 1 1 1 1 1 1, abbiamo i seguenti casi</p>
            <ol>
                <li>Se il segno è positivo (0) e la mantissa M = 0 avremo + infinito&nbsp;</li>
                <li>Se il segno è negativo (1) e la mantissa M = 0 avremo - infinito</li>
                <li>Se invece ho E con tutti uni e M ≠ 0 avremo NaN (Not a Number) riservato alle operazioni aritmetiche errate.</li>
            </ol>
            <p>Osserviamo che il Max{norm} ≈ 2<sup>128</sup>&nbsp;e il Min{norm}≈-2<sup>128</sup>.</p>
            <table>
                <caption style="caption-side:bottom;">&nbsp;</caption>
                <thead>
                    <tr>
                        <th scope="col">BIT</th>
                        <th scope="col">ESPONENTE</th>
                        <th scope="col">MANTISSA</th>
                        <th scope="col">BIAS</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>32&nbsp;</strong></td>
                        <td style="text-align:center;">&nbsp;8</td>
                        <td style="text-align:center;">23&nbsp;</td>
                        <td style="text-align:center;">127&nbsp;</td>
                    </tr>
                    <tr>
                        <td><strong>64&nbsp;</strong></td>
                        <td style="text-align:center;">11</td>
                        <td style="text-align:center;">52</td>
                        <td style="text-align:center;">1023</td>
                    </tr>
                    <tr>
                        <td><strong>80 (Non Standard)</strong></td>
                        <td style="text-align:center;">15</td>
                        <td style="text-align:center;">64</td>
                        <td style="text-align:center;">16383</td>
                    </tr>
                    <tr>
                        <td><strong>128&nbsp;</strong></td>
                        <td style="text-align:center;">15</td>
                        <td style="text-align:center;">112</td>
                        <td style="text-align:center;">16383</td>
                    </tr>
                </tbody>
            </table>
            <p>&nbsp;</p>
            <p>L'insieme dei numeri rappresentabili in funzione dei bit a disposizione risulta <em>in ogni caso</em>&nbsp;limitato, siamo quindi in grado di capire quale sia il più grande/piccolo numero rappresentabile. Per trovare per esempio il più grande
                ci basterà prendere il più grande esponente a cui assoceremmo una mantissa ''1.1 1 1 1 .. 1'' &nbsp;che vale circa 2.</p>
            <p>Nel caso di 32 bit abbiamo che il numero più grande risulta essere 2•2<sup>127</sup>≈ •2<sup>128</sup>&nbsp;ovvero circa 10<sup>38</sup>&nbsp;. Chiaramente risulta impossibile rappresentare tutti i numeri reali contenuti tra 0&lt;x&lt;Max
                e quindi ritroveremo un certo numero di ''buchi'' di ampiezza&nbsp;</p>
            <p>ΔX=0.00..0•2<sup>E</sup>, ( a destra dell'uguale c'è una&nbsp;sequenza di 23 zeri - E= esponente con cui stiamo lavorando ). Ciò significa che più aumentiamo l'esponente, maggiore sarà la distanza tra i valori e quindi <strong>non sono equidistanziati.&nbsp;</strong></p>
            <p><strong>Approssimazione dei numeri floating point.</strong></p>
            <p>Siccome siamo a disposizione di un numero limitato di valori, sarà necessario effettuare un arrotondamento dei numeri. In termini pratici supponiamo di avere due numeri X e Y normalizzati (per semplicità):</p>
            <p>X = 1. X<sub>1</sub> . . . X<sub>23</sub>&nbsp;•2<sup>5</sup></p>
            <p>Y = 1. Y<sub>1</sub>&nbsp;. . . Y<sub>23&nbsp;</sub>•2<sup>3</sup></p>
            <p>e di volerne fare la somma X+Y.</p>
            <p>Chiaramente la somma dei due numeri dipende dal loro esponente per cui non è possibile effettuare la somma delle mantisse, ma sarà necessario effettuare una conversione di uno dei due numeri (in una forma non normalizzata) che ci permetta
                di farlo in un momento successivo.</p>
            <p>Supponiamo di voler convertire Y in un numero moltiplicato per 2<sup>5</sup>&nbsp;che in termini di istruzioni macchina significa aggiungere un paio di zeri e quindi&nbsp;</p>
            <p>Y<sup>'</sup>=0.01Y<sub>1</sub>&nbsp;. . .Y<sub>23&nbsp;</sub>•2<sup>5</sup>&nbsp;.Chiaramente il numero convertito occuperà più spazio però non risulta essere un problema in quanto disponiamo di 32 bit.</p>
            <p>A questo punto potrò scrivere Z=X+Y<sup>'</sup></p>
            <p>Z=1.Z<sub>1</sub>&nbsp;. . . •2<sup>α</sup>. Quando devo impacchettare nuovamente il mio risultato nel campo a 32 bit dotato di segno, esponente e mantissa dovrò ''tagliare'' un pezzo della mantissa di Z in quanto contiene più di 23 bit facendo
                quindi un'approssimazione. A questo punto bisogna valutare qual è la migliore approssimazione da fare per evitare una propagazione considerevole dell'errore.</p>
            <p>Lo standard ci dice che esistono 4 tipi di arrotondamento:</p>
            <ol>
                <li>Arrotondamento al numero più ''vicino''</li>
                <li>Arrotondamento verso + infinito</li>
                <li>Arrotondamento verso - infinito</li>
                <li>Arrotondamento verso 0&nbsp;</li>
            </ol>
            <p>Normalmente i compilatori scelgono di default l'utilizzo dell'arrotondamento al numero più vicino, molto più utile in termini pratici.&nbsp;</p>
            <p><br></p>
            <h4>Differenze principali con i sistemi numerici matematici</h4>
            <p>Alcuni numeri che in base 10 sono rappresentati con un numero finito di cifre diventano periodici in base 2. Inoltre l'insieme dei numeri che possiamo rappresentare è limitato e non denso. Peraltro, i numeri non sono neanche uniformemente
                distribuiti.</p>
            <p>Un'altra conseguenza dell'avere una precisione limitata è che non vale più l'unicità dell'elemento neutro. ad es. \( 1.34 \cdot 10^2 + 1.21 \cdot 10^{-4} = 1.3400121 \cdot 10^2. \) Se ho disponibilità di solo 2 cifre, il secondo addendo è
                un numero \( \neq 0 \) che sommato al primo restituisce il primo numero invariato: è simile a un elemento neutro.</p>
            <p>A causa dell'effetto appena menzionato, la proprietà associativa smette di valere:</p>
            <p>\( (A + B)+C=A+(B+C) \)</p>
            <p>con \( A=1.34, B=0.0041,C=0.0041 \) e precisione di due cifre dopo la virgola, non vale:</p>
            <p>\( (1.34+0.0041)+0.0041=1.34+0.0041=1.34; \)</p>
            <p>\( 1.34 + (0.0041+0.0041)=1.34 + 0.0081 (=1.3481)=1.35 \)</p>
            <p>Per tener traccia di questa imprecisione c'è un parametro, detto <strong>precisione macchina</strong> \( \varepsilon_M \), che indica la precisione relativa, cioè sulla mantissa (a parità di esponente). \(\varepsilon_M\) è il più piccolo valore
                che tale che \( 1+\varepsilon_M &gt; 1 \). L'unità di arrotondamento è l'ampiezza dell'intervallo (sulla mantissa) di tutti i numeri che vengono espressi con la stessa sequenza di bit, ossia la differenza tra la più grande e la più piccola
                mantissa reale che ricevono la stessa mantissa nel computer. <strong>Importante!</strong> Questi valori indicano una precisione relativa, cioè sempre a parità di esponente e senza considerare l'esponente. Altrimenti l'unità di arrotondamento
                diventerebbe tanto più grande quanto più grandi diventano gli esponenti dei numeri che salviamo.</p>
            <p>Se \(x_v\) è il valore vero, un approssimante \(x\) ha \(p\) cifre significative esatte se \( \frac{|x-x_v|}{|x_v|}&lt;0.5\cdot 10^p \)</p>
            <table style="text-align:center;" border="1" cellspacing="0" cellpadding="0">
                <caption>&nbsp;</caption>
                <thead>
                    <tr>
                        <th scope="col">Bit</th>
                        <th scope="col">Bit significativi</th>
                        <th scope="col">\( (\varepsilon_M)_2 \)</th>
                        <th scope="col">\( (\varepsilon_M)_{10} \)</th>
                        <th scope="col">Cifre significative esatte</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>32</td>
                        <td>24</td>
                        <td>\(2^{-24}\)</td>
                        <td>\(0.596\cdot10^{-8}\approx10^{-7}\)</td>
                        <td>6</td>
                    </tr>
                    <tr>
                        <td>64</td>
                        <td>53</td>
                        <td>\(2^{-53}\)</td>
                        <td>\(1.11\cdot10^{-16}\approx10^{-16}\)</td>
                        <td>15</td>
                    </tr>
                    <tr>
                        <td>80</td>
                        <td>64</td>
                        <td>\(2^{-64}\)</td>
                        <td>\(0.542\cdot10^{-20}\approx10^{-19}\)</td>
                        <td>18</td>
                    </tr>
                    <tr>
                        <td>128</td>
                        <td>113</td>
                        <td>\(2^{-113}\)</td>
                        <td>\(0.962\cdot10^{-34}\approx10^{-34}\)</td>
                        <td>33</td>
                    </tr>
                </tbody>
            </table>
            <p>Ad esempio, se faccio stampare a Fortran il numero \(0.1\), quello che vedo è la migliore approssimazione della conversione del numero in forma binaria. In generale \( x_c=x_v(1+\varepsilon_x) \), con \( |\varepsilon_x|&lt;\varepsilon_M \).</p>
            <p>Consideriamo ora anche \(&nbsp; y_c=y_v(1+\varepsilon_y) \) e \( x_c\cdot y_c=x_v(1+\varepsilon_x)y_v(1+\varepsilon_v)=x_vy_v(1+\varepsilon_x+\varepsilon_y+\varepsilon_x\varepsilon_y) \approx&nbsp;x_vy_v(1+\varepsilon_x+\varepsilon_y) \leq
                x_vy_v(1+2\varepsilon_M) \)</p>
            <p>Analogamente \( \frac {x_c}{y_c}=\frac {x_v}{y_v}\cdot\frac{1+\varepsilon_x}{1+\varepsilon_y}\approx\left(\frac {x_v}{y_v}\right)(1+\varepsilon_x)(1-\varepsilon_y)\approx\left(\frac {x_v}{y_v}\right)(1+\varepsilon_x-\varepsilon_y)\leq\left(\frac
                {x_v}{y_v}\right)(1+2\varepsilon_M) \)</p>
            <p>DA AGGIUNGERE!! Cancellazioni sottrattive ed errori sulle somme</p>
            <h3>Come evitare cancellazioni sottrattive?</h3>
            <p>Si può riformulare il problema in modo equivalente dal punto di vista matematico, ma in modo che non ci siano errori di cancellazione: se si vuole calcolare \( e^{-x} = \sum_{n=0}^\infty (-1)^n\frac{x^n}{n!} \) per valori grandi di \(x \)
                si rischia di andare incontro ad errori di cancellazione man mano che si va avanti con le somme. Una soluzione è calcolare prima \( e^x \) e successivamente \( e^{-x}=1/e^x \). Il vantaggio è che la serie di Taylor per \(e^x \) non è a
                segni alterni, quindi non soffre di cancellazioni sottrattive. Un altro esempio è il calcolo delle soluzioni di un'equazione di secondo grado con \( b&gt;0 \): \( x_\pm = \frac{-b\pm\sqrt{b^2-4ac}}{2a} \) potrebbe avere cancellazioni sottrattive
                al numeratore della soluzione con il segno \( + \). La formula equivalente \( x_+=\frac{2c}{-b-\sqrt{b^2-4ac}}\) non presenta questo problema.</p>
            <h3>Altri errori di arrotondamento</h3>
            <p>Non esistono solo le cancellazioni sottrattive. Una situazione diversa ma potenzialmente pericolosa è quella di errori di arrotondamento che si sommano in modo coerente. P.es. il caso di un ciclo in cui si vuole calcolare i valori di punti
                equispaziati in un intervallo. Ci sono diversi modi per ottenere i punti della suddivisione dell'intervallo: volendo dividere \( [a,b] \) in \( N \) parti separate di \( h= (b-a)/N \) si può ottenere l'\(i\)-esimo elemento sia come <code> x_i = a + ih </code>                che come</p>
            <pre>x = a
do i=1,N
    x = x +h
end do
</pre>
            <p>Il secondo modo somma errori tutti ufuali e quindi non possiamo sperare in cancellazioni degli stessi. La somma coerente di tanti errori tutti dello stesso segno provoca un deterioramento crescente della precisione deli punti, Se questi sono
                punti del dominio di una funzione potrebbero uscire dal dominio a causa della somma di tanti piccoli errori.</p>
            <h2>Il controllo della precisione in Fortran</h2>
            <p>Ogni tipo numerico ha un attributo <code>kind</code> che comunica al compilatore la precisione da attribuire al numero. Il valore dell'attributo <code>kind</code> non ha nessun legame fisso con l'effettiva precisione. Questo legame varia con
                i diversi sistemi operativi e compilatori. Ad esempio:</p>
            <pre>integer, parameter :: ik=selected_int_kind(12) !Valore del kind per avere 12 cifre decimali (fino a 10^12)
integer, parameter :: rk=selected_real_kind(5, 20) !Valore del kind per almeno 5 cifre decimali significative, con esponenti da 10^20 a 10^(-20)
integer(kind=ik) :: big_int
real(kind=rk) :: x,y,z
real(rk),parameter :: delta = 2.1_rk
real(rk) :: x
x= 2.134655437_rk
</pre>
            <p>Bisogna fare molta attenzione a inserire <code>_nomeKind</code> dopo la costante letterale affinché questa venga salvata con la precisione richiesta.</p>
            <h2>Calcolo scientifico</h2>
            <p>Nel risolvere numericamente un problema bisogna distinguere tra i parametri fisici e parametri numerici dell'algoritmo. I parametri numerici derivano tutti dal fatto che stiamo calcolando dei "fotogrammi successivi" del fenomeno fisico come
                approssimazione del continuo evolvere del tempo. I parametri fisici sono le masse, le leggi di forza, ecc.</p>
            <h3>L'algoritmo di Eulero</h3>
            <p>Si vuole cercare la soluzione a equazioni differenziali del tipo \( \ddot x =\frac {F(x(t),\dot x(t),t)} m \). Equazioni di questo tipo possono facilmente diventare troppo complesse per ottenere "analiticamente" (con strumenti matematici)
                la soluzione esatta. In questi casi si può, fornendo le condizioni iniziali, calcolare in modo approssimato "punto per punto" la posizione tramite metodi cosiddetti numerici.</p>
            <p>Ad esempio, si può considerare il problema di Cauchy dell'oscillatore armonico:</p>
            <p>\( \begin{cases}\ddot x = -\omega^2 x \\ x(0)=x_0\\ \dot x(0)=v_0 \end{cases} \)</p>
            <p>Si può studiare lo sviluppo di Taylor della soluzione per ottenere i valori della funzione incognita a tempi arbitrari:</p>
            <p>\( \displaystyle&nbsp; x(t)=x(0)+\dot x(0)t+\frac{\ddot x(0)}{2}t^2+&nbsp;\frac{\dddot x(0)}{6}t^3 ...= x_0(1 - \omega^2\frac{t^2}{2} + \omega^4\frac{t^4}{4!} - \omega^6\frac{t^6}{6!} + \dots) + \frac{v_0}{\omega}(\omega t - \frac{\omega^3
                t^3}{3!} + \frac{\omega^5 t^5}{5!}...) =x_0 cos( \omega t) +&nbsp;\frac{v_0}{\omega} sin( \omega t). \)</p>
            <p>Se però ci accontentiamo di ottenere i valori ad un tempo sufficientemente piccolo \( \Delta t \), posso scrivere</p>
            <p>\(\displaystyle&nbsp; x(\Delta t)=x(0)+\dot x(0)\Delta t+\frac{\ddot x(t=0)}{2}\Delta t^2+O(\Delta t^3) \)</p>
            <p>\(\displaystyle&nbsp; v(\Delta t)=v(0)+\dot v(0)\Delta t+O(\Delta t^2) \)</p>
            <p>Si può quindi ottenere un risultato approssimato non calcolando gli \( O \): se non si considerano errori di arrotondamento, tanto più piccolo sarà \( \Delta t \), tanto migliore l'approssimazione. Si prosegue poi calcolando</p>
            <p>\(\displaystyle&nbsp; x(2\Delta t)= x(\Delta t)+v(\Delta t)\Delta t + \frac{\ddot x(x(\Delta t))}2\Delta t^2 \)</p>
            <p>\(\displaystyle&nbsp; v(2\Delta t)=v(\Delta t)+\ddot x(\Delta t)\Delta t \)</p>
            <p>e così via. Per stimare l'errore si può usare la formula di Taylor per cui</p>
            <p>\(\displaystyle&nbsp; x(\Delta t)=x_v(\Delta t)+\frac{\dot a(\tau)}6\Delta t^3 \)</p>
            <p>\(\displaystyle&nbsp; v(\Delta t)=v_v(\Delta t)+\frac{\ddot a(\tau')}2\Delta t^2\)</p>
            <p>con \( \tau,\tau'\in[0,\Delta t] \). Da qui si può calcolare l'errore fatto per \( N \) passi:</p>
            <p>\( \displaystyle Pos_{err}(N passi)= \frac{\Delta t^3}6\sum_{i=1}^N\dot a(\tau_i)=\frac{N\Delta t^3}6\left(\frac 1 N\sum_{i=1}^N\dot a(\tau_i)\right) = T\frac{\Delta t^2}6\dot a(\tilde\tau) \)</p>
            <p>\( \displaystyle Vel_{err}(N passi)= \frac{\Delta t^2}2\sum_{i=1}^N\ddot a(\tau_i)=\frac{N\Delta t^2}2\left(\frac 1 N\sum_{i=1}^N\ddot a(\tau_i)\right) = T\frac{\Delta t}2\ddot a(\tilde\tau) \)</p>
            <p>La dipendenza scala quindi di una potenza rispetto a \(\Delta t\). A parità di intervallo di tempo, l'errore va a 0 per \(\Delta t \to0\). A questo punto si presentano però dei problemi pratici di implementazione, ma discutendo di algoritmi
                terremo l'ipotesi che la nostra macchina non abbia limitazioni (possa avere una precisione arbitraria)</p>
            <h3>Come scegliere il giusto <span>Δ</span><span>t</span>?</h3>
            <p>Bisogna assicurarsi di non ottenere immagini ridicole: ad esempio, simulare un moto armonico con un \(\Delta t\) superiore al periodo non può in nessun modo dare risultati soddisfacenti. A spanne, almeno 50 punti per periodo sono quasi decenti.
                Meglio un centesimo del periodo. Se diminuendo \(\Delta t\) non si osservano cambiamenti significativi, allora abbiamo un buon valore.</p>
            <p>Se la legge di forza è conservativa, possiamo verificare di avere un buon \(\Delta t\) calcolando l'energia meccanica istante per istante e verificando che resti costante. Non succederà mai, a causa degli errori, ma almeno deve restare conservata
                allo stesso ordine&nbsp; in \(\Delta t\) dell'errore globale dell' algoritmo.</p>
            <h3>L'algoritmo di Verlet</h3>
            <p>Le leggi di conservazione derivano da simmetrie dei problemi che consideriamo. Se le forze dipendono solo dalla posizione e non dalla velocità vale la cosiddetta "simmetria per inversione temporale". Si può verificare la bontà del nostro algoritmo
                invertendo il segno della velocità a un certo istante e verificando che ci porti alla posizione precedente. Non succederà mai neanche questo, ma almeno potrebbe differire di poco.</p>
            <p>Usando la notazione \(\begin {cases} x(t)=:x_0 \\ \Delta t =: \Delta, \\ x(t+\Delta)=:x_t \end{cases}\) l'algoritmo di Eulero diventa</p>
            <p>\(\begin{cases} x_t=x_0+v_0\Delta+\frac{a_0}2\Delta^2 \\ v_t=v_0+a_0\Delta\end{cases}\)</p>
            <p>quindi, per tornare indietro,</p>
            <p>\(\begin{cases} x_0'=x_t-v_t\Delta+\frac{a_t}2\Delta^2 \\ v_0'=-v_t+a_t\Delta\end{cases}\)</p>
            <p>da cui</p>
            <p>\(\begin{cases}x_0'=x_0+\frac{(a_t-a_0)}2\Delta^2 \\ v_0'=-v_0-\Delta(a_0-a_t)\end{cases}.\)</p>
            <p>Si può compensare questo difetto tramite un termine \(c_0=\frac{a_t-a_0}2\) e ottenere il nuovo algoritmo</p>
            <p>\(\begin{cases}x_t=x_0+v_0\Delta+\frac{a_0}2\Delta^2 \\ v_t=v_0+a_0\Delta + c_0\Delta=v_0+\frac{a_0+a_t}2\Delta\end{cases}\)</p>
            <p>Questa modifica restituisce la simmetria temporale e, come si vede da un'analisi in serie di Taylor, ha il vantaggio che sia le \(x\) che le \( v\) hanno un errore locale del tipo \(O(\Delta^3)\) e globale&nbsp; \(O(\Delta^2)\), quindi anche
                l'energia sarà approssimata meglio: all'ordine \(\Delta^2\).</p>
            <p>Questo algoritmo è il prototipo di una classe di algoritmi, detti simplettici, che soddisfano a richieste di tipo geometrico. Così com'è non è applicabile in modo semplice con leggi che hanno dipendenze da velocità.</p>
            <h3>Algoritmo di Groot-Warren</h3>
            <p>Una modifica dell'algoritmo di Verlet per leggi di forza che dipendono dalla velocità si può ottenere con la stessa formula per la posizione, introducendo due variabili intermedie \(\tilde v, \tilde a\):</p>
            <p>\(\begin{cases}x_t=x_0+v_0\Delta+\frac{a_0}2\Delta^2 \\\tilde v=v_0+a_0\Delta \\\tilde a=a(x_t,\tilde v)\\v_t=v_0+\frac{(a_0+\tilde a)}2\Delta\\a_t=a(x_t,v_t)\end{cases}\)</p>
            <p>Questo algoritmo valuta due volte le forze per ogni passo. Ci sono altri algoritmi che calcolano più volte le forze e hanno precisioni di ordine maggiore rispetto a \(\Delta\). Quale sia il più adatto dipende dalle limitazioni in termini di
                tempo: se la valutazione della forza è il collo di bottiglia Groot-Warren è un ottimo compromesso. Se invece serve grande precisione e non ci sono problemi di tempo si possono preferire altri algoritmi.</p>
            <h3>L'implementazione</h3>
            <p>Se lavoro in precisione di default e decido di prendere un \(\Delta t\) molto basso, rischio di avere errori di arrotondamento.</p>
            <h3>Calcolo di derivate</h3>
            <p>La definizione matematica di derivata di una funzione \(f\) come \( f'(x)=\lim_{\Delta x\to 0}\frac{f(x+\Delta x)-f(x)}{\Delta x} \) non è ben applicabile algoritmicamente. Per cui anziché utilizzare il limite che non è uno ''strumento'' ben
                definito algoritmicamente ci si concentra sulla definizione di rapporto incrementale, che dipende da x, ma anche da \(\Delta x\). Se non ci fossero errori di arrotondamento, si potrebbe avere un risultato tanto migliore quanto più piccolo
                \(\Delta x\). Si può quantificare grazie alla formula di Taylor:</p>
            <p>\(\displaystyle\frac{f(x+\Delta x)-f(x)}{\Delta x}=f'(x)+\frac{f''(\xi)\Delta x}2\) con \(\xi\in(x,x+\Delta x)\)</p>
            <p>Una formula migliore si può ottenere come</p>
            <p>\(\displaystyle f(x+\Delta x)=f(x)+f'(x)\Delta x+f''(x)\frac{\Delta x^2}2+\frac{f'''(\xi')}6\Delta x^3\)</p>
            <p>\(\displaystyle f(x-\Delta x)=f(x)-f'(x)\Delta x+f''(x)\frac{\Delta x^2}2-\frac{f'''(\xi'')}6\Delta x^3\)</p>
            <p>\(\displaystyle f(x+\Delta x)-f(x-\Delta x)=2\Delta xf'(x)+\frac16[f'''(\xi')+f'''(\xi'')]\Delta x^3\)</p>
            <p>\(\displaystyle\frac{f(x+\Delta x)-f(x-\Delta x)}{2\Delta x}=f'(x)+\frac16[\frac{f'''(\xi')+f'''(\xi'')}{2}]\Delta x^2=f'(x)+\frac16f'''(\bar\xi)\Delta x^2\)</p>
            <p>Questa formula viene detta <strong>delle differenze simmetriche</strong> e al limite restituisce la derivata se la funzione è derivabile. Ha il vantaggio che il termine di correzione scende come il quadrato di \(\Delta x\), ma lavorando con
                un numero finito di cifre significative tutte queste formule diventano disastrose con valori piccoli di \(\Delta x\). Come fare? Esistono dei valori intermedi tra quelli troppo grandi e quelli troppo piccoli?</p>
            <p>Detto \(Df=\frac{f_2-f_1}{c\Delta x}\), il rapporto incrementale (calcolato con una delle formule), il suo valore calcolato dal computer sarà \(Df_c\) tale che</p>
            <p>\(\displaystyle|Df_c-Df| \leq \left|-\varepsilon_{\Delta x}Df+\varepsilon_{f_2}\frac{f_2}{c\Delta x}-\varepsilon_{f_1}\frac{f_1}{c\Delta x}\right| \leq \varepsilon_M\left( |Df|+\left|\frac{f_2}{c\Delta x}\right|+\left|\frac{f_1}{c\Delta x}\right|
                \right) \approx \varepsilon_M \left(|f'(x)|+2\left|\frac{f(x)}{c\Delta x}\right|\right)\)</p>
            <p>&nbsp;</p>
            <p>Per le differenze asimmetriche avremo quindi un errore del tipo</p>
            <p>\(\displaystyle Err(D_Af)=A\Delta x+\frac{B\varepsilon_M}{\Delta x}\)</p>
            <p>Che ci aspettiamo abbia un punto di minimo per \(\Delta x\) dove \(\displaystyle A-\frac{B\varepsilon_M}{\Delta x^2}=0\), quindi \(\Delta x_{min}\propto\varepsilon_M^{1/2}\) e \(Err_{min}\propto \varepsilon_M^{1/2}\).</p>
            <p>&nbsp;</p>
            <p>Per le differenze simmetriche avremo un errore del tipo</p>
            <p>\(\displaystyle Err(D_Af)=A\Delta x^2+\frac{B\varepsilon_M}{\Delta x}\)</p>
            <p>Che ci aspettiamo abbia un punto di minimo per \(\Delta x\) dove \(\displaystyle2A\Delta x-\frac{B\varepsilon_M}{\Delta x^2}=0\), quindi \(\Delta x_{min}\propto\varepsilon_M^{1/3}\) e \(Err_{min}\propto \varepsilon_M^{2/3}\).</p>
            <p>Da un semplice calcolo numerico si vede che la formula per differenze simmetriche ha un valore ottimale di \(\Delta x\) di circa un ordine di grandezza maggiore della formula per differenze asimmetriche, che risulta in un errore minimo di
                un ordine di grandezza inferiore.</p>
            <h3>Risoluzione di equazioni</h3>
            <p>Una necessità frequente è quella di risolvere equazioni del tipo \( f(x)=0 \). In pochi casi particolari esistono formule risolutive esplicite, ma nella maggior parte dei casi la soluzione non si può esprimere in termini di funzioni elementari.
                A quel punto può essere utile trovare numericamente una soluzione approssimata. Come fare?</p>
            <h4>Il teorema degli zeri</h4>
            <p>Alcuni teoremi di Analisi possono tornare utili: se sappiamo che \( f \) è continua, possiamo usare il teorema degli zeri: se la funzione ha segni opposti in due punti, ce ne sarà uno intermedio in cui varrà 0.</p>
            <p>Un metodo algoritmico per implementare questo metodo e trovare il punto di zero potrebbe essere strutturato così:</p>
            <p>
            </p>
            <pre>Data f su [a,b]
fa=f(a)
fb=f(b)
se fa*fb&lt;0
ripeti sempre:
  c=(a+b)/2
  fc=f(c)
  se fc=0  EXIT       (!)
  se fa*fc&lt;0
    b=c
    fb=fc
  altrimenti
    a=c
    fa=fc
</pre>
            <p>Questo in teoria potrebbe non essere un buon algoritmo: potrebbe non raggiungere mai la condizione di uscita. In realtà su un computer la distanza dalla soluzione diminuisce sempre di più fino a non cambiare più. Si può facilmente ovviare
                a questo problema ponendo, invece della condizione in <code>(!)</code> \( f_c=0 \), una condizione del tipo \( |f_c|&lt;\varepsilon \). Il parametro \(\varepsilon\) non può però essere piccolo a piacere: non può essere più piccolo del
                <u>successivo dello 0</u>. Il vero problema è che i numeri sul computer, oltre a non essere densi, non sono neanche equispaziati. Quindi la precisione assoluta con cui si può chiedere la soluzione dipende dall'ordine di grandezza dei valori
                della funzione nel punto, e con essa la precisione macchina da richiedere. Il problema si risolve fissando l'incertezza massima non sul valore della funzione ma sulla posizione dell'ascissa che annulla la funzione. Dopo \(n \) passi, l'intervallo
                in cui si trova lo zero è ampio \( \frac{b-a}{2^n} \)</p>
            <pre>ripeti 10000 volte
se (|fc| &lt; epsilon .or. b-a &lt; delta .or. (b-a)/min(|a|,|b|) &lt; C * errore_macchina)
ecc.
</pre>
            <h4>Il metodo iterativo</h4>
            <p>Notiamo che da \( f(x)=0 \) segue immediatamente \( x= x+f(x) \), per cui la successione definita per ricorrenza come \( x_{i+1}=x_i+f(x_i)=g(x_i) \), se ha limite, converge a un punto di zero di \(f\). Si converte così il problema in un problema
                di punto fisso. Ad es. l'equazione \( x^2+3x-2=0 \) genera la sucessione \( x_{i+1} = x_i+x_i^2+3x_i-2 \)</p>
            <p>Problema: quanti punti fissi ha la successione \(x_{i+1}=\sqrt{x_i} \)?</p>
            <p>Teorema: Date le ipotesi che non ho scritto, se \( |g'(x)|&lt;1 \) la successione converge al punto fisso. Ad esempio se \( g(x)=\sqrt{x} \), il "bacino di attrazione" di 1 è tutto \( \mathbb{R}^+ \) meno lo 0.</p>
            <h4>Il metodo di Newton</h4>
            <p>Da un punto di partenza si può considerare la retta tangente al grafico della funzione e considerare il punto in cui si annulla. Su quel punto considero la retta tangente al grafico e dove si annulla. Itero questo procedimento finché non arrivo
                su uno zero. Questo metodo funziona a patto di partire abbastanza vicini al punto di zero. </p>
            <p>L'(n+1)-esimo punto della successione è ricavabile a partire dall'equazione della retta tangente valutata nel punto in cui si annulla \( (y=0)) \).</p>
            <p>\( 0-f(x_n) = f'(x_n) (x_{n+1}-x_n) \)</p>
            <p>Rimaneggiando l'equazione otteniamo l'espressione esplicita per \( x_{n+1} \)</p>
            <p>\(x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)} \)</p>
            <p><b>Attenzione: </b>è molto importante utilizzare una derivata ottenuta analiticamente e non numericamente, anche i piccoli errori causali dovuti al calcolo numerico (per sua natura approssimativo) della derivata possono portare a significative
                differenze nei risultati.</p>
            <h3>Interpolazione</h3>
            <p>L'interpolazione costituisce una tecnica utilizzata nella derivazione e integrazione approssimata di funzioni di cui si conosce un limitato numero di punti. Una situazione di questo tipo può verificarsi durante l'analisi di dati sperimentali,
                dove è possibile che le misurazioni effettuate non siano sufficienti a garantire un intervallo di dati abbastanza elevato per definire la funzione cercata, se non tramite un'approssimazione.</p>
            <p>Supponiamo quindi di avere una funzione \(g(x)\) detta "<i>interpolante</i>" che assume i valori \(y_i=g(x_i)\) all'interno dell'intervallo [a, b] a cui appartengono gli n+1 punti \(x_i\) con \(i=0,\dots,n\) detti "<i>nodi </i>dell'interpolazione".
                Su tale intervallo si suppone essere fissato un numero n+1 di funzioni \(\sum_{j=0}^n \lambda_j \Phi_j(x)\) fra loro linearmente indipendenti e quindi tali che</p>
            <p style="text-align:center;">\(\sum_{j=0}^n \lambda_j \Phi_j(x)=0\) se e solo se \(\lambda_j=0\) per \(j=0, \dots , n\)</p>
            <p>Scopo dell'interpolazione è determinare una funzione \(f(x_i)=\sum_{j=0}^n \lambda_j \Phi_j(x)\) che assuma gli stessi valori \(y_i\) nei punti \(x_i\), ossia tale che \(f(x_i)=y_i\) con&nbsp; \(i=0, \dots , n\).</p>
            <p><br></p>
            <h4>Interpolanti polinomiali</h4>
            <p>Una possibile funzione interpolante può assumere la forma di un polinomio \(p_n(x)\) di grado \(n\) del tipo</p>
            <p style="text-align:center;">\(p(x) = a_0x^n + a_1x^{n-1}+ \dots + a_{n-1}x+a_n+a_0\)</p>
            <p style="text-align:left;">dove \(a_0 \neq 0\).</p>
            <p>Si può dimostrare come dati n+1 punti \((x_i,y_i)\) con \(i=0, \dots, n\) tali che \(x_i&nbsp; \neq x_j\) per \(i\neq j\), esiste ed è unico il <i>polinomio di interpolazione </i>\(p(x)\) per cui vale</p>
            <p style="text-align:center;">\(p_n(x_i)=y_i\) per ogni \(i=0, \dots , n\)</p>
            <p style="text-align:left;">dove \(p_n(x_i)\) è il polinomio di grado \(n\) calcolato nel punto \(x_i\).</p>
            <p style="text-align:left;">Tale risultato garantisce quindi l'esistenza e l'unicità della soluzione calcolata per nodi distinti: ne segue che se due nodi forniscono la stessa soluzione allora devono necessariamente costituire un unico nodo.</p>
            <p style="text-align:left;"><br></p>
            <h4>Interpolanti di Lagrange</h4>
            <p>Il polinomio della forma di Lagrange viene utilizzato per la determinazione del valore che il polinomio \(p(x)\) assume in un determinato punto \(x\). Introduciamo quindi l'<i>interpolante di Lagrange </i>\(L_j^n\), un interpolante a due indici
                definito come</p>
            <p style="text-align:center;"><span style="font-size:14.44px;">\(L_j^n(x)=\prod_{i=0, i \neq j}^n \frac{x-x_i}{x_j-x_i}\)</span></p>
            <p style="text-align:left;">Ne segue che&nbsp;</p>
            <p style="text-align:center;">\(L_j^n(x_i)=\begin{cases} 1 \quad \text{se} \quad i=j,\\ 0 \quad \text{se} \quad i\neq j \end{cases}\)</p>
            <p style="text-align:left;">Il polinomio di grado al più \(n\)</p>
            <p style="text-align:center;">\(p_n(x)= \sum_{j=0}^n y_j L_j^n(x)\)</p>
            <p style="text-align:left;">varrà quindi</p>
            <p style="text-align:center;">\(p_n(x_i)= \sum_{j=0}^n y_j L_j^n(x_i)=y_i\)</p>
            <p style="text-align:left;">con \(j=0, \dots, n\). Tale polinomio è detto <i>"polinomio di interpolazione di Lagrange".</i></p>
            <p style="text-align:left;"><span></span></p>
            <h4 style="font-style:italic;"><br></h4>
            <h4 style="font-style:italic;"><br></h4>
            <h4>Interpolazione di punti equispaziati</h4>
            <p style="text-align:left;"><span style="font-size:14.44px;">Siano \(x_i\) con \(i=0, \dots, n\) dei punti equidistanti di </span><i style="font-size:14.44px;">passo \(h\) </i><span style="font-size:14.44px;">e quindi tali che</span></p>
            <p style="text-align:center;"><span style="font-size:14.44px;">\(x_i = x_0 + ih\)</span></p>
            <p style="text-align:left;"><span style="font-size:14.44px;">effettuando un cambio di variabile</span></p>
            <p style="text-align:center;">\(x=x_0 +th\)</p>
            <p style="text-align:left;">si ottiene</p>
            <p style="text-align:center;"><span style="font-size:14.44px;text-align:left;">\(L_j^n(t)=\prod_{i=0, i \neq j}^n \frac{t-i}{j-i}\)</span><br></p>
            <p style="text-align:center;"><span style="font-size:14.44px;"><span><br></span></span>
            </p>
            <h4 style="text-align:left;"><span style="font-size:14.44px;"><span></span></span>
            </h4>
            <h4>Errore nell'interpolazione polinomiale</h4>
            <p><span style="font-size:14.44px;">Assumendo \(p(x)\) come polinomio interpolante della funzione \(f(x)\) è possibile definire la <i>funzione errore</i>&nbsp;dell'interpolazione di \(f(x)\) con \(p(x)\) data da&nbsp;</span></p>
            <p style="text-align:center;"><span style="font-size:14.44px;">\(r(x)=f(x)-p(x)\)</span></p>
            <p style="text-align:left;"><span style="font-size:14.44px;">e che si annulla sui nodi \(x_i\).</span></p>
            <p style="text-align:left;"><span style="font-size:14.44px;">Supponendo la \(f(x)\) derivabile n+1 volte sull'intervallo [a,b] con derivate continue, si ha</span></p>
            <p style="text-align:center;"><span style="font-size:14.44px;">\(r(x)= (x-x_0) \dots (x-x_n) \frac{f^{n+1}(\xi_n)}{(n+1)!}\)</span></p>
            <p><span style="font-size:14.44px;">Detto \(\pi_{n+1}=(x-x_0)\dots(x-x_n) \) il polinomio di grado n+1, otteniamo l'espressione</span></p>
            <p style="text-align:center;"><span style="font-size:14.44px;">\(r(x)=&nbsp;\pi_{n+1} \frac{f^{n+1}(\xi_n)}{(n+1)!}\)<br></span></p>
            <p><span style="font-size:14.44px;">E' possibile notare come l'errore d'interpolazione risulti essere molto maggiore negli estremi dell'intervallo della funzione rispetto alla parte centrale, dalla quale si allontana molto rapidamente: in particolare, la funzione cresce simmetricamente rispetto al punto medio dell'intervallo [0,n] per \(n\) dispari, mentre per \(n\) pari l'andamento è di tipo antisimmetrico, come evidenziato dalle seguenti rappresentazioni:<br></span></p>
            <p><span style="font-size:14.44px;"><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/interpolazione1.png" alt="interpolazione1" width="1200" height="959" style="vertical-align:text-bottom;margin:0px .5em;" class="img-responsive"><br></span></p>
            <p><span style="font-size:14.44px;">&nbsp;<img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/interpolazione2.png" alt="interpolazione2" width="1200" height="1115" style="vertical-align:text-bottom;margin:0px .5em;" class="img-responsive"></span></p>
            <p>Anziché cercare di interpolare tutti i punti, risulta quindi più efficiente un'interpolazione polinomiale "a pezzi" che per ogni punto costruisca una cubica diversa: le diverse cubiche si raccordano e vanno così a determinare un andamento
                più regolare della funzione interpolante.</p>
            <h3>Integrazione</h3>
            <p>Per stimare l'integrale di una funzione si può calcolare l'integrale di un interpolante lineare</p>

            <p>Il metodo trapezoidale esteso</p>
            <p>\( \displaystyle h=\frac{b-a}{N} \), \(I=h(\frac{f(x_0)}2+f(x_1)+\dots+f(x_{N-1})+\frac{f(x_N)}2)\)</p>
            <p>Interpolante parabolico: \(I=\frac h3 (f(x_0)+4f(x_1)+2f(x_2)+4f(x_3)+\dots+4f(x_{N-1})+f(x_N)) \) con \( N \) pari, ovvero un numero di intervalli N pari e un numero di punti N+1 dispari. Questa è nota come formula di Cavalieri-Simpson estesa.</p>
            <p>L'errore è sempre del tipo \( |r(x)|=|f(x)-p_N(x)|=\frac{|f^{(N-1)}(\xi_x)|}{(n+1)!}|\pi_{N+1}(x)|=\frac{|f^{(N-1)}(\xi_x)|}{(n+1)!}t(t-1)\dots(t-n)h^{N+1}.\)</p>
            <p>Quindi per l'interpolante lineare \( \int_{x_0}^{x_1}f(x)dx=\int_{x_0}^{x_1}p_1(x)dx+\int_{x_0}^{x_1}\frac{f''(\xi_x)}2\pi_{1+1}(x)dx\).</p>
            <p>\(Err_T=\int_{x_0}^{x_1}\frac{f''(\xi_x)}2\pi_{1+1}(x)dx\approx\frac{h^3}{2}f''(\bar\xi)\int_{0}^{1}t(t-1)dt=\mathcal{C}f''(\bar\xi)h^3.\)</p>
            <p>Per l'interpolante parabolico l'errore è del tipo:</p>
            <p>\( \int_{x_0}^{x_2}\frac{f'''(\xi_x')}{3!}\pi_3(x)dx.\)</p>
            <p>\( f'''(\xi'_x)=f'''(x_0)+f^{iv}(x_0)(x-x_0)+\dots\)</p>
            <p>Ma \(\pi_3(x)\)</p>
            <p>Riassumendo:</p>
            <p>\(Err_{T}\sim C f''(\xi)h^3\)</p>
            <p>\(Err_{CS}\sim C' f^{iv}(\xi')h^5\)</p>
            <p>L'errore totale sarà:</p>
            <p>\(Er_{TR(E)}\sim NCh^3\frac1N\sum f''(\xi_i)\sim\widetilde Cf''(\bar\xi)\frac1{N^2}\)</p>
            <p></p>
            <p>\(Er_{CS(E)}\sim NC'h^5\frac1N\sum f^{iv}(\xi'_i)\sim\widetilde C'f''(\bar\xi)\frac1{N^4}\)</p>
            <p>In realtà con troppi punti l'errore di arrotondamento può influire negativamente:</p>
            <p>\(\sum f_i^cw_i^c=\sum f_i^v(1+\varepsilon_{f_i})w_i^v(1+\varepsilon_{w_i})\approx\sum f_i^vw_i^v+\sum f_iw_i(\varepsilon_{f_i}+\varepsilon_{w_i})\)</p>
            <p>\(Err_r\approx A\sqrt{N}\varepsilon_M\)</p>
            <p>Notare che se si modifica il valore su un punto della funzione, nella teoria dell'integrazione l'integrale dovrebbe restare invariato, ma in pratica c'è un peso proporzionale ad \(h\).</p>
            <p>Esempio: \(\int_0^1 \frac{\cos x}{\sqrt{x}}dx=\int_0^1 \frac{\cos x-1}{\sqrt{x}}+\int_0^1 \frac{1}{\sqrt{x}}\). In questo modo si evita di lavorare con funzioni che divergono nell'origine: \(&nbsp;\cos x-1 \) va come \(x^2\) intorno all'origine.</p>
            <h2>Gestione di Input e Output (I/O)</h2>
            <p>Nonostante abbiamo già visto che è possibile manipolare l'input e l'output attraverso i costrutti <b>stdin</b> e <b>stdout</b>, Fortran mette a disposizione due funzioni&nbsp;<code>open</code>&nbsp;e&nbsp;<code>close</code>, che permettono
                di controllare meglio e più nello specifico queste sorgenti.<br></p>
            <p>Un'istruzione del tipo <b>open(unit=10, file="pippo")</b> crea un collegamento tra l'unità logica 10 e il file di nome "pippo". Di conseguenza, qualsiasi istruzione <b>write</b>&nbsp;applicata<span> </span><u>alla stessa</u> unità logica farà
                riferimento a questo file e non al classico <b>fort.10</b>.</p>
            <p>Tuttavia, si possono presentare alcune problematiche nel momento in cui si utilizza l'istruzione open all'interno di un sottoprogramma e questo viene chiamato più di una volta. Infatti, così facendo, si starebbe cercando di aprire un collegamento
                che, di fatto, già esiste! Ecco allora che risulta utile l'altra funzione <b>close</b> che, appunto, si occupa di chiudere il collegamento aperto con il comando <b>open</b>. Nell'esempio introdotto, la sintassi sarebbe <b>close(10)</b>.
                Questa istruzione funziona indifferentemente se il file con il quale è stato effettuato il collegamento è in lettura o in scrittura oppure entrambi.</p>
            <p>In molte situazioni può essere utile aprire il collegamento con un file dato in input al momento di esecuzione del programma al posto di uno prefissato. Il seguente costrutto illustra come farlo:</p>
            <p style="text-align:center;"><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/Schermata%202021-06-09%20alle%2017.12.43.png" alt=""><br></p>
            <p>Dopo un certo numero n di operazioni di lettura e scrittura, si potrebbe essere arrivati alla fine del proprio file. Se si avesse il bisogno di leggere nuovamente i dati di tale file dall'inizio, un'istruzione <b>read</b> non andrebbe bene
                perché cercherebbe di leggere la riga successiva inesistente. Perciò, in questo caso si può usare l'istruzione <b>rewind(unità logica)</b> che torna all'inizio del file in questione.</p>
            <p>È possibile trattare i dati connessi all'input e all'output attraverso il formato, che rappresenta uno degli argomenti di istruzioni quali <b>read</b> e <b>write</b>. Di seguito sono riportati tre possibili formati:</p>
            <p style="text-align:center;"><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/Schermata%202021-06-09%20alle%2017.22.53.png" alt=""><br></p>
            <p>L'asterisco indica il formato di default, quello deciso dallo sviluppatore del particolare compilatore Fortran; "<b>formatted</b>" specifica che i dati contenuti nel file "pippo" saranno convertiti da rappresentazione binaria interna a caratteri
                ASCII; "<b>unformatted</b>" indica che non c'è la conversione precedente.</p>
            <p style="text-align:center;"><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/Schermata%202021-06-09%20alle%2017.37.23.png" alt=""><br></p>
            <p>A sinistra un esempio di file <b>formatted</b>, a destra il corrispondente file <b>unformatted</b>.</p>
            <p>Un altro modo per distinguere una scrittura formattata da una non formattata è il seguente:</p>
            <p style="text-align:center;"><img src="https://moodle2.units.it/draftfile.php/345818/user/draft/253454031/Schermata%202021-06-09%20alle%2018.03.01.png" alt=""><br></p>
            <p>La scrittura su file di dati&nbsp;<code>formatted</code>&nbsp;è più lenta di quella degli&nbsp;<code>unformatted</code>. Questo è dovuto al fatto che i&nbsp;<code>formatted</code>&nbsp;non contengono solo i bit relativi al valore ma anche
                quelli relativi alla formattazione. Anche la dimensione del file è significativamente differente; il numero di bit utilizzati per rappresentare ogni valore dipende sia dal tipo dati che dal tipo di formattazione. In altre parole, i tempi
                di esecuzione sono minori per un file <b>unformatted</b> proprio perché non ci sono delle conversioni da fare.<br></p>
            <p>La scelta di uno di questi attributi determina se il compito di scegliere come vengono fatte le conversioni e come vengono visualizzati i risultati di questi ultimi sia affidato all'utente (formatted e unformatted) oppure al compilatore (*).</p>
            <p>Esistono numerosi altri formati creati appositamente, per esempio, per i numeri <i>floating point</i>, per la rappresentazione a virgola mobile, per i numeri interi, per inserire degli spazi e molti altri. Chi è interessato ad approfondire
                l'argomento può consultare i seguenti link:</p>
            <p><u><a href="https://docs.oracle.com/cd/E19957-01/805-4939/6j4m0vnaf/index.html" target="_blank" rel="noreferrer noopener">OPEN&nbsp;</a></u></p>
            <p><u><a href="https://docs.oracle.com/cd/E19957-01/805-4939/6j4m0vn7t/index.html" target="_blank" rel="noreferrer noopener">CLOSE</a></u></p>
            <p>...</p>
            <p>Come sappiamo, un file contiene una sequenza di byte che a loro volta contengono tutte le informazioni necessarie. Più nello specifico, in Fortran normalmente i file vengono considerati come dotati di una struttura interna costituita da delle
                sotto unità chiamate <b>record</b>. Per un file formattato, un record corrisponde a una riga. Quindi, ogni istruzione <b>print</b> o <b>write</b> lavora su un record.</p>
            <p>Ora, tornando al discorso sul controllo di input e output, uno dei possibili argomenti del comando open è access che specifica&nbsp;il tipo di file Fortran associato all' unità. I tipi possibili sono:</p>
            <p></p>
            <ul>
                <li><i>sequential </i>(file ad accesso sequenziale): l'accesso ai vari record viene fatto in sequenza, uno dopo l'altro. È formattato di default.</li>
                <li><i>stream</i>: non viene implementato il record e, di conseguenza, il file consiste in una sequenza non struttura di byte. In altre parole, non è formattato. Questo tipo di accesso è utile quando si stanno raccogliendo dei dati da una
                    strumentazione.</li>
                <li><i>direct </i>(file ad accesso diretto):&nbsp;i record sono numerati e possono essere letti o scritti in qualsiasi ordine, senza passare per i record precedenti, al contrario di quanto accade per l'accesso sequenziale. Questo tipo di accesso
                    può essere visto come un'estensione degli array sul disco (così come è possibile lavorare con la singola componente di un array che si trova su RAM, così è possibile lavorare con il singolo record sul disco).</li>
            </ul>
            <p>Un ulteriore argomento dell'istruzione <b>open</b> è<b> iostat=code_err,</b> dove<b> code_err</b> è una variabile intera che segnala un errore nel caso sia diversa da zero, altrimenti indica che il programma è stato eseguito con successo.
                Com'è possibile incorrere in un errore attraverso il comando <b>open</b>? Per esempio, per poterlo usare, il file a cui fa riferimento deve esistere!</p>
            <h2>Errori frequenti</h2>
            <h3>Errori di compilazione</h3>
            <h4>Modificare una costante</h4>
            <p>Una variabile definita come <code>parameter</code> non può essere modificata successivamente. Qualsiasi assegnazione successiva, o istruzione di tipo <code>read*,</code> darà errore.</p>
            <h4>Definire un <code>kind</code> come variabile non costante</h4>
            <p>Qualsiasi <code>kind</code> va dichiarato come <code>integer,parameter</code>. Anzi, il costrutto da preferire è:</p>
            <pre>integer,parameter :: nomeTipoIntero=selected_int_kind(10) !Gli interi dichiarati con (kind=nomeTipoIntero) potranno spaziare da -10^10 a 10^10
integer,parameter :: nomeTipoReale=selected_real_kind(10) !I reali dichiarati con (kind=nomeTipoReale) potranno avere una mantissa con 10 cifre decimali significative

integer(kind=nomeTipoIntero) :: big_int
integer(nomeTipoIntero) :: altro_big_int
</pre>
            <h4>Usare una costante numerica come <code>kind</code></h4>
            <p>La scrittura <code>kind=8</code> o in generale qualsiasi assegnazione con una costante numerica è pericolosa, in quanto imprevedibile. Il numero 8 dell'esempio, infatti, altro non è che un'etichetta assegnata dallo specifico compilatore a
                quel kind. Compilatori diversi potrebbero assegnare quell'etichetta a un altro kind, peggio, non assegnarla a nessun kind. Potrebbe bastare un aggiornamento del compilatore per perdere la funzionalità di un programma. Per questo motivo
                è meglio dichiarare i kind tramite il costrutto <code>selected_tipo_kind</code>, in modo che il comportamento sia lo stesso su tutte le macchine che compileranno il programma.</p>
            <h4>Dimenticare un <code>*</code></h4>
            <p>Dimenticarsi che Fortran non capisce la moltiplicazione implicita del tipo <code>2x</code> può dare errori vari, tra cui un errore di utilizzo delle parentesi. Purtroppo bisogna adeguarsi a questa sintassi, scrivere sempre <code>2*x</code>!</p>
            <h4>Utilizzare <code>^</code> al posto di <code>**</code> </h4>
            <p>Dimenticarsi che Fortran non utilizza il convenzionale <code>^</code> per indicare gli esponenti. L'errore segnalato sarà del tipo <code>syntax error</code> in fase di compilazione. Sostituire con <code>**</code></p>
            <h4>Non utilizzare correttamente le interface</h4>
            Un programma del tipo
            <pre>function f(x) result(res)
     integer :: x
          res=x+2
end function

program main
     implicit none
          real :: x
          real, external :: f
     read*,x
     print*, f(x)
end program main
</pre> Questo errore è molto insidioso perché il programma verrà compilato ed eseguito normalmente. Tuttavia dal punto di vista del program, x è un real, quindi sarà trattato come tale, mentre dal punto di vista della function è un integer. La differente
            rappresentazione di real e integer fa sì che il programma restituisca valori numerici apparentemente insensati.
            <h3>Errori di runtime (durante l'esecuzione)</h3>
            <h4>Usare per sbaglio la divisione intera</h4>
            <p>La scrittura <code>a= 1/n</code> con <code>n</code> intero darà sempre e comunque 0, anche se <code>a</code> è di tipo <code>real</code>. Se si vuole il risultato frazionario occorre scrivere <code>a= 1./n</code></p>
            <h4>Accedere a una variabile non inizializzata</h4>
            <p>Se ci si dimentica di inizializzare una variabile, non c'è nessun modo (fattibile) per prevedere il valore che si troverà lì dentro: potrebbe essere qualsiasi residuo cbe programmi vecchi abbiano lasciato in RAM. Non c'è da stupirsi se i risultati
                sono strani. Sempre inizializzare le variabili!</p>
            <h4>Assegnare a una variabile con alta precisione un valore di tipo default</h4>
            <p>Se abbiamo definito un tipo <code>rk</code> che ci dà grande precisione, la scrittura <code>real(rk), parameter :: pi = acos(-1.0)</code> potrebbe dare risultati assai deludenti: il calcolo del valore <code>acos(-1.0)</code> è fatto con la
                precisione di default e solo successivamente viene convertito nel tipo desiderato. Il risultato è che le prime cifre del nostro <code>pi</code> saranno quelle calcolate, seguite da tanti zeri quanto maggiore è la precisione di <code>rk</code>                rispetto al tipo di default. La scrittura corretta è <code>real(rk), parameter :: pi = acos(-1.0_rk)</code>.</p>
            <h4>Fiondarsi su alte precisioni</h4>
            <p>Usare alte precisioni non porta solo vantaggi: quasi sempre il tipo reale a 128 bit non è supportato dall'hardware e viene realizzato con uno stratagemma del software. Ciò può comportare un aumento del tempo di calcolo anche di fattori dell'ordine
                del 20: 20 minuti di calcolo possono diventare 6 ore e 40 minuti. Meglio ponderare certe scelte.</p>
            <h2>Trucchi e consigli</h2>
            <h4>Correzione errori</h4>

            <p></p>
            <ol>
                <li>Non panicare se, al momento della compilazione, vedi una sfilza infinita di errori. Inizia sempre dai primi visto che, molto probabilmente, saranno quelli a generare a cascata gli altri.
                </li>
                <li>Leggi bene il messaggio di errore e capisci cosa il compilatore ti sta dicendo. Una volta capito il problema è molto più facile andare a cercare cosa lo causa (syntax error, type mismatch, undefined variable ecc...)</li>
                <li>Cerca su internet. Sembra banale come consiglio, ma sicuramente troverai forum in cui qualcuno ha avuto il tuo stesso problema; assicurati he le soluzioni siano legali rispetto quanto richiesto in questo corso.</li>
                <li>Utilizza i commenti. Se proprio non riesci a trovare cosa causa il problema, commenta alcune sezioni di codice (anteponendo <code>&amp;</code> alla riga) e ricompila fino ad isolare le righe in cui insorge il problema.</li>
            </ol>
            <p></p>
            <h4>Logaritmi in base arbitraria</h4>
            <p>Fortran supporta di default solo le istruzioni <code>log(x)</code> e <code>log10(x)</code> che corrispondono rispettivamente a&nbsp;\( ln(x) \)&nbsp;e a \( log_{10}(x) \). Se si vuole utilizzare un logaritmo in base \( n \) occorre utilizzare
                un cambiamento di base: \( log_{n}(x)=\frac{log_{10}(x)}{log_{10}(n)} \)</p>
            <h4>Pinguini sul terminale</h4>
            <p>Non sarebbe un easter egg degno di questo nome se ti dicessi dove trovarlo, ricorda che la pazienza è la virtù dei forti.</p>
            <h2>Link utili</h2>
            <p><a href="https://www.asciitable.it/" target="_blank" rel="noreferrer noopener">https://www.asciitable.it/</a></p>
            <p><a href="https://www.asciitable.com/" target="_blank" rel="noreferrer noopener">https://www.asciitable.com/</a></p>
            <p><a href="https://it.wikipedia.org/wiki/ASCII" target="_blank" rel="noreferrer noopener">https://it.wikipedia.org/wiki/ASCII</a></p>
            <p><a href="http://www.ismycomputeron.com" target="_blank" rel="noreferrer noopener">http://www.ismycomputeron.com</a></p>
            <p><a href="http://www.ee.surrey.ac.uk/Teaching/Unix/">http://www.ee.surrey.ac.uk/Teaching/Unix/</a>&nbsp;</p>
            <p><a href="http://informatica.abaluth.com/il-computer/le-informazioni/rappresentazione-dei-numeri-reali-standard-ieee-754/#:~:text=Lo%20standard%20IEEE%20754%20prevede,23%20bit%20per%20la%20mantissa" target="_blank" rel="noreferrer noopener">http://informatica.abaluth.com/il-computer/le-informazioni/rappresentazione-dei-numeri-reali-standard-ieee-754</a></p>
            <p><a href="https://github.com/marcellofonda/labcalc" target="_blank" rel="noreferrer noopener">GitHub: Programmi visti a lezione</a></p>
            <p>Ottima dispensa (contiene un po' di tutto):&nbsp;<a href="http://homes.di.unimi.it/informatica-ls-chimica/Doc/Dispensa_fortran_Raucci.pdf">http://homes.di.unimi.it/informatica-ls-chimica/Doc/Dispensa_fortran_Raucci.pdf&nbsp;</a></p>
            <h2>Video istruttivi consigliati</h2>
            <p><a href="https://www.youtube.com/watch?v=dI-JW2UIAG0">Video Nasa</a></p>
            <p><a href="https://www.youtube.com/watch?v=Z5JC9Ve1sfI">The Fetch-Execute Cycle: What's Your Computer Actually Doing? - YouTube</a></p>
            <p>&nbsp;</p>
            <p>&nbsp;</p>


            <h2>Documentazione sintetica</h2>


            <p><code>spread(vettore, 1, quantità)</code> restituisce un array <code>dimension(quantità,size(vettore))</code></p>
            <p><code>spread(vettore, 2, quantità)</code> restituisce un array <code>dimension(size(vettore),quantità)</code></p>
