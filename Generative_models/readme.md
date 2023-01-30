# Modele generatywne

Tym razem zadanie będzie polegało na stworzeniu modelu generatywnego który generował będzie nowe obrazki przedstawiające znaki drogowe. Do wyboru mają Państwo dowolny model generatywny (VAE, GAN inne opcje o których nie wspominaliśmy jak GLOW czy VAEGAN). Zbiór danych udestępniony jest przez office 365 (trafic_32.zip) i ma taką samą strukturę jak poprzednio (zgodną z domyślnymi ustawieniami ImageFolderu). Znaki podzielone są na klasy, które jak najbardziej mogą Państwo wykorzystywać do generowania próbek. Tym razem zamiast predykcji proszę o zwrócenie mi kodu z implementacją eksperymentów i przykładowe 1000 wygenerowanych za pomocą Państwa metody próbek.

Ewaluacja:

- Wygenerowane obrazki porównywał będę do zbioru testowego za pomocą metryki Frechet Inception Distance o której wspominałem na ćwiczeniach. Jeżeli chcieliby Państwo z niej skorzystać do ewaluacji swoich modeli, to odsyłam do repozytorium z wygodną implementacją: https://github.com/mseitzer/pytorch-fid
- W zbiorze testowym obrazki mają ten sam rozkład klas co w treningowym
- Proszę pamiętać o denormalizacji próbek :)
