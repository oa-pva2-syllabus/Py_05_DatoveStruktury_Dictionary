# PVA2 - Programování a vývoj aplikací
## Cvičení 05: Datové struktury: Slovník

### Jak řešit
- Všechny úkoly řešte v souboru `reseni.py`, kde jsou připravená data a proměnné ve tvaru `vysledek = ...`.
- Místo `...` doplňte své řešení. Názvy proměnných neměňte, podle nich se řešení automaticky vyhodnocuje.
- Výsledek počítejte z dat v programu (klíčem, metodou, funkcí), ne opsáním hodnoty.
- Po každém `git push` se řešení vyhodnotí a výsledek najdete v pull requestu **Feedback**.
  Čísla požadavků odpovídají číslům úkolů níže.

### 1
Vytvořte slovník `zamestnanec` s klíči křestní jméno `name`, příjmení `surname` a příjem `salary`.
Zaměstnanec se jmenuje Jan Novák a má příjem 30000 (číslo, ne text).

### 2
Ve slovníku `zamestnanec` navyšte zaměstnanci mzdu o 6 %.

### 3
Do slovníku `employees` přidejte pod klíč `emp3` zaměstnance z předchozích úkolů.

```python
employees = {
    'emp1': {'name': 'John', 'surname': 'Doe', 'salary': 32000},
    'emp2': {'name': 'Emma', 'surname': 'Phillips', 'salary': 28000}
}
```

### 4
Hodnoty zaměstnance s klíčem `emp2` uložte jako seznam do `emp2Hodnoty` a zobrazte je.

### 5
Ve slovníku `emp_selected` přejmenujte klíč `city` na `location`.

```python
emp_selected = {
    "name": "Maria",
    "age": 34,
    "salary": 47000,
    "city": "Prague"
}
```

Očekávaný výstup: `{'name': 'Maria', 'age': 34, 'salary': 47000, 'location': 'Prague'}`

### 6
Ze slovníku `emp_selected` odstraňte klíče `age` a `salary`.

### 7
Průměr bodů ze slovníku `grades` uložte do `prumer`.

```python
grades = {
    'Czech': 85,
    'Chemistry': 67,
    'History': 73,
    'Economics': 88,
    'Physics': 64,
    'Computer Science': 91,
    'Mathematics': 71
}
```

### 8
Ze slovníku `grades` získejte pomocí adekvátní metody všechny získané body. Hodnoty uložte do `body` jako samostatný seznam (ne slovník).

### 9
Ze slovníku `grades` získejte pomocí adekvátní metody hodnocené předměty. Hodnoty uložte do `predmety` jako samostatný seznam (ne slovník).

### 10
Do `bodyBiologie` uložte body z předmětu `Biology`. Předmět ve slovníku není – použijte metodu, která místo chyby vrátí výchozí hodnotu `0`.

### 11
Pomocí operátoru `in`:
1. do `maFyziku` uložte, zda je ve slovníku `grades` předmět `Physics`,
2. do `ma100` uložte, zda je mezi body ve slovníku `grades` hodnota `100`.

### 12
```python
trida = [
    {'jmeno': 'Jana', 'znamky': [1, 2, 1]},
    {'jmeno': 'Petr', 'znamky': [3, 2]}
]
```

Do `prvniZnamkaPetra` uložte první známku žáka Petr ze seznamu `trida`.

### 13
Do seznamu `trida` přidejte žákyni `Eva` se známkami `[2, 2]`.
