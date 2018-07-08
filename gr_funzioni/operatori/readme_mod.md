# Operatori

Questo gruppo contiene operatori es. + - *

| Funzione  | Descrizione|
|:----------:|:-----------|
|[a + b](funzioni/somma.html)|Addizione di due valori|
|[a - b](funzioni/meno.html)|Sottrazione di due valori.|
|[a * b](funzioni/prodotto.html)|Moltiplicazione di due valori|
|[a / b](funzioni/divisione.html)|Divisione di due valori|
|[a % b](funzioni/resto_divisione.html)|Resto della divisione|
|[a ^ b](funzioni/potenza.html)|Elevazione a potenza di due valori|
|[a < b](funzioni/minore.html)|Confronta due valori e pone a 1 se il valore a sinistra è minore del valore a destra|
|[a <= b](funzioni/minoreuguale.html)|Confronta due valori e pone a 1 se il valore a sinistra è minore o uguale del valore a destra|
|[a <> b](funzioni/diverso.html)|Confronta due valori e pone a 1 se essi non sono uguali|
|[a = b](funzioni/uguale.html)|Confronta due valori e pone a 1 se essi sono uguali.|
|a != b|	a and b are not equal|
|[a > b](funzioni/maggiore.html)|Confronta due valori e pone a 1 se il valore a sinistra è maggiore del valore a destra|
|[a >= b](funzioni/maggioreuguale.html)|Confronta due valori e pone a 1 se il valore a sinistra è maggiore o uguale del valore a destra.|
|[a ~ b](funzioni/tilde.html)|Esegue un'espressione regolare su di una stringa.|
|[\|\|](funzioni/doppio_pipe.html)|Unisce due valori assieme in una stringa. Se uno dei valori è NULL il risultato sarà NULL. Vedi la funzione CONCAT con caratteristiche differenti.|
|‘\n’|	Inserisce una nuova linea|
|[LIKE](funzioni/LIKE.html)|	Restituisce 1 se il primo parametro soddisfa il modello fornito. Funziona anche con i numeri|
|[ILIKE](funzioni/ILIKE.html)|Restituisce 1 se il primo parametro soddisfa senza tener conto delle maiuscole o minuscole il modello fornito. LIKE può essere usato al posto di ILIKE per eseguire una comparazione che tenga conto delle maiuscole e minuscole. Funziona anche con i numeri|
|[a IS b](funzioni/IS.html)|Restituisce 1 se *a* è uguale a *b*.|
|[a OR b](funzioni/OR.html)|Restituisce 1 quando la condizione a oppure b è vera|
|[a AND b](funzioni/AND.html)|Restituisce 1 quando le condizioni a e b sono vere.|
|[NOT](funzioni/NOT.html)|Nega una condizione|
|"column"| nome "nome colonna"  nome della colonna del campo, fare attenzione a non confondere con la citazione semplice, vedere sotto|
|‘string’|	un valore stringa, fare attenzione a non  confondere con virgolette doppie, vedi sopra|
|NULL|	null value|
|a IS NULL|*a* non è valorizzato|
|a IS NOT NULL|	*a* è valorizzato|
|[a IN (a,b,..)](funzioni/IN.html)|Restituisce 1 se il valore viene trovato in una lista di valori|
|a NOT IN (value[,value])|	*a* non è presente nella lista|

![](/img/operatori/gruppo_operatori1.png)
