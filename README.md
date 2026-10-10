# Neon Maze: Blackout

Neonowy labirynt 2D przygotowany w Unity na komputer i Androida.

## Pobierz grę i projekt

Wydanie **v0.1.0** zawiera:

- [NeonMazeBlackout-Android.apk](https://github.com/Xortus/neon-maze-blackout/releases/download/v0.1.0/NeonMazeBlackout-Android.apk) — instalator gry na Androida.
- [NeonMazeBlackout-UnityProject.zip](https://github.com/Xortus/neon-maze-blackout/releases/download/v0.1.0/NeonMazeBlackout-UnityProject.zip) — pełny projekt Unity: Assets, Packages, ProjectSettings i pliki .meta.
- [Strona wydania](https://github.com/Xortus/neon-maze-blackout/releases/tag/v0.1.0) — opis wersji i pliki do pobrania.

Projekt jest udostępniony jako archiwum w wydaniu. Automatyczne archiwa „Source code” GitHuba zawierają pliki tego repozytorium; do otwarcia gry pobierz **NeonMazeBlackout-UnityProject.zip**.

## Android

1. Pobierz APK na telefon.
2. Otwórz go i zezwól na instalację z aplikacji, z której otwierasz plik.
3. Uruchom Neon Maze: Blackout. Gra działa w poziomie; ruch obsługuje joystick, umiejętność — przycisk klasy.

APK jest wersją prototypową ostatnio przygotowaną i zainstalowaną na telefonie. Nowe zmiany w kodzie wymagają ponownej budowy aplikacji.

## Projekt Unity

1. Pobierz i rozpakuj **NeonMazeBlackout-UnityProject.zip**.
2. W Unity Hub wybierz **Add → Add project from disk** i folder **NeonMazeBlackout**.
3. Otwórz projekt w **Unity 6.3 LTS, 6000.3.26f1**.
4. Poczekaj na pobranie pakietów i import zasobów.
5. Otwórz scenę **Assets/Scenes/SampleScene.unity** i naciśnij Play.

Archiwum zawiera kod C#, mapy, grafiki, sceny, zależności i ustawienia. Foldery Library, Temp, Logs oraz UserSettings nie są potrzebne — Unity odtworzy lokalne dane.

Do budowy Androida potrzebne są moduły Android Build Support, SDK/NDK i OpenJDK dla tej wersji Unity.

## Obecne elementy gry

- Kampania 18 poziomów w sześciu wymiarach.
- Kryształy energii, drony, meta i okresowy blackout.
- Klasy: Zwiadowca, Inżynier, Łowca i Strażnik.
- Kreator neonowego rdzenia: kolor, obwódka i ślad.
- Sterowanie klawiaturą i dotykowe.
- Rekordy lokalne i integracja rankingu z PlayFab.
- Tworzenie i dołączanie do prywatnych pokoi przez Unity Relay.

**Pełna wspólna rozgrywka dwóch graczy jest na etapie zatwierdzonego projektu i planu.** To wydanie zawiera istniejące połączenie pokoju; synchronizacja mapy, kryształów i wspólnej mety jest kolejnym etapem.

## Usługi online

Pokoje wymagają konfiguracji Unity Services / Authentication / Relay. Ranking wymaga konfiguracji PlayFab Title ID. Dla własnej publikacji skonfiguruj własne projekty tych usług; dane instalacji i nick gracza pozostają lokalne.

Gra oraz archiwum projektu są prototypem. Dołączone biblioteki i zasoby zachowują własne pliki licencji i informacji o autorach.
