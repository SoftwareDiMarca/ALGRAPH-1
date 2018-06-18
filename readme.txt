ALGRAPH

	Esecuzione dell'algoritmo di Bellman Ford Moore su di un grafo, con output a schermo step by step delle strutture dati.

Per l'utilizzo:
	Da menu principale scegliere una delle seguenti voci:
		-Generate Graph Manually
		-Generate Random Graph
		-Impot Graph From File

Generate Graph Manually:
	Questa funzionalit� permette di creare manualmente il grafo mediante alcuni bottoni:
		-Add node: Aggiunge un nodo
		-Switch to [mode] mode: permette di scgliere fra le due modalit� di modifica: Selection e Link.
			-Selection mode: cliccando su uno degli elementi del grafo, questo viene selezionato.
			-Link mode: cliccando su due nodi viene creato un arco orientato fra questi due nodi dal primo al secondo che si ha cliccato.
		-Remove: elimina ogni elemento selezionato.
	Cliccando sulle etichette degli elementi viene aperta una finestra di dialogo che permette all'utente di reimpostare il peso dell'arco o l'etichetta del nodo.
	Infine � possibile trascinare i nodi del grafo per conferire al grafo un aspetto pi� gradevole

Grenerate Random Graph:
	Mediante una finestra di dialogo � possibile settare alcuni parametri per la generazione del grafo: 
		-Max Nodes
		-Min Nodes
		-Max Weight
		-Min Weight
	Density, infine, permette di aumentare il numero di archi totali del grafo: selezionandolo sar� pi� probabile che l'algoritmo generi grafi densi.

Import Graph From File:
	Mediante una finestra � possibile selezionare quale file importare, una volta effettuata la scelta, verr� aperta la pagina principale del programma.
	
Main Page:
	In questa pagina, oltre che alle funzionalit� di modifica di un grafo, sono persenti anche una barra dei menu, il pulsante Apply Algorithm e una lista di log.

Menu Bar:
	Prevede due pulsanti:
		-Save, per il salvataggio dei file
		-Open, per l'apertura dei file

Apply Algorithm:
	Mediante questo pulsante viene lanciata l'esecuzione dell'algoritmo dal nodo selezionato; qualora ve ne sia pi� di uno, o vi siano dei cicli negativil'algoritmo non parte.
	La radice viene colorata in rosso.
	Il nodo estratto dalla coda viene colorato in blu.
	Il nodo adiacente ad esso preso in analisi viene colorato in verde.
	Ad ogni step � possibile, cliccando sopra ad un nodo, leggere in tempo reale la distanza di questo dalla radice.
	Ad ogni step le frecce che fanno parte del vettore dei padri vengono colorate in rosso, in modo da dare una lettura intuitiva del vettore dei padri.
	Ad ogni step la lcoda dei nodi viene mostrata nella parte destra della log bar.  
	

Log Bar:
	Questa area dello schermo mostra tutte le attivit� del programma e le linee di pseudocodice eseguite dall'algoritmo nella parte sinistra
	Nella parte destra viene mostrato lo stato della coda dell'algoritmo.

Sviluppatori:
	-Simone Branchetti		simone.branchetti2@studio.unibo.it
	-Luca Michele Contalbo		lucamichele.contalbo@studio.unibo.it
	-Davide Davoli			davide.davoli4@studio.unibo.it