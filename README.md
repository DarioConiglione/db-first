Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


Column:

id: INT - NOT NULL - UNIQUE
targa: VARCHAR(8) - NOT NULL - UNIQUE
marca: VARCHAR(10) - NOT NULL 
modello: VARCHAR(15) - NOT NULL
km_percorsi: INT - NOT NULL
anno_immatricolazione: SMALLINT - NOT NULL
carburante: VARCHAR(7) - NOT NULL
potenza(cv): SMALLINT - NULL
cilidranta: INT - - NOT NULL
colore: VARCHAR(13) - NULL
cambio: ENUM(‘manuale’, ‘automatico’) - NULL
nuova: BOOLEAN - NULL
posti: TINYINT - NULL
porte: TINYINT - NULL
descrizione: TEXT - NULL