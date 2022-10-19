# BigData2022-initial-project

Przykładowy szablon do rozwijania projektów w ramach kursu Big Data 2022 na PŁ.

Ten plik stanowi podstawową dokumentację dla odbiorcy projektu.

# Rekomendowany setup środowiska

Spróbujemy pracować ze środowiskiem Anaconda, która pozwala na wygodne i równoległe posiadanie wiele różnych wersji pythona zainstalowanych w systemie. Rekomendowane jest również posiadanie zainstalowanie gitbasha do interakcji z repo, gdy ta wykracza poza możliwości vs code.

1. Na początek warto w terminalu dokonać aktywacji środowiska condy za pomocą komendy
```
source ścieżka/do/katalogu/anacondy/bin/activate
```
1. W efekcie działania tego polecenia terminal powinien zareagować zmianą perspektywy
```
dyschemist@pkowalski-predator-helios:~$ source /opt/anaconda3/bin/activate 
(base) dyschemist@pkowalski-predator-helios:~$ 
```

Domyślnie uruchomione jest środowisko bazowe condy. Utworzymy środowisko wirtualne do działania

```
conda create --name bd2022 python=3.10
```

gdzie bd2022 jest nazwą własną, którą samemu możecie wybrać.

pozostaje aktywować środowisko za pomocą komendy

```
conda activate [nazwa venv]
```

Co ponownie zmienia perspektywę według wzorca

```
(base) dyschemist@pkowalski-predator-helios:~$ conda activate bd2022
(bd2022) dyschemist@pkowalski-predator-helios:~$
```

Później pozostaje zainstalować zależności według metody.

1. `cd` do katalogu głównego projektu
1. przekazanie requirement.txt

```
pip install -r requirements.txt 
```

