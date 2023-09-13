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
  
