# Dependency Inversion Principle (DIP)

Zasada **dependency inversion principle** czyli po polsku **zasada odwrócenia zależności** lub w skrócie **DIP**, to czwarta z zasad [**SOLID**](index.html). Jej oryginalna uproszczona treść to **"high-level modules should not import anything from low-level modules, both should depend on abstractions"**. Tłumacząc na polski, mówi ona, że **wysokopoziomowe moduły nie powinny zależeć od modułów niskiego poziomu, oba powinny zależeć od abstrakcji**.

## Zalety
**DIP** ma kilka zalet:
- **upraszcza testowanie kodu** - gdy moduły zależą od abstrakcji, można je testować niezależnie od ich implementacji.
- **ułatwia rozszerzanie kodu** - gdy moduły zależą od abstrakcji, można łatwo dodać nowe moduły bez konieczności modyfikowania istniejących modułów.
- **łatwiejsze utrzymanie kodu oraz mniejsze ryzyko popełnienia błędu** - gdy moduły zależą od abstrakcji, zmiany w implementacji jednego modułu nie wpływają na inne moduły.

## Metody Stosowania
Oto kilka wskazówek, jak stosować zasadę **DIP**:
- **używaj interfejsów** - interfejsy to abstrakcje, które definiują kontrakt, który muszą spełniać moduły.
- **używaj zależności konstruktora** - zależności konstruktora to sposób na zapewnienie, że moduły zależą od abstrakcji, a nie od konkretnych implementacji.

## Podsumowanie
Zasada **DIP** to ważna zasada programowania obiektowego, która **pomaga w tworzeniu łatwiejszego w utrzymaniu oraz posiadającego mniejsze prawdopodobieństwo popełnienia błędu kodu**. Zastosowanie jej sprawi, że **istnieje mniejsza szansa, że popełnimy błąd oraz roszerzanie i testowanie kodu będą prostszymi zadaniami**.
