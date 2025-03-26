---
title: Zmiana ikony serwera
icon: 
logo: /static/logo.png
order: 1
description: Zmiana ikony serwera
authors:
    - name: AziQr
      avatar: /static/avatars/aziqr.png
    - name: Jäger
      avatar: /static/avatars/jager.png
---

# 🔧 Jak zmienić port txAdmin w FiveM
Poniżej znajdziesz szczegółową instrukcję zmiany portu txAdmin w panelu WaveHost. Postępuj zgodnie z krokami, aby zapewnić prawidłowe działanie panelu administracyjnego serwera.

**1. Sprawdzenie dostępnego portu**
- Zaloguj się do panelu WaveHost.
- Przejdź do zakładki <span style="color:rgb(67, 136, 233);">"Network"</span>.
- Drugie IP na liście – będzie ono używane do konfiguracji txAdmin.

    ![](/static/fivem/portadmin1.png)

- Skopiuj port drugiego IP na liście.

**2. Zmiana portu w konfiguracji serwera**
- Przejdź do zakładki <span style="color:rgb(67, 136, 233);">"Startup"</span>.
- Zmień port w "TXADMIN PORT" okienku na port skopiowany w zakładce <span style="color:rgb(67, 136, 233);">"Network"</span>.
  
     ![](/static/fivem/portadmin2.png)
  
- Następnie zmień port w "STARTUP COMMAND" na port skopiowany w zakładce <span style="color:rgb(67, 136, 233);">"Network"</span>.
  
     ![](/static/fivem/portadmin3.png)

🎉 Gratulacje! Port txAdmin został pomyślnie zmieniony. Jeśli napotkasz problemy, skontaktuj się z pomocą techniczną WaveHost. 🚀
