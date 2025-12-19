---
icon: hand-wave
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
metaLinks: {}
---

# Witaj w dokumentacji

Tutaj dowiesz się wszystkiego o Space Station 14 oraz działaniu serwera i prac.

### Sprawdź

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-cover data-type="image">Cover image</th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td><i class="fa-bolt">:bolt:</i></td><td><strong>MAPA</strong></td><td>Zobacz jak wygląda statek</td><td><a href=".gitbook/assets/Zrzut ekranu 2025-12-17 203837.png">Zrzut ekranu 2025-12-17 203837.png</a></td><td></td><td><a href="hub/prace.md">prace.md</a></td></tr><tr><td><i class="fa-leaf">:leaf:</i></td><td><strong>PRACE</strong></td><td>Sprawdź listę prac</td><td><a href=".gitbook/assets/NTLogo (1).png">NTLogo (1).png</a></td><td></td><td><a href="https://github.com/GitbookIO/gitbook-templates/blob/main/product-docs/broken-reference/README.md">https://github.com/GitbookIO/gitbook-templates/blob/main/product-docs/broken-reference/README.md</a></td></tr><tr><td><i class="fa-globe-pointer">:globe-pointer:</i></td><td><strong>REGULAMIN</strong></td><td>Zasady panujące na naszym serwerze</td><td><a href=".gitbook/assets/800px-Job_tree3.png">800px-Job_tree3.png</a></td><td></td><td><a href="hub/regulamin.md">regulamin.md</a></td></tr></tbody></table>

## GŁÓWNE ZASADY GRY

#### Zdrajcy

Zasady gry Traitors wymagają co najmniej pięciu graczy na początku rundy. Gra wybiera jednego z dziesięciu graczy (maksymalnie 8), którzy zostaną zdrajcami Jeśli gracz zostanie wybrany, może nie otrzymać roli z osłoną umysłu. `Traitor`

Po czterech do siedmiu minutach zdrajcy zostaną poinformowani o swoich misjach. Dodatkowo, gracze dołączający późno mogą zostać oznaczeni jako zdrajcy, aby wyrównać stosunek jeden do dziesięciu.

Ich cele są określone przez ich cele i mogą obejmować wszystko, od drobnych kradzieży po masowe morderstwa.

#### Agenci nuklearni

Zasada gry „**Agenci Nuklearni**” `Nukeops` wymaga co najmniej 20 graczy na początku rundy. Na początku rundy w placówce Syndykatu pojawi się od 3 do 5 [Agentów Nuklearnych,](https://wiki.spacestation14.com/wiki/Nuclear_Operative) w stosunku jeden do dziesięciu, priorytetowo traktując najpierw Dowódcę, potem Agenta, a na końcu pozostałych agentów.

Ich celem jest zdobycie [Dysku Uwierzytelniającego](https://wiki.spacestation14.com/wiki/Nuclear_Authentication_Disk) do bomby jądrowej i zdetonowanie Bomby jądrowej na pokładzie stacji.

#### Rewolucjoniści

Zasada gry „Rewolucjoniści” wymaga `Revolutionary`co najmniej 15 graczy na początku rundy. Na początku rundy 1-3 graczy z grupy jeden na piętnastu zostanie wyznaczonych na [Głownych Rewolucjonistów](https://wiki.spacestation14.com/wiki/Head_Revolutionary) , a następnie otrzymają oni latarkę i okulary przeciwsłoneczne. Jeśli zostanie wybrany Głowny Rewolucjonista, gracz ten może nie otrzymać roli z osłoną umysłu.

#### Zombie

Zasada gry Zombies `Zombie` wymaga co najmniej 20 graczy na początku rundy. Pomiędzy 10 a 15 minutą rundy, maksymalnie sześciu graczy zostanie oznaczonych jako [Początkowi Zakażeni](https://wiki.spacestation14.com/wiki/Initial_Infected) w stosunku jeden do dziesięciu. Jeśli zostanie wybrany Początkowy Zarażony, gracz ten może nie otrzymać roli z osłoną umysłu.

Ich celem jest przemienić się w [Zombie,](https://wiki.spacestation14.com/wiki/Zombie) gdy nadejdzie odpowiedni moment, by przejąć kontrolę nad stacją i jej załogą.

### Czarodziej

Aby gra Czarodziej działała , na początku rundy musi być co najmniej 15 graczy. Pojawi się jeden czarodziej na jego statku – potężnym wahadłowcu, który dostarcza prawdziwego agenta chaosu pod drzwi NT14.

Rolą Czarodzieja jest sianie chaosu, jakkolwiek uzna to za stosowne. Ma wolną rękę w kwestii wszystkiego, co służy pogłębianiu chaosu na stacji

### Zespół Kesslera

Syndrom Kesslera generuje `KesslerSyndrome`dużą liczbę meteorów, których liczba rośnie w trakcie rundy. Meteory będą generowane z tymi samymi obliczeniami, co w przypadku [zdarzeń Ramping Station](https://wiki.spacestation14.com/wiki/Game_Modes#Ramping_Station_Events) , ale zamiast tego będą wybierane z tabeli meteorów pokazanej w [Meteorach](https://wiki.spacestation14.com/wiki/Game_Modes#Meteors)

#### Wydarzenia na stacji

Wydarzenia Ramping Station `RampingStationEventScheduler` będą generować [wydarzenia](https://wiki.spacestation14.com/wiki/Game_Modes#Events) z rosnącą częstotliwością w trakcie rundy. Na początku rundy zostanie wybrana wartość Maksymalnego Chaosu między 9 a 15 i wartość Czasu Zakończenia między 67,5 a 112,5 minuty. Wartość Chaosu rozpocznie się od jednej dziesiątej wartości Maksymalnego Chaosu i będzie rosła liniowo, aż osiągnie Maksymalny Chaos w Czasie Zakończenia .

Harmonogram rozpocznie się od czasu odnowienia wynoszącego od 4 do 12 minut, podzielonego przez aktualną wartość Chaos . Następnie wybierze losowe [zdarzenie](https://wiki.spacestation14.com/wiki/Game_Modes#Event) do uruchomienia. Po zakończeniu zdarzenia wybierze nowy, prawdopodobnie krótszy, czas odnowienia, aby zaplanować kolejne zdarzenie.

Po nadejściu Czasu Końca zdarzenia będą się powtarzać co 16–80 sekund.
