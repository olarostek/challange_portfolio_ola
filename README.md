# ``Task 1``
## Subtask 1
8 punktów
## Subtask 3
*Cześć! Nazywam się ``Ola``. Zdecydowałam się na udział w projekcie, gdyż w końcu postanowiłam wziąć życie w swoje ręce i nauczyć się czegoś, co pomoże mi je trochę zmienić 🙂 Chcę i potrzebuję zmienić pracę na taką, która pozwoli mi się rozwijać, ucząc się czegoś nowego, dać więcej satysfakcji i nie ukrywam, że więcej złotówek 🙃 W IT drzemie potencjał 😀 Chciałabym, aby projekt ten uchwycił i pokazał to, z czym na co dzień mierzą się testerzy.*
## Subtask 4
Aplikacja Scouts to aplikacja służąca do:
* obserwacji aktywnych graczy futbolowych w celach wyszukiwania talentów,
* wprowadznia nowych potencjalnych talentów

Polega na:

1. przeglądaniu zawodników futbolowych,
2. śledzenia ich aktywności zawodniczej,
3. śledzenia ich umiejętności,
4. tworzeniu raportów z uwzględnieniem różnych czynników


W czasie próby logowania pojawiają się pierwsze błędy:

* wpisując poprawny login, ale złe hasło informacja o niepoprawnym loginie lub haśle,  wyświetlana jest w języku angielskim, mimo iż wybrany jest język polski.
* niepoprawne dane do logowania powodują, że komunikat, który się pojawia przesuwa przyciski z wyborem języka i zaloguj w dół okna, co powoduje, że jest to nieestetyczne

Po zalogowaniu pokazuje nam się strona główna aplikacji, która jest czytelna i intuicyjna. Po przejściu do sedna, czyli po kliknięciu na graczy, wyświetlana tabelka pokazuje jasne i zrozumiałe informacje. Na tym jednak prostota się kończy. Brakujące elementy, które ułatwiłyby dalsze poruszanie się po aplikacji:

* widoczna możliwość filtrowania poprzez umieszczenie w nagłówku tabeli ikony filtrowania,
* możliwość przejścia do pierwszej i ostatniej strony (jest tylko możliwość przejścia na następną stronę),
* możliwość wyboru ilośći wyświetlanych rekordów na danej stronie.

Kolejne błędy, które zostały znalezione w zakładce Gracze:

* niepoprawnie działa funkcja sortowania graczy: klikając kursorem na imię, lista graczy posortowała się w następujący sposób: na samej górze listy pokazały się rekordy z pustym polem, klikając 3 razy na następną stronę zaczynają się pojawiać rekordy z wpisanym imieniem, jednak pokazują się one już niezgodnie z przyjętym typem sortowania: najpierw pokazały się rekordy zaczynające się od A (A, Adam), następnie pojawił się "Mateusz" a  pod nim "cv", następnie znaki specjalne, cyfry, aby ponownie na stronie 15 wyświetliły się rekordy rozpoczynające się od litery A.
* kolejnym błędem jest fakt, iż po najechaniu kursorem na opcję drukowania wyświetla się komunikat "drukuj" w języku angielskim, mimo iż wybrany jest język polski. Taka sama sytuacja wygląda w przypadku wybrania inncyh opcji: ściągnięcia pliku, filtrowania oraz wyświetlanych kolumn. Opcja mieszanego języka pojawia się w aplikacji w wielu miejscach, np. przyciski: submit i clear podczas dodawania graczy czy meczów
* po kliknięciu ikony drukowania, na podglądzie widzimy, że tabelka na wydruku nie będzie miała konstrukcji tabelki takiej jak widzimy na stronie aplikacji
* przy najechaniu kursorem na gracza, kursor nie zmienia się na na hand, przez co sugeruje, że z danymi nie można nic zrobić (a przecież da się edytować po kliknięciu),
* po wybraniu opcji edycji zawodnika, nie działa przycisk clear (po raz kolejny w języku angielskim),
* po dodaniu linka w polu "link do YouTube" brak aktywnego hiperłącza, podobnie jak i w miejscu na "profil facebook"
* podczas edycji meczu wpisując tylko jedno pole oznaczone gwiazką, wyświetla się komunikat (ponownie po angielsku), iż należy uzupełnić pole oznaczone gwiazdką, które znajduje się obok wcześniej wypisanego pola (tu w takiej sytuacji powinien pojawić się komunikat przy każdym polu oznaczonym gwiazdką)
* podczas dodawania meczu konkretnego zawodnika można wybrać datę przyszłą
* w edycji meczu można wpisać czas z wartością minusową,

