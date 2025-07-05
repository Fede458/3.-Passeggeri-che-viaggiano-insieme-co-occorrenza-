Come funziona la query

Si confronta la tabella Biglietto con sé stessa (auto-join), per mettere a confronto ogni biglietto con gli altri.

Si filtrano solo i casi in cui i biglietti riguardano la stessa tratta e lo stesso giorno.

Per evitare duplicati o confronti dello stesso passeggero con sé stesso, si usa la condizione A.id_passeggero < B.id_passeggero.

Si raggruppano le coppie di passeggeri in modo da contare quante volte hanno viaggiato insieme.

Vengono mostrati solo i casi in cui hanno viaggiato insieme almeno una volta, ordinati dalla coppia che ha viaggiato insieme più spesso a quella meno frequente.

Questa analisi è utile per individuare gruppi di clienti abituali o per creare offerte mirate per chi viaggia insieme.

