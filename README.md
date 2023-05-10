# DB Concessionario macchine usate

## Data types:

- strings: [varchar(number), char(number), text, longtext]
- numbers: [tinyint, smallint, mediumint, int, bigint]
- decimals: [float(i,d), double(i,d), decimal(i,d)]
- dates: [datetime, date, time, year, timestamp]

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
