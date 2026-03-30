# R - projekt: analiza alertów
W naszym projekcie zajmiemy się problemem klasyfikacji danych. Zbiór, którym się posługujemy zawiera dane dotyczące alertu trzęsienia ziemi w
zależności od 5 cech takich jak:
- wielkość (magnitude) w skali Richtera,
- głębokość (depth)
- odległość od powierzchni Ziemi do punktu, w którym rozpoczyna się pękanie,
- cdi-maksymalną zgłoszoną intensywność
trzęsienia ziemi w danym zakresie
- mmi- maksymalną szacowaną intensywność trzęsienia ziemi zmierzoną przyrządami
- sig - kompleksowy wskaźnik znaczenia trzęsienia ziemi, określany na podstawie wielu czynników.

Naszym celem będzie zatem budowa modelu, który na podstawie danych
treningowych nauczy się przewidywać kolor alertu dla danych parametrów
ze zbioru testowego. Porównamy drzewo decyzyjne, las losowy, k-NN oraz
naiwny klasyfikator Bayesowski i sprawdzimy, która z tych metod
najlepiej przewiduje kolor alertu trzęsienia ziemi.
