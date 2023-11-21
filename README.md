# DataScience3
16.11.2023 Zadanie z kursu CODE:ME

WCZYTANIE DANYCH
<br />1. Wczytano dane 'CSV Temp_K_PL.csv'

PRZYGOTOWANIE DANYCH DO ALGORYTMU
<br />2. Przekształcenie typu danych indeksu na datetime
<br />3. Ustawienie częstotliwości na tygodniową
<br />4. Wybór z ramki szeregu median
<br />5. Wydział z szeregu zbioru treningowego i testowego

MODEL
<br />6. Wytrenowanie modelu treningowego przy pomocy ExponentialSmoothing
<br />7. Sprawdzenie wyników używając metryk Forecast Bias i Mean Squared Error

PĘTLA FOR
<br />8. Powiększanie danych treningowych o 1 rekord tygodniowo
<br />9. Zapis rezultatów do listy - w kolumnach kolejno: aktualna wielkość zbioru treningowego, data, mean squared error

WIZUALIZACJA
<br />10. Zapis resultatów do DataFrame
<br />11. Wyrysowanie wykresu zależności błędu od czasu
<br />12. Wyrysowanie wykresu zależności błędu od długości zbioru treningowego

BIBLIOTEKI
<br />numpy
<br />pandas
<br />matplotlib.pyplot
<br />sklearn.metrics import mean_squared_error
<br />statsmodels.tsa.holtwinters import ExponentialSmoothing
<br />statsmodels.tsa.seasonal import seasonal_decompose
