# Dokumentowanie Kodu

**Dokumentowanie kodu** to proces opisu kodu źródłowego, który ma na celu **ułatwienie jego zrozumienia i wykorzystania**. Dokumentacja może być przeznaczona dla programistów, użytkowników końcowych, a nawet osób nietechnicznych.

<img style="border: 1px solid rgb(49, 49, 49); border-radius: 20px;" src="imgs/1.png">

## Cele
**Dokumentowanie kodu** ma następujące cele:
- **ułatwienie zrozumienia kodu przez programistów** - dobrze napisana dokumentacja pomaga programistom zrozumieć, jak działa kod, jakie są jego ograniczenia i możliwości. Może również pomóc programistom znaleźć i naprawić błędy w kodzie.
- **ułatwienie utrzymania kodu przez programistów** - dokumentacja kodu pomaga programistom zrozumieć, jak kod został napisany i dlaczego. Powinna pomóc programistom także wprowadzić zmiany w kodzie bez wprowadzania błędów.
- **ułatwienie korzystania z oprogramowania przez użytkowników końcowych** - dobrze napisana dokumentacja może pomóc użytkownikom końcowym zrozumieć, jak korzystać z oprogramowania. Może również pomóc użytkownikom końcowym w rozwiązywaniu problemów z nim.
- **poinformowanie użytkowników końcowych o możliwościach oprogramowania** - dokumentacja kodu może pomóc użytkownikom końcowym zrozumieć, do czego oprogramowanie jest przeznaczone. Pomaga także pomóc użytkownikom końcowym w wykorzystaniu kodu w pełnym zakresie jego możliwości.

## Rodzaje
**Dokumentacja kodu** może być podzielona na następujące rodzaje:
- **wewnętrzna** - przeznaczona dla programistów. Zawiera informacje o strukturze kodu, jego działaniu, a także o potencjalnych problemach.
- **zewnętrzna** - przeznaczona dla użytkowników końcowych. Zawiera informacje o tym, jak korzystać z kodu, a także o jego możliwościach.

## Dobre Praktyki
Dobra **dokumentacja kodu** powinna spełniać następujące cechy:
- **dokładność i bezbłędność** - dokumentacja powinna być zgodna z kodem, a także wolna od błędów.
- **kompletność** - dokumentacja powinna zawierać wszystkie niezbędne informacje.
- **spójność** - dokumentacja powinna być napisana w spójny sposób, zarówno pod względem językowym, jak i wizualnym.
- **klarowność i jednoznaczność** - dokumentacja powinna być napisana w sposób jasny i jednoznaczny, aby każdy mógł ją zrozumieć.
- **łatwość wyszukiwania** - dokumentacja powinna być zorganizowana w sposób, który ułatwia użytkownikowi znalezienie potrzebnych informacji.

## Przykład
Oto przykładowa klasa `BankAccount` napisana w języku **Java**. Klasa ta **zawiera dokumentację** kodu oraz **jest poprawnie opisana**.
```java
/**
 * Klasa reprezentująca rachunek bankowy.
 *
 * @author Jan Kowalski
 * @version 1.0
 */
public class BankAccount {
    // Numer konta bankowego.
    private String accountNumber;

    // Saldo konta bankowego.
    private double balance;

    /**
     * Konstruktor klasy BankAccount.
     * @param accountNumber Numer konta bankowego.
     * @param balance Saldo konta bankowego.
     */
    public BankAccount(String accountNumber, double balance) {
        this.accountNumber = accountNumber;
        this.balance = balance;
    }

    /**
     * Zwraca numer konta bankowego.
     * @return Numer konta bankowego.
     */
    public String getAccountNumber() {
        return accountNumber;
    }

    /**
     * Zwraca saldo konta bankowego.
     * @return Saldo konta bankowego.
     */
    public double getBalance() {
        return balance;
    }

    /**
     * Dokonuje wpłaty na konto bankowe.
     * @param amount Kwota wpłaty.
     */
    public void deposit(double amount) {
        balance += amount;
    }

    /**
     * Dokonuje wypłaty z konta bankowego.
     * @param amount Kwota wypłaty.
     */
    public void withdraw(double amount) {
        balance -= amount;
    }
}
```

Dokumentacja kodu w Javie jest **tworzona za pomocą komentarzy**. Komentarze w Javie mogą być tworzone na dwa sposoby:
1. `// To jest komentarz.`
2. `/* To jest komentarz. */`

W tym przykładzie dokumentacja **zawiera następujące informacje**:
- **nazwa klasy** - `BankAccount`
- **autor** - `Jan Kowalski`
- **wersja** - `1.0`
- **opis ogólny** - klasa reprezentująca rachunek bankowy.
- **opis pól:**
    - `accountNumber` - numer konta bankowego.
    - `balance` - saldo konta bankowego.
- **opis metod:**
    - `getAccountNumber()` - zwraca numer konta bankowego.
    - `getBalance()` - zwraca saldo konta bankowego.
    - `deposit()` - dokonuje wpłaty na konto bankowe.
    - `withdraw()` - dokonuje wypłaty z konta bankowego.

## Podsumowanie
**Dokumentowanie kodu** jest ważną częścią procesu tworzenia oprogramowania. Dobra dokumentacja **ułatwia zrozumienie kodu, jego utrzymanie i wykorzystanie**.
