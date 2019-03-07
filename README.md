# Dimedia - Zadatak 2

## Opis zadatka

Imamo staru galeriju koja radi na jQuery-u 1.4.4. Galerija treba raditi jQuery-u 1.9.0, ne smije se mijenjati galerija.

## Rješenje

U jQuery verziji 1.9.0 više nema metode jQuery.browser()

Najelegantnije rješenje je iskoristiti jQuery migrate plugin "http://code.jquery.com/jquery-migrate-1.4.1.js"

Dodavanjem skripte koja importira ovaj plugin, galerija ponovno radi.