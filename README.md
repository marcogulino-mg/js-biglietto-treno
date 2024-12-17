# js-biglietto-treno

TRACCIA

Il programma dovrà chiedere all’utente il numero di chilometri che vuole percorrere e l’età del passeggero. Sulla base di queste informazioni dovrà calcolare il prezzo totale del viaggio, secondo queste regole:
- il prezzo del biglietto è definito in base ai km (0.21 € al km)
- va applicato uno sconto del 20% per i minorenni
- va applicato uno sconto del 40% per gli over 65.
- L’output del prezzo finale va messo fuori in forma umana (con massimo due decimali, per indicare centesimi sul prezzo). Questo richiederà un minimo di ricerca. 

HUMAN CODE

-CHIEDO ALL'UTENTE A QUANTI KM AMMONTA IL VIAGGIO 

-CHIEDO ALL'UTENTE LA SUA ETA

-CALCOLO IL PREZZO DEL BIGLIETTO MOLTIPLICANDO I KM PER 0,21€ 
    -SE L'ETA DELL'UTENTE E' INFERIORE AI 18 ANNI
        -APPLICO UNO SCONTO DEL 20% AL PREZZO DEL BIGLIETTO
        -STAMPO IL PREZZO DEL BIGLIETTO
    -SE L'ETA DELL'UTENTE E' SUPERIORE AI 65 ANNI
        -APPLICO UNO SCONTO DEL 40% AL PREZZO DEL BIGLIETTO
        -STAMPO IL PREZZO DEL BIGLIETTO
    -ALTRIMENTI
        -STAMPO IL PREZZO DEL BIGLIETTO

-L'UTENTE PAGA IL PREZZO DEL BIGLIETTO