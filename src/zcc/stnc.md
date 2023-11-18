# Stick To Naming Conventions (STNC)

**Stick to naming conventions** czyli po polsku **trzymaj się konwencji nazewniczych** lub w skrócie **STNC**, to **bardzo prosta i krótka** zasada [**clean code**](index.html). Mówi ona, że powinniśmy **trzymać się konwencji** nazewniczych ustalonych przez twórców danego języka. Oznacza to że nazywając funkcje, klasy i inne elementy kodu, powinniśmy **stosować konwencje nazewnicze języka z którego korzystamy**.

> Konwencje nazewnicze oraz poradniki dotyczące stylu **zawsze znajdziemy w dokumentacji** języka programowania. Przykładowo, dla **Pythona** możemy znaleźć je [tutaj](https://peps.python.org/pep-0008/).

## Zalety
Przykładowymi zaletami stosowania **STNC** są:
- **ułatwia współpracę z innymi programistami** - konwencje nazewnicze pomagają zapewnić, że kod napisany przez różnych programistów jest spójny i łatwy do zrozumienia.
- **zwiększa czytelność kodu** - nazwy, które są zgodne z konwencjami nazewniczymi, są łatwiejsze do zrozumienia, zarówno dla programistów, jak i dla użytkowników końcowych.

## Przykład Zastosowania
Oto **przykładowy kod** napisany w języku **Python**, który prezentuje wyniki zastosowania metody **STNC**.

### Przed Zastosowaniem
Kod **przed zastosowaniem** metody STNC:
```python
My_Name = "adam"

def capitalizeName(Name):
    return Name.capitalize()
```

<div class="warning">
    Ten kod, jest <b>niezgodny z zasadą STNC</b>, ponieważ <b>nie stosuje się</b> do konwencji nazewniczych Pythona.
</div>

### Po Zastosowaniu
Tak natomiast wygląda kod **po zastosowaniu** w nim zasady STNC:
```python
my_name = "adam"

def capitalize_name(name):
    return name.capitalize()
```
Po zastosowaniu metody STNC **zmieniły się nazwy zmiennych i funkcji w kodzie**. Python używa **snake case** do nazewnictwa zmiennych i funkcji, dlatego ta zmiana była wymagana aby była **zgodna z konwencjami**. Zmiana ta **nie zmieniła sposobu działania programu**, lecz poprawiła **czytelność i klarowność** kodu.

## Podsumowanie
Zasada **STNC** to prawdopodobnie **najprostsza** ze wszystkich zasad. Sprawia że pisany przez nas kod będzie **łatwiej zrozumiały** dla innych programistów, co pomaga w współpracy oraz zrozumieniu się nawzajem.
