# Law of Demeter (LoD)

Zasada **law of demeter** czyli po polsku **prawo demeter** lub w skrócie **LoD**, to zasada programowania obiektowego, która mówi, że **byt (np. klasa) powinien komunikować się tylko z tymi bytami, które są mu bezpośrednio powiązane**.

## Zalety
**LoD** ma kilka zalet:
- **poprawia możliwości testowania kodu** - gdy byty komunikują się tylko z bytami, które są im bezpośrednio powiązane, można je testować niezależnie od siebie.
- **sprawia, że mniej kodu wymaga modyfikacji przy dodawaniu nowych funkcji** - gdy byty komunikują się tylko z bytami, które są im bezpośrednio powiązane, można łatwo dodać nowe funkcje lub zadania bez konieczności modyfikacji innych bytów.
- **mniejsze prawdopodobieństwo błędu** - gdy byty komunikują się tylko z bytami, które są im bezpośrednio powiązane, zmiany w jednym bycie nie wpływają na inne byty.

## Metody Stosowania
Oto kilka wskazówek, jak stosować zasadę **LoD**:
- **używaj wstrzykiwania zależności** - wstrzykiwanie zależności to technika, która pozwala na przekazanie obiektu do konstruktora lub metody. Wstrzykiwanie zależności może pomóc w zapewnieniu, że klasy komunikują się tylko z obiektami, które są im bezpośrednio powiązane.
- **używaj interfejsów** - interfejsy zapewniają spójne metody dla różnych implementacji. Używanie interfejsów może pomóc w zapewnieniu, że klasy komunikują się tylko z bytami, które są potrzebne.

## Podsumowanie
Zasada **LoD** to zasada programowania obiektowego, która **pomaga w pisaniu kodu, którego działanie jest bardziej logiczne**. Stosowanie jej sprawi, że np. **etapy rozszerzania funkcjonalności i testowania kodu będą prostsze i szybsze**.
