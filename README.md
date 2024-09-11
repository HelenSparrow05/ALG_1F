# AAP_1B_2024
# Obsah
- [Základní pojmy](#základní-pojmy)
  - [Algoritmus-definice](#algoritmus--definice)
  - [Vlastnosti algoritmu](#vlastnosti-algoritmu)
  - [Způsoby zápisu algoritmů](#zp%C5%AFsoby-z%C3%A1pisu-algoritm%C5%AF)
  - [Flowgorithm](#flowgorithm)
- [Proměnná](#prom%C4%9Bnn%C3%A9)
  - [Datové typy](#datov%C3%A9-typy)
  - [Deklarace a inicializace](#deklarace-a-inicializace)

# Základní pojmy
## Algoritmus – definice
* Algoritmus je přesně definovaná posloupnost kroků nebo procedur, které řeší určitý 
problém nebo vypočítávají určitý výsledek

## Vlastnosti algoritmu
* Konečnost - Algoritmus musí být konečný, což znamená, že musí se dát dokončit v konečném počtu kroků
* Vstup - Algoritmus musí přijmout nějaký vstup.
* Výstup - Algoritmus musí poskytnout nějaký výstup
* Přesnost - Algoritmus musí být přesný a dobře definovaný, aby každý, kdo ho používá, mohl dosáhnout stejného výsledku.
* Škálovatelný - obecný zápis, použití na více problémů, snadné rozšíření
## Způsoby zápisu algoritmů
* Vývojový diagram
  * Je grafický způsob zápisu algoritmu, kde jsou jednotlivé kroky reprezentovány 
různými symboly jako například příkazy, rozhodování a podmínky
  * Tyto symboly jsou propojeny šipkami, které ukazují, jak jsou jednotlivé kroky 
propojeny
<img src="https://github.com/user-attachments/assets/db127c42-8fe7-4853-b4d4-f39888df4b74" width="500">

* Pseudokód
  * Je způsob zápisu algoritmu, který používá běžné jazykové konstrukce a syntaxi, 
ale bez nutnosti dodržovat přesná pravidla konkrétního programovacího 
jazyka
  * Pseudokód umožňuje programátorovi zapsat algoritmus v podobě, kterou lze 
snadno pochopit a převést na zdrojový kód v konkrétním jazyce

![image](https://github.com/user-attachments/assets/d2d120ba-786f-482e-bf0d-4d37259fadd3)

## Flowgorithm
<img src="https://github.com/user-attachments/assets/d079b3cf-4383-447a-9016-22b04693875b" width="150" height="150">

Program na tvorbu vývojových diagramů.


[Odkaz na stažení programu](http://www.flowgorithm.org/download/index.html)

Na stránkách mají vypracovanou dokumentaci pro práci s programem.

[Dokumentace](http://www.flowgorithm.org/documentation/index.html)

### Přidávání schématických značek
Pro přidání schématické značky stačí rozkliknout šipku mezi počátečním a konečným nodem.
![image](https://github.com/user-attachments/assets/875d0bb0-8cc2-49b3-9b79-dd12f2532788)

Pro zapsání do schématické značky stačí dvakrát na ni kliknout.

### Ovládací menu

![image](https://github.com/user-attachments/assets/838f03ec-26f7-403c-90da-2c733ff687a1)


![image](https://github.com/user-attachments/assets/4f55c191-3bfb-4a03-8769-d4ca39734f5e)  Slouží pro otevření uložených vývojových diagramů. Lze otevřít soubory s koncovkou .fprg.

![image](https://github.com/user-attachments/assets/c5b38d47-7fde-4461-ad90-18f16c7a43b3) Pro ukládání souborů.

![image](https://github.com/user-attachments/assets/2d12e460-9056-4cc9-94c6-0ba56effce8e) Spouští konzoli a algoritmus.

![image](https://github.com/user-attachments/assets/0687a1d9-0578-4c04-8ac9-168494523a25) Umožňuje procházet algoritmem po jednotlivých krocích.

![image](https://github.com/user-attachments/assets/e533f88c-928c-4422-a801-0073f4d7e512) Zastaví průchod algoritmem na aktuálním kroku. Je možno znovu spustit od kroku kde se zastavil.

![image](https://github.com/user-attachments/assets/0a2aa6c6-73ae-4230-bf1a-b634c1388862) Ukončí průchod a při příším spuštění začne od znovu.


![image](https://github.com/user-attachments/assets/b0f8da45-d97d-42b8-b873-bfef553dff41)

Mění tempo přehrávání algoritmu.

> [!TIP]
> Pokud porgram spustíte a dlouho trvá provádění jednotlivých kroků, není to pomalým počítačem ale je to tohle tlačítko. Stačí přepnout zpátky na plnou rychlost.
> 
> ![image](https://github.com/user-attachments/assets/bfd8bcf6-2388-4203-98cd-09c34fa7c183)


# Proměnné
* Proměnná je hodnota která se v průběhu programu mění a mohou v ní být uloženy různé typy dat.
* Když vytváříme proměnnou musíme uvést její datový typ (druh dat, které můžeme do proměnné uložit) a název
## Datové typy
* Typ nebo rozsah hodnot kterých může proměnná nabývat
* Druhy
  * Integer (int) – Celé číslo – 1, 2, 8, -5
  * String – Textový řetězec – „Hello world“
  * Real – Reálné číslo (záporná, kladná, desetinná) – 3, 4, -5, 3.5, -2.1
  * Boolean – hodnota pravda/nepravda – true/false
## Deklarace a inicializace
### Deklarace
* Každou proměnnou je před jejím použitím potřeba deklarovat
* Deklarování vlastně říká programu, že chceme vytvořit proměnnou s určitým jménem a můžeme do ní vložit určitý typ dat
* Pro deklaraci proměnné musíme zapsat datový typ a název
> [!NOTE]
> Používejte názvy proměnných tak abyste dokázali rozeznat co je v ní uloženo. proměnná a, b není dobrý název
* Příklad zápisu: String name;

![image](https://github.com/user-attachments/assets/91e06013-b3d0-440b-9397-0335aefd3991)

Ve Flowgorithm je to tato značka.
Po rozkiknutí vás vyzve k zadání názvu a datového typu.

![image](https://github.com/user-attachments/assets/f35102ba-c06a-4bd3-89c8-8303794e3a1c)

### Inicializace
* Přiřazení konkrétní hodnoty do proměnné
* Příklad: name = Helena;
* Hodnotu máme již deklarovanou z předchzího kroku a zde jsme jen přiřadili hodnotu
 
![image](https://github.com/user-attachments/assets/f154a20b-9e7c-41bc-98c6-d3af333b134a)

Ve Flowgorithm je to tato značka.


