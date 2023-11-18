# Algorytmy Sortujące

**Algorytmy sortujące** to [algorytmy](../index.html), które służą do **uporządkowania elementów zbioru danych**. Ogólnie rzecz biorąc, sortowanie polega na przestawianiu elementów zbioru w taki sposób, aby **spełniały one ustalony porządek**.

## Podział
Istnieje wiele różnych **algorytmów sortujących**. Można je podzielić na kilka kategorii, w zależności od ich właściwości:
- **złożoność czasowa** - można podzielić je na algorytmy o czasie pracy liniowym, kwadratowym, logarytmicznym itd.
- **złożoność pamięciowa** - można podzielić je ze względu na ilość pamięci jaką algorytm potrzebuje wykonania zadania.
- **wymagania pamięciowe** - można podzielić je na algorytmy działające w miejscu (in-place) i algorytmy działające w miejscu dodatkowym (out-of-place). Algorytm działający w miejscu nie wymaga dodatkowej pamięci poza pamięcią wymaganą do przechowywania danych wejściowych.
- **stabilność** - podział na algorytmy stabilne i niestabilne. Algorytm stabilny zachowuje kolejność elementów o równej wartości.

## Wybór
Wybór **algorytmu sortującego** zależy od wielu czynników, w tym od:
- **rozmiaru zbioru danych** - algorytmy o czasie pracy liniowym są najszybsze dla małych zbiorów danych, natomiast algorytmy o czasie pracy kwadratowym są najszybsze dla dużych zbiorów danych.
- **stabilności** - jeśli kolejność elementów o równej wartości jest ważna, należy wybrać algorytm stabilny.
- **wymagań pamięciowych** - jeśli wymagana jest mała ilość pamięci, należy wybrać algorytm działający w miejscu.

## Przykłady
Do najbardziej podstawowych **algorytmów sortujących** należą:
- [**bąbelkowe**](bab.md) - porównuje kolejne elementy zbioru i zamienia je miejscami, jeśli są w niewłaściwej kolejności.
- [**przez wstawianie**](pws.md) - polega na dodawaniu kolejnych elementów do już posortowanego zbioru.
- [**przez wybór**](pwy.md) - polega na wyszukiwaniu najmniejszego elementu w zbiorze i umieszczaniu go na początku zbioru.
- [**stogowe**](stog.md) - polega na przekształceniu zbioru danych w stóg, a następnie usuwaniu elementów stogu w kolejności rosnącej.

## Podsumowanie
**Algorytmy sortujące** są ważnymi narzędziami stosowanymi w wielu dziedzinach informatyki. Istnieje **wiele różnych algorytmów sortujących**, które różnią się pod względem **czasu pracy, stabilności i wymagań pamięciowych**. Dobór odpowiedniego algorytmu sortującego **zależy od wielu czynników**.
