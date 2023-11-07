# Creazione tabella
1. creo manualmente il file database.db
2. creo manualmente il file crea_tabella.sql
3. inserisco il codice al suo interno ed eseguo il comando dallo script di sqlite nel command promt
## Il file crea_tabella.sql contiene il codice:
```sql
CREATE TABLE IF NOT EXISTS compagni (
id INTEGER PRIMARY KEY AUTOINCREMENT,
NOME TEXT,
COGNOME TEXT,
EMAIL TEXT);
```
# Inserimento dati
1. creo manualmente il file inserisci_dati.sql
2. inserisco il codice al suo interno
3. eseguo il comando dallo script di sqlite nel command promt

## Il file inserisci_dati.sql contiene il codice:
```sql
INSERT INTO compagni (NOME, COGNOME, EMAIL) VALUES ('Giorgio', 'Bruzzone', 'email1@gmail.com');
INSERT INTO compagni (NOME, COGNOME, EMAIL) VALUES ('Emanuele', 'Cappanera', 'email2@gmail.com');
INSERT INTO compagni (NOME, COGNOME, EMAIL) VALUES ('Andrea', 'Alivigni', 'email3@gmail.com');
INSERT INTO compagni (NOME, COGNOME, EMAIL) VALUES ('Greta', 'Di Fabio', 'email4@gmail.com');
INSERT INTO compagni (NOME, COGNOME, EMAIL) VALUES ('Alessandro', 'De Giacobbi', 'email5@gmail.com');
INSERT INTO compagni (NOME, COGNOME, EMAIL) VALUES ('Gianluca', 'Ciceri', 'email6@gmail.com');
INSERT INTO compagni (NOME, COGNOME, EMAIL) VALUES ('Tiziano', 'Gessa', 'email7@gmail.com');
INSERT INTO compagni (NOME, COGNOME, EMAIL) VALUES ('Simone', 'Rizzo', 'email8@gmail.com');
INSERT INTO compagni (NOME, COGNOME, EMAIL) VALUES ('Cristofer', 'Thompson', 'email9@gmail.com');
INSERT INTO compagni (NOME, COGNOME, EMAIL) VALUES ('Davide', 'Rivolta', 'email10@gmail.com');
```
