# aai_projekt

Repozytorium to zawiera kod źródłowy projektu zaliczeniowego na przedmiot AAI. Projekt został wykonany zgodnie z następującym planem:

## Faza 1: Wybór zbiorów danych i architektur

- Wybrano trzy proste zbiory danych: Iris Species, IMDB, oraz Boston Housing.
- Wybrano złożony zbiór danych - Chest X-Ray Images - który wymagał wstępnej obróbki.
- Wybrano trzy różne architektury dla każdego z prostych zbiorów danych.

## Faza 2: Implementacja i porównanie wyników

- Zaimplementowano wybrane architektury na prostych zbiorach danych.
- Porównano wyniki, w tym krzywe uczenia, metryki i cross-validacja.
- Opisano model oraz jego skuteczność (overfitting, underfitting, bias, variance).
- Zaimplementowano modele na złożonym zbiorze danych z odpowiednią obróbką.

## Faza 3: Dogłębna analiza działania i skuteczności modeli

- Przeanalizowano wpływ augmentacji w Image Recognition na skuteczność.
- Przeanalizowano wpływ pre-processingu danych Image Recognition na skuteczność.
- Porównano różne typy embedding w NLP i analizowano ich wpływ na skuteczność.
- Porównano wpływ technik takich jak normalizacja danych na skuteczność wyniku.

## Proste zbiory danych i zastosowane architektury

- Zbiór danych Iris Species (klasyfikacja)
  - Model drzewa decyzyjnego
  - Model k-najbliższych sąsiadów
  - Model naiwnego klasyfikatora Bayesa
- Zbiór danych IMDB (klasyfikacja tekstowa)
  - Model regresji logistycznej z zastosowaniem TF-IDF (Term Frequency-Inverse Document Frequency) jako cech
  - Model Naive Bayes
  - Prosty model sieci neuronowej
- Zbiór danych Boston Housing (regresja)
  - Model regresji liniowej
  - Model drzewa decyzyjnego
  - Model lasu losowego

## Złożony zbiór danych

- Zbiór danych Chest X-Ray Images

Zbiór danych składa się z obrazów rentgenowskich płuc, które są klasyfikowane jako "Normalne" lub "Pneumonia". Zadaniem jest zbudować model, który będzie w stanie poprawnie klasyfikować te obrazy. Zaimplementowano dwa modele sieci neuronowej o identycznej architekturze, jednak różniące się sposobem przetwarzania danych wejściowych. Jeden z modeli został wytrenowany na danych bez augmentacji, a drugi na danych po augmentacji. Wyniki działania obu modeli zostały porównane.

## Wymagania zawarte są w pliku requirements.txt
