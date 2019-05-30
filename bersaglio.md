Un labirinto "classico" è un unico percorso (anche estremamente contorto), privo di biforcazioni, che dall'ingresso conduce all'uscita. 

Un *labirinto di parole* è una concatenazione di vocaboli effettuata in base ad un insieme di regole, tale per cui da un vocabolo iniziale, si arriva al vocabolo terminale.

Due vocaboli possono essere concatenati tra loro se uno si ottiene dall'altro:
+ facendone l'anagramma (stessi caratteri ma in ordine diverso, ad esempio: ANSA, SANA)
+ cambiando un carattere (ad esempio: CARTA, CORTA)
+ aggiungendo un carattere (ad esempio: CASA, CASTA)
+ togliendo un carattere (ad esempio: PORTA, POTA)

Si realizzi un programma che chiede all'utente il nome di un file di testo che contiene una sequenza di vocaboli che rappresenta il problema di partenza *filesrc*, e un secondo nome di un file di testo che contiene la "presunta" soluzione del problema del labirinto di parole. Il programma verifica che la soluzione sia corretta e in tal caso visualizza "Soluzione esatta", altrimenti visualizza "Soluzione non corretta".

Perché la soluzione sia corretta è necessario che:
+ tutti i vocaboli del file del problema filesrc siano stati utilizzati una ed una sola volta
+ tra due vocaboli consecutivi valga una delle 4 regole elencate

Per esempio, se i contenuti del file sono i seguenti:

NUMERI PRESO sapore SUPER SARTE OPTARE RUSPE PRESTO OSARE SORTE TERSA RASPE POTARE PORTE PERSA POLARE SUPERI SPORTE stare POSARE SPORE Sumeri OSTARE PAROLE

NUMERI Sumeri SUPERI SUPER RUSPE RASPE PERSA TERSA stare SARTE SORTE PORTE SPORTE PRESTO PRESO SPORE sapore POSARE OSARE OSTARE OPTARE POTARE POLARE PAROLE

il programma visualizza "Soluzione esatta"
