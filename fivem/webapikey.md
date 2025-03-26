---
title: Podłączenie Steam Web Api Key
icon: key
logo: /static/logo.png
order: 1
description: Podłączenie Steam Web Api Key
authors:
    - name: AziQr
      avatar: /static/avatars/aziqr.png
    - name: Jäger
      avatar: /static/avatars/jager.png
---

# 🔑 Jak podłączyć Steam Web Api Key
Poniżej znajdziesz szczegółową instrukcję podłączenia klucza Steam Web API Key do serwera FiveM w panelu WaveHost. Postępuj zgodnie z krokami, aby zapewnić prawidłową konfigurację i stabilne działanie serwera.


**1. Pobranie klucza API**
- Przejdź na stronę [Steam Web API](https://steamcommunity.com/dev/apikey/)
- Zaloguj się na swoje konto Steam.
- Wprowadź nazwę swojego serwera, wygeneruj klucz i go skopiuj.

**2. Dodanie klucza do konfiguracji FiveM**
- - Zaloguj się do panelu WaveHost.
  - Przejdź do zakładki <span style="color:rgb(67, 136, 233);">"STARTUP"</span>
  - Wklej wcześniej wygenerowany kod z miejsce "Steam Web Api Key"
         ![](/static/fivem/webapi0.png)

**3. Alternatywne Dodanie klucza do konfiguracji FiveM**
- Zaloguj się do panelu WaveHost.
- Przejdź do edycji pliku server.cfg na swoim serwerze FiveM.
     ![](/static/fivem/webapi1.png)
- Znajdź linijkę i dodaj swój wcześniej wygenerowany klucz set steam_webApiKey "TWÓJ_KLUCZ"
- Zapisz plik przyciskiem <span style="color:rgb(67, 136, 233);">"SAVE CONTENT"</span>  i zrestartuj serwer.


🎉 Gratulacje! Twój klucz Steam Web API został pomyślnie podłączony. W razie problemów skontaktuj się z pomocą techniczną WaveHost.
