# pdf-test
Repozytorium na dashboardy do prognozowania

## GitHub Pages

Strona wyświetla plik `index.html` z katalogu głównego repozytorium.
Po wdrożeniu będzie dostępna pod adresem:
https://radekorszewski.github.io/pdf-test/

### Jednorazowa konfiguracja

1. W repozytorium otwórz **Settings → Pages**.
2. W sekcji **Build and deployment** ustaw **Source** na **GitHub Actions**.
3. Scal zmiany do gałęzi `main`. Workflow **Deploy GitHub Pages** opublikuje stronę.
   Jeśli zmiany zostały już scalone, uruchom go ręcznie w **Actions → Deploy GitHub Pages → Run workflow**, wybierając `main`.

Każdy kolejny push do `main` (również po scaleniu pull requesta) automatycznie
opublikuje aktualną stronę. Zmieniaj `index.html` i dodawaj potrzebne zasoby
(np. CSS, JavaScript lub PDF) do repozytorium. Używaj ścieżek względnych do zasobów,
ponieważ strona działa pod `/pdf-test/`.

Publikowana jest zawartość repozytorium z pominięciem plików ukrytych.
Nie dodawaj poufnych danych do plików strony.
Status wdrożenia i adres strony znajdziesz w zakładce **Actions**.
