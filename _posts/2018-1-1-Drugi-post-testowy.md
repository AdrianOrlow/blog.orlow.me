---
layout: post
title: Drugi post testowy
date: 2015-11-17 16:16:01 -0600
permalink: drugi-post
---

[<img src="{{ site.baseurl }}/images/img.jpg" alt="800 x 500"/>]({{ site.baseurl }}/drugi-post)
Ten tekst reprezentuje wstęp zachęcający do przeczytania [artykułu]({{ site.baseurl }}/drugi-post), czyli lead. Ten tekst reprezentuje wstęp zachęcający do przeczytania [artykułu]({{ site.baseurl }}/drugi-post), czyli lead. Ten tekst reprezentuje wstęp zachęcający do przeczytania [artykułu]({{ site.baseurl }}/drugi-post), czyli lead.
<!--more-->

# Podtytuł

##### Lorem ipsum to popularny wypełniacz tekstowy.
  - punktory nie dzialają
  - nie pozdrawiam
# Drugi podtytuł

Ta strona została zbudowana na podstawie Jekyll, a jest hostowana na GitHub. Jej kod został napisany w pełni przez Adriana Orłów.

> A to jest cytat. Tak, cytat. Nic ciekawego, ale nazywa się *Blockquote*

Ten tekst został oryginalnie napisany w języku *znaczników* zwanym **Markdown**. Jekyll tłumaczy go na kod HTML, a przeglądarka interpretuje wraz ze stylami napisanymi w CSS!

### Mniejszy nagłówek

Przykładowe linki:

*   [Nastoletni Programiści](nastoletni.pl) - strona społeczności skupiającej programujących nastolatków
*   [Adrian Orłów](orlow.me) - moja strona osobista
*   [Adrian Orłów Blog](blog.orlow.me) - Blog, na którym się obecnie znajdujesz

<br />
##### Cały kod jest na licencji MIT, co oznacza, że każdy może z niego korzystać jak chce, tylko musi podać oryginalnego autora. Wspaniałe, co nie?
<br />

#### Kalkulator w C++ (brak kolorowania składni, bo optymalizacja):
  
```cpp
#include <iostream>

int main()
{
    char op;
    float num1, num2;

    std::cout << "Wprowadź operator (+, -, *, /):" << std::endl;
    std::cin >> op;

    std::cout << "Wprowadź dwie liczby: ";
    std::cin >> num1 >> num2;

    switch(op)
    {
        case '+':
            cout << num1+num2;
            break;

        case '-':
            cout << num1-num2;
            break;

        case '*':
            cout << num1*num2;
            break;

        case '/':
            cout << num1/num2;
            break;

        default:
            cout << "Bledny operator";
            break;
    }

    return 0;
}
```

### Tak to kod!

A to tabelka (WiP):

| Kolumna I | Kolumna II |
| ------ | ------ |
| Wiersz I | Wiersz I w kolumnie II |
| Wiersz II | Wiersz II w kolumnie II |


# Co jeszcze?
Tak właściwie to nic, już możemy się pożegnać. <br/>
:)