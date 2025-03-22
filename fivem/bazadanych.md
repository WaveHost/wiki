---
title: Podłączenie bazy danych
icon: key
logo: /static/logo.png
order: 1
description: Podłączenie bazy danych - FiveM 
authors:
    - name: AziQr
      avatar: /static/avatars/aziqr.png
    - name: Jäger
      avatar: /static/avatars/jager.png
---

# 🔑 Jak podłączyć baze danych
Poniżej znajdziesz szczegółową instrukcję podłączenia bazy danych do serwera FiveM w panelu WaveHost. Postępuj zgodnie z krokami, aby zapewnić prawidłową konfigurację i stabilne działanie serwera.


1. Zaloguj się do [panelu wavehost](https://game.wavehost.eu)

2. Po zalogowaniu w zakładce Servers wybierz swój serwer przyciskiem <span style="color:rgb(67, 136, 233);">"Menage Server"</span>

   ![](/static/fivem/databases0.png)
3. Przejdź do zakładki <span style="color:rgb(67, 136, 233);">"Databases"</span> 

   ![](/static/fivem/databases1.png)

4. Kliknij <span style="color:rgb(67, 136, 233);">"New Database"</span> aby stworzyć bazę danych

5. Skopiuj gotowy fragment podłączenia bazy danych klikając w oczko oraz w linijkę `JDBC Connection String`

6. Teraz przejdź do zakładki Server Files, otwórz plik server.cfg i wklej skopiowaną linijkę

![](/static/fivem/databases2.png)

7. Alternatywna konfiguracja
   

8. Zapisz plik przyciskiem <span style="color:rgb(67, 136, 233);">"SAVE CONTENT"</span>
```set mysql_connection_string "server=___;port=____;database=___;userid=___;password=___"```

🎉 Gratulacje! Twoja baza danych została pomyślnie podłączona. W razie problemów skontaktuj się z pomocą techniczną WaveHost.
