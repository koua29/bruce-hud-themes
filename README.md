# 🎛️ Bruce HUD Themes

[![Bruce firmware](https://img.shields.io/badge/firmware-Bruce-8A2BE2?logo=github)](https://github.com/BruceDevices/firmware) [![Device](https://img.shields.io/badge/device-LilyGO%20T--Embed%20CC1101-1E90FF)](https://github.com/BruceDevices/firmware) [![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

> **EN** — Three "instrument / HUD" UI themes for the **[Bruce firmware](https://github.com/BruceDevices/firmware)** on the LilyGO T-Embed CC1101 (320×170). Each menu entry shows a clean technical Material icon on a blueprint background with a subtle animated light sweep. Colorways: **Amber**, **White**, **Blue**. Copy a theme folder to the SD card, then pick it in `Config → UI Theme`.

Thèmes UI « instrument / HUD » pour le firmware **[Bruce](https://github.com/BruceDevices/firmware)**, pensés pour le **LilyGO T-Embed CC1101** (écran 320×170). Chaque entrée du menu affiche une **icône technique propre** (jeu d'icônes Material) sur un fond « blueprint » avec un **léger balayage de lumière animé**.

![Aperçu des 3 coloris](docs/hero.png)

Trois coloris inclus :

| Thème | Coloris | Aperçu |
|-------|---------|--------|
| **Amber HUD** | Ambre / instrument rétro | [voir](docs/amber.png) |
| **White HUD** | Blanc / épuré | [voir](docs/white.png) |
| **Blue HUD** | Bleu / cyber | [voir](docs/blue.png) |

### Amber HUD
![Amber](docs/amber.png)
### White HUD
![White](docs/white.png)
### Blue HUD
![Blue](docs/blue.png)

## 📦 Contenu

Chaque thème (`Amber HUD/`, `White HUD/`, `Blue HUD/`) contient **16 GIF animés** (320×140) + son `.json`, couvrant les 16 entrées du menu Bruce :
WiFi, BLE, RF, RFID, FM, IR, Files, GPS, NRF24, Interpreter, Others, Clock, Connect, Config, Ethernet, LoRa.

- GIF animés avec balayage lumineux discret (~12 frames, ~45 Ko/icône).
- Nom du menu **intégré dans l'image** (`label: 0`) → texte à droite/sous l'icône selon le rendu.
- Icônes redimensionnées et centrées avec marges → **pas de débordement d'écran**.

## 🚀 Installation

### Via carte SD
1. Copie le dossier du thème voulu (ex. `Amber HUD`) à la racine de la carte SD.
2. Sur l'appareil : **Config → UI Theme → `Amber HUD/Amber HUD.json`**.

### Via WebUI (WiFi)
**Files → WebUI**, connecte-toi, upload le dossier dans la SD ou le LittleFS, puis sélectionne le `.json` dans **Config → UI Theme**.

## 🖥️ Compatibilité
Conçu pour le **LilyGO T-Embed CC1101** (320×170). Fonctionne aussi sur les cibles Bruce de résolution proche ; sur des écrans très différents, les images peuvent être recadrées.

> 💡 Les GIF sont animés → décodage un peu plus lourd que du statique. Sur demande, une variante statique est possible.

## 🎨 Crédits icônes
Icônes basées sur **[Material Icons](https://github.com/google/material-design-icons)** de Google — licence **Apache 2.0**.

## 🛒 Matériel / Hardware

Accessoires utiles pour ce projet — liens affiliés Amazon :

| [<img src="docs/amazon-B0D45MSMJR.jpg" width="200" alt="Anker 545 power bank (10 000 mAh)">](https://www.amazon.com/dp/B0D45MSMJR?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl) | [<img src="docs/amazon-B0C1FCZM94.jpg" width="200" alt="433 MHz SMA antenna (2-pack)">](https://www.amazon.com/dp/B0C1FCZM94?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl) | [<img src="docs/amazon-B0B7NVMBPL.jpg" width="200" alt="SanDisk 64 GB microSD (2-pack)">](https://www.amazon.com/dp/B0B7NVMBPL?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl) |
|:---:|:---:|:---:|
| 🔋 **[Anker 545 power bank (10 000 mAh)](https://www.amazon.com/dp/B0D45MSMJR?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl)**<br><sub>Pour faire tourner le T-Embed loin d'une prise</sub> | 📡 **[433 MHz SMA antenna (2-pack)](https://www.amazon.com/dp/B0C1FCZM94?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl)**<br><sub>Antenne sub-GHz pour la radio CC1101</sub> | 💾 **[SanDisk 64 GB microSD (2-pack)](https://www.amazon.com/dp/B0B7NVMBPL?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl)**<br><sub>Pour les thèmes, scripts et captures Bruce</sub> |

<sub>En tant que Partenaire Amazon, je réalise un bénéfice sur les achats remplissant les conditions requises. · As an Amazon Associate I earn from qualifying purchases.</sub>

## ☕ Un café ?
Si ces thèmes te plaisent :

<img src="docs/paypal-qr.png" width="180" alt="PayPal" />

## 📄 Licence
Code/assets du dépôt sous **MIT** (voir [LICENSE](LICENSE)). Icônes Material sous Apache 2.0. Thèmes par **koua29**.
