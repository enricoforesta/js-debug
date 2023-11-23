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



# Bundle-2


## Esercizio 1 

1. E' una funzione che determina se sei maggiorenne o minorenne. 

2. Si, bisogna sostituire const con let nella variabile message, perchè il suo valore in base a determinate condizioni varia. Le variabili assegnante con const non posso variare. 

3. Si, bisogna aggiungere un console.log() oppure visualizzarlo nel DOM senno la variabile message non viene mai letta. 


## Esecizio 2 

1. Questa è una funzione dove stampa in console, quanti elementi ci sono nell array.

2. Si, "{colors.lenght}" va sostituito con "{colors.length}" perchè la propietà è scritta in modo sbagliato. 

3. Logica corretta.

## Esecizio 3

1. Questa è una funzione dove restituisce un valore di un numero, dato da un prompt sommato a + 12.

2. Sintassi corretta. 

3. Si, bisogna trasformare il risultato del prompt in un numero, possiam farlo aggiungendo Number prima del prompt, oppure aggiungendo il segno "+" sempre prima del prompt.

## Esecizio 4

1. Questa è una funzione dove inserita un email, verifica se è presente nell array, oppure no. In questo caso scorriamo l array grazie al metodo ".includes"

2. Sintassi corretta.

3. Si, perchè "let grantAccess = 'false' " è sbagliato perchè cosi il valore è una stringa quindi dobbiamo togliere gli apici "let grantAccess = false" , per ritornare un valore booleano.

    Lo stesso bisonga fare nella condizione dell if quindi sarà "grantAccess = true " 

## Esecizio 5

1. Questa è una funzione dove inserita un email, verifica se è presente nell array, oppure no. L'array in questo caso viene ciclato da un ciclo for.

2. Si mancava una parentesi "}" che chiudeva la funzione.

3. Si le condizioni if e else vanno messe fuori il ciclo for, in modo che dopo che sia avvenuto il ciclo, controlliamo se l'email è presente o meno, Sennò per ogni ciclo avremmo una controllo. 