# WPFThreads
Nel seguente programma siamo andati a generare un contatore di numeri con l'aiuto dei Threads che al'inizio ci avevano causato dei problemi sul programma che poi siamo andati ad aggiustare aggiungendo uno Sleep e un Lock.
Abbiamo creato un counter di giri e una costante di giri così che il programma sapesse gia da dove partire  e che oltre quel litime non dovesse andare.

![Counter](https://user-images.githubusercontent.com/117436985/221884813-94729f99-e5e5-4f79-97f0-f6f5f3e80126.png)

### Threads
Sono sotto-processi che posso eseguirsi in parallelo o in serie ad'altri. 
Per far eseguire il codice regolarmente, senza che si blocchi, abbiamo aggiunto un Lock e uno Sleep.
### Sleep
Questo comando serve per sospendere il thread corrente per i millisecondi che andiamo ad indicare.
### Lock
Il Lock serve per bloccare la penetrazione di un thread in una sezione critica del codice nel quale è gia presente un thread.

![Threads](https://user-images.githubusercontent.com/117436985/221879374-4df8aea0-5df9-4dc8-895f-8160b7db9ce2.png)

In questa immagina si nota molto bene il funzionamento dello Sleep.
Notiamo anche che siamo andati ad utilizzare un Dispatcher.
### Dispatcher
Dispatcher gestisce una coda di elementi di lavoro con priorità per un thread specifico.
Quando un Dispatcher oggetto viene creato in un thread, diventa l'unico Dispatcher che può essere associato al thread, anche se viene Dispatcher arrestato.

### Lamba Expression
L'uso delle espressioni lambda serve per ridurre le righe di codice.
