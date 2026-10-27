# Linux Kink Clicker (Android)

Klikana gra z pingwinem w koronie. 4 motywy (różowy, zielony, biały, pomarańczowy), 12 ulepszeń,
6 boostów, osiągnięcia, złote korony, prestiż, postęp offline i zapis stanu.

## Jak zdobyć APK

**A. GitHub (bez instalowania czegokolwiek)**
1. Utwórz repozytorium na github.com i wgraj całą zawartość tego folderu.
2. Zakładka *Actions* → *Build APK* → po zakończeniu pobierz artefakt `LinuxKinkClicker-apk`.
3. Rozpakuj, przenieś `app-release.apk` na telefon i zainstaluj (zezwól na instalację z nieznanych źródeł).

**B. Android Studio**
1. *File → Open* i wskaż ten folder.
2. *Build → Build Bundle(s) / APK(s) → Build APK(s)*.

Grę można też edytować: cała logika jest w `app/src/main/assets/index.html`.
