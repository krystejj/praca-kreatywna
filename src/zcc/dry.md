# Don't Repeat Yourself (DRY)

**Don't repeat yourself** czyli po polsku **nie powtarzaj się** lub w skrócie **DRY**, to również jedna z **najważniejszych i najbardziej podstawowych** zasad [**clean code**](index.html). Mówi ona, że powinniśmy **unikać powtórzeń w kodzie**, gdyż zwiększają one nie potrzebnie ilość kodu, co sprawia że **jest mniej czytelny i trudniejszy w eksploatowaniu**. Powtarzający się kod może również **prowadzić do błędów**, gdy zostanie zmodyfikowany w jednym miejscu, ale nie w innych.

## Zalety
**DRY** ma wiele zalet, w tym:
- **zwiększa czytelność kodu** - kod, który nie zawiera powtórzeń, jest łatwiejszy do zrozumienia i utrzymania.
- **ułatwia utrzymanie kodu** - zmiana kodu, który nie zawiera powtórzeń, jest łatwiejsza, ponieważ nie trzeba zmieniać kodu w wielu miejscach.
- **upraszcza testowanie kodu** - kod, który nie zawiera powtórzeń, jest łatwiejszy do przetestowania, ponieważ nie trzeba testować kodu w wielu miejscach.
- **pozwala uniknąć błędów** - spowodowanych zmianą powtarzającego się kodu w jednym miejscu, lecz nie w innych.

## Metody Stosowania
Podstawowe metody stosowania zasady **DRY** to:
- **używaj funkcji i metod** - rozdzielaj powtarzający się kod na funkcje i metody. Pozwala to w łatwy sposób wywoływać wiele razy z róznych miejsc w programie ten sam blok kodu bez potrzeby powtarzania go.
- **używaj bibliotek i frameworków** - są one gotowymi zbiorami funkcji, klas, itp. które można wykorzystać do tworzenia programu. Eliminuje to potrzebe pisania niektórych części kodu samemu co może wyeliminować też problem powtórzeń.

## Przykład Zastosowania
Oto **przykładowy kod** napisany w języku **Python**, który prezentuje wyniki zastosowania metody **DRY**. Kod ten wyświetla przywitanie z trzema różnymi osobami.

### Przed Zastosowaniem
Kod **przed zastosowaniem** metody DRY:
```python
print("Witaj, Ania!")
print("Witaj, Karol!")
print("Witaj, Laura!")
```
**Wynikiem** uruchomienia tego kodu jest:
```
Witaj, Ania!
Witaj, Karol!
Witaj, Laura!
```

<div class="warning">
    Ten kod, pomimo że działa prawidłowo, jest on <b>niezgodny z zasadą DRY</b>, ponieważ zawiera powtórzenia. Przy chęci zmiany treści wiadomości, musielibyśmy edytować ją w <b>trzech różnych miejscach</b> w kodzie.
</div>

### Po Zastosowaniu
Tak natomiast wygląda kod **po zastosowaniu** w nim zasady DRY:
```python
def greeting(name):
    print(f"Witaj, {name.capitalize()}!")

greeting("ania")
greeting("karol")
greeting("laura")
```
**Wynik** uruchomienia tego kodu jest **identyczny** jak przed zastosowaniem zasady.

Pomimo tego że wynik działania kodu jest taki sam, oraz ilość kodu minimalnie się zwiększyła, zastosowanie tej zasady w tym kodzie **nadal zmniejsza prawdopodobieństwo wystąpienia późniejszych błędów**. Gdybyśmy chcieli zmienić treść wiadomości witającej osobe, nie musimy już zmieniać jej w **trzech różnych miejscach w kodzie tylko w jednym**, ponieważ stworzyliśmy funkcję `greeting` która przyjmuje imię jako parametr i to ta funkcja wyświetla przywitanie.

## Podsumowanie
**Zasada DRY również jest prosta, ale znacząca.** Tak jak poprzednia zasada nie jest nakazem lecz przyczynia się do tworzenia kodu w którym istnieje **mniejsze prawdopodobieństwo wystąpienia błędów oraz jest czytelniejszy i krótszy**.
