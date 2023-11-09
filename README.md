# Zadania lab 04
## Zadanie 1

Tekst **pogrubiony** lub _kursywa_

```sql
SELECT * FROM osoba;
```

```python
def funkcja():
  print('Ala ma kota')
```

Polecenie `SELECT` służy wybieraniu danych z bazy.

Lista ponumerowana
1. Punkt 1.
2. Punkt 2.
2.1. Punkt 2.1

Listy wypunktowane:
* punkt 1
* punkt 2
  * punkt 2.1


https://dillinger.io/



```sql
create table walizka( id_walizki int primary key auto_increment, pojemnosc int unsigned, kolor enum('rozowy', 'czerwony', 'teczowy', 'zolty'), id_wlasciciela int, foreign key(id_wlasciciela) references postac(id_postaci) on delete cascade);
```


```sql
describe walizka;
```
