# Obsah
- [Základní pojmy](#základní-pojmy)
  - [Algoritmus-definice](#algoritmus--definice)
  - [Vlastnosti algoritmu](#vlastnosti-algoritmu)
  - [Způsoby zápisu algoritmů](#zp%C5%AFsoby-z%C3%A1pisu-algoritm%C5%AF)
  - [Flowgorithm](#flowgorithm)
- [Proměnná](#prom%C4%9Bnn%C3%A1)
  - [Jak zapisovat proměnné](#jak-zapisovat-prom%C4%9Bnn%C3%A9)
  - [Datové typy](#datov%C3%A9-typy)
  - [Deklarace a inicializace](#deklarace-a-inicializace)
- [Output/Input](#outputinput)
  - [Output](#output)
  - [Input](#input)
- [Matematické operace](#matematick%C3%A9-operace)
- [Podmínka](#podm%C3%ADnka)
  - [Rozdíl mezi přiřazením a porovnáním](#rozd%C3%ADl-mezi-p%C5%99i%C5%99azen%C3%ADm-a-porovn%C3%A1n%C3%ADm)
  - [Vnořená podmínka](#vno%C5%99en%C3%A1-podm%C3%ADnka)


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


# Proměnná
* Proměnná je hodnota která se v průběhu programu mění a mohou v ní být uloženy různé typy dat.
* Když vytváříme proměnnou musíme uvést její datový typ (druh dat, které můžeme do proměnné uložit) a název
## Jak zapisovat proměnné
* Je jedno jestli anglicky nebo česky
* Pokud budete proměnnou zapisovat česky zapisujte ji bez diakritiky (věk -> vek)
* Pro víceslovné proměnné jsou dvě konvence zápisu CamelCase a snake notace
* Camel case - napíšeme všechna slova dohromady první slovo malé písmenko na začátku a každé další slovo velké písmenko na začátku (jmenoMehoPsa)
* snake notace - mezi všechna slova napíšeme podtržítka (jmeno_meho_psa)
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

# Output/Input
* Po spuštění algoritmu se otevře konzole, vstup a výstup slouží k interakci s touto konzolí 
## Output
* Výstup - slouží pro vypsání do konzole
* Můžeme například vypsat instrukce pro uživatele, to co máme uloženo v proměnné nebo výsledek matematické operace
* Pokud chceme vypsat text musíme ho vložit do uvozovek ("text"), pokud chceme vypsat co je uvnitř proměnné stačí nám k tomu její název (nazevPromenne)

![image](https://github.com/user-attachments/assets/6cc67e21-f00f-401b-9628-4c617bcc5c98)
* ve flowgorithm je to tato značka

## Input
* Vstup (input) - slouží pro získání vstupu od uživatele
* Umožní uživateli odpovídat a interagovat s konzolí
* Při vytváření proměnné je potřeba zadat proměnnou kam budeme vstup od uživatele ukládat

![image](https://github.com/user-attachments/assets/600f77db-ab32-4266-a2dc-4250ef0c04b4)
* ve flowgorithm je to tato značka

# Matematické operace
* Seznam základních matematických operací
  * Sčítání (+) - 10+5=15
  * Odčítání (-) - 10-5=5

  * Násobení (<img src=https://github.com/user-attachments/assets/009f2ae6-7cc9-470a-8441-7f312bddd17b width="20">) - 10<img src=https://github.com/user-attachments/assets/009f2ae6-7cc9-470a-8441-7f312bddd17b width="20">5=50
  * Dělení (/) - 10/5=2
  * Modulo (zbytek po celočíselném dělení)(%) - 10%5=0 , 10%4=2
    * Nejdřív se provede dělení a pak se vypíše zbytek (modulo vrátí pouze zbytek)
  * Mocnina (^) - 10^2=100 (deset na druhou)
  * Odmocnina (sqrt(n)) - sqrt(25)=5
    
> [!NOTE]
> Pokud vám modulo vypíše jako výsledek 0 nutně to neznamená, že tam máte chybu.
> Znamená to že jste dvě čísla mezi sebou vydělili beze zbytku

* Další
  * random(n) - vypíše náhodné číslo od 0 do zadaného čísla n-1, pokud zadáme random(50) nejmenší možné číslo je 0 a největší 49
  * pi - konstanta pro práci s Pí
    
# Podmínka
* Slouží k rozvětvení toku algoritmu
  
  ![image](https://github.com/user-attachments/assets/0e415018-f043-4d1e-b5d3-097b9a64dacf)

* Do těla podmínky je vždy potřeba zapsat nějaký výrok, který lze vyhodnotit jako true nebo false (pravdivý/nepravdivý)
* Podmínka se vyhodnotí a podle výsledku algoritmus pokračuje buď pravou nebo levou větví

![image](https://github.com/user-attachments/assets/db9f8245-1232-42fa-8f12-13576a84258f)


## Rozdíl mezi přiřazením a porovnáním
### Přiřazení
* Pro přiřazení se používá =

![image](https://github.com/user-attachments/assets/f72b2fb0-57c5-410c-90b9-a7626692aa2a)

* Je to vložení určité hodnoty do proměnné

![image](https://github.com/user-attachments/assets/fa5e49d3-63da-4286-a2f5-4069eae935f7)

### Porovnání dvou výrazů
* Pro porovnání se používá ==
* Porovnáváme levou stranu s pravou
* Výsledkem porovnání je hodnota true/false

![image](https://github.com/user-attachments/assets/e4a38da5-3f34-419d-9e6b-4e86153e12b4)

### Matematické porovnání
* Slouží k porovnání dvou čísel
* Větší než - >
* Menší než - <
* Větší nebo rovno - >=
* Menší nebo rovno - <=
* Rovno - ==

## Vnořená podmínka
* Vnořená podmínka znamená že uvnitř podmínky je podmínka další
* Příklad:

![image](https://github.com/user-attachments/assets/9f6155be-9c01-4fef-a35e-252e899c0678)



