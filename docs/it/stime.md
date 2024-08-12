#### Comprendere il processo

Quando si parla di stima si intende riuscire a delineare un confine temporale per la realizzazione di un'opera di qualche genere. Ci troviamo di fronte ad un tema controverso, e sicuramente chiedendo a dieci persone cosa rappresenta per loro una stima, probabilmente otterremo dieci risposte diverse con metodi o approcci anche molto distanti. Qui non vogliamo andare nel profondo di uno o più metodi, ma chiarire il tema per comprenderlo e dare degli strumenti e spunti di approfondimento.

Nell'ambito informatico, la stima può essere usata per dare una dimensione ad un task o ad un intero progetto, aiutando il business a delineare un'idea o a pianificare le attività ed è quindi piuttosto importante perché consente di prendere decisioni su come spendere le risorse. Dobbiamo ricordarci infatti che lo sviluppo è parte del business, e per molti versi lo stiamo facendo anche noi quando programmiamo.

Un parametro importante nello sviluppo di un progetto è il cosiddetto Time To Market (tempo di arrivo su un certo mercato), può risultare determinante nella riuscita di un prodotto; rappresenta quando riuscirete ad essere pronti per i clienti e quindi quando arriverete rispetto alla concorrenza. Il business lo tiene molto in considerazione perché è un buon indicatore di quando i profitti potrebbero iniziare ad arrivare cominciando, quindi, a rientrare degli investimenti. Questo parametro diventa perno, insieme ad altri fattori, per delineare le strategie aziendalie; delineare la pianificazione in base ad alla stima temporale non è l'unica maniera di gestire questo aspetto, ma è sicuramente spesso il preponderante.

Ma come mai la stima e la pianificazione, nel nostro campo, è così complessa? La risposta sta nel comprendere, prima di tutto, qual è lo scopo del processo di creazione del software stesso. Questo ci permette di definire meglio quelle variabili fino a quel momento incognite per cui le stime possono variare.

I processi si categorizzano infatti base ad una serie di variabili, ossia delle incognite che si incontrano durante il percorso; più è difficile predire quello che succederà durante il lavoro e più si dice che la variabilità cresce; è un poco come percorrere una strada e non sapere quanto traffico troveremo, se faremo quella strada molto spesso avremo comunque un'idea di cosa possa succedere e di quanto ci metteremo ad arrivare.

Partendo da questo concetto il processo di produzione di un qualsiasi prodotto può essere visto come definito, statistico ed empirico; il tipo "definito" è il più semplice, perché non c'è alcuna sorpresa durante lo svolgimento ed è qualcosa che abbiamo già fatto, quindi non richiede alcuno sforzo perché sappiamo già prevederlo a monte. Nel nostro campo l'esempio tipico è quello della configurazione di un servizio, l'installazione di un software e così via; si tratta di processi che non hanno alcuna variabilità se non minima quindi qui la stima è deterministica e non porta criticità particolari, se no quelle che riguardano l'adattamento allo specifico caso d'uso.
Quello "statistico" è simile al precedente, ma con variabilità più alta: significa che lo abbiamo già fatto ma sappiamo che potrebbero esserci dei problemi durante lo svolgimento. Qui si possono fare delle stime basate, per l'appunto, su esperienze precedenti, e per fortuna abbiamo una vasta gamma di pattern che possiamo sfruttare e che ci permettono di stabilire un tempo di esecuzione. In questo caso, si tratta di una stima meno semplice della precedente ma sempre fattibile, anche se magari con una "forbice" che definisce un intervallo entro cui muoversi.
L'ultimo è quello più ostico e lo è perché percorriamo una strada non battuta: è quello più frequente e che ha a che fare precisamente con processi di ricerca e sviluppo. Questo è di fatto il caso peggiore e richiede un approccio più complesso, perché la reale stima la si conosce una volta che il processo giunge a termine, visto che non abbiamo un'esperienza specifica che lo possa descrivere. Dobbiamo cercare quindi di portarci verso gli altri due casi e diminuire l'incertezza mano mano per raffinazioni successiva, in maniera incrementale. In altre parole, dobbiamo delineare delle strategie.

