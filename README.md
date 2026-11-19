# Modeliranje i implementacija baze podataka atletskih natjecanj

Projekt iz kolegija *Baze podataka* koji obuhvaća modeliranje relacijske baze podataka za evidenciju atletskih natjecanja te izradu SQL upita za dohvat i analizu podataka.

## O projektu

Cilj projekta je osmisliti bazu podataka koja omogućuje pohranu i povezivanje podataka o atletskim natjecanjima, sportašima, trenerima i disciplinama. Na temelju izrađenog modela definirana je relacijska shema te su izrađeni SQL upiti za dohvat različitih informacija iz baze.

## 1. Modeliranje baze podataka

U prvom dijelu projekta provedene su sljedeće aktivnosti:

- Identifikacija entiteta, atributa i veza između entiteta.
- Izrada konceptualnog modela pomoću Chenova ER dijagrama.
- Definiranje kardinalnosti veza.
- Transformacija konceptualnog modela u relacijsku shemu.
- Određivanje primarnih i stranih ključeva.
- Izrada rječnika podataka.
- Analiza funkcionalnih i višeznačnih ovisnosti.
- Normalizacija baze podataka kroz 1NF, 2NF, 3NF, BCNF i 4NF.

Baza obuhvaća šest tablica:

- SPORTAŠ
- TRENER
- NATJECANJE
- DISCIPLINA
- SUDJELUJE
- ODRŽAVA_SE

## 2. SQL upiti

U drugom dijelu projekta izrađeno je pet SQL upita za dohvat i analizu podataka iz baze.

Upiti obuhvaćaju:

1. **Broj sportaša po treneru** – izračun broja sportaša koje trenira pojedini trener.
2. **Broj sudionika po natjecanju** – određivanje broja sportaša koji sudjeluju na svakom natjecanju.
3. **Treneri s natprosječnim brojem sportaša** – pronalaženje trenera koji treniraju više sportaša od prosjeka.
4. **Natjecanje s najvećim brojem disciplina** – određivanje natjecanja na kojima se održava najveći broj disciplina.
5. **Broj različitih natjecanja po treneru** – analiza broja različitih natjecanja na kojima su sudjelovali sportaši pojedinog trenera.

### Korišteni SQL koncepti

- JOIN
- GROUP BY
- ORDER BY
- HAVING
- COUNT i COUNT DISTINCT
- Agregatne funkcije AVG i MAX
- Ugniježđeni podupiti (subqueries)

## Korištene tehnologije i koncepti

- SQL
- Relacijske baze podataka
- ER modeliranje
- Relacijska shema
- Primarni i strani ključevi
- Normalizacija baza podataka

## Dokumenti
- `database_design_and_normalization.pdf`
- `sql_queries.pdf`
