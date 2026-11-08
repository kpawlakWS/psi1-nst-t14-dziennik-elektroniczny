# 02. Słownik pojęć dziedziny

<!--
Zasady:
- Jedno pojęcie, jedna nazwa. Synonimy wpisujemy w osobnej kolumnie i NIE używamy ich w dokumentacji.
- Definicja w języku klienta, bez żargonu technicznego.
- Nazwa angielska posłuży w cz. 2 jako nazwa klasy/tabeli.
- Kolejność alfabetyczna.
-->

| Pojęcie | Nazwa ang. (dla kodu) | Definicja | Synonimy (niezalecane) | Przykład | Powiązane pojęcia |
|---|---|---|---|---|---|
|Dziennik elektroniczny| Electronic School Register | System informatyczny służący do rejestrowania i udostępniania informacji dotyczących przebiegu nauczania uczniów.
|Użytkownik |User| Osoba posiadająca konto umożliwiające korzystanie z systemu.
|Aktor| Actor | Osoba lub system zewnętrzny wchodzący w interakcję z projektowanym systemem.
|Interesariusz|Stakeholder |Osoba lub podmiot zainteresowany projektem, jego rezultatami lub mający wpływ na jego realizację.
|Rola użytkownika|User Role|Zestaw uprawnień określający zakres czynności dostępnych dla użytkownika.
|Ocena| Grade| Informacja określająca poziom osiągnięć edukacyjnych ucznia.
|Frekwencja|Attendance |Ewidencja obecności ucznia na zajęciach szkolnych.
|Nieobecność|Absence| Brak obecności ucznia na określonych zajęciach.
|Spóźnienie|Lateness|Przybycie ucznia na zajęcia po ich planowanym rozpoczęciu.
|Wiadomość|Message|Informacja tekstowa przekazywana pomiędzy użytkownikami systemu.
|Ogłoszenie| Announcement|Informacja przeznaczona do udostępnienia określonej grupie użytkowników.
|Klasa|Class|Grupa uczniów przypisana do określonego oddziału szkolnego.
|Przedmiot|School Subject|Dziedzina nauczania realizowana w ramach zajęć szkolnych.
|Nauczyciel|Teacher|Użytkownik odpowiedzialny za prowadzenie zajęć i dokumentowanie postępów uczniów.
| | | | | | |

## Wartości wyliczeniowe

<!-- Słowniki wartości: statusy, typy, kategorie. Przydadzą się w modelu danych. -->

### Status frekwencji

| Wartość | Znaczenie |
|---|---|
| OBECNY| Uczeń uczestniczy w zajęciach.|
| NIEOBECNY | Uczeń nie uczestniczy w zajęciach.|
| SPÓŹNIONY |Uczeń spóźnił się na zajęcia |
| NIEOBECNOŚĆ USPRAWIEDLIWIONA | Nieobecność ucznia została usprawiedliwiona.|
| NIEOBECNOŚĆ NIEUSPRAWIEDLIWIONA |Nieobecność ucznia nie została usprawiedliwiona. |

