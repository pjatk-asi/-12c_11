ASI - PROJEKT
Predykcja najlepszej oceny gry komputerowej Steam przy pomocy uczenia maszynowego

Link: https://dss-bfd5c14e-32c34eaf-dku.eu-west-3.app.dataiku.io/projects/ASI_1/flow/

General Głównym celem projektu jest przewidywanie jakie czynniki spowodują bądź będą miały wpływ na to, że ocena gry komputerowej Steam będzie najwyższa. Dane wejściowe zawierają informacje m.in. o: dacie wydania, wydawcy, cenie itd. Użyjemy ich w celu wytrenowania modelu i sprawdzenia czy będzie on odpowiednio przewidywać wyniki. Następnym etapem będzie wykrywanie dryfu danych oraz trenowanie modelu na nowych danych treningowych.

Zestaw danych Wykorzystany zestaw danych to zbiór podstawowych informacji o danej grze komputerowej takie jak.: -name, -english, -developer, -publisher, -required_age, -achievements, -positive_ratings, -negative_ratings, -average_playtime, -median_playtime -owners, -priceitd. Zbiór zawiera także dane techniczne tj. dostępna platforma (Windows/Mac/Linux). Największy wpływ na wynik mają następujące informacje: ilość pozytywnych oraz negatywnych opinii.

Do monitorowani dryfu danych miał być zastosowany plugin do DSS - " Model Drift Monitoring" który miał na celu analize potencjalnego dryfu modeli uczenia maszynowego. Ograniczenia licencyjne Dataiku nie pozwoliły na jego zastosowanie. Nie było ponadto żadnego innego narzędzia wbudowanego.

Wykorzystanie Potencjalnymi klientami, do których skierowana jest omawiana aplikacja są firmy z branży gamedev oraz developerzy.

Autorzy Norbert Dąbrowski Sebastian Piórecki Marlena Czurak

