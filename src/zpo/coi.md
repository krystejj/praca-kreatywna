# Composition Over Inheritance (COI)

Zasada **composition over inheritance** czyli po polsku **kompozycja nad dziedziczeniem** lub w skrócie **COI**, to następna zasada programowania obiektowego. Jej oryginalna treść to **"favor composition over inheritance"**. Tłumacząc na polski, mówi ona, że **powinniśmy preferować kompozycję nad dziedziczeniem**.

## Zalety
**COI** ma kilka zalet:
- **pozwala na implementację polimorfizmu** - gdy klasy są połączone za pomocą kompozycji, można łatwo zaimplementować polimorfizm poprzez przekazywanie obiektów różnych klas do metod.
- **ułatwia modularyzację kodu** - gdy klasy są połączone za pomocą kompozycji, można je łatwo podzielić na moduły, które są niezależne od siebie.
- **sprawia skalowalność kodu prostszą** - gdy klasy są połączone za pomocą kompozycji, można łatwo dodać nowe funkcje lub zadania bez konieczności modyfikacji istniejących klas.

## Metody Stosowania
Oto kilka wskazówek, jak stosować zasadę **COI**:
- **używaj zależności konstruktora** - zależności konstruktora to sposób na zapewnienie, że klasy są połączone za pomocą kompozycji, a nie dziedziczenia.
- **używaj interfejsów** - interfejsy to abstrakcje, które definiują kontrakt, który muszą spełniać klasy.

## Podsumowanie
Zasada **COI** to zasada programowania obiektowego, która **pomaga w tworzeniu bardziej modularnego i skalowalnego kodu**. Stosowanie jej sprawi, żew naszym kodzie **zacznie być możliwy polimorfizm oraz modularyzacja, będzie również łatwiej skalowalny**.
