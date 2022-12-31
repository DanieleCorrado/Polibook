Project done for the software engineering exam.
Presents a university website where the user (student) can monitor the progress of his university career.

Convenzioni:
    * javascript : camelCase
    * php : snake_case
    * html, css: kebab-case

Commenti:
    * in italiano
    * !! per indicare importanza

Come usare dbh.inc.php:
    1) usare open_conn() che ritorna la connessione al db
    2) usare fetch_DB($conn, $query, ...$argomenti) per il fetch dei dati
        2.1) i risultati ritornati da fetch_DB sono un cursore, usare mysqli_fetch_assoc($results) per ritornare i risultati una riga alla volta
    3) usare insert_DB($conn, $tabella, ...$argomenti) per l'inserzione dei dati
        3.1) la funzione restiruirà un booleano che indica se la query è andata a buon fine
    3) chiudere la connessione con $conn -> close() (si consiglia di farlo sempre);

DB:
    * il file '/my_polibooklet.sql' è il file contenente la struttura del db.

'/javascript/methods.js':
    * contiene i metodi javascript in comune

