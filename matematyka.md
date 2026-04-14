# Matematyka

Zbiorczy sylabus przedmiotów matematycznych na kierunku informatycznym. Obejmuje: wstęp do matematyki i informatyki, algebrę liniową, analizę matematyczną, matematykę dyskretną oraz rachunek prawdopodobieństwa i statystykę.

---

## Spis treści

1. [Wstęp do matematyki i informatyki](#wstęp-do-matematyki-i-informatyki)
2. [Algebra liniowa](#algebra-liniowa)
3. [Analiza matematyczna](#analiza-matematyczna)
4. [Matematyka dyskretna](#matematyka-dyskretna)
5. [Rachunek prawdopodobieństwa](#rachunek-prawdopodobieństwa)
6. [Statystyka](#statystyka)

---

## Wstęp do matematyki i informatyki

Celem przedmiotu jest wprowadzenie podstawowych pojęć z matematyki oraz informatyki niezbędnych każdemu programiście. Język wspólny informatyków/matematyków.

### Tematyka kursu:

- **Indukcja matematyczna**

- **Logika**
  - Podstawowe operatory: `and`, `or`, `not` razem z naturalnym zastosowaniem
  - Rachunek zdań
  - Kwantyfikatory
  - Opcjonalnie rachunek predykatów

- **Funkcje**
  - Typy i własności

- **Zbiory**
  - Operacje na zbiorach
  - Liczebność zbioru (skończony, przeliczalny, nieprzeliczalny)

- **Relacje**
  - Relacje równoważności i konstrukcje ilorazowe

- **Porządki**
  - Częściowe, liniowe
  - Zbiory dobrze uporządkowane (związek z indukcją)

---

## Algebra liniowa

Kurs koncentruje się na dwóch głównych tematach: wektorach i macierzach. Nadrzędnymi celami są:

0. Dążymy do przedstawienia metod uczenia maszynowego np. regresja liniowa, SVM, … etc.
1. Jeśli chodzi o Algebrę I: geometryczne intuicje
2. Algorytmy ML, rozwiązywanie układów równań, predykcja liniowa

### Algebra liniowa 1

#### Tematyka kursu:

- **Wektory w przestrzeniach Euklidesowych $` \mathbb{R}^d `$**
  - Działania na wektorach
  - Intuicje geometryczne w tym proste, płaszczyzny, rzutowania itd.
  - Iloczyn skalarny, prostopadłość + rzuty
  - Liniowa niezależność, bazy, układ współrzędnych
  - Wypukłość
  - *Opcjonalnie* Iloczyn wektorowy + nieformalnie pojęcie orientacji

### Algebra liniowa 2

- **Macierze**
  - Pojęcie macierzy, spojrzenie na macierze przez pryzmat przekształceń liniowych (zależność Analiza matematyczna II: macierz Jakobiego)
  - Działania na macierzach
  - Eliminacja Gaussa + elementarne macierze
  - Wyznacznik macierzy oraz jej rząd, interpretacja wyznacznika (objętość równoległościanu)
  - Macierz odwrotna (+ po co np. rozwiązywanie równań)
  - Układy równań liniowych
  - Zastosowanie macierzy w uczeniu maszynowym

- **Tematy dla grupy gwiazdkowej**
  - Wprowadzenie do pojęcia tensorów i ich zastosowań (w grupie gwiazdkowej możliwe zadanie projektowe z tensorów np. w PyTorch)
  - Programowanie kwantowe + macierze unitarne + pojęcie kubitu

---

## Analiza matematyczna

### Analiza matematyczna 1

Proponuje się rozłożenie poniższego programu na dwa semestry, aby lepiej zorganizować materiał.

#### Tematyka kursu:

- **Systemy liczbowe $` \mathbb{Q}, \mathbb{R}, \mathbb{C} `$ i podstawowe nierówności\***

- **Ciągi wektorowe i liczbowe**
  - Granica; punkt skupienia; granice dolna i górna
  - Granice niewłaściwe
  - Granice ciągów zadanych rekurencyjnie
  - Asymptotyka i notacja Bachmana-Landaua z przykładami

- **Szeregi liczbowe**
  - Warunek konieczny
  - Sumy częściowe, szeregi arytmetyczny, geometryczny, harmoniczny
  - Kryteria zbieżności

- **Granica i ciągłość funkcji**
  - Definicje Cauchy'ego i Heinego
  - Własność Darboux
  - Twierdzenie Weierstrassa o osiąganiu kresów przez funkcję ciągłą
  - Granice niewłaściwe
  - Ciągłość w punkcie i ciągłość jednostajna

- **Ciągi i szeregi funkcyjne**
  - Ciągi funkcji i rodzaje zbieżności (punktowa, jednostajna)
  - Szeregi potęgowe, promień zbieżności
  - Szeregi trygonometryczne\*
  - Rodziny wielomianów ortogonalnych\*

- **Pochodna**
  - Interpretacja geometryczna i fizyczna
  - Twierdzenia o pochodnych
  - Symbole nieoznaczone; reguła de l'Hospitala
  - Twierdzenie Rolle'a; twierdzenie Lagrange'a
  - Monotoniczność
  - Ekstrema
  - Pochodne wyższych rzędów
  - Wzór Taylora
  - Wypukłość
  - Badanie przebiegu zmienności funkcji
  - Interpretacje fizyczne\*

- **Pierwotna (całka nieoznaczona)**
  - Metody całkowania

- **Całka Riemanna funkcji jednej zmiennej – podejście geometryczne**
  - Interpretacja geometryczna; funkcje całkowalne w sensie Riemanna
  - Podstawowe twierdzenie rachunku różniczkowego i całkowego (Newtona-Leibniza)
  - Twierdzenie o zmianie zmiennych w całce Riemanna
  - Długość krzywej
  - Obliczanie pól powierzchni i objętości brył obrotowych
  - Interpretacje fizyczne\*

### Analiza matematyczna 2

- **Funkcje wielu zmiennych**
  - Granice i ciągłość funkcji wielu zmiennych
  - Różniczkowanie funkcji wielu zmiennych: pochodna Frécheta, pochodna kierunkowa, pochodne cząstkowe
  - Gradient funkcji, ekstrema funkcji wielu zmiennych
  - Funkcje wypukłe
  - Macierz Jacobiego (zależne od Algebra II: omówienie macierzy jako funkcji liniowych)
  - Ekstrema warunkowe, metoda współczynników nieoznaczonych
  - Zastosowania: oszacowania błędów rachunkowych, metoda najmniejszych kwadratów, metoda najszybszego spadku
  - Interpretacje fizyczne\*

- **Rachunek całkowy funkcji wielu zmiennych**
  - Całki podwójne, potrójne i wielokrotne — Tw. Fubiniego i całki iterowane
  - Całki krzywoliniowe i powierzchniowe
  - Wzory Greena, Gaussa-Ostrogradskiego i Stokes'a
  - Interpretacje fizyczne\*

Ten program ma na celu zapewnienie solidnych podstaw w analizie matematycznej, niezbędnych dla dalszej nauki w dziedzinie matematyki i informatyki.

---

## Matematyka dyskretna

Kurs „Matematyka Dyskretna" ma na celu wprowadzenie studentów w kluczowe koncepcje matematyki dyskretnej, które są niezbędne w informatyce i algorytmice.

### Tematyka kursu:

1. **Rekurencja**
   - Rekurencja i równania rekurencyjne
   - Dowodzenie poprawności rekurencji

2. **Kombinatoryka**
   - Podstawowe pojęcia kombinatoryki: wariacje, permutacje, rozbicia

3. **Asymptotyka i złożoność algorytmu**
   - Notacja asymptotyczna
   - Twierdzenie o rekursji uniwersalnej

4. **Drzewa binarne**
   - Struktura i operacje na drzewach binarnych
   - Zastosowania drzew binarnych w algorytmice (problemy łatwo rozwiązywalne przez rekurencję)

5. **Teoria grafów**
   - Podstawowe pojęcia teorii grafów: wierzchołki, krawędzie, ścieżki, cykle, kliki, spójność
   - Problemy Eulera, Hamiltona
   - Kolorowanie

### Cele edukacyjne:

- Zrozumienie podstawowych koncepcji rekurencji oraz umiejętność rozwiązywania równań rekurencyjnych.
- Nabycie umiejętności w zakresie kombinatoryki oraz interpretacji kombinatorycznych.
- Zrozumienie pojęcia asymptotyki oraz umiejętność analizy złożoności algorytmów.
- Umiejętność pracy z drzewami binarnymi oraz ich zastosowań w praktyce.
- Zrozumienie podstaw teorii grafów oraz rozwiązywania problemów związanych z grafami.

Kurs ten ma na celu przygotowanie studentów do dalszej nauki w dziedzinie informatyki, zwłaszcza w kontekście algorytmiki i analizy danych.

---

## Rachunek prawdopodobieństwa

Sekcja obejmuje formalne podstawy teorii prawdopodobieństwa — od aparatu pojęciowego (σ-ciała, miary) przez zmienne losowe i ich charakterystyki, aż po elementy procesów stochastycznych.

### Tematyka kursu:

1. **Podstawy teorii miary**
   - σ-ciała (σ-algebry zbiorów) — definicja, przykłady, σ-ciało generowane przez rodzinę zbiorów
   - Miara i przestrzeń mierzalna
   - Miara probabilistyczna jako szczególny przypadek miary

2. **Doświadczenie losowe i przestrzeń probabilistyczna**
   - Przestrzeń zdarzeń elementarnych, zdarzenia losowe
   - Aksjomaty teorii prawdopodobieństwa (aksjomaty Kołmogorowa)
   - Własności prawdopodobieństwa (monotoniczność, ciągłość, nierówność Boole'a)
   - Klasyczna definicja prawdopodobieństwa (model Laplace'a)

3. **Prawdopodobieństwo warunkowe i niezależność**
   - Prawdopodobieństwo warunkowe — definicja i własności
   - Wzór na prawdopodobieństwo całkowite
   - Wzór Bayesa
   - Niezależność zdarzeń
   - Niezależność doświadczeń losowych
   - Schemat Bernoulliego

4. **Zmienne losowe**
   - Definicja zmiennej losowej jako funkcji mierzalnej
   - Rozkład zmiennej losowej — dyskretny i ciągły
   - Dystrybuanta — definicja, własności, interpretacja
   - Funkcja gęstości prawdopodobieństwa (dla rozkładów ciągłych)
   - Funkcja masy prawdopodobieństwa (dla rozkładów dyskretnych)
   - Przykłady rozkładów: dwumianowy, Poissona, jednostajny, wykładniczy, normalny

5. **Charakterystyki liczbowe zmiennych losowych**
   - Wartość oczekiwana — definicja, własności, interpretacja
   - Wariancja i odchylenie standardowe
   - Momenty wyższych rzędów
   - Kowariancja i współczynnik korelacji

6. **Elementy teorii procesów stochastycznych**
   - Definicja procesu stochastycznego
   - Procesy o przyrostach niezależnych
   - Procesy stacjonarne
   - Podstawowe charakterystyki procesów stochastycznych (funkcja średnia, funkcja korelacji)

---

## Statystyka

Sekcja poświęcona jest metodom opisu danych oraz wnioskowaniu statystycznemu, opierającym się na pojęciach wprowadzonych w rachunku prawdopodobieństwa.

### Tematyka kursu:

1. **Statystyka opisowa**
   - Rodzaje danych i skal pomiarowych
   - Miary tendencji centralnej: średnia arytmetyczna, mediana, dominanta (moda)
   - Miary rozproszenia: wariancja, odchylenie standardowe, rozstęp, odchylenie ćwiartkowe
   - Wizualizacja danych: histogramy, wykresy pudełkowe, wykresy rozrzutu

2. **Wnioskowanie statystyczne**
   - Pojęcie próby losowej i populacji
   - Estymacja punktowa i przedziałowa
   - Estymacja wartości oczekiwanej — estymatory, obciążenie, efektywność
   - Testowanie hipotez statystycznych — pojęcia podstawowe (hipoteza zerowa i alternatywna, poziom istotności, p-wartość)
   - Testowanie hipotez o wartości oczekiwanej (test t-Studenta, test z)
