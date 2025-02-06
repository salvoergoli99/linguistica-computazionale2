# linguistica-computazionale2
Progetto di Linguistica Computazionale II dell'anno accademico 2022/2023

Descrizione del progetto: 
1. Sviluppare un classificatore basato su SVM lineari che prende in input una rappresentazione
del testo basata solo su informazioni linguistiche non lessicali estratte utilizzando il sistema
Profiling-UD. Riportare i seguenti risultati:
• valutazione del sistema con un processo di 5-fold cross validation condotto sul training
set;
• valutazione del sistema sul test set ufficiale del task;
• elenco delle 15 feature più importanti per la classificazione.
2. Sviluppare un classificatore basato su SVM lineari che prende in input una rappresentazione
del testo basata su n-grammi di caratteri, parole e part-of-speech. Riportare i seguenti
risultati:
• testare diverse rappresentazioni del testo che variano rispetto alla lunghezza degli ngrammi utilizzati e/o rispetto al tipo di informazione utilizzata all’interno degli ngrammi (forme, lemmi, caratteri, part-of-speech) e valutare i diversi sistemi con un
processo di 5-fold cross validation condotto sul training set.
• valutazione sul test set ufficiale del miglior sistema rispetto ai risultati ottenuti con il
processo di 5-fold cross validation del punto sopra .
3. Sviluppare un classificatore basato su SVM lineari che prende in input una rappresentazione
del testo costruita attraverso l’uso dei word embedding
(http://www.italianlp.it/resources/italian-word-embeddings/). Riportare i seguenti risultati:
• testare diverse rappresentazioni del testo che variano rispetto al modo di combinare gli
embedding delle singole parole e/o rispetto alle categorie grammaticali delle parole
prese in considerazione. Valutare i diversi sistemi con un processo di 5-fold cross
validation condotto sul training set.
• valutazione sul test set ufficiale del miglior sistema rispetto ai risultati ottenuti con il
processo di 5-fold cross validation del punto sopra .
1. Dopo aver scelto un Neural Language Model tra quelli visti a lezione, condurre un processo
di fine-tuning per 5 epoche. Riportare i seguenti risultati:
• riportare le curve di loss di training e di validation;
• per ogni epoca valutare il sistema sul validation set;
• alla fine dell’ultima epoca, riportare la valutazione del sistema sul test set ufficiale.
