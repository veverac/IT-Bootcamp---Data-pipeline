### ETL projekt - Da li pobede prodaju dresove?

Projekat obrađuje podatke prodavnice Northern Star Shop i fudbalske lige NSL

## Opis projekta

Cilj projekta je da povežem podatke o prodaji proizvoda sa podacima o fudbalskim timovima i njihovim rezultatima.

Za sada je urađeno prvih 11 zadataka (možda i tačno) odnosno deo koji se odnosi na preuzimanje, čišćenje i pripremu podataka.

Podaci su preuzimani sa (J)API-ja, kao i iz CSV i parquet fajlova.

Prvo su napravljene funkcije za preuzimanje svih potrebnih podataka, koje čuvaju originalne fajlove u /data/raw folderu.

Nakon toga, napisane su funkcije za čišćenje preuzetih podataka:
    - uklonjeni su duplikati;
    - sređeni tekstualni podaci;
    - uređene cene;
    - izvršena validacija porudžbina

