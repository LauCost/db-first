#Automobile

id | BIGINT - PRIMARY KEY, NOTNULL, AUTO INCREMENT, UNIQUE
marca | VARCHAR(70) - NOTNULL
modello | VARCHAR(100) - NOTNULL
colore | VARCHAR(20) - NULL
porte | TINYINT(5) - DEFAULT(5)
targa | CHAR(7) - NULL, UNIQUE
immatricolazione | YEAR - NULL
codice_telaio | CHAR(17) - NULL, UNIQUE
peso | SMALLINT - NULL
cavalli | SMALLINT - NULL
alimentazione | VARCHARR(10) - NULL
condizione | VARCHAR(50) - NULL
km_percorsi | MEDIUMINT - NULL
prezzo | DECIMAL(8,2) - NULL
classe_emissioni | TINYINT(10) - NULL
descrizione | TEXT(100) - NULL
marce | TINYINT(20) - NULL

