# Composition Over Inheritance (COI)

Zasada **composition over inheritance** czyli po polsku **kompozycja nad dziedziczeniem** lub w skrócie **COI**, to następna zasada programowania obiektowego. Jej oryginalna treść to **"favor composition over inheritance"**. Tłumacząc na polski, mówi ona, że **powinniśmy preferować kompozycję nad dziedziczeniem**.

## Zalety
**COI** ma kilka zalet:
- **pozwala na implementację polimorfizmu** - gdy klasy są połączone za pomocą kompozycji, można łatwo zaimplementować polimorfizm poprzez przekazywanie obiektów różnych klas do metod.
- **ułatwia modularyzację kodu** - gdy klasy są połączone za pomocą kompozycji, można je łatwo podzielić na moduły, które są niezależne od siebie.
- **sprawia skalowalność kodu prostszą** - gdy klasy są połączone za pomocą kompozycji, można łatwo dodać nowe funkcje lub zadania bez konieczności modyfikacji istniejących klas.

> Bardziej szczegółowo o tym co to jest **polimorfizm** dowiesz się z [**artykułu Stackify**](https://stackify.com/oop-concept-polymorphism/)

## Metody Stosowania
Oto kilka wskazówek, jak stosować zasadę **COI**:
- **używaj zależności konstruktora** - zależności konstruktora to sposób na zapewnienie, że klasy są połączone za pomocą kompozycji, a nie dziedziczenia.
- **używaj interfejsów** - interfejsy to abstrakcje, które definiują kontrakt, który muszą spełniać klasy.

## Przykład Zastosowania
Przykład zastosowania z zasady [**Dependency Inversion Principle**](solid/dip.md) jest poprawny również dla **Composition Over Inheritance**. Sprawdź [**tamten przykład**](solid/dip.md#przykład-zastosowania).

## Podsumowanie
Oto film [YouTubera CodeAesthetic](https://www.youtube.com/@CodeAesthetic) przedstawiający **problemy z dziedziczeniem**:
<iframe width="560" height="315" style="border: 1px solid rgb(49, 49, 49); border-radius: 20px;" src="https://www.youtube-nocookie.com/embed/hxGOiiR9ZKg?si=jAugFzLJ6kRQ1qMR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Zasada **COI** to zasada programowania obiektowego, która pomaga w tworzeniu bardziej **modularnego i skalowalnego** kodu. Stosowanie jej sprawi, żew naszym kodzie zacznie być możliwy **polimorfizm oraz modularyzacja**, będzie również **łatwiej skalowalny**.
