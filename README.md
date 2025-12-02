Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


Column:

id: INT
targa: VARCHAR(8)
marca: VARCHAR(10)
modello: VARCHAR(15)
km_percorsi: INT
anno_immatricolazione: SMALLINT
carburante: VARCHAR(7)
potenza(cv): SMALLINT
cilidranta: INT
colore: VARCHAR(13)
cambio: ENUM(‘manuale’, ‘automatico’)
nuova: BOOLEAN
posti: TINYINT
porte: TINYINT
descrizione: TEXT