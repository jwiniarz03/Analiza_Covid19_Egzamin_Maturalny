# Analiza_Covid19_Egzamin_Maturalny

Autor: Julia Winiarz
Data: 03.01.2024

Projekt powstał na zaliczenie zajęć "Statystyka I z R"


## Opis projektu

Celem projektu jest analiza wpływu pandemii COVID-19 na egzaminy maturalne w Polsce. Praca porównuje dane z lat 2015–2023, przyglądając się między innymi liczbie osób przystępujących do egzaminów, zdawalności oraz średnim wynikom egzaminów. Szczególna uwaga została poświęcona okresowi pandemii oraz reformom wprowadzonym w edukacji (np. nauczaniu zdalnemu, zmianom w formule egzaminu).

Projekt odpowiada na pytania:

Czy nauczanie zdalne wpłynęło negatywnie na wyniki egzaminów?
Jak zmieniała się liczba przystępujących do matury w czasie?
Czy pandemia pogłębiła różnice płciowe w zdawalności?


## Wykorzystane narzędzia

- R – język programowania do analizy danych
- RMarkdown – do prezentacji wyników w formie raportu
- Pakiety:
  - readxl – do importu danych z plików Excel
  - dplyr, ggplot2 – do przetwarzania i wizualizacji danych
  - plotly, DT, kableExtra – do interaktywnych wykresów i tabel


## Przykładowe wyniki

- Każdego roku więcej kobiet niż mężczyzn przystępuje i zdaje maturę.
- W czasie pandemii obniżono wymagania egzaminacyjne, co może mieć wpływ na dalsze losy edukacyjne młodzieży.
- Wyniki matur z matematyki i języka polskiego pozostają relatywnie stabilne, natomiast angielski wykazuje lekki wzrost.


## Uwaga dotycząca danych

Repozytorium zawiera kompletny kod analityczny oraz wygenerowane raporty podsumowujące. Analiza została przeprowadzona na podstawie historycznych, publicznie dostępnych raportów Centralnej Komisji Egzaminacyjnej (CKE) z lat 2015–2023, obejmujących m.in. płeć oraz liczbę zdających.

Ze względu na specyfikę i archiwizację oryginalnych raportów źródłowych, repozytorium pełni funkcję statycznego portfolio analitycznego (snapshot). Prezentuje ono pełen proces myślowy: od manipulacji i przygotowania danych (data wrangling), przez wizualizację (ggplot2, plotly), aż po wnioski końcowe wygenerowane w formacie RMarkdown.


## Licencja
Projekt ma charakter edukacyjny i niekomercyjny. Dane pochodzą z publicznych źródeł (np. CKE) i zostały przetworzone jedynie na potrzeby analizy.
