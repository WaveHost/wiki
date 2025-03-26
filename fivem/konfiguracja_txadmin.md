---
title: Konfiguracja txAdmin
icon: 
logo: /static/logo.png
order: 1
description: Konfiguracja txAdmin
authors:
    - name: AziQr
      avatar: /static/avatars/aziqr.png
    - name: Jäger
      avatar: /static/avatars/jager.png
---

# 🔧 Konfiguracja txAdmin w FiveM
Poniżej znajdziesz szczegółową instrukcję konfiguracji txAdmin w panelu WaveHost. Postępuj zgodnie z krokami, aby poprawnie uruchomić i skonfigurować panel administracyjny serwera.
!!!primary UWAGA
Aby zacząć konfigurację ustaw porty txAdmina -> [Jak ustawić porty txAdmina](https://wavehost.github.io/wiki/fivem/port_txadmin/)

!!!


**1. Włączenie txAdmin**
- Zaloguj się do panelu WaveHost.
- Przejdź do zakładki <span style="color:rgb(67, 136, 233);">"Startup"</span>.
- Znajdź opcję txAdmin Enable i ustaw ją na Enabled (włączone).

    ![](/static/fivem/konfiguracja_txadmin1.png)

- Zapisz zmiany i zrestartuj serwer.

  **2. Uzyskanie dostępu do panelu txAdmin**
  - Przejdź do zakładki <span style="color:rgb(67, 136, 233);">"Console"</span> i uruchom ponownie serwer.
  - Po uruchomieniu serwera w konsoli pojawi się link oraz kod dostępu do panelu.

      ![](/static/fivem/konfiguracja_txadmin2.png)
    
  - Przejdź pod podany adres i zaloguj się za pomocą wygenerowanego kodu.
  - Opcjonalnie ustaw identyfikator konta Discord oraz hasło zapasowe.
  - Zaakceptuj regulamin i kliknij Register.

**3. Konfiguracja serwera w txAdmin**
- W pierwszym kroku konfiguracji wpisz nazwę serwera i kliknij NEXT.

    ![](/static/fivem/konfiguracja_txadmin3.png)
- W drugim kroku wybierz opcję "Existing Server Data", aby użyć istniejących plików serwera.

  ![](/static/fivem/konfiguracja_txadmin4.png)
  
- W trzecim kroku ustaw ścieżkę folderu głównego serwera i kliknij NEXT:
```
/home/container/
```
  ![](/static/fivem/konfiguracja_txadmin5.png)

- W piątym kroku ustaw ścieżkę pliku "server.cfg":
```
/home/container/server.cfg
```
  ![](/static/fivem/konfiguracja_txadmin6.png)

**5. Uruchomienie serwera w txAdmin**
- Kliknij "Save & Start Server", aby zakończyć konfigurację i uruchomić serwer.
  
  ![](/static/fivem/konfiguracja_txadmin7.png)
  
- Po uruchomieniu powinien pojawić się panel zarządzania txAdmin.
  
    ![](/static/fivem/konfiguracja_txadmin8.png)

🎉 Gratulacje! Twój txAdmin został pomyślnie skonfigurowany i jest gotowy do użycia. Jeśli napotkasz problemy, skontaktuj się z pomocą techniczną WaveHost. 🚀
