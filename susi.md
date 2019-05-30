# Il quesito della Susi

Si vuole risolvere il problema posto da Susi, sviluppando un programma che trovi la combinazione di numeri che rispetta i vincoli elencati da Susi.

![Quesito della Susi](risorse/susi.png)

La soluzione più immediata (da pensare, non più efficiente in termini di tempo per trovarla) consiste nel provare tutte le combinazioni di 6 cifre, fino a quando non si trova quella che si sta cercando. Per ogni combinazione presa in considerazione, si verifica se tutti i vincoli sono rispettati: se è così, è la configurazione che stiamo cercando, altrimenti, non appena ci accorgiamo che un vincolo non è rispettato, la scartiamo e passiamo alla combinazione successiva. 

E' il metodo forse più facile da pensare, e si basa sulla "forza bruta". 

L'alternativa è analizzare solo un sottoinsieme di possibili combinazioni di 6 cifre, generate a partire dai vincoli stessi. Si fa più fatica a generare le combinazioni da analizzare, ma se ne generano molte di meno.