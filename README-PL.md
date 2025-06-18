# Filmweb Movie Analysis

Projekt skupia się na analizie 500 najlepszych filmów według rankingu serwisu **[Filmweb](https://www.filmweb.pl/)**, jednego z najpopularniejszych polskich portali filmowych. Dane zostały pozyskane samodzielnie poprzez web scraping, co umożliwiło szczegółowe zbadanie różnych cech filmów, ich gatunków, ocen oraz informacji o produkcji. Celem analizy jest wyłonienie interesujących zależności i wniosków na podstawie tej starannie dobranej kolekcji filmów.

🇬🇧 English version of the document can be found [here](/README.md) / Angielską wersję dokumentu można znaleźć [tutaj](/README.md). 🇬🇧

## Zawartość

- [Przepływ pracy (Workflow)](#przepływ-pracy-workflow)
- [Technologie](#technologie)
- [Przykładowe wizualizacje](#przykładowe-wizualizacje)
- [Kluczowe spostrzeżenia](#kluczowe-spostrzeżenia)

## Przepływ pracy (Workflow)
1. **Web scraping**: Pozyskiwanie surowych danych poprzez automatyczne wyciąganie informacji ze strony Filmweb. Proces kończy się eksportem uporządkowanego zbioru danych w formacie CSV, który stanowi podstawę dalszej analizy.

2. **Transformacja danych**: Czyszczenie i wstępne przetwarzanie danych, w tym uzupełnianie brakujących wartości, konwersja typów danych oraz reorganizacja kolumn pod kątem analizy.

3. **EDA (Eksploracyjna analiza danych)**: Wstępne badanie danych w celu poznania rozkładów, wykrycia wartości odstających oraz zidentyfikowania zależności między zmiennymi.

4. **Wizualizacja danych**: Tworzenie statycznych i interaktywnych wizualizacji ilustrujących kluczowe odkrycia i wzorce w zbiorze danych.

5. **Prezentacja wniosków**: Podsumowanie najważniejszych odkryć i konkluzji, poparte wizualizacjami oraz wynikami analizy.

## Technologie

Projekt został zrealizowany z wykorzystaniem następujących technologii:
- **Język programowania**: Python  
- **Środowisko programistyczne**: Visual Studio Code, Jupyter Notebook  
- **Web Scraping**: Requests, BeautifulSoup, urllib, RegEx  
- **Analiza danych**: Pandas, NumPy, RegEx, pycountry, ast, collections.Counter  
- **Wizualizacja**: Matplotlib, Seaborn, Plotly

## Przykładowe wizualizacje

### Statyczne wizualizacje:

![Przykładowe wizualizacje](/Data%20Visualization/Visualization%20Samples.gif)

![Przykładowe wizualizacje](/Data%20Visualization/Visualization%20Samples2.gif)

*Wszystkie wizualizacje są dostępne bezpośrednio w notebookach lub jako pliki PNG w folderze [Data Visualization](/Data%20Visualization/).*

### Interaktywne wizualizacje:

[![World Map](/Data%20Visualization/Country%20Visualizations/map_count.png)](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Country%20Visualizations/map_count.html)
*Kliknij obrazek lub [tutaj](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Country%20Visualizations/map_count.html) aby otworzyć wersję interaktywną.*

[![Regions Donut Chart](/Data%20Visualization/Country%20Visualizations/regions_donut.png)](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Country%20Visualizations/region_donut.html)
*Kliknij obrazek lub [tutaj](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Country%20Visualizations/region_donut.html) aby otworzyć wersję interaktywną.*

[![Genres Combinations Treemap](/Data%20Visualization/Genres%20Visualizations/genres_treemap.png)](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Genres%20Visualizations/genres_treemap.html)
*Kliknij obrazek lub [tutaj](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Genres%20Visualizations/genres_treemap.html) aby otworzyć wersję interaktywną.*

## Kluczowe spostrzeżenia

Kluczowe wnioski i odkrycia z tej analizy zostały podsumowane w prezentacji, dostępnej w formatach **[PowerPoint](/Filmweb%20Movie%20Analysis.pptx)** oraz **[PDF](/Filmweb%20Movie%20Analysis.pdf)**.
Proszę o zapoznanie się z tymi plikami, aby uzyskać szczegółowy przegląd wyników i wizualizacji.