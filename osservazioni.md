# Osservazioni — Esercitazione 0

Gruppo:

Componenti (nome, cognome e username GitHub di entrambi):
Francesca Lupo, Pietro Intemerato
Francesca-Lupo, Pietro1ab

URL del repository condiviso: https://github.com/Francesca-Lupo/esercitazione-0-template.git


Chi ha usato la tastiera nello step 1 e nello step 2: Francesca Lupo (step 1), Pietro Intemerato (step 2). 

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione: gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato: ./hello. Risultato osservato: stampa "Hello, computational physics!".

Che cosa ho capito su sorgente ed eseguibile: Il codice sorgente contiene le istruzioni del programma. Tale codice viene compilato (tramite compilatore gcc) e "tradotto" in linguaggio macchina eseguibile. 

Output richiesto e comportamento del programma prima della modifica: Prima della modifica, l'output a seguito della compilazione è esattamente il listato "Hello, computational physics!". 

Esito dopo la modifica e spiegazione della correzione: Se viene modificato il codice sorgente senza ricompilazione successiva, l'esecuzione del programma rimane invariata, restituendo il messaggio precedente. Se si effettua la ricompilazione con gcc, in seguito viene stampato il listato modificato. 

## Step 1 — Git

Quali file ho incluso nel commit e perché: sono stati inclusi i file hello.c ed osservazioni.md in quanto sono i due file modificati (vogliamo salvare le nuove versioni nel repository locale con git, attraverso un nuovo commit)


Come ho verificato che la versione provata sia presente su GitHub: Verificando il contenuto della repository online su GitHub (remota) e consultando la cronologia dei commit. Abbiamo verificato che l'identificativo dell'ultimo commit sia quello mostrato da gitlog. 

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone:prima di effettuare git pull la copia locale non mostrava le modifiche eseguite sulla copia remota. attraverso git pull è stata aggiornata la copia locale , che ora presenta le modifiche apportate sulla copia remota. Non è stato necessario effettuare nuovamente git clone perchè tale operazione serve a copiare una repository esistente solo su github ed "esportarla" localmente. dopo aver eseguito git clone la prima volta, tale repository è già presente localmente ed è sufficiente usare git pull per importare le modifiche nuove. 

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato:

Che cosa posso concludere:

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:

Che cosa ho capito su testo, conversioni e stampa:

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`:

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:

Come un controllo automatico può riconoscere un errore:

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:
