**Predykcja najlepszej oceny gry komputerowej Steam przy pomocy uczenia
maszynowego**

General

Głównym celem projektu jest przewidywanie jakie czynniki spowodują bądź
będą miały wpływ na to, że ocena gry komputerowej Steam będzie
najwyższa. Dane wejściowe zawierają informacje m.in. o: dacie wydania,
wydawcy, cenie itd. Użyjemy ich w celu wytrenowania modelu i sprawdzenia
czy będzie on odpowiednio przewidywać wyniki. Następnym etapem będzie
wykrywanie dryfu danych oraz trenowanie modelu na nowych danych
treningowych.

http://dataiku.pjwstk.edu.pl:11000/workspaces/ASI_12C/ASI_4/DASHBOARD/ceQxOTO

Zestaw danych

Wykorzystany zestaw danych to zbiór podstawowych informacji o danej grze
komputerowej pobrane z bazy Steam takie jak:

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

Zbiór zawiera także dane techniczne tj. dostępna platforma
(Windows/Mac/Linux). Największy wpływ na wynik mają następujące
informacje: ilość pozytywnych oraz negatywnych opinii.

![](vertopal_1c96b1ce24aa4482a937df49c66bbd7c/media/image1.png){width="5.953125546806649in"
height="3.776907261592301in"}

Algorytm który został wykorzystany do predykcji to: Gradient Boosted
Trees który osiągał najlepsze wyniki
predykcji![](vertopal_1c96b1ce24aa4482a937df49c66bbd7c/media/image2.png){width="6.671959755030621in"
height="1.6402821522309712in"}

Do użytku wykorzystany został moduł Dashboard dzięki któremu możemy
uruchomić cały proces jak i podejrzeć wyniki treningów

![](vertopal_1c96b1ce24aa4482a937df49c66bbd7c/media/image3.png){width="6.267716535433071in"
height="2.9583333333333335in"}

Do monitorowani dryfu danych miał być zastosowany plugin do DSS - \"
Model Drift Monitoring\" który miał na celu analize potencjalnego dryfu
modeli uczenia maszynowego. Ograniczenia licencyjne nie pozwoliły na
jego zastosowanie a co za tym idzie automatyczne doczytanie danych do
treningu przy wykryciu Dryfu

Wykorzystanie

Potencjalnymi klientami, do których skierowana jest omawiana aplikacja
są firmy z branży gamedev oraz developerzy.

Autorzy

Norbert Dąbrowski

Sebastian Piórecki

Marlena Czurak
