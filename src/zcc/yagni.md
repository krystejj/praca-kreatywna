# You Ain't Gonna Need It (YAGNI)

**You ain't gonna need it** czyli po polsku **nie będziesz tego potrzebował** lub w skrócie **YAGNI**, to także jedna z **najbardziej podstawowych** zasad [**clean code**](index.html). Zakłada ona, że nie powinniśmy pisać tak zwanego **dead code** czyli kodu który jest po prostu **nie używany**. Nawet gdy planujemy użyć tego kodu w późniejszych etapach tworzenia programu, **nie warto jest go tworzyć teraz**, a tylko wtedy gdy już będzie nam potrzebny. Piszemy kod, którego potrzebujemy tylko w **aktualnym momencie**, a nie później.

## Zalety
Jedne z wielu zalet stosowania **YAGNI** to:
- **mniej zaśmiecony kod** - nie piszemy kodu o którym możemy później zapomnieć.
- **zwiększa czytelność i klarowność kodu** - kod, który nie zawiera funkcji lub możliwości, których nie potrzebujemy, jest łatwiejszy do zrozumienia.
- **zwiększa wydajność kodu** - kod, który nie zawiera funkcji lub możliwości, których nie potrzebujemy, jest bardziej wydajny.

## Metody Stosowania
Podstawowe metody stosowania zasady **YAGNI** to:
- **przemyśl dobrze swoje potrzeby** - zanim zaczniesz implementować nową funkcję lub klasę, zastanów się, czy naprawdę jej potrzebujesz. Czy jest to konieczne do wykonania określonego zadania?
- **pisz tylko ten kod którego potrzebujesz w aktualnym momencie** - nie pisz kodu którego będziesz potrzebował później, napiszesz go wtedy gdy będziesz go potrzebował.

## Przykład Zastosowania
Oto **przykładowy kod** napisany w języku **Python**, który prezentuje wyniki zastosowania metody **YAGNI**.

### Przed Zastosowaniem
Kod **przed zastosowaniem** metody YAGNI:
```python
def sum(a, b):
    return a + b

def sub(a, b):
    return a - b

print(sum(5, 8))
```
**Wynikiem** uruchomienia tego kodu jest:
```
13
```
Jak widać kod działa poprawnie, wyświetla porządane informacje w prawidłowy sposób.

### Po Zastosowaniu
Tak natomiast wygląda kod **po zastosowaniu** w nim zasady YAGNI:
```python
def sum(a, b):
    return a + b

print(sum(5, 8))
```
**Wynik** uruchomienia tego kodu jest **identyczny** jak przed zastosowaniem zasady.

Jedyna rzecz jaka zmieniła się po zastosowaniu metody YAGNI, to **usunięcie funkcji** `sub` z kodu. Usunięcie tej funkcji nastąpiło dlatego, gdyż była ona po prostu **nie używana** co sprawiało ją **bezużyteczną i zaśmiecającą kod**.

## Podsumowanie
Zasada **YAGNI** to kolejna **banalna ale ważna zasada**. Pozwala na pisanie **krótszego kodu** który jest **pozbawiony nie używanych funkcji i innych nie używanych elementów**.
