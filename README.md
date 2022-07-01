Predykcja najlepszej oceny gry komputerowej Steam przy pomocy uczenia maszynowego

General
Głównym celem projektu jest przewidywanie jakie czynniki spowodują bądź będą miały wpływ na to, że ocena gry komputerowej Steam będzie najwyższa. Dane wejściowe zawierają informacje m.in. o: dacie wydania, wydawcy, cenie itd. Użyjemy ich w celu wytrenowania modelu i sprawdzenia czy będzie on odpowiednio przewidywać wyniki. Następnym etapem będzie wykrywanie dryfu danych oraz trenowanie modelu na nowych danych treningowych.  

Zestaw danych
Wykorzystany zestaw danych to zbiór podstawowych informacji o danej grze komputerowej pobrane z bazy Steam takie jak:
-name,
-english,
-developer,
-publisher,
-required_age,
-achievements,
-positive_ratings,
-negative_ratings,
-average_playtime,
-median_playtime
-owners,
-price

Dane są w postaci pliku CSV
Zbiór danych posiada ok 70tys rekordów.
Zbiór zawiera także dane techniczne tj. dostępna platforma (Windows/Mac/Linux). Największy wpływ na wynik mają następujące informacje: ilość pozytywnych oraz negatywnych opinii.  


Algorytm który został wykorzystany do predykcji to: Gradient Boosted Trees który osiągał najlepsze wyniki predykcji

Do użytku wykorzystany został moduł Dashboard dzięki któremu możemy uruchomić cały proces jak i podejrzeć wyniki treningów




Do monitorowani dryfu danych miał być zastosowany plugin do DSS - " Model Drift Monitoring" który miał na celu analize potencjalnego dryfu modeli uczenia maszynowego. Ograniczenia licencyjne nie pozwoliły na jego zastosowanie a co za tym idzie automatyczne doczytanie danych do treningu przy wykryciu Dryfu

Wykorzystanie
Potencjalnymi klientami, do których skierowana jest omawiana aplikacja są firmy z branży gamedev oraz developerzy.   

Autorzy 
Norbert Dąbrowski
Sebastian Piórecki
Marlena Czurak
  

     

