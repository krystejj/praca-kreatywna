# Zasady Programowania Obiektowego

**Zasady programowania obiektowego** pomagają w tworzeniu efektywnego i utrzymywalnego kodu obiektowego. Zasady te **są oparte na koncepcjach programowania obiektowego**, takich jak **abstrakcja, dziedziczenie, kompozycja i polimorfizm**. Przydają się one zawsze, gdy tworzymy kod obiektowy.

## Cel
Celem zasad programowania obiektowego jest ułatwienie tworzenia kodu, który jest:
- **elastyczny** - można go łatwo rozszerzać i dostosowywać do nowych potrzeb.
- **utrzymywalny** - łatwy do zrozumienia, modyfikowania i testowania.
- **testowalny** - można go łatwo przetestować, aby upewnić się, że działa poprawnie.

## Podstawowe Zasady
Najbardziej kluczowe zasady **programowania obiektowego** to:
- [**SOLID**](solid.md) - zbiór 5 zasad pozwalających na pisanie elastycznijeszego i ławtiejszego w utrzymaniu kodu.
    - [**Single-responsibility principle**](solid/srp.md) - klasa powinna skupiać się na wykonywaniu tylko jednego zadania.
    - [**Open-closed principle**](solid/ocp.md) - kod powinien być zaprojektowany z myślą o możliwości późniejszego łatwego rozszerzania go.
    - [**Liskov substitution principle**](solid/lsp.md) - kod, który działa z typem bazowym, powinien również działać z podtypem.
    - [**Interface segregation principle**](solid/isp.md) - lepiej jest mieć wiele interfejsów specyficznych niż jeden interfejs ogólny.
    - [**Dependency inversion principle**](solid/dip.md) - kod powinien opierać się na abstrakcjach a nie implementacjach.
- [**Law of Demeter**](lod.md) - kod powinien ograniczać dostęp z klas do klas, z którymi nie ma bezpośredniego związku.
- [**Composition over inheritance**](coi.md) - lepiej jest używać kompozycji niż dziedziczenia.

## Podsumowanie
Stosowanie zasad programowania obiektowego **wymaga pewnego wysiłku i czasu**, ale **przyniesie wiele korzyści**. Kod, który jest zgodny z tymi zasadami, **jest bardziej elastyczny, utrzymywalny i testowalny**.
