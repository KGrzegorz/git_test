# Narzędzia dla programistów





### Oprogramowanie:



https://aka.ms/devtoolsforteaching

Latex (Lateh)

Git



### Bash:



MinGW na GitHubie

Git + Bash + VIM



### Lektura:



Robbins a Baash 2017

Lach M Bash 2015

Przybylski B Lua i Latex 2016

Loeliger J kontrola wersji Git 2014





# **1 Wykład**



Powłoka - Program który odbiera sygnały od użytkownika które później interpretuje tego jako polecenie albo uruchamia inne oprogramowanie i wyświetla wyniki na ekranie

&#x20;

#### cechy powłoki:



przekazuje parametry

umożliwia wczytanie wcześniej utworzonych skryptów

łaczy wejścia i wyjscia



#### Przykładowe powłoki:



command.com DOS i windows 16bit

cscript.exe win 98

PowerShell win

sh pierwotne powłoki dla systemów unixowych

KornSchell, c Schell, Tcsh, Zsh powłoki systemów unixwóych portowane do innych systemów operacyjnych



#### Znak zachęty:



znak umieszczony na początku wiersza w celu wskazania gotowości systemu do przetwarzanie poleceń



PS1 początek wprowadzenia poleceń (h,w,u,$)

PS2 kontynuacja nieskończonej linii (>)

PS3 wygląd zapytania select

PS4 wykonywanie poleceń w trybie debugowania



#### Bieżący katalog:



aktualny katalog w którym wykonują się polecenia



Plik - elemntarna struktóra do przechowywania uporzadkowanych danych na jednym strumieniu (ciagu) binarnie

ścieżka - skwencja nazw katalogów nadrzednych poprzedzajacyhc nazwę docelowego pliku

katalog - logiczna struktura, która agreguje informacje o położeniu plików i katalogów należących do tej struktury, w efekcie otrzymujemy strukturę drzewa

system plików - specyficzna dla systemu operacyjnego organizację danych informacyjnych o położeniach poszczególnych katalogów i plików



### Polecenia:



pwd - ścieżka robocza

mkdir - tworzy katalog

cd - zmiana katalogu

echo > plik.txt wpisanie w plik zamiast na terimnal

ls - zawartość katalogu

dir - zawartość katalogu

cat nazwa - wyświetla zawartość pliku/maszyna do pisania

start - tylko wsywietla plik

clear - czyscenie ekranu

restart - restart

rm - usuwanie pliku

rmmdir - usuwanie katalogu

rm -rf - wymusza usuniecie nawet jak katalog ma coś w sobie

cp - kopiowanie pliku

mv - zmiana nazwy/przesuniecie pliku

pushd - zmiana katalogu i zapamiętanie aktualnego katalogu roboczego

popd - powrót to zapamiętanego katalogu



* wewnętrzne - interpretowana przez Basha
* zewnętrzne - wykonywane przez zewnętrzny program



znaki specjalne



hash (#) - komentarz

cudzysłów (") - rozpoczyna i kończy łańcuch tekstowy jako dalsza część polecenia i rozwija zmienne

apostrof (') - rozpoczyna i kończy łańcuch tekstowy ale zmienne nie są rozwijane

backslah (\\) - przejście do nowej lini, zmiana znaczenia następującego po sobie znaku

dolar ($) - nadaje nazwe zmienej

średnik (;) - separacja poleceń

większy (>) - przekierowanie np. tekstu do pliku txt

wiekszy podwójny (>>) - wpisz na koniec pliku txt

mnijeszy (<) - odczytanie pliku

pipe (|) - połączenie wyjścia programu z wejściem po prawej

inne ((,),\[,],{,})



echo - wyświetla tekst który się napisze

&#x09;n - blokuje wystanie znaku nowej linii po zakończeniu polecenia

&#x09;e - włącza interpretowanie znaku backslash jako escape-sekwencji



### systemy plików:



* Windows: FAT12, FAT16, FAT32, exFAT, NTFS,
* Mac OS X: HPFS, HPFS+, AppleFS, FAT (r/w), NTFS (r)
* Linux: ext, ext2, ext3, ext4, ... (i prawie wszystkie powyżej)



## **WYKŁAD DRUGI**



### Zmiene:



zmiena - pewny parametr oznaczony przez nazwę składającą sie liter, cyfr i znaków

wielkosc znaków ma znaczenie



nadawanie wartosci zmienych



ZMIENA=wartosc

PRZEDMIOT="Narzedzie dla programistów"



unset - usuwanie zmiennych



## **WYKŁAD TRZECI**



bash rozróznia wilekie i małe litery



read - wpisuje wartosc do zmienej



zmiene specjlane - $? pokazuje kod zakończenia (kod błedu)



; - speracja poleceń



\&\& - drugie polecenia urchomia sie tylko wtedy jak pierwszy działą



|| - alternatywa - drugie działa jezeli pierwsze nie i na odwrót



test -f prawidzwe gdy jest plikiem

test -h prwadizwe gdy jest lnikiem symbolicznym



\-a plik istnieje

\-d

\-r

\-s

\-w plik istnieje i można go zapisać





