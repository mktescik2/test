## kolokwium nr 3 ze "Środowiska programisty"

Program zapisany jest w trzech plikach:
    main.cpp
	funkcja.cpp
	funkcja.h

Kompilacja odbywa się w następujący sposób:

Polecenie
    ```g++ -c main.cpp```
tworzy plik ```main.o```. Do jego wykonania potrzebne są
pliki ```main.cpp``` i ```funkcja.h```.

Polecenie
    ```g++ -c funkcja.cpp```
tworzy plik ```funkcja.o```. Do jego wykonania potrzebne są
pliki ```funkcja.cpp``` i ```funkcja.h```.

Polecenie ```g++ -o program main.o funkcja.o```
tworzy plik ```program``` z plików ```main.o``` i ```funkcja.o```.

Stworzyć odpowiedni plik ```Makefile``` automatyzujący proces
kompilacji, a następnie umieścić go
w odpowiednim repozytorium w serwisie ```github.com```.