Poniżej kilka błędów po wyborze edycji danego zawodnika:

* po utworzeniu meczu, jego modyfikacji i powrocie na główną stronę pojawia się informacja o niezapisanym meczu, jednak po kliknięciu opcji "wróć do edycji" nie ma takiej możliwości,
* kilkając w raport po lewej stronie, a następnie dodaj raport, zostajemy przekierowani nie na stronę z edycją raportu, ale na stronę z meczami (zły link przypisany do przycisku dodaj raport na górze strony), dopiero z tej pozycji, klikając w ikonę środkową możemy dodać nowy raport do meczu,
* po kliknięciu w "submit" otwiera nam się strona, w której możemy na dole mamy link przekierowujący na stronę www.futboldetektyw.pl, jednak po kliknięciu w nią, wyskakuje komunikat, iż taka strona nie została znaleziona (błąd w elemencie a)
 

Poniżej kilka kwestii dotyczących usability:

  - po kliknięciu "dodaj gracza" brak rozwijanej listy z pozycją zawodnika do wyboru,
  - w polu osiągnięcia można by było wygospodarować trochę więcej miejsca, pozostawienie tylko jednej linijki powoduje, że przy wielu osiągnięciach, informacje będą nieczytelne
  - nie do końca wiadomo co autor aplikacji miał na myśli zostawiając puste pole zatytułowane "łączy nas piłka" czy też "90 minut"


Podsumowując aplikacja jest mało intuicyjna, powinna być na tyle prosta we funkcjonowaniu, aby nowa osoba nie musiała się zastanawiać co trzeba zrobić, aby dodać najważniejsze dane związane z umiejętnościami danego zawodnika.

# ``Task 2``
## Subtask 1
https://docs.google.com/document/d/17D-BikjEUZibNXc3xewLm7Wyb_F6susp9aSmoBRhKGc/edit?usp=sharing
## Subtask 2
https://docs.google.com/document/d/1yb9OE22LTHD5NW46WWSOaZNwbMr_1ym8CrZOQzPN3GE/edit?usp=sharing

## Subtask 3
Przypadki testowe to bardzo ważny aspekt procesu testowania oprogramowania. Pisząc przypadki testowe opisujemy tym samym kroki, które trzeba wykonać, aby sprawdzić działanie konkretnej funkcjonalności systemu lub też apliakcji.
Przypadki testowe umożliwiają:

* zaplanowanie testów
* uporządkowanie testów,
* powtórzenie dokładnych kroków do odtworzenia przez każdego testera

Wszystko po to, aby móc zweryfikować czy określona funkcjonalność działa zgodnie z oczekiwaniami.
Pisanie przypadków testowych umożliwia więc prawidłowe testowanie systemu, aplikacji, co w konsekwencji przekłada się na poprawę niezawodności tworzonego oprogramowania. Pozwala dodatkowo lepiej zrozumieć oczekiwania biznesowe, co w konsekwencji przyczyni się do zadowolenia klienta i prawidłowej współpracy pomiędzy uczestnikami. Dobrze przetestowany produkt to duże prawdopodobieństwo wypuszczenia produktu spełniającego oczekiwania nie tylko klienta, ale przede wszystkim użytkowników.

## Subtask 4
https://docs.google.com/spreadsheets/d/1VgJt98b6bYua1-8JfPPsxL6sXEJKsAZaQiAxdqr93Bk/edit?usp=share_link

# ``Task 3``
## Subtask 1
https://docs.google.com/spreadsheets/d/1VfiKt3gnKMrn8xvNtIucffeSJgK9-ok_r4UU9uagUXg/edit?usp=sharing

## Subtask 2
https://docs.google.com/spreadsheets/d/1Yfqzht6YNsvPOchZkJMm4pjl2nOUyDE4RnX3iv3WD1g/edit?usp=sharing

