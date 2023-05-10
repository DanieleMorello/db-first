# DB Concessionario macchine usate

## Data types:

- strings: [ VARCHAR(number), CHAR(number), TEXT, LONGTEXT ]
- numbers: [ TINYINT, SMALLINT, MEDIUMINT, INT, BIGINT ]
- decimals: [ FLOAT(i,d), DOUBLE(i,d), DECIMAL(i,d) ]
- dates: [ DATETIME, DATE, TIME, YEAR, TIMESTAMP ]

## Attributes

- NULL/NOTNULL
- DEFAULT
- AUTO_INCREMENT
- UNIQUE

## Entity name: car

## Table name: cars

## Table colums

- id | BIGINT | PRIMARY_KEY | AUTO_INCREMENT | NOTNULL | UNIQUE
- marca | VARCHAR(50) | NOTNUL
- modello | VARCHAR(50) | NOTNUL
- anno | YEAR | NULL
- chilometraggio | INT | NULL
- prezzo | DECIMALS(8,2) | NULL
- stato | VARCHAR(20) | NULL
- descrizione | TEXT | NULL
- immagine | VARCHAR(255) | NULL
