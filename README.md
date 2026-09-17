---
icon: hand-wave
layout:
  width: default
  title:
    visible: false
  description:
    visible: false
  tableOfContents:
    visible: false
  outline:
    visible: false
  pagination:
    visible: true
  metadata:
    visible: false
  tags:
    visible: true
  actions:
    visible: false
  anchors:
    visible: false
metaLinks: {}
---

# Witaj w dokumentacji

<figure><img src=".gitbook/assets/end.png" alt=""><figcaption></figcaption></figure>

Tutaj dowiesz się wszystkiego o Space Station 14 oraz działaniu naszego serwera i jego prac.



<h2 align="center">KATEGORIE</h2>

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-cover data-type="image">Cover image</th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td><i class="fa-bolt">:bolt:</i></td><td><strong>MAPA</strong></td><td>Zobacz jak wygląda nasz statek</td><td><a href=".gitbook/assets/Zrzut ekranu 2025-12-17 203837.png">Zrzut ekranu 2025-12-17 203837.png</a></td><td></td><td><a href="https://app.gitbook.com/s/mC1p83fUVY9J6CrORaqI/prace">PRACE</a></td></tr><tr><td><i class="fa-leaf">:leaf:</i></td><td><strong>PRACE</strong></td><td>Sprawdź listę prac jakie są na serwerze</td><td><a href=".gitbook/assets/NTLogo (1).png">NTLogo (1).png</a></td><td></td><td><a href="https://app.gitbook.com/s/mC1p83fUVY9J6CrORaqI/prace">PRACE</a></td></tr><tr><td><i class="fa-globe-pointer">:globe-pointer:</i></td><td><strong>REGULAMIN</strong></td><td>Zasady panujące na naszym serwerze</td><td><a href=".gitbook/assets/800px-Job_tree3.png">800px-Job_tree3.png</a></td><td></td><td><a href="hub/regulamin.md">regulamin.md</a></td></tr></tbody></table>

## Nanotrasen <a href="#firstheading" id="firstheading"></a>

Nanotrasen to korporacja, dla której pracujesz, zarządzana przez swoje Dowództwo Centralne, a wszyscy pracownicy są zobowiązani do przestrzegania jej zasad. Nanotrasen jest właścicielem wielu stacji, takich jak niesławna Stacja Kosmiczna 13 i ta, na której obecnie się znajdujesz (Stacja Kosmiczna 14).

Nanotrasen ma wielu wrogów, między innymi: <mark style="color:red;">**Syndykat**</mark>, konkurencyjne korporacje, takie jak **CyberSun**, oraz <mark style="color:$primary;">**Piratów**</mark>.

Nanotrasen to organizacja przestrzegająca prawa, której głównym celem jest utrzymanie i ulepszanie stacji, przy jednoczesnym przetrwaniu i przestrzeganiu prawa.

***

## GŁÓWNE ZASADY GRY

#### Zdrajcy

Zasady gry Traitors wymagają co najmniej pięciu graczy na początku rundy. Gra wybiera jednego z dziesięciu graczy (maksymalnie 8), którzy zostaną zdrajcami Jeśli gracz zostanie wybrany, może nie otrzymać roli z osłoną umysłu. `Traitor`

Po czterech do siedmiu minutach zdrajcy zostaną poinformowani o swoich misjach. Dodatkowo, gracze dołączający późno mogą zostać oznaczeni jako zdrajcy, aby wyrównać stosunek jeden do dziesięciu.

Ich cele są określone przez ich cele i mogą obejmować wszystko, od drobnych kradzieży po masowe morderstwa.

#### Agenci nuklearni

Zasada gry „**Agenci Nuklearni**” `Nukeops` wymaga co najmniej 20 graczy na początku rundy. Na początku rundy w placówce Syndykatu pojawi się od 3 do 5 Agentów Nuklearnych, w stosunku jeden do dziesięciu, priorytetowo traktując najpierw Dowódcę, potem Agenta, a na końcu pozostałych agentów.

Ich celem jest zdobycie Dysku Uwierzytelniającego do bomby jądrowej i zdetonowanie Bomby jądrowej na pokładzie stacji.

#### Rewolucjoniści

Zasada gry „Rewolucjoniści” wymaga `Revolutionary`co najmniej 15 graczy na początku rundy. Na początku rundy 1-3 graczy z grupy jeden na piętnastu zostanie wyznaczonych na Głownych Rewolucjonistów , a następnie otrzymają oni latarkę i okulary przeciwsłoneczne. Jeśli zostanie wybrany Głowny Rewolucjonista, gracz ten może nie otrzymać roli z osłoną umysłu.

#### Zombie

Zasada gry Zombies `Zombie` wymaga co najmniej 20 graczy na początku rundy. Pomiędzy 10 a 15 minutą rundy, maksymalnie sześciu graczy zostanie oznaczonych jako Początkowi Zakażeni w stosunku jeden do dziesięciu. Jeśli zostanie wybrany Początkowy Zarażony, gracz ten może nie otrzymać roli z osłoną umysłu.

Ich celem jest przemienić się w Zombie, gdy nadejdzie odpowiedni moment, by przejąć kontrolę nad stacją i jej załogą.

#### Czarodziej

Aby gra Czarodziej działała , na początku rundy musi być co najmniej 15 graczy. Pojawi się jeden czarodziej na jego statku – potężnym wahadłowcu, który dostarcza prawdziwego agenta chaosu pod drzwi NT14.

Rolą Czarodzieja jest sianie chaosu, jakkolwiek uzna to za stosowne. Ma wolną rękę w kwestii wszystkiego, co służy pogłębianiu chaosu na stacji

#### Zespół Kesslera

Syndrom Kesslera generuje `KesslerSyndrome`dużą liczbę meteorów, których liczba rośnie w trakcie rundy. Meteory będą generowane z tymi samymi obliczeniami, co w przypadku zdarzeń Ramping Station , ale zamiast tego będą wybierane z tabeli meteorów pokazanej w Meteorach

#### Wydarzenia na stacji

Wydarzenia Ramping Station `RampingStationEventScheduler` będą generować wydarzenia z rosnącą częstotliwością w trakcie rundy. Na początku rundy zostanie wybrana wartość Maksymalnego Chaosu między 9 a 15 i wartość Czasu Zakończenia między 67,5 a 112,5 minuty. Wartość Chaosu rozpocznie się od jednej dziesiątej wartości Maksymalnego Chaosu i będzie rosła liniowo, aż osiągnie Maksymalny Chaos w Czasie Zakończenia .

Harmonogram rozpocznie się od czasu odnowienia wynoszącego od 4 do 12 minut, podzielonego przez aktualną wartość Chaos . Następnie wybierze losowe zdarzenie do uruchomienia. Po zakończeniu zdarzenia wybierze nowy, prawdopodobnie krótszy, czas odnowienia, aby zaplanować kolejne zdarzenie.

Po nadejściu Czasu Końca zdarzenia będą się powtarzać co 16–80 sekund.
