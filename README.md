# Platforme-za-slu-anje-muzike---Platform-for-listening-music
Zadatak za ispit Baze podataka 1 na PMF, UNS. Opisan je informacioni sistem platforme za slušanje muzike u SQLDeveloper.  
Osvojeno je  45/45 bodova. 


Platforma sadrži izvođače i sistem čuva podatke o njihovom imenu, kratkoj biografiji i da
li se radi o bendu ili samostalnom izvođaču.
● Izvođač može da objavi albume. Svaki album se odnosi na samo jednog izvođača, a
pamti se njegov naziv i datum objave.
● Album se sastoji od jedne ili više pesama, a svaka pesma se može nalaziti na samo
jednom albumu. Pesme imaju svoj naziv i trajanje.
● Korisnik platforme može da sluša pesme. Pošto isti korisnik može da sluša jednu pesmu
više puta, za svako slušanje se pamte i datum i vreme slušanja pesme. Svaki korisnik
ima svoj username i password i informaciju da li je premijum korisnik.
● Pre slušananja svake pesme sistem može da ubaci reklamu, koju je potrebno zapamtiti.
Reklame imaju svoj naziv, cenu i trajanje, a jedna reklama može da se pušta prilikom
više slušanja.

Zadaci:
1. Na osnovu date specifikacije kreirati model entiteta i poveznika i napraviti logički model u
Oracle SQL Developer-u. (16 bodova)
2. Prevesti kreirani logički (ER) model u relacioni. (0 bodova)
3. U bazi napraviti tabele i ograničenja (napraviti prefiks u relacionom modelu, izgenerisati
DDL i izvršiti ga). (6 bodova)
4. Popuniti tabele podacima (makar jedan red u svakoj tabeli). (6 bodova)
5. Prikazati izvođača koji je najslušaniji od strane korisnika i broj slušanja njegovih pesama.
(7 bodova)
6. Povećati cenu reklamama koje su se prikazale više od _____ puta. (5 bodova)
7. Izbrisati korisnika sa username-om ________________ (izabrati korisnika koji je slušao
pesme). (5 bodova)
