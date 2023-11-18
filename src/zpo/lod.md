# Law of Demeter (LoD)

Zasada **law of Demeter** czyli po polsku **prawo Demeter** lub w skrócie **LoD**, to zasada programowania obiektowego, która mówi, że **byt (np. klasa) powinien komunikować się tylko z tymi bytami, które są mu bezpośrednio powiązane**.

> Ta zasada została nazwana od nazwy projektu **Demeter Project**, który został tak nazwany na cześć [**Demeter**](https://en.wikipedia.org/wiki/Demeter), greckiej bogini rolnictwa.

## Zalety
**LoD** ma kilka zalet:
- **poprawia możliwości testowania kodu** - gdy byty komunikują się tylko z bytami, które są im bezpośrednio powiązane, można je testować niezależnie od siebie.
- **sprawia, że mniej kodu wymaga modyfikacji przy dodawaniu nowych funkcji** - gdy byty komunikują się tylko z bytami, które są im bezpośrednio powiązane, można łatwo dodać nowe funkcje lub zadania bez konieczności modyfikacji innych bytów.
- **mniejsze prawdopodobieństwo błędu** - gdy byty komunikują się tylko z bytami, które są im bezpośrednio powiązane, zmiany w jednym bycie nie wpływają na inne byty.

## Metody Stosowania
Oto kilka wskazówek, jak stosować zasadę **LoD**:
- **używaj wstrzykiwania zależności** - wstrzykiwanie zależności to technika, która pozwala na przekazanie obiektu do konstruktora lub metody. Wstrzykiwanie zależności może pomóc w zapewnieniu, że klasy komunikują się tylko z obiektami, które są im bezpośrednio powiązane.
- **używaj interfejsów** - interfejsy zapewniają spójne metody dla różnych implementacji. Używanie interfejsów może pomóc w zapewnieniu, że klasy komunikują się tylko z bytami, które są potrzebne.

## Przykłady Zastosowania
Oto kilka przykładów zastosowania **prawa Demetera**:
- zamiast wysyłać wiadomość do obiektu, aby poprosić go o pobranie właściwości innego obiektu, możesz poprosić pierwszy obiekt o podanie Ci odwołania do drugiego obiektu, a następnie **pobrać właściwości samodzielnie**,
- zamiast wysyłać wiadomość do obiektu, aby wykonać operację na innym obiekcie, możesz poprosić pierwszy obiekt o utworzenie drugiego obiektu, a następnie **wykonać operację samodzielnie**,
- zamiast wysyłać wiadomość do obiektu, aby poprosić go o wykonanie złożonej operacji, możesz **podzielić operację na mniejsze kroki** i **wysyłać oddzielne wiadomości** dla każdego kroku.

## Podsumowanie
> Więcej o prawie Demeter na przykładzie **Javy** możesz dowiedzieć się z [artykułu Baeldung](https://www.baeldung.com/java-demeter-law).

Zasada **LoD** to zasada programowania obiektowego, która pomaga w pisaniu kodu, którego działanie jest **bardziej logiczne**. Stosowanie jej sprawi, że np. etapy rozszerzania funkcjonalności i testowania kodu będą **prostsze i szybsze**.
