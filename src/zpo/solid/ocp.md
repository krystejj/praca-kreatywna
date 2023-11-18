# Open-Closed Principle (OCP)

Zasada **open-closed principle** czyli po polsku **zasada otwarte-zamknięte** lub w skrócie **OCP**, to druga zasada [**SOLID**](index.html). Jej oryginalna treść to **"software entities should be open for extension, but closed for modification"**. Tłumacząc na polski, mówi ona, że każdy element kodu **(klasa, metoda, itd.)** powinien być **otwarty na rozszerzenie**, ale **zamknięty na modyfikację**.

## Zalety
**OCP** ma kilka zalet:
- **większa rozszerzalność kodu** - gdy klasa jest otwarta na rozszerzenie, można dodać nowe funkcje lub zadania bez naruszania istniejącego kodu.
- **ułatwia utrzymanie kodu i zapobiega występywaniu błędów** - gdy klasa jest zamknięta na modyfikację, zmiany są ograniczone do nowych rozszerzeń, co ułatwia utrzymanie kodu i zapobiega błędom.
- **upraszcza etap testowania kodu** - gdy klasa jest otwarta na rozszerzenie, można napisać testy dla nowych rozszerzeń, co pomaga zapewnić ich poprawne działanie.

## Metody Stosowania
Oto kilka wskazówek, jak stosować zasadę **OCP**:
- **używaj dziedziczenia** - dziedziczenie pozwala na dodanie nowych funkcji lub zadań do istniejącej klasy bez modyfikowania tej klasy.
- **używaj interfejsów** - interfejsy pozwalają na dodanie nowych funkcji lub zadań do istniejącej klasy bez modyfikowania jej.
- **używaj abstrakcji** - abstrakcja pozwala na ukrycie szczegółów implementacji, co ułatwia rozszerzanie kodu.

## Podsumowanie
Zasada **OCP** to również ważna zasada programowania obiektowego, która **pomaga w tworzeniu łatwiej rozszerzalnego kodu, w którym będzie mniejsze prawdopodobieństwo wystąpienia problemów**. Stosowanie jej sprawi, że **późniejsze wzbogacanie o nowe funkcje i testowanie naszego kodu będzie dużo prostsze**.
