# Predykcja obrotów: porównanie modeli ML i własnego modelu liniowego w KNIME
Projekt analizy danych skoncentrowany na budowie oraz porównaniu modeli predykcyjnych z wykorzystaniem narzędzi uczenia maszynowego i modelowania liniowego. Analiza została wykonana w środowisku **KNIME**, na podstawie rzeczywistych danych dotyczących dziennego obrotu handlowego. Projekt obejmuje zarówno tworzenie modeli ML, jak i konstrukcję własnego modelu liniowego na podstawie rozpoznanych wzorców czasowych i rynkowych.

## Zakres projektu

- Przygotowanie i eksploracyjna analiza danych (zmienne czasowe, liczba konkurencji, obrót)
- Wykrycie wzorców sezonowych i dziennych wpływających na obrót
- Analiza wpływu liczby konkurencji na zmienność wartości predykcyjnej
- Wygładzanie danych poprzez obliczanie bonusów czasowych i rynkowych (dziennych, miesięcznych, konkurencyjnych)
- Budowa własnego modelu liniowego z wykorzystaniem zidentyfikowanych wzorców
- Stworzenie i trening trzech modeli ML:
  - Simple Regression Tree  
  - Gradient Boosted Trees  
  - Random Forest  
- Ocena skuteczności każdego modelu z użyciem statystyk błędu względnego
- Porównanie dokładności oraz interpretowalności modeli
- Wizualizacja wyników i wnioski końcowe

## Narzędzia

- [KNIME](https://www.knime.com/) – analiza danych, modelowanie i wizualizacje
