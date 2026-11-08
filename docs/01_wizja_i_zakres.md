# 01. Wizja i zakres systemu

## 1.1. Opis problemu

| | |
|---|---|
| **Problem** | Brak skutecznej komunikacji między rodzicami i nauczycielami,  niepełne informacje o ocenach i frekwencji|
| **dotyczy** | nauczyciele (w tym wychowawcy), rodzice, uczniowe, pozostały personel szkoły |
| **skutkiem jest** | chaos w organizacji i w komunikacji w relacjach nauczyciel-rodzic-uczeń |
| **dobre rozwiązanie** | Nauczyciel wstawia oceny i dane o frekwencji do dziennika elektroniczniego, rodzic w każdej chwili może to sprawdzić, logując się do systemu |

## 1.2. Cel biznesowy i mierniki sukcesu

<!-- Cele mierzalne (SMART), np. „skrócenie czasu obsługi rezerwacji z 10 do 3 minut”. -->

| ID | Cel | Miernik | Wartość docelowa |
|---|---|---|---|
| CEL-01 |Elektroniczne zarządzanie ocenami |Możliwość rejestracji ocen wszystkich objętych systemem uczniów |100% ocen uczniów rejestrowanych w systemie dziennika elektronicznego. |
| CEL-02 |Dostęp rodziców do informacji |Dostęp do ocen i frekwencji przez konto rodzica |100% rodziców posiadających aktywne konto z możliwością dostępu do informacji o ocenach i frekwencji swojego dziecka.|
| CEL-03 |Elektroniczna rejestracja frekwencji|Obsługa obecności, spóźnień i nieobecności | 100% wpisów dotyczących frekwencji rejestrowanych w systemie elektronicznym.|
| CEL-04 |Ochrona danych uczniów|Wszystkie testy uprawnień zakończone pozytywnie | 100% kont użytkowników objętych uwierzytelnianiem i kontrolą dostępu zgodną z przypisaną rolą.|
| CEL-05 |Komunikacja elektroniczna|Wymiana informacji między nauczycielami i rodzicami w postaci wiadomości | 100 % kont nauczycieli z możliwością wymiany wiadomości z rodzicami|

## 1.3. Interesariusze
Interesariusz – osoba lub podmiot zainteresowany projektem, jego rezultatami albo mający wpływ na jego realizację.

| ID | Interesariusz | Opis / rola | Oczekiwania wobec systemu | Wpływ (W/Ś/N) | Zainteresowanie (W/Ś/N) |
|---|---|---|---|---|---|
| INT-01 |Dyrektor szkoły |Nadzór nad funkcjonowaniem szkoły |dostęp do informacji i raportów |W |W |
| INT-02 |Nauczyciel |Prowadzenie zajęć, wystawianie ocen |Możliwość wstawiania ocen, frekwencji, komunikacji z rodzicami/opiekunami ucznia |Ś |W |
| INT-03 |Wychowawca |Opieka nad klasą, sprawy wychowawcze |Możliwość wstawiania ocen, frekwencji, komunikacji z rodzicami/opiekunami ucznia |Ś |W |
| INT-04 |Uczeń |Pobieranie nauki |Możliwość sprawdzenia własnych ocen i frekwencji |N |W |
| INT-05 |Rodzic/Opiekun |Opieka nad uczniem |Monitorowanie postępów dziecka, ocen, frekwencji i komunikatów |N |W |
| INT-06 |Administrator systemu |Zarządzanie systemem, dodawanie/usuwanie użytkowników/uprawnień |Zarządzanie kontami, uprawnieniami i konfiguracją systemu |W |W |
| INT-07 |Sekretariat szkoły |Obsługa danych uczniów i dokumentacji administracyjnej|Dostęp do systemu w celu uzupełnienia/zmiany danych ucznia |Ś |Ś |

## 1.4. Użytkownicy systemu (aktorzy)
Aktor – osoba lub system zewnętrzny bezpośrednio wchodzący w interakcję z projektowanym systemem.

