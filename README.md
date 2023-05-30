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
- in, not in
- like
- is null, is not null

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

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/93299e22-f58e-496b-be47-9efa7b910ca3)

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

```
select * from customers
where customer_id = 2 or customer_id = 4 or customer_id = 6
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/a93d8c2f-c917-42cc-a776-bc3b638480b3)

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

```
select * from customers
where customer_id in (1, 3, 5)
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/a1411a3e-7494-4a0a-b185-9aaf1b517f7e)

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

```
select * from actors
where name like 'An%'
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/6a04afdf-1781-4ff5-869a-8a82e1f2e08d)

9. Wyświetl dane klienta, który nie ma podanego adresu email.

```
select * from customers
where email is null
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/f67fae51-d742-4ff9-a4f0-e1f4f9a72169)

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

```
select * from movies
where (price > 9) and (movie_id between 2 and 8)
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/ae94bc56-8848-4a4c-a720-ab9ad184c193)

# ``Task 6``

## Subtask 1

11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd.

```
update customers
set surname = 'Miler'
where surname = 'Muler' and name = 'Ania'
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/4b7b2fca-113e-4d33-b670-d835c8b1d915)

12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.

```
select s.movie_id, s.sale_date, c.customer_id, c.name, c.email
from sale as s
join customers as c on c.customer_id = s.customer_id
where s.movie_id = 4
order by s.sale_date desc
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/bde1e105-37cf-4f82-8920-07d6e86487c6)

13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com

```
select * from customers where name = 'Patrycja' ;

update customers
set email = 'pati@mail.com'
where customer_id = 4
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/ca4c1652-dfbe-4627-bf6d-98452277dcbf)

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/d90389a8-995f-4b8f-9c6b-7ce11ac65e7e)

14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).

```
select c.name, c.surname, m.title
from sale as s
join customers as c on c.customer_id = s.customer_id
join movies as m on m.movie_id = s.movie_id
order by c.surname, c.name
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/3cfeb99d-5643-473e-97e9-c1031f9ca477)

15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag

```
alter table customers add pseudonym varchar(20) default null ;

update customers
set pseudonym = concat(substring(name, 1, 2), substring(surname, -1, 1))
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/4f4bdd47-6f2e-41c7-a891-fddb7fff3925)

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/4e4d96ca-f64a-44cb-a32b-717404b8dca3)

16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

```
select distinct m.title
from sale as s
join movies as m on m.movie_id = s.movie_id
order by m.title
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/0b27a3fd-d44e-4322-a1b9-f180f18b8127)

17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

```
select name
from customers
union
select name
from actors
order by name
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/2c0865b1-1560-48c2-9d7b-549904341330)

18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

```
update movies
set price = price + 2.5
where year_of_production > 2000
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/83d960f5-f2a0-4bc8-98ad-6cbc80f2ae0a)

19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał

```
select a.name, a.surname, m.title
from cast c
join actors a on a.actor_id = c.actor_id
join movies m on m.movie_id = c.movie_id
where a.actor_id = 4
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/23cb87f9-8839-4779-bbd6-80c0f9f1507e)

20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa

```
insert into customers
(customer_id, name, surname, email, pseudonym)
values
(7, 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa')
```

![image](https://github.com/olarostek/challenge_portfolio_ola/assets/129790470/05227b19-ba3e-4303-877b-b1c182ecd7b0)

## Subtask 2

14 punktów

## Subtask 3

[My Portfolio](https://github.com/olarostek/MyPortfolio/blob/main/README.md)

