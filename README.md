# Ventoy Theme — Glass Luxe (`v1.0.1`)

Минималистичная безрамочная тёмная тема для мультизагрузочной флешки **Ventoy (`1.1.x+`)** с универсальным разрешением **`1024×768`**, шрифтом **`Electrolize`**, выводом реального системного времени материнской платы (RTC) и чёткими векторными иконками без рамок. Доступна в двух версиях: **Русской (`RU`)** и **Английской (`EN`)**.

Ultra-minimalist frameless dark bootloader theme for **Ventoy (`1.1.x+`)** featuring universal **`1024×768`** compatibility, crisp **`Electrolize`** typography, real motherboard hardware RTC date & time, and authentic vector icons without frames. Available in **Russian (`RU`)** and **English (`EN`)** editions.

![Glass Luxe v1.0.1 Main Menu Preview](./preview/main_menu.png)

---

## 🇷🇺 RU — Особенности и установка

### Особенности `v1.0.1`
- **Стабильное универсальное разрешение `1024×768`:** мгновенно работает как на реальных ПК и ноутбуках (**UEFI** и **Legacy BIOS**), так и в виртуальных машинах (**VirtualBox / QEMU / VMware**) без сбоев автоопределения видеорежима.
- **Гладкий шрифт `Electrolize`:** полная поддержка кириллицы и латиницы с выверенной геометрией без зубцов.
- **Реальная дата и время материнской платы:** автоматическое чтение аппаратных часов CMOS / UEFI RTC при старте (`ДД.ММ.ГГГГ  ЧЧ:ММ`) в правой части верхней строки.
- **Чистый безрамочный минимализм:** убраны громоздкие окна, прикреплённые вкладки, лишние статусы и нижний футер `www.ventoy.net` — только список образов, лаконичные подсказки (`Выбор образа`, `Обзор дисков F2`, `Дерево папок F3`, `Терминал C`) и режим загрузки.
- **24 аутентичные векторные иконки (`1:1`, без внешних рамок):** оригинальные пропорции и логотипы для Windows 11, Windows 10, WinPE / Hiren's BootCD, антивирусов (Comodo / Kaspersky / Dr.Web), MemTest86+, Ubuntu, Debian, Linux Mint, Fedora, Arch, Manjaro, Kali, Linux, утилит восстановления, дисков `F2`, папок `F3` и подменю ISO.

### Установка на флешку
1. Перейдите в **[Releases](../../releases)** и скачайте нужный архив:
   - **`Glass_Luxe_v1.0.1_RU.zip`** — русский интерфейс
   - **`Glass_Luxe_v1.0.1_EN.zip`** — английский интерфейс
2. Распакуйте папку **`ventoy`** в **корень первого раздела флешки Ventoy** (туда, где лежат `.iso` файлы), предварительно удалив старую папку `ventoy`:
   ```text
   <Флешка Ventoy>/
   └── ventoy/
       ├── ventoy.json
       └── theme/
           ├── theme.txt
           ├── background.jpg
           ├── fonts/
           └── icons/
   ```
   *(Либо скопируйте папку `ventoy` напрямую из каталога [`ru/`](./ru/) или [`en/`](./en/) репозитория).*

---

## 🇬🇧 EN — Features & Installation

### Highlights (`v1.0.1`)
- **Universal `1024×768` Compatibility:** works reliably out-of-the-box across UEFI GOP, Legacy BIOS, and virtual machines (VirtualBox / QEMU / VMware).
- **Crisp `Electrolize` Typography:** clean technical font with full Latin & Cyrillic coverage.
- **Hardware Motherboard Clock (RTC):** reads real CMOS / UEFI RTC date & time (`DD.MM.YYYY  HH:MM`) automatically on boot.
- **Frameless Minimalist Layout & Authentic Vector Icons:** clean floating ISO list without window cards or tabs, streamlined navigation (`Select image`, `Browse drives F2`, `Folder tree F3`, `Terminal C`), and 24 crisp 1:1 vector-rendered OS & utility icons without outer frames.

### Installation
1. Download your preferred edition from **[Releases](../../releases)**:
   - **`Glass_Luxe_v1.0.1_EN.zip`** — English UI
   - **`Glass_Luxe_v1.0.1_RU.zip`** — Russian UI
2. Extract the **`ventoy`** folder into the **root of your Ventoy USB drive's main ISO partition** (replacing any old `ventoy` folder).
