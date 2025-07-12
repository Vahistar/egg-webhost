<p align="center">
  <a href="https://github.com/YourVenoOrganization](https://github.com/veno-design">
    <img src="https://media.discordapp.net/attachments/1393311228998189188/1393311249131114667/logo.png?ex=6872b5b8&is=68716438&hm=153c8db1241bb6003837f428be1e7e9e597e373b3c9119adbe3cefc824193239&=&format=webp&quality=lossless&width=2267&height=1272" alt="Nie Wczytuje Logo" width="200"/>
  </a>
</p>

# 🪶 Pelican Webhost Egg
Prosty w instalacji Hosting WWW z opcjonalnym WordPressem 🚀

### 🥚 O jajku
Te jajko to **zmodyfikowany fork** oryginalnego [pterodactyl-nginx](https://gitlab.com/tenten8401/pterodactyl-nginx),
który został **dostosowany** do działania z **Pelican Panelem**

Zmieniono strukturę i konfigurację tak, aby w pełni współpracował z nowoczesnym środowiskiem Pelicana – nie jest to już egg dla Pterodactyla.

### ✨ Co oferuje
* 🌐 Gotowe środowisko NGINX + PHP
* 📦 Automatyczna instalacja WordPress jednym kliknięciem
* 🔀 Gotowość pod reverse proxy z własną domeną
* 💡 Minimalna konfiguracja, maksymalna wygoda

### 📎 Dodatkowe informacje
* 🔒 Bezpieczne środowisko uruchomieniowe
* 🧱 Idealny do hostowania:
  * stron firmowych
  * blogów
  * prostych aplikacji
  * landing pages
* 🐘 Gotowość do rozszerzania przez paczki PHP i pluginy WP

---

### 🔇 Wyłączenie logów z konsoli:
Aby usunąć logi `access` i `error` z konsoli:
1. Przejdź do pliku:
```
nginx/conf.d/default.conf
```

2. Odkomentuj poniższe linie (usuń znak `#`):
```nginx
access_log /home/container/naccess.log;
error_log  /home/container/nerror.log error;
```

---
veno.design © 2025

Z miłości do open-source i społeczności Pelicana 😍
