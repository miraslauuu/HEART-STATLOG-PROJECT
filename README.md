# Heart Disease Prediction Project (Statlog Heart)

**Autor:** Miraslau Alkhovk, 248655, Politechnika Łódzka

## Opis projektu

Celem projektu jest stworzenie modelu klasyfikacji, który na podstawie danych medycznych przewiduje obecność choroby serca. Zbiór danych *Statlog (Heart)* zawiera 270 rekordów z informacjami takimi jak wiek, płeć, typ bólu w klatce piersiowej, ciśnienie krwi, poziom cholesterolu, wyniki EKG, maksymalna częstotliwość akcji serca oraz inne istotne cechy. Zmienna docelowa `presence` określa, czy choroba serca występuje (1 = brak choroby, 2 = choroba).

## Zawartość projektu

- **Kod źródłowy:**  
  Notebook (`heart_statlog.ipynb`) zawierający:
  - Import i eksplorację danych.
  - Czyszczenie oraz analizę statystyczną.
  - Wizualizację zależności między cechami (wykresy korelacji, box ploty, heatmapa).
  - Budowę modeli klasyfikacyjnych:
    - Regresja logistyczna.
    - Drzewo decyzyjne.
  - Oceny modeli (macierze pomyłek, raporty klasyfikacyjne).

## Wymagania

Projekt został zrealizowany w Pythonie. Niezbędne biblioteki:
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`


## Instalacja i uruchomienie

1. **Sklonuj repozytorium:**

   ```bash
   git clone https://github.com/miraslauuu/heart.git
