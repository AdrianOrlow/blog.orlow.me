---
layout: post
title: Drugi post testowy
---

[<img src="{{ site.baseurl }}/images/img.jpg" alt="800 x 500"/>]({{ site.baseurl }}/2018-1-1-Drugi-post-testowy.md)
Ten tekst reprezentuje wstęp zachęcający do przeczytania [artykułu]({{ site.baseurl }}/2018-1-1-Drugi-post-testowy.md), czyli lead. Ten tekst reprezentuje wstęp zachęcający do przeczytania [artykułu]({{ site.baseurl }}/2018-1-1-Drugi-post-testowy.md), czyli lead. Ten tekst reprezentuje wstęp zachęcający do przeczytania [artykułu]({{ site.baseurl }}/2018-1-1-Drugi-post-testowy.md), czyli lead.




# Podtytuł

##### Lorem ipsum to popularny wypełniacz tekstowy.
  - punktor okrągły (WiP)
  - drugi punkt
  - i trzeci

# Drugi podtytuł

Ta strona została zbudowana na podstawie Jekyll, a jest hostowana na GitHub. Jej kod został napisany w pełni przez Adriana Orłów.

> A to jest cytat. Tak, cytat. Nic ciekawego, ale nazywa się *Blockquote*

Ten tekst został oryginalnie napisany w języku *znaczników* zwanym **Markdown**. Jekyll tłumaczy go na kod HTML, a przeglądarka interpretuje wraz ze stylami napisanymi w CSS!

### Mniejszy nagłówek

Przykładowe linki:

*   [Nastoletni Programiści](nastoletni.pl) - strona społeczności skupiającej programujących nastolatków
*   [Adrian Orłów](orlow.me) - moja strona osobista
*   [Adrian Orłów Blog](blog.orlow.me) - Blog, na którym się obecnie znajdujesz </br>

##### Cały kod jest na licencji MIT, co oznacza, że każdy może z niego korzystać jak chce, tylko musi podać oryginalnego autora. Wspaniałe, co nie?

#### Kalkulator w C++ (kolorowanie składni WiP):
  
```cpp
#include <cstdlib>
#include <iostream>

int main()
{
    char op;
    int a,b,wynik;
    do {
    std::cin >> op;
    std::cin >> a >> b;
    switch(op) {
        case '+':
            wynik = a+b;
            break;

        case '-':
            wynik = a-b;
            break;

        case '*':
            wynik = a*b;
            break;

        case '/':
            wynik = a/b;
            break;

        case '%':
            wynik = a%b;
            break;
        default:
                return 0;
        }
        std::cout << wynik;
    }while (std::cin>> op >> a >> b) ;
}

```

### Tak to kod!

A to tabelka (WiP):

| Kolumna I | Kolumna II |
| ------ | ------ |
| Wiersz I | Wiersz I w kolumnie II |
| Wiersz II | Wiersz II w kolumnie II |


# Co jeszcze?
Tak właściwie to nic, już możemy się pożegnać.