| Aktor | Kim jest | Jak często korzysta | Kompetencje cyfrowe |
|---|---|---|---|
|Nauczyciel |Pracownik dydaktyczny odpowiedzialny za oceny, frekwencję i informacje o uczniach |Codziennie |Średnie/Wysokie |
|Wychowawca |Pracownik dydaktyczny odpowiedzialny za oceny, frekwencję i informacje o uczniach, dodatkowo opiekun wychowawczy klasy |Codziennie |Średnie/Wysokie |
|Uczeń |Osoba korzystająca z informacji o własnych postępach w nauce |Codziennie/Kilka razy w tygodniu |Podstawowe / Średnie |
|Rodzic/opiekun |Osoba monitorująca postępy edukacyjne dziecka |Codziennie/Kilka razy w tygodniu |Podstawowe / Średnie |
|Pracownik szkoły |Upoważniony pracownik sekretariatu lub referent |Codziennie |Średnie |
|Administrator |Osoba zarządzająca kontami, uprawnieniami i konfiguracją systemu |Regularnie, w zależności od potrzeb |Wysokie |

## 1.5. Zakres systemu

### 1.5.1 W zakresie (MVP — realizacja w cz. 2)

- Zarządzanie użytkownikami i uprawnieniami/Konta użytkowników, logowanie, role i kontrola dostępu
- Zarządzanie ocenami/Wprowadzanie, przeglądanie i aktualizowanie ocen uczniów
- Ewidencja frekwencji/Rejestrowanie obecności, nieobecności i spóźnień
- Informacje o uczniu/Dostęp do podstawowych danych ucznia, klasy i przypisania do nauczycieli
- Komunikacja i powiadomienia/Przekazywanie informacji między nauczycielami a rodzicami i uczniami

### 1.5.2 Poza zakresem (świadomie wyłączone)

- Obsługa płatności i rozliczeń - Nie należy do podstawowych zadań dziennika
- Rekrutacja i zapisy uczniów - Proces obsługiwany przez odrębne systemy
- Obsługa kadr i wynagrodzeń nauczycieli - Funkcjonalność systemu kadrowo-płacowego
- Natywna aplikacja mobilna na Android i iOS - W pierwszej wersji wystarczy interfejs przeglądarkowy
- Organizacja transportu i wyżywienia - Wykracza poza podstawowy zakres dziennika

### 1.5.3 Możliwe rozszerzenia (po MVP)
- Plan lekcji - Prezentowanie planu zajęć uczniów i nauczycieli wraz z informacją o zmianach.
- Zadania domowe i materiały dydaktyczne - Publikowanie zadań, materiałów i dodatkowych informacji do zajęć.
- Terminarz szkolny - Kalendarz sprawdzianów, wydarzeń, zebrań i ważnych terminów.
- Aplikacja mobilna	 - Dedykowana aplikacja na urządzenia z Androidem i iOS.
- Rozbudowane raportowanie - Zestawienia wyników nauczania, frekwencji i postępów uczniów.

## 1.6. Kontekst i systemy zewnętrzne

|System zewnętrzny | Możliwa rola |
|---|---|
|Usługa poczty elektronicznej|Wysyłanie powiadomień i wiadomości|
|Usługa SMS|	Przekazywanie wybranych powiadomień|
|System uwierzytelniania|	Opcjonalne zewnętrzne uwierzytelnianie użytkowników|

## 1.7. Założenia i ograniczenia

| Typ | Opis |
|---|---|
| Założenie | System przeznaczony jest do obsługi jednej placówki szkolnej;Użytkownicy posiadają indywidualne konta; Każdy użytkownik otrzymuje uprawnienia odpowiednie do swojej roli; Każdy użytkownik otrzymuje uprawnienia odpowiednie do swojej roli. |
| Ograniczenie | np. budżet: wyłącznie darmowe/otwarte technologie; realizacja w 1 semestr przez zespół N-osobowy |

## 1.8. Rozwiązania konkurencyjne / analiza istniejących narzędzi

| Rozwiązanie | Co robi dobrze | Czego brakuje | Wniosek dla naszego projektu |
|---|---|---|---|
|Vulcan |Ewidencja Ocen i obecności |Obecności dziecka na zajęciach pozalekcyjnych |Uzupełnić o moduł obecności na zajęciach pozalekcyjnych |
|Librus| Ewidencja Ocen i obecności | |Uproszczony dziennik skoncentrowany na najważniejszych potrzebach użytkownika |
