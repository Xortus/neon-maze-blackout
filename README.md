# Neon Maze: Blackout

Neonowy labirynt 2D w Unity na komputer i Androida, z kampanią oraz współpracą dwóch graczy.

## Pobierz wersję v0.2.0

- [Gra na Androida — APK](https://github.com/Xortus/neon-maze-blackout/releases/download/v0.2.0/NeonMazeBlackout-Android.apk)
- [Projekt Unity — ZIP](https://github.com/Xortus/neon-maze-blackout/releases/download/v0.2.0/NeonMazeBlackout-UnityProject.zip)
- [Opis wydania i wszystkie pliki](https://github.com/Xortus/neon-maze-blackout/releases/tag/v0.2.0)

Do otwarcia projektu pobierz **NeonMazeBlackout-UnityProject.zip** z wydania. Automatyczne archiwa „Source code” GitHuba zawierają pliki repozytorium.

## Android

1. Pobierz APK na telefon i zainstaluj je. Jeśli Android poprosi o zgodę na instalację z aplikacji, w której otwierasz APK, udziel jej dla tej instalacji.
2. Uruchom grę. Ekran działa poziomo; ruchem steruje joystick, a umiejętnością przycisk klasy.
3. Aktualizację można zainstalować na wcześniejszej wersji bez odinstalowywania gry.

APK zawiera aktualną współpracę. Instalacja i wspólna gra telefon–komputer zostały potwierdzone przez autora na Redmi.

## Komputer i projekt Unity

1. Rozpakuj **NeonMazeBlackout-UnityProject.zip**.
2. W Unity Hub wybierz **Add → Add project from disk** i folder **NeonMazeBlackout**.
3. Otwórz go w **Unity 6.3 LTS — 6000.3.26f1** i poczekaj na import oraz pobranie pakietów.
4. Otwórz **Assets/Scenes/SampleScene.unity** i naciśnij Play.

Archiwum zawiera Assets, Packages, ProjectSettings oraz pliki .meta. Dane robocze Unity są odtwarzane po otwarciu. W tym wydaniu komputerową wersję uruchamia się z projektu Unity.

## Współpraca dwóch graczy

1. Na pierwszym urządzeniu wybierz **POKÓJ ONLINE → UTWÓRZ POKÓJ**.
2. Na drugim wpisz kod pokoju i wybierz **DOŁĄCZ**.
3. Wybierzcie klasy i potwierdźcie gotowość. Gospodarz rozpoczyna kampanię.

- Wspólne kryształy i wynik na tej samej mapie.
- 60 sekund na każdą z 18 map, start po załadowaniu mapy u obu graczy.
- Po zebraniu fali kryształów meta zostaje odblokowana; kryształy pojawiają się ponownie w innych miejscach.
- Dotknięcie przez drona cofa na start tylko złapanego gracza.
- Przejście dalej po dotarciu obu graczy do mety; pierwszy gracz czeka bezpiecznie.
- Osobne klasy i wygląd rdzenia dla każdego gracza.
- Rozłączenie kończy wspólną próbę; do nowej gry utwórzcie nowy pokój.

Na obu urządzeniach użyj tej samej wersji gry i pozostaw grę na pierwszym planie.

## Pozostałe elementy

- Kampania 18 poziomów w sześciu wymiarach.
- Drony, kryształy energii, meta i okresowy blackout.
- Klasy: Zwiadowca, Inżynier, Łowca i Strażnik.
- Kreator rdzenia: kolor, obwódka i ślad.
- Sterowanie klawiaturą oraz dotykowe.
- Rekordy lokalne i integracja z PlayFab; wyniki współpracy pozostają oddzielne od rekordów solo.

## Usługi i budowanie

Pokoje korzystają z Unity Services, Authentication i Relay. Ranking wymaga konfiguracji PlayFab Title ID. Dla własnej publikacji skonfiguruj własne projekty tych usług.

Do budowania Androida potrzebne są moduły Android Build Support, SDK/NDK i OpenJDK dla tej wersji Unity. Udostępnione APK obsługuje ARM64 i Androida od API 25.

To nadal rozwijany prototyp. Biblioteki i zasoby zachowują własne pliki licencji oraz informacji o autorach. Sumy kontrolne paczek są w pliku **SHA256SUMS.txt** dołączonym do wydania.
