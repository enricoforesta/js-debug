# Bundle-1

## Esercizio 1 

1. Questo codice ha un ciclo for, stampa in console i numeri da 0 a 4.

2. Si, bisogna sostituire "i > 5" con "i < 5" senno il ciclo for non viene mai eseguito, perchè se i = 0 non sarà mai maggiore di 5 quindi usciremo subito dal ciclo.

3. Corregendo l'errore, la logica è giusta.


## Esercizio 2 

1. Questa è una funzione dove passato un numero come argomento, se il numero è pari ci restituisce il numero + 5, se è dispari ci restituisce in numero inserito.

2.  Si, nella condizione If "(num % 2 = 0)" va sostituito con "(num % 2 === 0)" Perche bisogna fare un confronto, non riassegnare un valore.

3. Correggendo l'errore, la logica è giusta.

## Esercizio 3 

1. Questa è una funzione senza argomenti,stampa in console i numeri compresi tra 0 e 4.

2. Si, Nel ciclo bisogna sostiuire le "," con ";".

3. Correggendo l' errore, la logica è giusta. 

## Esercizio 4

1. Questa è una funzione senza argomenti, che contiene 2 array, dove il primo contiene i numeri da 1 a 8, invece nel secondo saranno inseriti solo i numeri pari, tramite  un ciclo.

2. Si, bisogna cancellare i ";" nella ciclo for, nelle condizioni del ciclo dopo "i++" e dopo la condizione if. 

    Bisogna sostiturire nella condizione "=" con "===" perche bisogna fare un confronto, non riassegnare un valore.

3. Si, bisogna cancellare "-1" dalla condizione if "numbers.length - 1", in modo che  possiamo scorrere tutti gli elementi dell array, lasciandolo in quel modo escludiamo l'ultimo.

    Bisogna sistemare nella condizione if il ".push", bisogna pushare il numbers in posizione "i", quindi sostituiamo "evenNumbers.push(i);" con "evenNumbers.push(numbers[i]);"

    Bisogna spostare il return subito dopo il ciclo for, sennò dopo il primo ciclo si blocca, perchè return fa uscire dal ciclo.


