# Keep It Simple, Stupid! (KISS)

**Keep it simple, stupid!** czyli po polsku **nie komplikuj, głupcze!** lub w skrócie **KISS**, to jedna z **najważniejszych i najbardziej podstawowych** zasad [**clean code**](index.html). Mówi ona, że rozwiązania powinny być **jak najprostsze**, ponieważ **im coś jest prostsze, tym łatwiej jest to zrozumieć**. Oznacza to że w kodzie powinno się **unikać trudnych do zrozumienia** i dalszego eksploatowania rozwiązań.

## Pochodzenie
<img class="right" width="200px" style="margin-left: 15px; border: 1px solid rgb(49, 49, 49); border-radius: 20px;" alt="Kelly Johnson, 1975" src="https://upload.wikimedia.org/wikipedia/commons/e/ea/ClarenceLeonardKellyJohnson.jpg">

Wbrew pozorom zasada ta nie została pierwotnie stworzona z myślą o programowaniu. Została ona sformułowana przez amerykańskiego wojskowego inżyniera lotnictwa [Kelly'ego Johnsona](https://en.wikipedia.org/wiki/Kelly_Johnson_(engineer)) w latach 60-tych, a jej przekazem miało być tworzenie samolotów w tak **prosty sposób**, aby każdy **nawet najmniej uzdolniony mechanik** mógł je naprawić w każdych, nawet najcięższych warunkach takich jak polowe oraz przy użyciu najbardziej podstawowych narzędzi.

## Zalety
**KISS** ma wiele zalet, w tym:
- **zwiększa czytelność kodu** - prosty kod jest łatwiejszy do zrozumienia, zarówno dla programistów, jak i dla użytkowników końcowych.
- **ułatwia utrzymanie kodu** - prosty kod jest łatwiejszy do modyfikacji i rozszerzania, bez wprowadzania błędów.
- **ułatwia testowanie kodu** - prosty kod jest łatwiejszy do przetestowania, aby upewnić się, że działa poprawnie.
- **zwiększa wydajność kodu** - prosty kod jest bardziej wydajny niż kod złożony.
- **zwiększa bezpieczeństwo kodu** - prosty kod jest często bardziej bezpieczny niż kod złożony, ponieważ gdy jest mniej kodu, istnieje mniejsze prawdopodobieństwo popełnienia błędu.

## Metody Stosowania
Podstawowe metody stosowania zasady **KISS** to:
- **dziel duże zadania na mniejsze, bardziej przystępne zadania** - im mniejsze zadanie, tym łatwiej je zrozumieć i wykonać.
- **używaj prostych, sprawdzonych rozwiązań** - nie próbuj wymyślać koła na nowo. Jeśli istnieje proste rozwiązanie, które działa, użyj go.
- **unikaj skomplikowanych algorytmów i struktur danych** - jeśli możesz osiągnąć ten sam wynik za pomocą prostszego rozwiązania, użyj go.
- **używaj jasnego i czytelnego języka** - kod powinien być łatwy do zrozumienia dla innych programistów.

## Przykład Zastosowania
Oto **przykładowy kod** napisany w języku **Python**, który prezentuje wyniki zastosowania metody **KISS**. Kod ten porównuje dwie liczby, po czym wyświetla informacje która jest większa od której lub czy są sobie równe.

### Przed Zastosowaniem
Kod **przed zastosowaniem** metody KISS:
```python
a = 10
b = 20

if a > b:
    print("a jest większe od b")
else:
    print("b jest większe od a")

if a < b:
    print("a jest mniejsze od b")
else:
    print("b jest mniejsze od a")

if a == b:
    print("a jest równe b")
else:
    print("a nie jest równe b")
```
**Wynikiem** uruchomienia tego kodu jest:
```
b jest większe od a
a jest mniejsze od b
a nie jest równe b
```

<div class="warning">
    Jak widać <b>kod ten wyświetla nie potrzebne informacje</b>, jeśli zostaje wyświetlona informacja że <code>b jest większe od a</code> to logicznym jest że <code>a jest mniejsze od b</code> oraz <code>a nie jest równe b</code>, <b>te informacje wywołują nie potrzebny bałagan</b> w kodzie oraz w wyniku programu.
</div>

### Po Zastosowaniu
Tak natomiast wygląda kod **po zastosowaniu** w nim zasady KISS:
```python
def compare(a, b):
    if a == b:
        print("a jest równe b")
    elif a > b:
        print("a jest większe od b")
    else:
        print("b jest większe od a")

compare(10, 20)
```
**Wynikiem** uruchomienia tego kodu jest:
```
b jest większe od a
```
Od razu widocznym jest że sam **kod jest krótszy, oraz pozbyliśmy się nie potrzebnych informacji z wyniku jego działania**. Kod został przekształcony tak aby porównanie było wykonywane jednym blokiem instrukcji warunkowej zamiast trzema, a instrukcja warunkowa została umieszczona w funkcji `compare`, co na dodatek pozwala na użycie tego porównania w innych miejscach w kodzie bez potrzeby powtarzania całej instrukcji warunkowej.

## Podsumowanie
Zasada **KISS** jest **prosta, ale potężna**. Zasada ta nie jest nakazem lecz stosowanie tej pomaga w tworzeniu **lepszego kodu**, ale także produktów i usług, które są **łatwiejsze w użyciu i utrzymaniu**.
