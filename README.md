# forkplug

Плагин для [exteraGram](https://github.com/exteraSquad/exteraGram): аватары в упоминаниях, M3 Expressive индикаторы загрузки, окно реакций, анимации меню и бейджи ролей.

A plugin for [exteraGram](https://github.com/exteraSquad/exteraGram): mention avatars, M3 Expressive progress indicators, reactors window, menu animations and role badges.

![version](https://img.shields.io/badge/version-1.5.17-blue)
![exteraGram](https://img.shields.io/badge/exteraGram-%E2%89%A5%2012.5.1-2AABEE)
![SDK](https://img.shields.io/badge/SDK-%E2%89%A5%201.4.3.6-green)

[Русский](#русский) · [English](#english)

---

## Русский

### Возможности

- **Аватары в упоминаниях** — аватарка перед `@упоминанием` в сообщениях и в описании профиля
- **Окно реакций** — удержание реакции показывает, кто её поставил
- **Material 3 Expressive индикатор** — волнистое кольцо загрузки, крестик отмены, стрелка до старта
- **M3E в просмотре фото и спиннерах** — то же кольцо вместо обычного круга
- **Анимации главного меню** — стандартная, масштаб, часы (маятник), 3D-переворот, растворение, покачивание
- **Анимации списка чатов** при прокрутке
- **Теги каналов и бейджи ролей** рядом с ником
- **Обновления по воздуху** через GitHub

### Установка

1. Скачайте [`forkplug.plugin`](https://raw.githubusercontent.com/c0rel5/forkplug/main/forkplug.plugin)
2. Откройте файл в exteraGram (или отправьте себе в «Избранное» и нажмите на него)
3. Подтвердите установку

Настройки: **Настройки → Плагины → forkplug**

### Обновления

В настройках плагина, в разделе «Обновления», укажите репозиторий:

```
c0rel5/forkplug
```

Включите «Проверять обновления при запуске» или нажмите «Проверить обновления сейчас».

### Требования

- exteraGram `≥ 12.5.1`
- Plugin SDK `≥ 1.4.3.6`

---

## English

### Features

- **Mention avatars** — a profile picture before every `@mention` in messages and bios
- **Reactors window** — long-press a reaction to see who reacted
- **Material 3 Expressive indicator** — wavy download ring, cancel cross, arrow before start
- **M3E in photo viewer and spinners** — the same ring instead of the stock circle
- **Main menu animations** — default, scale, clock (pendulum), 3D flip, dissolve, wobble
- **Chat list scroll animations**
- **Channel tags and role badges** next to the nickname
- **Over-the-air updates** via GitHub

### Installation

1. Download [`forkplug.plugin`](https://raw.githubusercontent.com/c0rel5/forkplug/main/forkplug.plugin)
2. Open the file in exteraGram (or send it to Saved Messages and tap it)
3. Confirm the installation

Settings: **Settings → Plugins → forkplug**

### Updates

In the plugin settings, under "Updates", set the repository:

```
c0rel5/forkplug
```

Enable "Check for updates on launch" or tap "Check for updates now".

### Requirements

- exteraGram `≥ 12.5.1`
- Plugin SDK `≥ 1.4.3.6`

> The plugin UI is currently in Russian.

---

## Repository

| File | Purpose |
|---|---|
| `forkplug.plugin` | the plugin |
| `update.json` | update manifest (`version`, `url`, `changelog`) |

To release a new version, set the same version in `__version__` (plugin) and `update.json`, then commit both to `main`.

## Author

[@c0rel5](https://t.me/c0rel5)
