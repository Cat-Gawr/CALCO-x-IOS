# CALCO-x-IOS

------------------------------------------------------------

salve , oggi il 28 - 02 - 2025 pubblicherò l'intero codice 
di un'applicazione in Switf { per il sistema operativo IOS }

# PROGETTO

Il progetto è composto da otto attività obbligatorie e tre attività facoltative, ho svolto solo quelle obbligatorie che sono le seguenti:
Fai funzionare la calcolatrice come mostrato nelle lezioni 1 e 2 ( per questo compito guarda i primi due video del corso ).
La tua calcolatrice funziona già con numeri in virgola mobile (ad esempio, se tocchi 3 ÷ 4 =, mostrerà correttamente 0,75), tuttavia, non c'è modo per l'utente di immettere direttamente un numero in virgola mobile. Risolvi questo problema consentendo l'immissione di numeri in virgola mobile legali (ad esempio, "192.168.0.1" non è un numero in virgola mobile legale!) . Dovrai avere un pulsante "." nella tua calcolatrice. Non preoccuparti troppo della precisione o delle cifre significative in questo compito (farlo è un credito extra).
Aggiungi altri pulsanti operativi alla tua calcolatrice in modo che abbia almeno una dozzina di operazioni totali (può averne anche di più se vuoi). Puoi scegliere qualsiasi operazione ti piaccia. I pulsanti devono sistemarsi bene in modalità verticale e orizzontale su tutti gli iPhone 6 e 7. ( Ho aggiunto solo sette operazioni ).
Usa il colore per rendere gradevole la tua interfaccia utente . Come minimo, i pulsanti delle tue operazioni devono avere un colore diverso dai pulsanti della tua tastiera, ma altrimenti puoi usare il colore in qualsiasi modo ritieni gradevole.
Aggiungi una proprietà Bool al tuo CalculatorBrain chiamata resultIsPending che restituisce un valore che indica se è in corso un'operazione binaria.
Aggiungi una proprietà String al tuo CalculatorBrain chiamata description che restituisce una descrizione della sequenza di operandi e operazioni che hanno portato al valore restituito da result (o al risultato finora se resultIsPending). Il carattere = (segno di uguale) non dovrebbe mai apparire in questa descrizione, né ... (puntini di sospensione).
Implementa un UILabel nella tua UI che mostra la sequenza di operandi e operazioni che hanno portato a (o stanno portando a se resultIsPending) ciò che è (o "sarà" se resultIsPending) visualizzato nel display . Se resultIsPending è vero, metti . . . alla fine di UILabel, altrimenti metti =. Se userIsInTheMiddleOfTyping, puoi lasciare che UILabel mostri ciò che era lì prima che l'utente iniziasse a digitare il numero. Esempi ...

Toccando 7 + verrà visualizzato "7 + ..." (con 7 ancora sul display)

°7 + 9 mostrerebbe “7 + ..." (9 sul display)

°7 + 9 = mostrerebbe “7 + 9 =" (16 sul display)

°7 + 9 = √ mostrerebbe “√(7 + 9) =” (4 sul display)

°7 + 9 = √ + 2 = mostrerebbe “√(7 + 9) + 2 =” (6 sul display)

°7 + 9 √ mostrerebbe “7 + √(9) ...” (3 sul display)

°7 + 9 √ = mostrerebbe “7 + √(9) =“ (10 sul display)

°7 + 9 = + 6 = + 3 = mostrerebbe “7 + 9 + 6 + 3 =" (25 sul display)

°7 + 9 = √ 6 + 3 = mostrerebbe “6 + 3 =" (9 sul display)

°5 + 6 = 7 3 mostrerebbe “5 + 6 =" (73 sul display)


°Aggiungi un pulsante C che cancella tutto (il tuo display, la nuova UILabel che hai aggiunto sopra, tutte le operazioni binarie in sospeso, ecc.). Idealmente, questo dovrebbe lasciare la tua Calcolatrice nello stesso stato in cui si trovava quando l'hai avviata.
