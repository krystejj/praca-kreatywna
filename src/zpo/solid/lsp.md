# Liskov Substitution Principle (LSP)

Zasada **liskov substitution principle** czyli po polsku **zasada podstawienia Liskov** lub w skrócie **LSP**, to trzecia zasada [**SOLID**](index.html). Wymyślona przez amerykańską informatyczkę [Barbarę Liskov](https://en.wikipedia.org/wiki/Barbara_Liskov) w roku 1987. Jej oryginalna treść to **"if S subtypes T, what holds for T-objects holds for S-objects"**. Tłumacząc na polski, mówi ona, że **jeśli S jest podtypem T, to obiekty typu S mogą być używane wszędzie tam, gdzie oczekiwane są obiekty typu T**.

## Zalety
**LSP** ma kilka zalet:
- **większa użyteczność klas** - gdy podtyp zachowuje się w taki sam sposób jak typ bazowy, można go używać w miejscu typu bazowego, bez konieczności modyfikowania kodu.
- **ułatwia utrzymanie kodu** - gdy podtyp zachowuje się w taki sam sposób jak typ bazowy, zmiany w typie bazowym nie wpływają na podtyp.

## Metody Stosowania
Oto kilka wskazówek, jak stosować zasadę **LSP**:
- **przy tworzeniu podtypów, należy zachować zachowania typu bazowego** - podtyp powinien być w stanie wykonać wszystkie operacje, które może wykonać typ bazowy, w taki sam sposób jak typ bazowy.
- **należy unikać nadpisywania metod typu bazowego** - nadpisanie metody typu bazowego może spowodować, że podtyp nie będzie zachowywał się w taki sam sposób jak typ bazowy.
- **należy unikać dodawania nowych ograniczeń do podtypów** - dodanie nowego ograniczenia do podtypu może spowodować, że podtyp nie będzie mógł być używany w miejscu typu bazowego.

## Podsumowanie
Zasada **LSP** to kolejna ważna zasada programowania obiektowego, która **pomaga w tworzeniu łatwiejszego do utrzymania i łatwiej rozszerzalnego kodu**. Stosowanie jej sprawi, że **utrzymywanie naszego kodu w przyszłości będzie prostsze**.
