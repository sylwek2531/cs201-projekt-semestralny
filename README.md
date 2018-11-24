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

* projekt realizowany jest w grupach 2- lub 3-osobowych (projekty jednoosobowe wyłącznie za zgoda prowadzącego zajęcia, w wyjątkowych sytuacjach)
* projekt musi być realizowany z wykorzystaniem GitHub jako repozytorium kodu i dokumentacji
* w momencie oddania projektu do oceny, repozytorium GitHub musi być publiczne, a jego adres przekazany oceniającemu.
* grupa studentów wybiera lidera
* lider tworzy repozytorium na GitHub
* lider odpowiedzialny jest za  

## Temat projektu

Ze względu na złożoność dodatkowych zadań do wykonania (prowadzenie projektu na GitHub, dokumentacja, ...), aplikacja nie musi być "duża" i skomplikowana.

Temat projektu studenci ustalają samodzielnie.
Może to być prosta gra logiczna (np. [saper](http://gra-saper.pl/)) lub zręcznościowa - zachęcam do przeglądania repozytoriów _Microsoft Store_ lub _Google Play_ dla naśladownictwa.

Może to być prosta aplikacja użytkowa.

Studenci specjalności BI mogą zrealizować prostą aplikację CRUD dla bazy danych (MS SQL Express, sugerowany `SQLite`).

## Zasady i kryteria oceny

Kryteria oceny projektu:

* oryginalność projektu
* jakość kodu
* kompletność kodu
* jakość dokumentacji kodu
* estetyka aplikacji
* sposób prowadzenia projektu na GitHub
* dokumentowanie projektu na GitHub
* współpraca w realizacji projektu (monitorowana na GitHub)

Lider zespołu, w wyznaczonym terminie, przesyła kopię (archiwum ZIP) projektu prowadzonego na GitHub (_clone_) do oceny, za pośrednictwem platformy edukacyjnej e.wsei.edu.pl - we wskazanym przez prowadzącego zajęcia miejscu. W wyświetlonym formularzu podaje:
* link do projektu na GitHub
* listę współautorów
* oświadczenie współautorów o procentowym udziale w realizacji projektu (do podziału 100%) wraz z wykazem realizowanych zadań w ramach projektu



- - - - - -

## Referencje

* [The complete WPF tutorial](https://wpf-tutorial.com/)
* [Windows Presentation Foundation @MSDN](https://docs.microsoft.com/en-us/dotnet/framework/wpf/)
* [Universal Windows Platform documentation](https://docs.microsoft.com/en-us/windows/uwp/index)
* [Fluent Design System](https://www.microsoft.com/design/fluent/)

