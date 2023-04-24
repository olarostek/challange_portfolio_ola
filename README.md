# Task 1
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

Poniżej kilka kwestii dotyczących usability:

  - po kliknięciu "dodaj gracza" brak rozwijanej listy z pozycją zawodnika do wyboru,
  - w polu osiągnięcia można by było wygospodarować trochę więcej miejsca, pozostawienie tylko jednej linijki powoduje, że przy wielu osiągnięciach, informacje będą nieczytelne
  - nie do końca wiadomo co autor aplikacji miał na myśli zostawiając puste pole zatytułowane "łączy nas piłka" czy też "90 minut"


Nie można dodać listy zdarzeń przy edycji meczu.
Nie ma opcji zmiany danych statystycznych.
Po utworzeniu meczu, jego modyfikacji i powrocie na główną stronę pojawia się informacja o niezapisanym meczu, jednak po kliknięciu opcji "wróć do edycji" nie ma takiej możliwości


Aplikacja jest mało intuicyjna, powinna być na tyle prosta we funkcjonowaniu, aby nowa osoba nie musiała się zastanawiać co trzeba zrobić, aby dodać najważniejsze dane związane z umiejętnościami danego zawodnika.

