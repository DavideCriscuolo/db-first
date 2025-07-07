// Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

# used_cars

- id BIGINT AUTOINCREMENT UNIQUE NOT NULL PRIMARY KEY
- Marchio Varchar(30) NOT NULL INDEX
- Modello Varchar(20) NOT NULL
- Tipologia Varchar(20) NOT NULL
- Motorizzazione Varchar(15) NOT NULL
- KM FLOAT(6,3) NOT NULL
- Condizioni Varchar(255) NOT NULL
- Colore Varchar(20) NULL
- Lavori_Effettuati Text NULL
- Optional Text NULL
- Anno_di_produzione Year Not Null
- Potenza_Cv Int Not Null
- Prezzo Money Not Null Index
