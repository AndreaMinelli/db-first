Vi chiediamo di immaginare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario!

| COLONNE                   | TYPES       | ATTRIBUTI                                | INDICI      |
| ------------------------- | ----------- | ---------------------------------------- | ----------- |
| ID                        | INT         | UNIQUE, AUTOINCREMENT, NOTNULL, UNSIGNED | PRIMARY KEY |
| MARCA                     | VARCHAR(20) | NOTNULL                                  |
| MODELLO                   | VARCHAR(50) | NOTNULL                                  |
| TARGA                     | VARCHAR(20) | NOTNULL                                  |
| CONFIGURAZIONE            | VARCHAR(20) | NULL                                     |
| ACCESSORI                 | TEXT        | NULL                                     |
| DESTINAZIONE D'USO        | CHAR(1)     | NOTNULL                                  |
| IMMATRICOLAZIONE          | DATE        | NOTNULL                                  |
| LUOGO DI IMMATRICOLAZIONE | VARCHAR(50) | NOTNULL                                  |
| ALIMENTAZIONE             | CHAR(1)     | NOTNULL                                  |
| TIPO CAMBIO               | CHAR(2)     | NOTNULL                                  |
| TIPO MOTORE               | VARCHAR(15) | NOTNULL                                  |
| NUMERO MARCE              | TINYINT     | NOTNULL                                  |
| CLASSE EMISSIONI          | CHAR(1)     | NOTNULL                                  |
| CILINDRATA                | SMALLINT    | NOTNULL, UNSIGNED                        |
| KW                        | SMALLINT    | NOTNULL, UNSIGNED                        |
| CV                        | SMALLINT    | NOTNULL, UNSIGNED                        |
| KM                        | MEDIUMINT   | NOTNULL, UNSIGNED                        |
| PREZZO                    | MEDIUMINT   | NOTNULL, UNSIGNED                        |
| RATEIZZABILE              | TINYINT(1)  | NULL, DEFAULT(0)                         |
| RATING STATO VETTURA      | CHAR(1)     | NOTNULL                                  |
| COSTO                     | MEDIUMINT   | NOTNULL, UNSIGNED                        |
| DATA ACQUISIZIONE         | DATE        | NOTNULL                                  |
| ANNOTAZIONI               | TEXT        | NULL                                     |
| NUMERO EX PROPRIETARI     | TINYINT     | NOTNULL, UNSIGNED                        |
| NUMERO POSTI              | TINYINT     | NOTNULL                                  |
| NUMERO PORTE              | TINYINT     | NOTNULL                                  |
| TIPO CARROZZERIA          | CHAR (3)    | NOTNULL                                  |
| COLORE CARROZZERIA        | VARCHAR(50) | NOTNULL                                  |
