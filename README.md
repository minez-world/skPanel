# SKPanel
Panel internetowy dla serwerów Minecraft napisany w PHP

SKPanel może zarządzać nieograniczoną liczbą serwerów Minecraft, w tym CraftBukkit, Tekkit i każdą inną niestandardowym silnikiem który używa pliku .jar.


## Wymagania

    PHP 5.3+ z biblioteką GD (GD używane tylko dla twarzy graczy)
    GNU Screen (instalowany domyślnie na wielu platformach)
    Java 6/7/16 Headless (OpenJDK JRE działa świetnie)


## Instalacja

```
Prześlij wszystkie pliki do katalogu dostępnego w sieci na swoim serwerze
Skopiuj data/config-sample.php do data/config.php
Edytuj data/config.php i ustaw KT_LOCAL_IP na publiczny adres IP twojego serwera
Przejdź do install.php w przeglądarce i skonfiguruj użytkownika administratora
Dodaj dowolny plik .jar serwera Minecraft do swojego katalogu domowego
Upewnij się, że użytkownik serwera WWW ma dostęp do zapisu do głównego MCHP i danych/katalogów.
```

## Konfiguracja użytkownika
```Zaloguj się jako administrator
Przejdź do Panelu Administratora
Użyj formularza „Dodaj nowego użytkownika”, aby założyć nowe konto, katalog home/domowy **NIE POWINIEN** być dostępny przez  internet, ponieważ pliki SKPanel'u są tam zapisywane
Dodaj dowolny plik .jar serwera Minecraft do katalogu użytkownika
Upewnij się, że użytkownik serwera WWW ma dostęp do zapisu w katalogu
W razie potrzeby możesz teraz uruchomić serwer użytkownika ze strony Administracja```
