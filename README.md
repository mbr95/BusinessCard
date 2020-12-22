# Projekt HTML & CSS — Wizytówka / Portfolio

Projekt został stworzony na podstawie przykładu interfejsu strony: 
https://www.figma.com/file/WHtiMfcNHt4tc7mDamNBYa/CodersCamp2020-Wizytowka?node-id=0%3A1

## Elementy projektu

#### Wrapper

Wszystkie sekcje strony owinięte są kontenerem flexboxowym układającym je w jedną kolumnę.
#### Nagłówek

Nagłowek strony stnowi logo wraz z menu nawigacyjnym.
Zostały one wystylowane przy pomocy flexboxa.
W przypadku niskich rozdzielczości nagłówek ułożony jest na samej górze strony jako kolumna.
Od rozdzielczości o szerokości 480px jest on przyklejony do górnej krawędzi okna przeglądarki (position: fixed),
a elementy ułożone są w jednym rzędzie.
Elementy menu zmieniają kolor po najechaniu na nie oraz prowadzą do przypisanych im sekcji po kliknięciu.

#### Sekcja powitalna

Sekcja powitalna posiada zdjęcie jako tło, na przodzie znajdują się napisy powitalne oraze ikony do social mediów (font awesome).
Elementy ułożone są za pomocą flexboxa.
Nagłówek h2 posiada krótką animację obramowania po odpaleniu strony (keyframes).
Po najechaniu na jedną z ikon (pseudo klasa :hover) staje się ona częściowo przezroczysta.

#### Sekcja "O mnie"

Składa się z karty wystylizowanej za pomocą atrybutu box-shadow.
Karta podzielona jest na minisekcje oddzielone kropkowaną linią (border-bottom lub border-right).
Elementy zarówno sekcji jak i minisekcji ułożone są przy pomocy flexboxa.
W przypadku niskich rozdzielczości jest to ułożenie kolumnowe natomiast przy wytarczająco dużej rozdzielczości
mini sekcje układają się w jednym rzędzie;

#### Sekcja "Umiejętności"

Ta sekcja również korzysta z klasy karty użytej w sekcji poprzedniej.
Zawiera podział na minisekcje ułożone w pionie lub poziomie w zależności od rozdzielczości
i podzielone przy pomocy bordera. Kazda z mini seckji zawiera logo i spis umiejętności.
Elementy są wyśrodkowane w sekcjach za pomocą flexboxa.

#### Sekcja "Portfolio"

W sekcji portfolio znajdują się zdjęcia ułożone za pomocą flexboxa w kontenerze o szerokości ustawionej na 90%.
W przypadku niskich rozdzielczości zdjęcia układają się w jednej kolumnie.
Do odpowiedniego ułożenia użyłem jednostek relatywnych właściwości overflow: hidden oraz object-fit: cover.
Dwa zdjęcia pokrywa gradient stworzony przy pomocy dodatkowej klasy oraz pseudoelementu ::before.
Zawierają one również overlay z tekstu oraz buttona (position: absolute oraz atrybut z-index).
Buttony na całej stronie zmieniają kolor backgroundu czcionki oraz krawędzi podczas najechania na nie kursorem.

#### Sekcja "Kontakt"

Sekcja na telefonach wyświetla się w kolumnie (flexbox).
Jest podzielona na mniejsze sekcje (formularz i sekcja informacyjna).
Od rozdzielczości 480px obie sekcje ułożone są w karcie której szerokość wynosi 80%.
Formularz zbudowany jest z 3 pól typu imput oraz jednego kilkuliniowego pola textarea (oraz buttona).
Pola zawierają placeholdery, których nazwy wskazują na ich przeznaczenie.
Druga część karty zawiera ikonę wiadomości, podstawowe informacje oraz ikony social mediow (tak jak w przypadku ikon w pierwszej sekcji
po najechaniu zmienia się ich opacity).
W przypadku rozdzielczości desktopowych (1200px+) karta układa się w poziomie (flex-direction: row-reverse).

#### Stopka

Na samym dole strony znajduje się wycentrowana stopka.


##### Fonty

Zastosowane fonty - 'Raleway', 'Ubuntu'.