#### Scomposizione

La prima tattica è quello di dividere il problema in problemi più semplic: un task o un progetto diventano via via più raffinati e più piccoli e al tempo stesso più semplici da stimare ma anche più facili da confinare come problematica. Come in precedenza, si cerca di trovare un pattern conosciuto e partire con quello. Questo vuol dire gestire un lavoro più piccolo, il che ci consente di comprenderlo meglio, visto che il cervello umano non è in grado di tenere sotto controllo una moltitudine di elementi, ma ci consente di avere una visione prima di insieme e poi del dettaglio, così da rendere le cose più facili da dominare. La riduzione rende anche chiare altre due cose, ovvero le criticità: parliamo di quelle parti meno esplorate e in cui ci sono più difficoltà. Mette in luce anche le dipendenze, cioè quali siano le fondamentali e quali siano le parti accessorie, cominciando anche a delineare una sequenza.

#### Isolare le criticità

Nella suddivisione si possono scorgere, come si è visto, criticità; sono le parti più complesse da stimare, quelle che ci pongono di fronte a situazioni nuove dove un pattern già conosciuto non è visibile o proprio è assente. Si possono adottare due strategie concatenate: la prima è quella di "assegnare ad una stima del tempo di stima": sembra un gioco di parole ma non lo è. Se un tema è complesso e non scomponibile e ha bisogno di essere studiato è necessario prendersi il tempo per farlo. Assegnare a questo task una stima per consentirci di avere le idee più chiare ci da la maniera di introdurre il concetto di PoC: proof of concept. Di fatto è un micro task orientato alla creazione di uno o più proprietà del progetto finale che sono critiche e che, una volta sbrogliate, rendono tutto il processo di creazione più chiaro. Può anche essere utile mostrarlo, a volte può bastare provare se l'idea funziona a livello tecnico, ma a volte è possibile anche mostrarlo a chi poi prenderà decisioni perché dà immediatamente un'idea di dove si vuole arrivare, che prestazioni o di che interattività si parla.

#### Forbice

L'espressione della stima è intuitivamente temporale in ore o giorni uomo, ma non è l'unica possibilità. In alcuni framework agili questa viene sostituita con delle unità adimensionali o addirittura con qualcosa di non numerico: l'esempio classico sono le taglie delle magliette. Questo approccio è tipico di quei team che lavorano per sessioni (chiamati a volte sprint) che durano da una settimana in su dove il gruppo sa che entreranno un certo numero di task con una determinata taglia, rimanere vaghi è un metodo per evitare due cose, la prima è che si faccia della matematica non opportuna sulle stime: la sequenza di come si svolge il lavoro è importante e sommarle ciecamente può comportare problemi nello svolgimento poi; capita spesso, infatti, che chi sovraintende il lavoro abbia bisogno di avere una scaletta (ancora meglio una data) e la cosa più immediata è sommare i tempi ma magari non è la solzione migliore perché ci sono dipendenze tra i lavori o si ha un'idea globale del lavoro ma non sufficientemente dettagliata e possono sorgere fraintendimenti.
La seconda è che si vuole semplificare il lavoro di stima evitando di dare un numero in ore e quindi si sa che ce la si farà in una sessione ma si evita di approfondire quanto anche per non creare fraintendimenti.
Se la stima invece è scritta sotto forma di tempo possiamo usare lo stratagemma di creare una forbice con un tempo minimo e massimo per lo svolgimento del lavoro, questo per conteggiare il rischio soprattutto di quelle parti che risultano nuove che potrebbero portare con sé delle criticità. Un altro modo è spesso quello di indicare una stima e poi aggiungere un margine, questo è forse il metodo più incerto perché il margine è spesso arbitrario; generalmente si usa Pareto aggiungendo il venti per cento a quanto ottenuto.

#### Specifiche

