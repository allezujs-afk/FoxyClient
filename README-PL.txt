FOXY CLIENT — ZAMOWIENIA Z KODEM 6-CYFROWYM

WYMAGANIA: Node.js 18 lub nowszy.

1. Zmien nazwe .env.example na .env.
2. Wklej do DISCORD_WEBHOOK_URL NOWY webhook Discord.
3. W terminalu w folderze projektu uruchom:
   npm install
   npm start
4. Otworz http://localhost:3000

Po kliknieciu "Przejdz do zamowienia":
- serwer generuje losowy kod 6-cyfrowy,
- wysyla kod, plan, metode platnosci i nick Discord na webhook,
- strona pokazuje kod i wybrany plan.

BEZPIECZENSTWO:
Webhook podany w rozmowie jest sekretem i nalezy go usunac/rotowac w ustawieniach Discorda.
Nie wklejaj webhooka do index.html ani do publicznego repozytorium. Wklej tylko nowy adres do lokalnego pliku .env na serwerze.
Nie udostepniaj folderu .env.
To jest system tworzenia zgloszenia, nie automatyczne potwierdzanie wplaty.

SZYBKIE URUCHOMIENIE W WINDOWS:
1. Zainstaluj Node.js LTS: https://nodejs.org/
2. Skonfiguruj plik .env zgodnie z instrukcja powyzej.
3. Kliknij dwa razy START-FOXY.bat.
4. Nie otwieraj index.html bezposrednio z folderu — wtedy przegladarka nie ma dostepu do endpointu /api/order i pojawia sie Failed to fetch.
5. Nie zamykaj okna "Foxy Client Server".

NOWE W TEJ WERSJI:
- Plynniejsze, bardziej widoczne animowane tlo i delikatna siatka.
- Glosniejszy, plynny dzwiek klikniecia.
- Sekcja Spotify: wklej link do playlisty/albumu/utworu i kliknij Polacz Spotify.
Uwaga: to oficjalny Spotify Embed. Pelne sterowanie kontem/uzytkownikiem wymaga konfiguracji Spotify OAuth i danych aplikacji Spotify.
