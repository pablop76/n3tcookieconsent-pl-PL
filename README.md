# n3t Cookie Consent: polskie tłumaczenie

Polskie pliki językowe do wtyczki **n3t Cookie Consent** (Pavel Poles, n3t.cz) dla Joomli.
Wtyczka wyświetla okienko zgody na pliki cookie, ale ma w paczce tylko angielski.
Na polskiej stronie odwiedzający widzą więc „We use cookies” i „Accept all”.

## Co jest przetłumaczone

- **Wszystko, co widzi odwiedzający:** okienko zgody, okno ustawień, ikona ustawień
  i komunikaty przy zablokowanych ramkach iframe (YouTube, Vimeo, mapy).
- **Cały panel ustawień wtyczki** w administracji, 448 tekstów.
- **Opisy plików cookie** Joomli i samej wtyczki oraz najczęstszych usług:
  Google Analytics, Google i Mapy Google, reCAPTCHA, Facebook.

Pozostałe opisy z bazy Open Cookie Database (około 2200) zostają po angielsku.
Joomla najpierw wczytuje plik angielski i dopiero na niego nakłada polski.
Brakujący opis pokaże się więc po angielsku, a nie jako surowy klucz.

## Odmiana liczebników

Angielski plik zna tylko dwie formy, „1 year” i „2 years”. Polska paczka Joomli
potrzebuje osobnej formy dla liczb 2–4, 22–24 i podobnych (końcówka `_FEW`).
Bez niej przy „2 lata” wtyczka wyświetliłaby surowy klucz. To tłumaczenie tę formę
dodaje: 1 rok, 2 lata, 5 lat, tak samo dla miesięcy, dni, godzin, minut i sekund.

## Wymagania

- n3t Cookie Consent 4.5.1
- Joomla 5.x z zainstalowanym językiem polskim (sprawdzone na Joomli 5.4.6)

## Instalacja

1. Pobierz paczkę `n3tcookieconsent-pl-PL-*.zip` z zakładki
   [Releases](https://github.com/pablop76/n3tcookieconsent-pl-PL/releases).
2. `System → Instaluj rozszerzenia` → wgraj paczkę.

Paczka instaluje się jako rozszerzenie typu plik (`files_n3tcookieconsent_plpl`),
więc można ją później odinstalować jak każde inne rozszerzenie.

Bez instalatora wystarczy wgrać trzy pliki z `administrator/language/pl-PL/`
do tego samego katalogu na serwerze. Wtedy jednak Joomla nie będzie pokazywać aktualizacji.

## Aktualizacje

Od wersji 4.5.1.3 paczka rejestruje w Joomli serwer aktualizacji. Nową wersję tłumaczenia
zobaczysz w `System → Aktualizacja → Rozszerzenia` i zainstalujesz jednym kliknięciem,
jak każdą inną aktualizację. Starsze wersje (4.5.1.1 i 4.5.1.2) nie mają tego wpisu,
więc 4.5.1.3 trzeba raz wgrać ręcznie.

## Po instalacji

Teksty okienka zgody nie zawierają odnośnika do polityki prywatności, dopóki nie
wskażesz jej w ustawieniach wtyczki: pierwsza zakładka („Dodatek”), pole
„Polityka prywatności”.

## Licencja

GNU GPL v3, tak jak oryginalna wtyczka. Autor wtyczki: Pavel Poles
([n3t.bitbucket.io](https://n3t.bitbucket.io/)). Tłumaczenie:
[pablop76](https://web-service.com.pl/).
