# Kurumi Tokisaki — Nightmare 🕰️🔴

**TR** | Date A Live'dan Kurumi Tokisaki temalı Vencord Discord teması.
**EN** | A Kurumi Tokisaki (Date A Live) themed Discord theme for Vencord.

> *"Ara Ara... Zafkiel."*

---

## 🇹🇷 Türkçe

### Bu tema nedir?

Discord'un görünümünü baştan aşağı Kurumi Tokisaki estetiğine çeviren bir temadır: gece siyahı zeminler üzerine Kurumi kızılı vurgular, altın "saat gözü" detayları ve her köşede animasyonlu Kurumi GIF'leri.

### Özellikler

- 🎞️ **Animasyonlu GIF arkaplanlar** — sunucu sohbetleri, DM konuşmaları, kanal listesi, üye listesi, profil kartı, kullanıcı paneli ve Direkt Mesajlar butonu
- 🔴 **Kızıl & siyah gotik palet** — butonlar, linkler, kaydırma çubukları, bahsetmeler dahil her şey uyumlu
- ✨ **Akıllı okunabilirlik** — sohbette soldan sağa karartma degradesi: yazılar solda net okunur, GIF sağda manzara gibi görünür
- 🌫️ **Pikselleşme önleyici** — GIF'ler hafif yumuşatma katmanıyla çizilir, düşük çözünürlük belli olmaz
- 🖱️ **Hover'da açılan kullanıcı paneli** — sol alt köşe normalde sadece GIF gösterir, fareyi getirince mikrofon/kulaklık/ayarlar belirir
- 🔤 **Özel yazı tipleri** — başlıklarda gotik Cinzel, metinlerde modern Sora (Google Fonts'tan otomatik yüklenir)

### Gereksinimler

1. **Discord** (masaüstü uygulaması)
2. **Vencord** — Discord istemci modu. Kurulu değilse: [vencord.dev](https://vencord.dev) adresinden indirip kur (Discord kapalıyken kurulum yapılır, 1 dakika sürer).

### Kurulum (adım adım)

1. Bu repodaki **`kurumi-tokisaki.theme.css`** dosyasını indir:
   dosyaya tıkla → sağ üstteki **Download raw file** (indirme oku) butonuna bas.
2. Discord'u aç → **Kullanıcı Ayarları** (sol alttaki dişli) → sol menüde **Vencord → Themes**.
3. **Open Themes Folder** butonuna tıkla — `%AppData%\Vencord\themes` klasörü açılır.
4. İndirdiğin `kurumi-tokisaki.theme.css` dosyasını bu klasöre taşı/kopyala.
5. Discord'a dön, Themes sekmesinde teman görünecek — **kutucuğu işaretle**.
6. Görünüm ayarlarından **Koyu (Dark)** temanın seçili olduğundan emin ol.
7. Tema anında uygulanır; görünmezse **Ctrl+R** ile Discord'u yenile.

### Güncelleme

Repodan yeni sürümü indirip aynı dosyanın üzerine yazman yeterli — Discord'da Ctrl+R yap.

### Özelleştirme

`kurumi-tokisaki.theme.css` dosyasını Not Defteri ile aç; en üstteki `:root` bölümünden şunları değiştirebilirsin:

| Değişken | Ne işe yarar | Varsayılan |
|---|---|---|
| `--kurumi-red` | Ana kızıl renk | `#e3164a` |
| `--kurumi-gold` | Altın vurgu (linkler, okunmamış noktaları) | `#f0b83c` |
| `--kurumi-chat-parlaklik` | Sohbet GIF'inin belirginliği (0.2 sönük – 0.6 canlı) | `0.55` |
| `--kurumi-chat-blur` | Pikselleşme önleyici yumuşatma (`0px` = kapalı, keskin) | `2px` |
| `--kurumi-img-*` | GIF adresleri — kendi GIF linklerini koyabilirsin | Tenor |

### Sorun giderme

- **Tema listede görünmüyor** → dosyanın uzantısının `.theme.css` olduğundan emin ol (`.txt` olmasın).
- **Renkler var ama GIF'ler yok** → internet bağlantını kontrol et; bazı GIF'ler Tenor'dan yüklenir. Sohbet GIF'leri dosyaya gömülüdür, her zaman çalışır.
- **Yazılar zor okunuyor** → `--kurumi-chat-parlaklik` değerini düşür (ör. `0.35`).
- **Performans/kasma** → `--kurumi-chat-blur: 0px` yap ve karanlık bir ortamda `--kurumi-chat-parlaklik: 0.3` kullan.

---

## 🇬🇧 English

### What is this?

A theme that transforms Discord into full Kurumi Tokisaki aesthetics: pitch-black backgrounds with crimson accents, golden "clock eye" details, and animated Kurumi GIFs in every corner.

### Features

- 🎞️ **Animated GIF backgrounds** — server chats, DM conversations, channel list, member list, profile card, user panel and the Direct Messages button
- 🔴 **Crimson & black gothic palette** — buttons, links, scrollbars and mentions all match
- ✨ **Smart readability** — a left-to-right darkening gradient over chat: text stays crisp on the left while the GIF shines on the right
- 🌫️ **Anti-pixelation** — GIFs are rendered through a subtle blur layer so low resolution never shows
- 🖱️ **Hover-reveal user panel** — the bottom-left panel shows only the GIF; controls fade in on hover
- 🔤 **Custom fonts** — gothic Cinzel for headings, modern Sora for body text (auto-loaded from Google Fonts)

### Requirements

1. **Discord** (desktop app)
2. **Vencord** — a Discord client mod. If you don't have it: download from [vencord.dev](https://vencord.dev) and install (takes a minute, Discord must be closed).

### Installation (step by step)

1. Download **`kurumi-tokisaki.theme.css`** from this repo:
   click the file → press **Download raw file** (the download arrow, top right).
2. Open Discord → **User Settings** (gear icon, bottom left) → **Vencord → Themes** in the left menu.
3. Click **Open Themes Folder** — the `%AppData%\Vencord\themes` folder opens.
4. Move/copy the downloaded `kurumi-tokisaki.theme.css` into that folder.
5. Back in Discord, the theme appears in the Themes tab — **tick the checkbox**.
6. Make sure **Dark** appearance is selected in Discord settings.
7. The theme applies instantly; if not, reload Discord with **Ctrl+R**.

### Updating

Download the new version from this repo and overwrite the same file, then press Ctrl+R in Discord.

### Customization

Open `kurumi-tokisaki.theme.css` in any text editor; tweak the `:root` block at the top:

| Variable | What it does | Default |
|---|---|---|
| `--kurumi-red` | Main crimson color | `#e3164a` |
| `--kurumi-gold` | Gold accent (links, unread dots) | `#f0b83c` |
| `--kurumi-chat-parlaklik` | Chat GIF visibility (0.2 dim – 0.6 vivid) | `0.55` |
| `--kurumi-chat-blur` | Anti-pixelation blur (`0px` = off, sharp) | `2px` |
| `--kurumi-img-*` | GIF URLs — swap in your own GIFs | Tenor |

### Troubleshooting

- **Theme doesn't show up in the list** → make sure the file extension is `.theme.css` (not `.txt`).
- **Colors work but GIFs don't load** → check your internet connection; some GIFs load from Tenor. Chat GIFs are embedded in the file and always work.
- **Text is hard to read** → lower `--kurumi-chat-parlaklik` (e.g. `0.35`).
- **Performance issues** → set `--kurumi-chat-blur: 0px` and use `--kurumi-chat-parlaklik: 0.3`.

---

## Lisans / License

[MIT](LICENSE)
