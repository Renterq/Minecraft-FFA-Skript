# Minecraft-FFA-Skript
An automated, dynamic World Border Free-For-All (FFA) minigame system for Minecraft servers using Skript.
# ⚔️ Minecraft Advanced FFA (Free-For-All) Skript
*(English description is available below)*

Bu proje, Minecraft PvP sunucuları için tamamen otomatikleştirilmiş, dinamik bir Free-For-All (Herkes Tek) arena sistemidir. Skript kullanılarak geliştirilmiştir ve oyunculara kesintisiz bir savaş deneyimi sunar.

## 🚀 Özellikler (Features)

- **Dinamik Dünya Sınırı (World Border):** Maç başladığında arena sınırı 500 blok olarak ayarlanır ve 480 saniye (8 dakika) içerisinde yavaşça 20 bloğa kadar daralır. Bu sayede oyuncular merkezde savaşmaya zorlanır ve maçların uzaması engellenir.
- **Otomatik İzleyici (Spectator) Modu:** Ölen oyuncular anında izleyici moduna alınır, böylece arenada haksız rekabet veya maça müdahale engellenir.
- **Leş (Kill) Takibi ve Bildirimler:** Öldürme işlemleri anlık olarak takip edilir ve sunucu sohbetine katil, kurban ve güncel leş sayısı bilgisi yansıtılır.
- **Son Kalan Kazanır:** Arena sistemimiz hayatta kalan son oyuncuyu otomatik olarak tespit eder, kazananı tüm sunucuya duyurur ve bir sonraki maç için dünya sınırını sıfırlar.
- **Sonradan Katılma Koruması:** Maç devam ederken sunucuya giriş yapan oyuncular, maçı bozmamaları için otomatik olarak izleyici modunda başlatılır.

## 🛠️ Kurulum (Installation)

1. Sunucunuzda **Skript** eklentisinin kurulu olduğundan emin olun.
2. Bu repodaki `ffa.sk` dosyasını indirin.
3. Dosyayı sunucunuzun `plugins/Skript/scripts` klasörünün içine atın.
4. Oyun içinden veya konsoldan `/sk reload ffa` komutunu çalıştırarak sistemi aktif hale getirin.

## 🎮 Kullanım Komutları (Commands)

- `/ffabaslat` : (Sadece OP yetkisine sahip kişiler kullanabilir) Arenayı sıfırlar, dünya sınırını ayarlar ve FFA maçını başlatır.

## ⚙️ Gereksinimler (Requirements)
- Skript
- İsim gizleme özellikleri için NametagEdit (İsteğe bağlı, kod içinden düzenlenebilir)

---
---

# ⚔️ Minecraft Advanced FFA (Free-For-All) Skript (English)

This project is a fully automated, dynamic Free-For-All (FFA) arena system for Minecraft PvP servers. Developed using Skript, it provides players with a seamless combat experience.

## 🚀 Features

- **Dynamic World Border:** When the match starts, the arena border is set to 500 blocks and slowly shrinks to 20 blocks over 480 seconds (8 minutes). This forces players to fight in the center and prevents matches from dragging on.
- **Auto-Spectator Mode:** Eliminated players are instantly put into spectator mode, preventing unfair advantage or interference in the arena.
- **Kill Tracking & Notifications:** Kills are tracked in real-time, and the killer, victim, and current kill count are announced in the server chat.
- **Last Man Standing:** Our arena system automatically detects the last surviving player, announces the winner to the entire server, and resets the world border for the next match.
- **Late Join Protection:** Players who join the server while a match is in progress are automatically put into spectator mode so they don't disrupt the game.

## 🛠️ Installation

1. Ensure that the **Skript** plugin is installed on your server.
2. Download the `ffa.sk` file from this repository.
3. Place the file inside your server's `plugins/Skript/scripts` folder.
4. Run the `/sk reload ffa` command in-game or from the console to activate the system.

## 🎮 Usage Commands

- `/ffabaslat` : (Requires OP permission) Resets the arena, sets the world border, and starts the FFA match.

## ⚙️ Requirements
- Skript
- NametagEdit for name-hiding features (Optional, can be edited within the code)
