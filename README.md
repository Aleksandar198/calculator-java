LOC izvestaj
Datum: 17.3.2026.

 File name         |       LOC
-------------------------------
1. Calculator.java |        188
2. Start.java      |         26
-------------------------------
                   | total: 214
Napomena: LOC ukljucuje prazne linije i komentare. 


Staticka analiza - izvestaj
Datum: 17.3.2026.

Calculator.java - linija 8 - Klasa 'Operations' je staticka unutrasnja klasa koja samo definise konstante, mozda je bolje umesto nje koristiti enum

Calculator.java - linija 15 - Privatni konstruktor je bespotreban

Calculator.java - linija 18 - Metoda 'ToString()' ne prati Java konvenciju imenovanja (camel case)

Calculator.java - linija 24 - Metoda 'Run()'  ne prati Java konvenciju imenovanja

Calculator.java - linija 53 - Petlja 'for' se moze zameniti unapredjenom 'for' petljom

Claculator.java - linija 55 - Uslovni izraz 'if' se moze zameniti izrazom 'switch'

Calculator.java - linija 63 - Hvatanje generickog 'Exception' je presiroko, moglo bi se zameniti sa 'NumberFormatException'

Calculator.java - linija 70 - Promenljiva 'textResult' je bespotrebna, 'Float.toString(finalResult)' moze direktno da se vrati.

Calculator.java - linija 74 - Metoda 'Calculate' ne prati Java konvenciju imenovanja

Calculator.java - linija 183 - Nepotreban 'return' statement

Start.java - linija 6 - Promenljiva 'Expression' ne prati Java konvenciju imenovanja

Start.java - linija 7 - Promenljiva 'active' se koristi kao kontrola petlje, ali mogla bi se zameniti direktnim 'while(true)' uz 'break' radi čitljivosti

Start.java - linija 15 - poredjenje stringa sa 'exit' koristi metodu 'equals', sto je ok, ali je mozda bolje koristitit metodu 'equalsIgnoreCase' da bi se pokrili razliciti slucajevi unosa.




