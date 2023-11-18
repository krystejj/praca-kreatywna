# Fail Fast (FF)

**Fail fast** czyli po polsku **szybka awaria** lub w skrócie **FF**, to również **bardzo prosta i krótka** zasada [**clean code**](index.html). Mówi ona, że program po otrzymaniu nie prawidłowych danych lub wystąpieniu błędu powinien **natychmiast zakończyć swoje działanie**.

## Zalety
Jednymi z wielu zalet stosowania **FF** są:
- **zwiększa niezawodność programu** - program, który zgłasza błędy szybko, jest mniej podatny na uszkodzenie danych lub nieoczekiwane zachowanie.
- **ułatwia debugowanie programu** - gdy program zgłasza błąd szybko, programista może łatwo zlokalizować źródło błędu.

## Metody Stosowania
Podstawowe metody stosowania zasady **FF** to:
- **sprawdzaj poprawność podanych danych** - sprawdzaj poprawność każdej danej pobranej od użytkownika, jeśli jest nie poprawna, zakończ działanie.
- **używaj warunków** - sprawdzaj poprawność zmiennych i innych danych instrukcjami warunkowymi.

## Przykład Zastosowania
Oto **przykładowy kod** napisany w języku **Python**, który prezentuje wyniki zastosowania metody **FF**.

### Przed Zastosowaniem
Kod **przed zastosowaniem** metody FF:
```python
result = input("Wpisz `tak` lub `nie`: ")
```

### Po Zastosowaniu
Tak natomiast wygląda kod **po zastosowaniu** w nim zasady FF:
```python
result = input("Wpisz `tak` lub `nie`: ")

if result != "tak" AND result != "nie":
    print("Nie prawidłowa odpowiedź")
    exit()
```
Zastosowanie metody FF zmieniło to, że gdy zostanie podana inna wartość niż `tak` lub `nie` program **wyświetli informacje o nie prawidłowej odpowiedzi i zakończy swoje działanie**. Nie będzie kontynuował działania z **nieprawidłowymi informacjami**.

## Podsumowanie
Zasada **FF** jest **bardzo ważną zasadą jeśli chodzi o bezpieczeństwo**. Dzięki niej, tworzymy program, który jest w stanie **rozpoznać nieprawidłowe informacje i odrzucić je** a nie kontynuować swoje działanie z **nieprawidłowymi danymi** i **spowodować potencjalne szkody**.
