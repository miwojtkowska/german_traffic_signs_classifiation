# german_traffic_signs_classifiation 
Wykrywanie i rozpoznawanie znaków drogowych ma kluczowe znaczenie dla rozwoju będących ostatnio "na czasie" 
pojazdów autonomicznych. Przedstawiony kod służy do rozpoznawania na zdjeciach znaków drogowych poprzez proces klasyfikacji.
Wykorzytano tu augmentację danych, zrównoważono niezbalansowane klasy, a także przebadano różne architektury sieci neuronowych -
dense network i convolutional neural network. 

Zaprezentowany kod składa się z części typowych dla większości procesów ML:
* Analiza danych
* Wstępne przetworzenie danych (wyrównanie histogramu, transformacja RGB -> GRAY itp.)
* Budowa architektury CNN
* Trening sieci
* Testowanie modelu
* Iteracja powyższych punktów do czasu osiągnięcia rezultatu o wystarczającej dokładności

W rezultacie najlepszy osiągniety wynik to accuracy = 97%.

References:
https://towardsdatascience.com/my-tryst-with-deep-learning-german-traffic-data-set-with-keras-87970dfb18b7