Partendo sempre dal metodo empirico ci accorgiamo prima di tutto che l'incertezza comporta una cosa tanto banale quanto vera: sappiamo quanto ci abbiamo messo quando lo abbiamo fatto. Questo perché è solamente alla fine che è chiaro quello che si voleva produrre, in una parola serviva sapere quale era la definizione di fatto.
Per saperlo è necessario avere delle specifiche ed è facile intuire che più sono precise più è semplice pianificare. Anche chi lavora da poco nel settore sa che sono complicate da ottenere e a volte fumose. Il primo consiglio qui è quello di studiare il dominio applicativo perché avere una nomenclatura delle cose dà uno slancio non irrisorio. Poi è necessario parlare con chi ha questa conoscenza, andare a cercare alla fonte e chiedere più chiarimenti possibili; anche in questo caso la scomposizione e l'iterazione sono utili. Ci sono delle cerimonie specifiche in alcuni framework e metodologie che possono venirci incontro, ad esempio l'event storming il cui scopo è proprio quello di chiarire i flussi e nomi del dominio il più possibile. Qui la contaminazione col business è fondamentale per un prodotto di qualità e ridurre al minimo i fraintendimenti.

#### Condivisione

La ricerca di pattern, come già citato, può essere molto utile poiché ci consente di riconoscere requisiti o funzionalità già visti o fatti; abbiamo poi accennato al concetto di Proof of Concept, che aiuta laddove ci si trovi davanti ad un problema nuovo.

Il problema di entrambi gli approcci è che si basano sulla nostra conoscenza e capacità di osservazione e studio.

La condivisione e la contaminazione con il business e con figure con esperienze diverse dalla nostra possono risultare una chiave fondamentale per risolvere i problemi apparentemente più complessi.
Ma come possiamo ottenere contaminazione e condivisione in maniera efficace?

Si possono organizzare dei meeting di condivisione e di stima dei problemi; il problema visto da angolazioni differenti può svelare caratteristiche di cui non avevamo tenuto conto, e anche un singolo confronto può risultare fondamentale nel risolvere una problematica che sembrava insormontabile.

In alcuni framework agili ci sono proprio dei momenti per questo tipo di approccio, per citarne uno: "planning poker"; questa è quella che si chiama "gamification", cioè trasformare l'attività in qualcosa di simile ad un gioco per renderla più leggera. Questa attività si svolge in maniera simile ad una mano di poker dove ogni partecipate ha un mazzo di carte dove al posto dei semi ci sono dei numeri. Si inizia spiegnado per bene il problema da risolvere e che si vuole stimare, si inizia poi un giro in cui ogni persona sceglie una carta col numero che rappresenta la sua stima (es. 8 ore) e la appoggia sul tavolo, a questo punto bisonga giustificare la propria scelta; si procede in questo senso fino a che non c'è una convergenza su una stima comune o una forbice. La base di questo procedimento è dire quanto ci si metterebbe ma soprattutto perché, questo accresce nel gruppo la consapevolezza degli ostacoli da superare dal punto di vista di ogni componente del gruppo; consapevolezze che, magari, singolarmente poterebbero non così evidenti o richiedere più iterazioni di studio. Le carte sono facilmente reperibili, sono spesso numerate con unità temporali base come l'ora, la giornata o la settimana (e così via) oppure si usano sequenze come quella di Fibonacci, quest'ultima è spesso utilizzata come referimento perché approssima meglio la realtò anche come si presentano in natura come in botanica o musica.

#### MVP

Il concetto di riduzione e scomposizione porta con sé un approccio naturale, cioè definire quali siano le parti fondamentali dell'applicativo. Si può introdurre un concetto semplice ma piuttosto efficiente ed efficace: dare una risposta alla domanda "quali sono le funzionalità minime per poter andare sul mercato?"; questo accorcia di molto il tempo di arrivo sul mercato perché elimina le funzioni non necessarie, semplifica la visione e lo sviluppo. Questo concetto è alla base del pensiero agile e va sotto il nome di Minimum Viable Product (MVP), abbassa il rischio rendendo più corto lo sviluppo, chiarisce meglio i goal del progetto e aiuta ancora una volta a scomporre le cose in elementi più piccoli o, se vogliamo, minimi perché il progetto abbia quel valore sul mercato che il business si aspetta.