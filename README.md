Laravel DC Comics

## Progetto per gestire un archivio di fumetti.

Inizializziamo il progetto con Laravel 9.2 creando una cartella utilizzando il terminale, seguendo questi passaggi:

    - composer create-project --prefer-dist laravel/laravel:^9.2 your_project_name_here

    - composer require pacificdev/laravel_9_preset

    - php artisan preset:ui bootstrap

    - npm install 

    a questo punto apriamo il progetto con VSC, apriamo il terminale di VSC e lanciamo il progetto con i comandi:

        -npm run dev

        -php artisan serve

    ricordarsi di lanciare i comandi in due terminali separati.

A questo punto accediamo a phpmyadmin e creiamo un nuovo database, successivamente modifichiamo il file .env        

1. Importiamo il file dati comics.php

2. Creiamo una migration per il model "Comic"

    - creiamo la struttura della tabella basandoci sui dati forniti nel file comics.php

3. Creiamo un seeder per il modello "Comic"

    - importiamo i dati dal file comics.php

4. Creiamo una pagina Home generica

5. Definiamo le operazioni CRUD
