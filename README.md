# Dziennik elektroniczny (uproszczony)

> Projekt zespołowy systemu informatycznego, cz. 1 (dokumentacja), semestr zimowy 2026/27, studia niestacjonarne.
> Temat nr **[14]**: [Dziennik elektroniczny (uproszczony) ]

## O systemie

Dziennik elektroniczny zastępuje tradycyjną, papierową dokumentację przebiegu nauczania i rozwiązuje szereg problemów komunikacyjnych, organizacyjnych oraz logistycznych, z którymi codziennie mierzą się szkoły, nauczyciele, rodzice i uczniowie: 
- natychmiastowy dostęp do ocen, uwag, frekwencji i planu lekcji dla wszystkich zainteresowanych stron.
- bezpośredni, całodobowy komunikator zastępujący nieodebrane telefony i inne niedogodne formy komunikacji między kadrą pedagogiczną a rodzicami.
- rozwiązanie problemu chaosu organizacyjnego i konfliktów poprzez blokowanie możliwości wpisania zbyt wielu sprawdzianów w tygodniu oraz likwidacja kolejek nauczycieli po fizyczny dziennik w pokoju nauczycielskim.

Dziennik elektroniczny jest dostępny zarówno poprzez komputer stacjonarny, jak też przez urządzenia mobilne.

## Zespół

| Osoba | Login GitHub/GitLab | Rola główna | Role dodatkowe |
|---|---|---|---|
|Kacper Pawlak | @kpawlakWS | Kierownik projektu | |
| Kacper Pawlak | @kpawlakWS | Analityk wymagań | |
| Kacper Pawlak | @kpawlakWS| Architekt / projektant BD | |
| Kacper Pawlak | @kpawlakWS | Projektant UX/UI | |
| Kacper Pawlak | @kpawlakWS| QA / wdrożenie | |

### Macierz odpowiedzialności (RACI)

R = wykonuje, A = odpowiada (tylko jedna osoba), C = konsultowany, I = informowany

| Sekcja dokumentacji | PM | Analityk | Architekt | UX/UI | QA/wdrożenie |
|---|---|---|---|---|---|
| 00 Zarządzanie projektem | A | C | C | C | R |
| 01 Wizja i zakres | A | R | C | C | I |
| 02 Słownik | C | A | R | C | I |
| 03 Wymagania | C | A | C | R | R |
| 04 Procesy i UC | I | A | R | C | C |
| 05 Architektura | C | C | A | I | R |
| 06 Model danych | I | C | A | I | C |
| 07 Interfejs | C | R | I | A | C |
| 08 Bezpieczeństwo | C | C | A | C | R |
| 09 Wdrożenie | I | I | C | I | A |
| 10 Testy | C | R | C | C | A |
| 11 Plan realizacji | A | C | R | R | R |
| Macierz śledzenia | C | R | C | C | A |
## Dokumentacja

| Nr | Dokument | Właściciel | Status |
|---|---|---|---|
| 00 | [Zarządzanie projektem](docs/00_zarzadzanie.md) | | ⬜ |
| 01 | [Wizja i zakres](docs/01_wizja_i_zakres.md) | | ⬜ |
| 02 | [Słownik pojęć](docs/02_slownik.md) | | ⬜ |
| 03 | [Wymagania](docs/03_wymagania.md) | | ⬜ |
| 04 | [Procesy i przypadki użycia](docs/04_procesy_i_przypadki_uzycia.md) | | ⬜ |
| 05 | [Architektura](docs/05_architektura.md) + [ADR](docs/adr/) | | ⬜ |
| 06 | [Model danych](docs/06_model_danych.md) | | ⬜ |
| 07 | [Interfejs użytkownika](docs/07_interfejs_uzytkownika.md) + [makiety](docs/makiety/) | | ⬜ |
| 08 | [Bezpieczeństwo](docs/08_bezpieczenstwo.md) | | ⬜ |
| 09 | [Wdrożenie](docs/09_wdrozenie.md) | | ⬜ |
| 10 | [Testy i jakość](docs/10_testy_i_jakosc.md) | | ⬜ |
| 11 | [Plan realizacji cz. 2](docs/11_plan_realizacji.md) | | ⬜ |
| — | [Macierz śledzenia wymagań](docs/macierz_sledzenia.md) | | ⬜ |

Statusy: ⬜ nie rozpoczęto · 🟨 w trakcie · 🟩 gotowe do recenzji · ✅ zatwierdzone

## Kamienie milowe

| Tag | Zawartość | Termin | Oddano |
|---|---|---|---|
| `m1` | repozytorium i tablica zadań, zespół i RACI, wizja i zakres, interesariusze, rejestr ryzyk, wstępny słownik, ćwiczenie git, pytania do wywiadu | 8.11.2026 | |
| `m2` | słownik, wymagania WF/WNF z MoSCoW, reguły biznesowe, historyjki z kryteriami akceptacji, C4 kontekst, protokół wywiadu, aktualizacja zakresu | | |
| `m3` | UC, procesy, model dziedziny, ERD, architektura, ADR, bezpieczeństwo | | |
| `m4` | UI, wdrożenie, testy, plan realizacji, macierz śledzenia | | |
| `v1.0` | wersja końcowa | | |

## Konwencje

Zasady pracy z repozytorium opisuje [CONTRIBUTING.md](CONTRIBUTING.md).

### Identyfikatory artefaktów

| Prefiks | Artefakt | Przykład |
|---|---|---|
| `CEL-` | cel biznesowy | CEL-01 |
| `INT-` | interesariusz | INT-01 Recepcjonistka |
| `RB-` | reguła biznesowa | RB-01 |
| `WF-` | wymaganie funkcjonalne | WF-07 |
| `WNF-` | wymaganie niefunkcjonalne | WNF-03 |
| `US-` | historyjka użytkownika | US-12 |
| `PB-` | proces biznesowy | PB-02 |
| `UC-` | przypadek użycia | UC-05 |
| `EKR-` | ekran / makieta | EKR-04 |
| `ADR-` | decyzja architektoniczna | ADR-0003 |
| `TC-` | przypadek testowy | TC-21 |
| `RYZ-` | ryzyko | RYZ-02 |

Identyfikatora raz nadanego **nie zmienia się i nie używa ponownie**. Usunięte wymaganie oznacza się jako ~~wycofane~~.
