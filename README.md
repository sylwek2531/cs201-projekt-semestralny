# Projekt semestralny (Programowanie obiektowe C#)

> Opracowanie: _Krzysztof Molenda_
> Wersja: _2018-11-03_
---
Celem projektu jest zrealizowanie prostej aplikacji desktopowej w języku C#, pracującej w środowisku graficznym użytkownika, z wykorzystaniem framework'a WPF (UWP, fluent UI, ...).

## Cele dydaktyczne

* zapoznanie się z głównymi metodami opracowania graficznego interfejsu użytkownika (XAML) oraz oprogramowania go,
* wykształcenie umiejętności separowania kodu aplikacji od opisu jej wyglądu,
* współpraca w zespole, podział zadań,
* praca z systemem kontroli wersji (git, GitHub),
* wykształcenie umiejętności tworzenia testów jednostkowych i świadomości konieczności ich opracowania
* nabycie umiejętności właściwego dokumentowania kodu (dokumentacja XML)
* nabycie umiejętności tworzenia dokumentacji API (logiki aplikacji)
* tworzenie dokumentacji projektu na GitHub

## Aspekty techniczne opracowanej aplikacji

* aplikacja desktopowa WPF (klasyczna, UWP, fluent UI)
* do opracowania interfejsu graficznego wykorzystany XAML
* interfejs graficzny aplikacji musi być responsywny, wykorzystanie `async`/`await`
* aplikacja musi mieć wyraźnie rozdzieloną część logiki od części interfejsu
* cześć logiki aplikacji musi być przetestowana (testy jednostkowe dla publicznych funkcjonalności)
* _solution_ składa się co najmniej z:
  - projektu typu _Class Library_ zawierającego logikę aplikacji
  - projektu będącego właściwą aplikacją z interfejsem graficznym
  - projektu z testami jednostkowymi dla _Class Library_
* projekt typu _Class Library_ powinien być udokumentowany (np. automatycznie wygenerowana dokumentacja html w DocFx)
* zalecana lokalizacja aplikacji (wersja polska i angielska)
* zalecane wykorzystanie _Resources_ (elementy graficzne, multimedialne aplikacji)
* aplikacja w wersji ostatecznej powinna być dostarczona w formie instalatora
* ewentualna konfiguracja zainstalowanej aplikacji powinna odbywać się z poziomu zewnętrznych plików konfiguracyjnych lub wpisów w rejestrze

## Aspekty organizacyjne

* projekt realizowany jest w grupach 2- lub 3-osobowych (projekty jednoosobowe wyłącznie za zgoda prowadzącego zajęcia, w wyjątkowych sytuacjach),
* projekt musi być realizowany z wykorzystaniem GitHub jako repozytorium kodu i dokumentacji,
* do momentu zakończenia projektu (jego ocenienia), repozytorium GitHub **musi być publiczne**, a jego adres przekazany oceniającemu. Oceniający **musi** mieć możliwość śledzenia rozwoju projektu,
* grupa studentów wybiera lidera,
* lider tworzy repozytorium na GitHub i dodaje pozostałych członków zespołu,
* zespół umawia się co do zasada komunikowania się i aktualizacji repozytorium (sugeruję unikanie pracy równoczesnej z projektem)
* lider odpowiedzialny jest za realizację projektu 

## Temat projektu

Ze względu na złożoność dodatkowych zadań do wykonania (prowadzenie projektu na GitHub, dokumentacja, ...), aplikacja nie musi być "duża" i skomplikowana.

Temat projektu studenci ustalają samodzielnie.
Może to być prosta gra logiczna (np. [saper](http://gra-saper.pl/), kółko i krzyżyk na plan większej niż 3x3, sudoku, ...) lub zręcznościowa - zachęcam do przeglądania repozytoriów _Microsoft Store_ lub _Google Play_ dla ewentualnego naśladownictwa.

Może to być prosta aplikacja użytkowa (np. wyszukiwarka zduplikowanych zdjęć na dysku czy wskazanym katalogu, ..).

Studenci specjalności BI mogą zrealizować prostą aplikację bazodanową (z MS SQL Express, sugerowany `SQLite`), np. katalogowanie e-booków czy audiobooków, ... .

Temat projektu nie musi być unikalny, ale jego realizacja **NIE MOŻE BYĆ PLAGIATEM**. Jeśli temat, koncepcja, czy nawet fragmenty kodu będą zapożyczone, należy to wyraźnie zapisać zarówno w kodzie, jak i w dokumentacji.

Możliwe jest wykorzystanie dostępnych bibliotek (spoza standardu języka/.NET). Należy ten fakt opisać w dokumentacji. Jednak w projektowanej aplikacji musi być wyodrębniona cześć odpowiedzialna za jej logikę (która np. korzysta z zewnętrznych bibliotek).

Projekt może być rozwinięciem lub oddzielną odnogą (_fork_) istniejącego projektu na GitHub - byle spełniał ogólne założenia (aplikacja desktopowa, WPF, XAML, ...).

## Zasady i kryteria oceny

Kryteria oceny projektu:

* oryginalność projektu - 10%
* jakość kodu - 30%
* kompletność kodu - 20%
* jakość dokumentacji kodu - 10%
* estetyka aplikacji - 10%
* sposób prowadzenia projektu na GitHub - 10%
* dokumentowanie projektu na GitHub - 10%
* współpraca w realizacji projektu (monitorowana na GitHub) - 10%

Lider zespołu zgłasza - najwcześniej jak to jest możliwe - temat projektu, współautorów oraz link do projektu prowadzonego na GitHub w ramach specjalnego forum dyskusyjnego dotyczącego projektu zamieszczonego na stronach kursu na platformie e.wsei.edu.pl

Następnie zespół realizuje projekt, zatwierdzając regularnie poprawki na GitHub.

Lider zespołu, w wyznaczonym terminie, przesyła kopię (archiwum ZIP) projektu prowadzonego na GitHub (_clone_) do oceny, za pośrednictwem platformy edukacyjnej e.wsei.edu.pl - we wskazanym przez prowadzącego zajęcia miejscu. W wyświetlonym formularzu podaje:

* link do projektu na GitHub
* listę współautorów
* oświadczenie współautorów o procentowym udziale w realizacji projektu (do podziału 100%) wraz z wykazem realizowanych zadań w ramach projektu



- - -

## Referencje

* [The complete WPF tutorial](https://wpf-tutorial.com/)
* [Windows Presentation Foundation @MSDN](https://docs.microsoft.com/en-us/dotnet/framework/wpf/)
* [Universal Windows Platform documentation](https://docs.microsoft.com/en-us/windows/uwp/index)
* [Fluent Design System](https://www.microsoft.com/design/fluent/)
