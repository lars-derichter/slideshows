# Een databank aanpassen

## Stap voor stap (in MySQL)

Beheer van databanken - Lars De Richter – Thomas More Hogeschool

---

## DDL

---

### Opmerking

Met `USE <database_name>` kan je voor een heel SQL-script bepalen op welke databank gewerkt zal worden, dan heb je geen dot-notatie `<database_name>.<table.name>`nodig.

---

### Commando’s

&&&

- (`CREATE`)
- (`DROP`)
- `ALTER`

---

### Tabellen wijzigen

&&&

#### Kolom toevoegen

```SQL
ALTER TABLE Persoon
  ADD email VARCHAR(120);
```

&&&

### Kolom verwijderen

```SQL
ALTER TABLE Persoon
  DROP COLUMN geboortedatum;
```

&&&

### Kolom(definitie) wijzigen

```SQL
ALTER TABLE Departement
  MODIFY COLUMN departement_naam
    VARCHAR(90) NOT NULL UNIQUE;
```

---

## DML

---

### Commando’s

- (`INSERT`)
- (`DELETE`)
- `UPDATE`

---

### Record/rij wijzigen

```SQL
UPDATE Persoon
  SET voornaam = 'Jeff'
  WHERE persoon_id = 2;
```

notes:

- WHERE-clause hetzelfde als bij SELECT
- Als in de WHERE-clause geen primary key staat, vind MySQL dat je een onveilige operatie doet en moet je SQL_SAFE_UPDATES op 0 zetten met `SET SQL_SAFE_UPDATES = 0;` Vergeet niet om die daarna terug op 1 te zetten.
- Je kan zo een kolom aanpassen voor meerdere rijen tegelijk.
- Tip: test voor je data onherroepelijk om zeep helpt je WHERE clause uit door die eerst te combineren met een SELECT-query.

---

## Licentie

Deze slides werden gemaakt door [Lars De Richter](mailto:lars.derichter@thomasmore.be) voor het Graduaat Programmeren aan [Thomas More.](http://thomasmore.be)

Beschikbaar onder de onder de volgende Creative Commons licentie: [Naamsvermelding-NietCommercieel-GelijkDelen 4.0 Internationaal (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.nl).

```

```
