# Regresja i analiza wariancji - PROJEKT

## Temat: Przewidywanie czasu snu na podstawie innych czynników

### Autor:
- **Anna Zembol**
- Politechnika Krakowska

## Opis projektu:

Projekt skupia się na analizie danych dotyczących zdrowia, stylu życia i jakości snu, w celu stworzenia modelu regresji umożliwiającego przewidywanie czasu snu na podstawie różnych czynników. Dane obejmują informacje takie jak wiek, jakość snu, poziom stresu, tętno, wskaźniki BMI oraz obecność zaburzeń snu.

## Struktura projektu:

- **`Sleep_health_and_lifestyle_dataset.csv`**: Plik zawierający dane potrzebne do analizy.
- **`README.md`**: Niniejszy plik z opisem projektu.
- **`analiza_danych.Rmd`**: Skrypt R zawierający analizę danych, przetwarzanie danych, modelowanie regresji, oraz testowanie założeń modelu.
- **`analiza_danych.html`**: Raport w formacie HTML generowany z analizy danych.
- **`analiza_danych.pdf`**: Raport w formacie PDF generowany z analizy danych.

## Koncepcja projektu:

1. **Przygotowanie danych**: Początkowa analiza danych obejmuje wczytanie danych z pliku CSV, podstawowe przetwarzanie danych (usuwanie niepotrzebnych kolumn, dzielenie kolumny ciśnienia krwi na składowe) oraz kodowanie zmiennych kategorycznych.
   
2. **Analiza korelacji**: Sprawdzamy zależności między zmiennymi, generując macierz korelacji oraz wykresy korelacji w celu zidentyfikowania istotnych zmiennych dla modelu.

3. **Podział na zbiory treningowe i testowe**: Dane są podzielone na zbiory treningowe i testowe w celu oceny modelu.

4. **Modelowanie regresji**: Tworzymy modele regresji prostych oraz wielorakich, badając różne zestawy zmiennych objaśniających.

5. **Testowanie założeń modelu**: Sprawdzamy, czy założenia modelu regresji są spełnione, przeprowadzając testy normalności, homoskedastyczności, niezależności reszt itp.

6. **Wartości wpływowe i odległość Cook'a**: Analizujemy wartości wpływowe oraz odległość Cook'a, aby ocenić wpływ poszczególnych obserwacji na model.

## Uwagi:

- Proszę pamiętać, że raport zawiera szczegółową analizę danych, przetwarzanie i testowanie modeli regresji. Każdy krok analizy jest szczegółowo opisany w raporcie w formacie HTML i PDF.

---

W razie pytań lub uwag proszę o kontakt.

*Dziękuję!*