## Subtask 3
https://docs.google.com/document/d/1efpFIAwh7yte6ytrQ_yFsukAgknW98ZSztR-xsCVtd0/edit?usp=sharing

# ``Task 4``
## Subtask 1
https://docs.google.com/spreadsheets/d/1fjltdKRO-ytSKI8-HGjfd3qDA8tD1H5Vkipo0Z1uTOU/edit?usp=drive_web&ouid=117693323209969745448

## Subtask 3

1. Aplikacja ta służy przede wszystkim do:

* przeglądania w celach zakupowych różnych ofert użytkowników społeczności korzystającej z tej aplikacji,
* finalizacji procesu przeglądania,
* sprzedaży 
* umożliwienie nawiązania kontaktu pomiędzy kupującymi i sprzedającymi,

2. Użytkownikami końcowymi aplikacji są 2 rodzaje grup:

* osoby, które chcą sprzedać swoje produkty,
* osoby, które poszukują różnych produktów

3. Wg mojej opinii aplikacja jest user friendly. Posiada wszystkie cechy aplikacji przyjaznej dla końcowego użytkownika:

* intuicyjność,
* przyjazny interfejs,
* szybkie łączenie się z pomocą,
* szybką odpowiedź na działania użytkownika (responsywność)
* przejrzystą, uporządkowaną treść

4. Usprawnienia, które mogłyby ulepszyć aplikację:

* zdjęcia powinny mieć możliwość przeglądania w poziomie
* możliwość wyszukiwania kategorii za pomocą pola do wyszukiwania - aktualnie brak takiej możliwości,
* możliwość wybrania profilu użytkownika, którego aktualnie jest oglądany przedmiot sprzedaży poprzez kliknięcie nazwy jego profilu

5. Podstawowe różnice pomiędzy testowaniem aplikacji mobilnych a webowych

* różne platformy: 
1. webowe - tu uruchamiamy przeglądarki internetowe na 
   1. urządzeniach komputerowych, 
   2. smartfonach, 
   3. tabletach
2. urządzenia mobilne:
   1. smartfony, 
   2. tablety
* różne testy - aplikacje webowe wymagają testów, które będą sprawdzały ich kompatybilność z różnymi sensorami (ekran dotykowy, kamera, GPS)
* testy bezpieczeństwa - w apliakcjach mobilnych koniecznie jest uwzględnienie bezpieczeństwa urządzeń jak i sieci, w której działa dane urządzenie
* testowanie wydajności, stabilności aplikacji mobilnych jest ważniejsze niż w przypadku aplikacji webowych - apliakacje mobilne muszą być bardzo responsywne, by nie zniechęcić użytkownika do dalszego z nich korzysatania
* oprogramowanie - narzędzia do testowania aplikacji webowych działają w przeglądarkach internetowych, z kolei narzędzia do testowania aplikacji mobilnych muszą być dostosowane do szczególnych wymagań platform mobilnych, wymagają też ich instalacji na tych urządzeniach

# ``Task 5``

## Subtask 1

### Poznane zapytania, komendy

- create table
- insert into
- select from

### Poznane klauzule, operatory

- order by
- where
- between
- =, <, >, <=, >=
- and, or

## Subtask 3

1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

```
select * from actors
order by surname
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/48e3383b-d4f4-4067-b1d1-525bd07975d6)

2. Wyświetl film, który powstał w 2019 roku.

```
select * from movies
where year_of_production = 2019
```
![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/1197791e-dba8-48b8-89c9-bc3356d0c1d4)

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

```
select * from movies
where year_of_production between 1900 and 1999
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/9616605e-f533-4f9f-9770-4e0728274adc)

4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$

```
select title, price from movies
where price < 7.0
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/3cb10414-5f8f-4842-b13e-5007c2bc9db6)

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

```
select * from actors
where actor_id >= 7 and actor_id <= 9
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/13ccab18-1ee1-4fde-a713-c3c3a20bef8f)

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

```
select * from 
```

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

```
select * from 
```

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

```
select * from 
```

9. Wyświetl dane klienta, który nie ma podanego adresu email.

```
select * from 
```

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

```
select * from 
```
