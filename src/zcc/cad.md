# Code as Documentation (CaD)

**Code as documentation** czyli po polsku **kod jako dokumentacja** lub w skrócie **CaD**, to zasada [**clean code**](index.html) dotycząca komentowania kodu. Mówi ona, że **kod powinien być sam w sobie zrozumiały, a komentarze powinny wyjaśniać dlaczego a nie co**. Znaczenie tej zasady jest takie, że powinniśmy pisać kod który jest **prosty w zrozumieniu**.

> "Kod powinien być taki, że po przeczytaniu go wiemy w jaki sposób działa. Komentarze powinny wyjaśniać dlaczego tak działa i jakie jest jego użycie, **a nie to jak działa**." - [Bard AI by Google](https://bard.google.com/)

## Zalety
Przykładowymi zaletami stosowania **CaD** są:
- **zwiększa wydajność pracy** - kod, który jest napisany w sposób ułatwiający jego zrozumienie, pozwala programistom skupić się na pisaniu kodu, a nie na czytaniu dokumentacji.
- **zwiększa czytelność kodu** - kod, który jest napisany w sposób ułatwiający jego zrozumienie, jest łatwiejszy do utrzymania i rozszerzania.
- **ułatwia współpracę z innymi programistami** - kod, który jest napisany w sposób ułatwiający jego zrozumienie, jest łatwiejszy do zrozumienia przez innych programistów.

## Metody Stosowania
Podstawowe metody stosowania zasady **CaD** to:
- **używanie opisowych nazw zmiennych i funkcji** - nazwy, które opisują, co zmienne lub funkcje reprezentują, ułatwiają zrozumienie kodu.
- **używanie struktur danych i algorytmów, które są dobrze znane** - struktury danych i algorytmy, które są dobrze znane, są łatwiejsze do zrozumienia.
- [**używanie konwencji nazewnictwa**](stnc.md) - konwencje nazewnictwa pomagają zachować spójność kodu i ułatwiają jego zrozumienie.

## Przykład Zastosowania
Oto **przykładowy kod** napisany w języku **Python**, który prezentuje wyniki zastosowania metody **CaD**.

### Przed Zastosowaniem
Kod **przed zastosowaniem** metody CaD:
```python
def tomato(a, b):
    return a / b
```
<div class="warning">
    Ten kod <b>narusza zasadę CaD</b> ponieważ nazwa funkcji <code>tomato()</code> w żaden sposób nie przedstawia działania tej funkcji.
</div>

### Po Zastosowaniu
Tak natomiast wygląda kod **po zastosowaniu** w nim zasady CaD:
```python
def divide(a, b):
    return a / b
```
Nazwa funkcji `tomato()` została **zamieniona** na `divide()`, teraz **od razu wiadomo**, że funkcja wykonuje działanie dzielenia.

## Podsumowanie
Zasada **CaD** jest prostą ale **przydatną w pracy zespołowej i nie tylko** zasadą. Dzięki niej, możemy **przyspieszyć pracę nad programem**, a także **ułatwić innym programistom prace z nim**.
