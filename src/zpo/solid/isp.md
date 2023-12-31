# Interface Segregation Principle (ISP)

Zasada **interface segregation principle** czyli po polsku **zasada segregacji interfejsów** lub w skrócie **ISP**, to czwarta zasada [**SOLID**](index.html). Jej oryginalna treść to **"no code should be forced to depend on methods it does not use"**. Tłumacząc na polski, mówi ona, że **żadna klasa nie powinna być zmuszana do implementacji metod interfejsu, których nie używa**.

## Zalety
**ISP** ma kilka zalet:
- **zwiększa klarowność i porządek kodu** - gdy interfejs jest podzielony na mniejsze, bardziej specyficzne interfejsy, jest łatwiej zrozumieć, co robią i jak działają.
- **pozwala na bardziej dokładne testowanie** - gdy interfejs jest podzielony na mniejsze, bardziej specyficzne interfejsy, łatwiej jest napisać testy, które sprawdzają, czy działa poprawnie.
- **sprawia, że dodawanie nowych funkcjonalności jest prostsze** - gdy interfejs jest podzielony na mniejsze, bardziej specyficzne interfejsy, łatwiej jest dodać nowe funkcje lub zadania bez naruszania istniejącego kodu.

## Metody Stosowania
Oto kilka wskazówek, jak stosować zasadę **ISP**:
- **rozważ, jakie są potrzeby klas implementujących interfejs** - czy klasa potrzebuje wszystkich metod interfejsu? Jeśli nie, rozdziel ten interfejs na dwa mniejsze. Jeden, który zawiera metody, których używa ta konkretna klasa, oraz drugi, który zawiera resztę.
- **zastanów się, czy można podzielić interfejs na mniejsze, bardziej specyficzne interfejsy** - czy można utworzyć osobne interfejsy dla różnych grup klas?

## Przykład Zastosowania
Załóżmy, że mamy klasę `BankAccount` reprezentującą rachunek bankowy. Klasa ta posiada następujące pola i metody:

<img style="border: 1px solid rgb(49, 49, 49); border-radius: 20px;" src="imgs/7.png">

Klasa ta implementuje metody do wykonywania podstawowych operacji na rachunku bankowym, takich jak wpłata, wypłata, sprawdzenie salda oraz historii transakcji.

<div class="warning">
    Ta implementacja <b>narusza zasadę ISP</b>, ponieważ metoda <code>get_transaction_history()</code> nie jest istotna dla wszystkich rachunków bankowych.
</div>

Aby naprawić to naruszenie, możemy **podzielić** klasę `BankAccount` na dwie klasy:

<img style="border: 1px solid rgb(49, 49, 49); border-radius: 20px;" src="imgs/8.png">

Klasa `TransactionAccount` dziedziczy po klasie `BankAccount` i **implementuje** metodę `get_transaction_history()`.

Klasa `SavingAccount` dziedziczy również po klasie `BankAccount`, ale **nie implementuje** metody `get_transaction_history()` tylko `get_interest_rate()`.

W ten sposób klienci, którzy **potrzebują dostępu do historii transakcji**, mogą korzystać z klasy `TransactionAccount`. Za to klienci, którzy **nie potrzebują dostępu do historii transakcji**, mogą korzystać z klasy `SavingAccount`.

## Podsumowanie
Zasada **ISP** to następna znacząca zasada programowania obiektowego, która **pomaga w tworzeniu bardziej uporządkowanego i prostszego w rozszerzaniu kodu**. Stosowanie jej sprawi, że **rozszerzanie, testowanie oraz interpretowanie naszego kodu będzie dużo prostsze**.
