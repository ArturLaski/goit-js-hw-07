# goit-js-hw-07

## Struktura projektu
Projekt składa się z następujących plików i folderów:
- `/js`
  - `task-1.js` - Rozwiązanie zadania 1: Categories
  - `task-2.js` - Rozwiązanie zadania 2: Image Gallery
  - `task-3.js` - Rozwiązanie zadania 3: Name Input
  - `task-4.js` - Rozwiązanie zadania 4: Login Form
  - `task-5.js` - Rozwiązanie zadania 5: Background Color Change
  - `task-6.js` - Rozwiązanie zadania 6: Create and Destroy Boxes
- `.gitignore` - Plik ignorujący niepotrzebne pliki w repozytorium
- `.prettierrc` - Plik konfiguracyjny dla Prettier
- `index.html` - Strona główna projektu, wyświetlająca wyniki zadań w przeglądarce
- `README.md` - Dokumentacja projektu

## Opis zadań

### Task 1: Categories
Zadanie polega na napisaniu skryptu, który:
1. Zlicza liczbę kategorii i wyświetla ją w konsoli.
2. Dla każdej kategorii wyświetla nazwę i liczbę elementów w tej kategorii.

### Task 2: Image Gallery
Zadanie polega na napisaniu skryptu, który na podstawie tablicy danych tworzy galerię obrazów i dodaje je do DOM.

### Task 3: Name Input
Zadanie polega na napisaniu skryptu, który na bieżąco aktualizuje powitanie na stronie w zależności od wartości wprowadzanej przez użytkownika w polu tekstowym.

### Task 4: Login Form
Zadanie polega na napisaniu skryptu, który obsługuje formularz logowania. Skrypt waliduje pola formularza i wyświetla alert, jeśli pola są puste.

### Task 5: Background Color Change
Zadanie polega na napisaniu skryptu, który zmienia kolor tła strony po kliknięciu przycisku oraz aktualizuje tekst informujący o aktualnym kolorze tła.

### Task 6: Create and Destroy Boxes
Zadanie polega na stworzeniu skryptu, który umożliwia użytkownikowi tworzenie i usuwanie dynamicznych elementów na stronie. Wygenerowane elementy mają zmieniający się rozmiar i losowy kolor.

## Wymagania
- Kod musi być sformatowany za pomocą Prettier.
- Nie mogą występować żadne błędy ani ostrzeżenia w konsoli po uruchomieniu zadań.
- Taski 1, 2, 3, 4, 5 i 6 muszą zostać wykonane i poprawnie wyświetlać wyniki w odpowiednich sekcjach strony `index.html`.

## Wyświetlanie wyników
Wyniki zadań są automatycznie wyświetlane w przeglądarce w odpowiednich sekcjach pliku `index.html`:

- Wyniki zadania 1 są wyświetlane w sekcji `#task-1`.
- Wyniki zadania 2 są wyświetlane w sekcji `#task-2`.
- Wyniki zadania 3 są wyświetlane w sekcji `#task-3`.
- Wyniki zadania 4 są wyświetlane w sekcji `#task-4`.
- Wyniki zadania 5 są wyświetlane w sekcji `#task-5`.
- Wyniki zadania 6 są wyświetlane w sekcji `#task-6`.

## Sformatowanie kodu za pomocą Prettier:

* Aby użyć Prettier, musisz zainstalować go w swoim projekcie. Można to zrobić, jeśli masz zainstalowany Node.js, za pomocą polecenia:
  
```bash
npm install --save-dev prettier
```

* Następnie możesz uruchomić Prettier na swoim kodzie za pomocą:

```bash
npx prettier --write .
```

To polecenie sformatuje wszystkie pliki w projekcie.
