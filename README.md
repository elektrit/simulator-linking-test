# Test powiązania projektów Elektrit z GitHubem

Repozytorium testowe konta elektrit. Projekt wykorzystuje jedną płytkę Arduino UNO i jej wbudowaną diodę L; nie wymaga przewodów ani dodatkowych bibliotek. Oczekiwany rytm: 500 ms świecenia i 500 ms przerwy.

## Plik projektu

- Repozytorium: elektrit/simulator-linking-test
- Gałąź: main
- Ścieżka: project.elektrit.json

Plik zawiera cały projekt: program, obwód, opis oraz E-learning. Jest przeznaczony do importu przez okno GitHub w symulatorze Elektrit.

## Sprawdzenie połączenia

1. Zaloguj się do Elektrit i otwórz okno GitHub w symulatorze.
2. Użyj opcji „Wybierz repozytoria na GitHubie”, aby nadać aplikacji dostęp tylko do tego repozytorium, a następnie połącz konto elektrit.
3. Wybierz repozytorium, gałąź oraz ścieżkę podane powyżej i kliknij „Sprawdź plik”.
4. Potwierdź zastąpienie bieżącego szkicu i użyj „Importuj projekt”. Niezapisany szkic należy wcześniej zachować.
5. Uruchom symulację i obserwuj diodę L. Następnie zatrzymaj symulację, zmień opis lub tytuł projektu, sprawdź docelowy plik i świadomie potwierdź „Zapisz na GitHubie”.
6. Sprawdź nowy commit oraz zachowanie zmienionych danych po ponownym imporcie.

Repozytorium jest publiczne, więc umożliwia też test zapisu z darmowego konta Elektrit. Nie zapisuj tu haseł, tokenów ani rzeczywistych danych użytkowników.

Format projektu został sprawdzony lokalnym walidatorem. Utworzenie tego repozytorium nie oznacza jeszcze sprawdzenia całego połączenia w symulatorze. Test wymaga skonfigurowanej aplikacji GitHub po stronie Elektrit.
