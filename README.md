# challenge_portfolio_Aleksandra
# TASK 1
 - 👉[Subtask 1](#Subtask-1)
 - 👉[Subtask 3](#Subtask-3)
 - 👉[Subtask 4](#Subtask-4)
 
## Subtask 1
8/10 punktów :blush: 
## Subtask 3

Cześć,

nazywam się Ola. Do udziału w projekcie zgłosiłam się z chęcią ustrukturyzowania posiadanej już wiedzy oraz stworzenia atrakcyjnego portfolio. Mam nadzieję, że w ciągu tych 7 tygodni nie tylko poszerzę swoje kompetencje ale również poznam ciekawych ludzi.  

Moim głównym celem jest zdobycie nowej pracy.

## Subtask 4
### Na czym polega aplikacja?
Aplikacja **Scouts Panel** jest aplikacją dedykowaną dla sportowych łowców talentów specjalizujących się w dziedzinie piłki nożnej. Umożliwia przeglądanie wskaźników, umiejętności i pozycje zawodników. Dostępna jest pod adresem: _https://scouts-test.futbolkolektyw.pl/_, a wgląd do danych mają tylko zarejetrowani użytkownicy.

### Jakie funkcjonalności znajdują się w aplikacji? Co bym zmieniła?
#### Panel logowania
- Logowania.
- Funkcja wysłania maila z przypomnieniem hasła.
  
#### Strona główna
Sekcja paska nazwy aplikacji

W tej sekcji znajduje się tylko nazwa aplikacji, dodałabym tutaj logo aplikacji z sekcji _"Scouts Panel"_.

Sekcja Menu nawigacji (boczna) 
- Funkcjonalność przejścia do strony głównej
- Funkcjonalność przejścia do listy graczy.
- Funkcjonalność zmiany języka ( możliwość wyboru między językiem, polski i angielskim).
- Funkcja wylogowania z aplikacji.

W tej sekcji funkcjonalność przejścia do strony głównej jest zbędna ponieważ użytkownik już się na niej znajduje.

Sekcja "Dodaj gracza"
- Funkcjonalność dodania nowego gracza.

Całą sekcję prezniosłabym w lewy górny róg aplikacji (nad sekcję _"Scounts Panel"_) ponieważ znajdując się na środku strony przy takim dużym odstępnie wygląda jak błąd.

Sekcja Informacji o Ilości utworzonych raportów.
- Licznik graczy, meczy, raportów, akcji.
  
Zgrupowałabym rekordy wyżej wymienionymi informacjami w orientacji pionowej, gdyż w ten sposób zgrupowane sią pozostałe sekcje.

Sekcja Aktywności
- Funkcja wyświetlania informacji o ostatnio zmienionych pozycjach: stworzonym graczu, zzaktualizowany gracz, stworzony mecz, zaaktualizowany mecz,  zaaktualizowany raport.

#### Strona dodawania gracza
- Funkcjonalność dodania gracza po uzupełnieniu informacji o graczu.
- Funkcjonalność dodania informacji o znajoomości języków obcych.
- Funkcjonalność dodania linku z Yutube.
- Funkcjonalność usunięcia danych o graczu.

Zmniejszyłabym przyciski _'Dodaj język"_ oraz _"Dodaj link z Youtube"_ oraz opcjonalnie zmieniłabym ich kolor, aby przycisk dodawania lub usunięcia gracza wybijał się na pierwszy plan (Użytkownik widzi od razu w któym miejscu dodaje się cały formularz. 

#### Strona dodawania meczu dla gracza
- Funkcjonalność dodania gracza po uzupełnieniu informacji o meczu.
- Funkcjonalność dodania informacji o znajoomości języków obcych.
- Funkcjonalność dodania linku z Yutube.
- Funkcjonalność usunięcia danych o meczu.

Tak jak na stronie dodawania gracza zmieniłabym wygląd przycisków.
  
#### Strona z listą graczy
- Lista utworzonych graczy z kolumnami (Imię, Nazwisko, Wiek, Pozycja, Klub, Recenzja).
- Funkcjonalność pobierania listy jako plik CSV.
- Funkcjonalność wdrukowania listy.
- Funkcjonalność zmiany ilości wyświeltanyc kolumn.
- Fukcjonalność wyszukiwania gracza po filtrach (Imię, Nazwisko, Wiek min/max, Pozycja, Klub, Wynik min/max).

### Czy aplikacja jest intuicyjna?
Aplikacja jest raczej intuiczyjna, jest to zasługą stosunkowo małej liczby fukcji. Aby uprościć poruszanie się po aplikacji warto dodać przyciski powrotu. 


### Jakie zauważam błędy? Co wydaje mi się błędem? 
#### Panel logowania
- (Wersja PL) Po nieudanej próbie logowania, komunikat wyświetla się w języku angielskim.
- (Wersja PL i EN) W Funkcjonalności _Przypomij hasło_ brak informacji o błędnie wypełnionym (brak znaku @) oraz przy nie uzupełnionym polu. W obu przypadkach wyświetlny zostaje komunikat o wysłaniu maila z przypmnieniem.
- (Wersja PL i EN) Brak możliwości dodania nowego użytkownika.
- (Wersja PL i EN) Wprzypadku niezapisania meczu w lewym dolnym rogu wyświetlana jest sekcja _"Niezapisany mecz"_, link _"Wróć do raportu" nie przekierowuje do strony z raportami.

#### Strona główna
- (Wersja PL) Sekcja _Dodawania gracza_ jest zatytułowana nie intuicyjnie **Linki pomocznicze**.
- (Wersja PL) W sekcji  _Scouts Panel_ link przenoszący do zespołu programistycznego nie jest przetłumaczony.

#### Strona dodawania gracza
- (Wersja PL) Przycisk z funkcją _Dodaj_ i _Usuń_ nie ma polskiego tłumaczenia.
- (Wersja EN) Komunikaty o braku uzupełnionych pól wyświetlają się w języku polskim.
- (Wersja EN) Tytuły pól _Łączy nas piłka_ i _90 minut_ nie posiadają tłumaczenia w  języku angielskim.
- (Wersja PL i EN) Po próbie dodania gracza, w przypadku nie uzupełnienia wszystkich wymaganych pól, komunikat informuje tylko o 1 pierwszym w kolejności nieuzupełnionym polu (zamiast o wszystkich wymaganych).
- (Wersja PL i EN) Brak informacji o błędzie w przypadku dodania gracza z błędną datą urodzenia (np. 2 tys lat temu, z przyszłosci).
- (Wersja PL i EN) Możliwość dodania gracza z niepoprawną wagą (np. ujemną)
- (Wersja PL i EN) Możliwość dodania gracza z niepoprawnym wzrostem (np. ujemnym)

#### Strona dodawania meczu dla gracza
- (Wersja PL) Tytuły pól _Web match_ i _General_ nie posiadają tłumaczenia w  języku polskim.
- (Wersja PL) Przycisk z funkcją _Dodaj_ i _Usuń_ nie ma polskiego tłumaczenia.
- (Wersja EN) Komunikaty wyświetlane są w języku polskim.
- (Wersja PL i EN) Brak ograniczenia liczby znaków w polach.
- (Wersja PL i EN) Po próbie dodania meczu, w przypadku nie uzupełnienia wszystkich wymaganych pól, komunikat informuje tylko o 1 pierwszym w kolejności nieuzupełnionym polu (zamiast o wszystkich wymaganych).
- (Wersja PL i EN) Możliwość dodania meczu z niepoprawną datą (np. w przysłości).

#### Lista graczy
- (Wersja PL) W sekcji funkcjonalności wyszukiwania gracza, przycisk _"Filtruj"_ i _"Resetuj"_ nie zostały przetłumaczone na język polski.
- (Wersja PL) Po najechaniu na ikony, podpowiedzi wyświetlają się w języku angielskim.

# TASK 3
Zadanie Task 3 zostało wykonane dla aplikacji _dareit.futbolkolektyw.pl_ w środowisku produkcyjnym. Plan testów oraz raport został opublikowany w arkuszu Excel pod linkiem: https://drive.google.com/drive/u/0/folders/1UR2puhAVboBAhpV2ZmQCMOp9ILxboQdy . 

# TASK 4
## Subtask 2
Zadanie Subtask 2 zostało wykonane dla aplikacji OLX pobranej w Sklepie Play na urządzeniu XIAOMI MI11 Lite 5G. Raport został opublikowany w arkuszu Excel pod linkiem: https://drive.google.com/drive/u/0/folders/1UR2puhAVboBAhpV2ZmQCMOp9ILxboQdy . 

## Subtask 3

#### Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?
Aplikacja OLX to aplikacja ogłoszeniowa, służy do kontaktu pomiędzy użytkownikami głównie kupującymi i sprzedającymi oraz pracodawcami i potencjalnymi pracownikami.

#### Kto ma być użytkownikiem końcowym aplikacji?
Użytkownikiem końcowym są osoby prywatne oraz firmy, które nawiązały kontakt z ogłoszeniodawcą.

#### Czy według Ciebie aplikacja jest user friendly? 
Aplikacja jest user friendly ze zwględu na swoją intuicyjność oraz nowoczesny design.
**Aplikacja charakteryzuje się wieloma cechami przyjaznymi użytkownikom:**
- Samouczek
Podczas pierwszego otwarcia alikacji oraz poszczególnych obszarów, wyświetlana jest któtka informacja. Nowy użytkownik nie przeklikuje się przez dziesiątki informacji ale jednocześnie wie do czego służy dany obszar.

- Wielokość ikonek i podpisy
Wielkość ikonek w stosunku do całego ekranu zosatła dobrze dobrana. Dodatkowo zarówno większe ikonki np. Kategorii jak i mniejsze w dolnej części ekranu - Menu, zosatły podpisane słowem kluczowym.

- Tryb wyświetlania, LIst ofert
Użytkownik ma możliwość zmiany prezentacji ofert - galeria, lista, mozaika

- Tryb ciemnego ekranu
Aplikacja domyślnie dostosowuje się trybem do ustawień urządzenia, a w ustawienich aplikacji użytkownik ma możliwość zmiany trybu. 

- Kompatybilność z innymi apliakcjami
Użytkownik ma możliwość utworzenia konta za pomocą maila oraz z wykorzysatniem istniejących kont - Apple, Google, Facebook

- Powiadomienia
Użytkownik ma możliwość wyboru informowania lub nie informowania o powiadomieniach na urządzeniu podczas nieotwartej aplikacji

- Bezpieczeństwo kupujących
Przed wystawieniem ogłoszenia aplikacja wymaga weryfikacji tożsamości użytkownika za pomocą numeru telefonu

- Szybkość działania
Aplikacja działa szybko, użytkownik nie czeka na ładowanie poszczególnych obszarów.

**Cechy które utrudniają korzystaie z aplikacji:**
- brak podziału na strony (np. co 20 pozycji) wyników wyszukiwania.
Ciągły scroling może wciągać użytkownika w niekończące się rolowanie przez co może on spędzić więcej czasu na wyszukiwaniu niż początkowo zamierzał. Nie jest też wstanie oszacować w którym momencie rolowania znalazł interesujący go przedmiot w przypadku gdy nie zapisze go w sekcji Ulubione. 

#### Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?
Aby poprawić łatwość ponownego wyszukiwania przedmiotu podzieliłabym sekcję znaleźionych ogłoszeń po kilkukrotność pozycji np. co 20, 50 100. Dzięki czemu użytkownik, który po jakimś czasie powróci do wyszukiwania będzie mógł zacząć wyszukiwanie np. od strony 5, a nie jak do tej pory od pierwszej pozycji.

#### Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?
Testowanie aplikacji natywnej uwzględnia również weryfikację responsywności względem róznych urządzeń oraz czytelnośći dla mniejszego ekranu urządzenia. Testowany jest dodatkowo wpływ aplikacji na urządznie taki jak wpływ na żywotność baterii czy pracę w tle.   

# TASK 5
## Subtask 1  Krótki opis operatorów i zapytań SQL
### Operatory
Służą do zdefiniowania warunków zapytań oraz łączenia wielu warunków. Wyróżniamy 4 typy operatorów: artymetyczne, porównawcze, logiczne, inne.
#### Operatory artymetyczne 

| Operator      | Definicja                                                  | 
|:-------------:|:-----------------------------------------------------------|
| +             | dodawanie                                                  |
| -             | odejmowanie                                                |
| *             | mnożenie                                                   |
| /             | dzielenie                                                  |
| %             | modulo - zwraca pozostałą część liczb całkowitych dzielenia|

#### Operatory porównania

| Operator 	    |Definicja                                                                                                                                 |
|:-------------:|:-----------------------------------------------------------------------------------------------------------------------------------------|
| =             |Sprawdzenie czy wartości po obu stronach operatora są równe czy nie. Jeżeli tak to warunek jest prawdziwy.                                | 
| !=            |Sprawdzenie czy wartości po obu stronach operatora są równe czy nie. Jeżeli nie to warunek jest prawdziwy.                                |
| <>            |Sprawdzenie czy wartości po obu stronach operatora są równe czy nie. Jeżeli nie to warunek jest prawdziwy.                                |
| > 	           |Sprawdzenie czy wartość po lewej stronie operatora jest większa. Jeżeli tak to warunek jest prawdziwy.                                    |
| < 	           |Sprawdzenie czy wartość po lewej stronie operatora jest mniejsza. Jeżeli tak to warunek jest prawdziwy.                                   |
| >=            |Sprawdzenie czy wartość po lewej stronie operatora jest większa bądź równa prawej stronie. Jeżeli tak to warunek jest prawdziwy.          |
| <=            |Sprawdzenie czy wartość po lewej stronie operatora jest mniejsza bądź równa prawej stronie. Jeżeli tak to warunek jest prawdziwy.         |
| !< 	          |Sprawdzenie czy wartość po lewej stronie operatora jest nie mniejsza od wartości po prawej stronie. Jeżeli tak to warunek jest prawdziwy. |
| !> 	          |Sprawdzenie czy wartość po lewej stronie jest nie większa od wartości po prawej stronie. Jeżeli tak to warunek jest prawdziwy.            |

#### Operatory logiczne

| Operator 	    |Definicja                                                                                                                                                                    |
|:-------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ALL           |Operator służy do porównania wartości ze wszystkimi wartościami w innym zestawie wartości. Warunek jest prawdziwy jeżeli wszystkie wartości pod-zapytania spełniają warunek. | 
| ANY           |Operator służy do porównania wartości z jakąkolwiek wartością w innym zestawie wartości. Warunek jest prawdziwy jeżeli którakolwiek wartość pod-zapytania spełnia warunek.   |
| AND           |Operator pozwala na łączenie wielu warunków w klauzuli WHERE.                                                                                                                |
| BETWEEN       |Operator pozwala na wyszukiwanie wartości, które mieszczą się w zdefiniowanym zbiorze wartości. Definicja zbioru opiera się na wartości minimalnej oraz maksymalnej.         |
| EXISTS        |Operator pozwala na sprawdzenie czy dany rekord istnieje w pod-zapytaniu.                                                                                                    |
| IN            |Operator pozwala na określenie wielu wartości w klauzuli WHERE.                                                                                                              |
| LIKE          |Operator pozwala na porównanie wartości z wartościami podobnymi przy zastosowaniu operatorów wieloznacznych.                                                                 |
| NOT	          |Operator negujący służy do odwrócenia znaczenia operatora logiczego z którym jest używany. Prostymi przykładami użycia są: NOT IN, NOT EXISTS, etc.                          |
| OR 	          |Operator pozwala na łączenie wielu warunków w klauzuli WHERE.                                                                                                                |
| IS NULL       |Operator pozwala na dokonanie porównania z 'wartością' NULL.                                                                                                                 |
| UNIQUE        |Operator pozwala na przeszukanie każdej tabeli pod kątem niepowtarzalności rekordów.                                                                                         |

### Priorytety operatorów 


| lp.     | Operator                   | 
|:-------------:|:---------------------|
| 1. | ( )                             | 
| 2. | * , /, %                        |  
| 3. | + , _                           |
| 4. | =, <, >, <=, >=, <>, !=, !<, !> |
| 5. | NOT                             | 
| 6. | AND                             |
| 7. | BETWEEN, IN, LIKE, OR           |
| 8. | = (przypisanie)                 |

### Zapytania
Są to polecenia wyszukiwań danych w bazie np. SELECT * FROM _nazwa-tabeli_ (gwaizdka oznacza, że należy wyszukać wszystkie kolumny tabeli).

#### Klauzule

| Klauzula      | Definicja                                              | 
|:-------------:|:-------------------------------------------------------|
| SELECT        |  określanie kształtu wyniku, selekcja pionowa (kolumn) |
| FROM          | określenie źródła (źródeł) i relacji między nimi       |  
| WHERE         | filtracja rekordów                                     |
| GROUP BY      | grupowanie rekordów                                    |
| HAVING        | filtrowanie grup                                       | 
| ORDER BY      | sortowanie wyniku                                      |

## Subtask 2 Krótki opis operatorów i zapytań SQL
## Subtask 3 Zadania 

####  1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/64ea23bd-d1ab-4c9b-b823-554d61e472a8)

####  2. Wyświetl film, który powstał w 2019 roku.
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/8990fdfc-2fee-4e86-9073-8b8cb8fa0189)

####  3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/b4336e51-b2c5-4cec-96c2-98519054f262)

####  4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/f0cf9935-676d-4409-9112-b21cfb42998b)

####  5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/b757bad0-0e89-4714-917d-3a2864084336)

####  6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/d2968c01-42b3-465c-bda5-6d2a1f4ba8bf)

####  7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/181f1fa3-f851-4b5b-bf0b-44d5001793af)

####  8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/a447931c-c2be-4c5a-96dc-7ee3f7c7ac71)

####  9. Wyświetl dane klienta, który nie ma podanego adresu email.
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/d46be3cc-e772-43a9-90da-139be0aa1abf)

#### 10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/fb144af6-80f1-4b88-a22d-b55a17df0d86)

## Pytania rekrutacyjne

👉 Co to jest SQL? <br>
SQL (Structured Query Language) to język programowania w postaci strukturalnego języka zapytań opartego o cztery polecenia SQL – Data Manipulation, Data Query, Data Control oraz SQL Data Definition. Język ten służy do tworzenia baz danych oraz ich modyfikacji i manipulacji danymi, które się w nich znajdują. Procesy te realizuje się w języku SQL.

👉 Co robi SELECT w zapytaniach SQLowych? <br>
SELECT jest to podstawowa klauzula SQL - używana do wyszukiwania danych w tabeli. Występuje wraz z klauzulą FROM.

👉 Co robi * postawiona za SELECTem  w zapytaniach SQLowych? <br>
Gwiazdka oznacza, że należy wyszukać wszystkie kolumny tabeli.

# TASK 6
## Subtask 1  Kurs podstaw SQL
#### 11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/fcb78a84-cd17-47ad-889e-18ee59ea732b)

#### 12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/f6cd5385-ef0e-4b1d-8a57-349343f965be)

#### 13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/a9a20b81-ce3b-4836-b0c5-e943a3d2dac9)

#### 14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/934179c1-869b-407a-871d-209281486178)

#### 15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. 
- Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,
  ![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/84557efe-ad25-461b-b37e-5340a027d20a)
- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag
  ![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/ae19b5f3-dd26-4f95-91ae-6dc2a4bdb6ee)

#### 16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/9999a663-8ce5-4d8a-b727-596724974970)

#### 17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/f1e0da50-151e-4df7-80f0-2cedc439ad7f)

#### 18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/0b9e889d-bd14-4f05-9be2-d21b01fe67e4)

#### 19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/393461e8-c23e-4943-8414-1d91936b02a7)

#### 20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa
![obraz](https://github.com/Aleksandra-Tarnawska/challenge_portfolio_Aleksandra/assets/75180405/cd70c0b1-2227-4e23-a141-776852ce3074)

## Subtask 2 Test 
Test z zakresu sylabusa ISTQB (zestaw pytań ECRU) znajduje się na stronie http://getistqb.com/. Mój wynik to 13/15 pkt.

## Subtask 3 Portfolio

## Pytania rekrutacyjne

👉 Do czego służy komenda Alter table.
Instrukcja ALTER TABLE pozwala na zmianę struktury istniejącej tabeli: dodania lub usuwania kolumn, tworzenia lub usuwania indeksów, zmieniania typów lub kolejności istniejących kolumn oraz zmieniania nazwy kolumn i  tabel. Pozwala również na edycję komentarzy do tabeli lub jej typu.

👉 Rozwiń skrót SQL
SQL - Structured Query Language.

👉 Jaka jest różnica pomiędzy SQL a MySql?
SQL to język zapytań bazy danych, a MySQL to system zarządzania relacyjną bazą danych. 

