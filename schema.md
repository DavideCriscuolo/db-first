// Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

# used cars

- id BIGINT AUTOINCREMENT UNIQUE NOT NULL PRIMARY KEY
- Marchio varchar(30) NOT NULL INDEX
- Modello varchar(20) NOT NULL
- Tipologia varchar(15) NOT NULL
- Motorizzazione varchar(15) NOT NULL
-
