Narysuj tekst używając: `text('Tekst do wyświetlenia', x, y)`

Tekst zostanie narysowany przy użyciu wartości `wypełnienia` ustawionej przed wywołaniem `tekstu`.

```python

text('Twój tekst', 250, 50)

```

Tekst zostanie umieszczony we współrzędnych (x, y) przez podanie dwóch liczb.

!['Twój tekst' pojawia się na siatce z pozycją (250, 50) zaznaczoną w lewym dolnym rogu.](images/text_grid.png)

Możesz również dostosować tekst, używając:

```python

text_align(polozenie_poziome, polozenie_pionowe) 

```

Który dostosowuje pozycję tekstu w niewidocznym polu, które tworzysz na docelowych współrzędnych. P5 zawiera specjalne zmienne dla każdej pozycji, której możesz chcieć użyć:

 - `polozenie_poziome` z `LEFT` spowoduje wyrównanie tekstu do lewej strony pola tekstowego
 - `polozenie_poziome` z `CENTER` spowoduje wyśrodkowanie tekstu w polu tekstowym w poziomie
 - `polozenie_poziome` z `RIGHT` spowoduje wyrównanie tekstu do prawej strony pola tekstowego
 - `polozenie_pionowe` z `TOP` spowoduje wyrównanie tekstu do górnej części pola tekstowego
 - `polozenie_pionowe` z `CENTER` spowoduje wyrównanie tekstu do środka pola tekstowego
 - `polozenie_pionowe` z `BOTTOM` spowoduje wyrównanie tekstu do dołu pola tekstowego

```python

text_size(rozmiar)

```

Który akceptuje liczbę w pikselach, która reprezentuje żądany rozmiar czcionki.

Na przykład, aby utworzyć słowo „Hello” w czerwonym tekście o wysokości 16 pikseli, wyśrodkowane na płótnie 400, 400, użyjesz:

```python

fill(200, 0, 0)
text_size(16)
text_align(CENTER, CENTER)
text('Hello', 200, 200)

```

!['Hello' pojawia się na czerwono, wyśrodkowany na siatce oznaczonej (200, 200).](images/all_features.png) 
