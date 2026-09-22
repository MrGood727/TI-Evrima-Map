# TI-Evrima-Map

**TI-Evrima-Map** — настольный картографический инструмент для **The Isle: Evrima** и карты **Gateway**.

Приложение объединяет интерактивную карту, координаты, пользовательские маркеры и области, маршруты, слои, пресеты и мини-карту с отслеживанием позиции игрока.

[Скачать последний релиз](ссылка/releases/latest)

## Возможности

* Карта Gateway
* Мини-карта с отслеживанием позиции игрока
* Навигация и поиск по координатам
* Точки маршрута
* Маршруты и траектории движения
* Пользовательские маркеры с названиями и цветами
* Пользовательские области:

  * Свободное рисование
  * Круг
  * Полигон
* Слои карты:

  * Миграции
  * Патрули
  * Святилища
  * Вода
  * Соль
* Пользовательская палитра цветов
* Пресеты карты
* Сохранение настроек
* Русский и английский интерфейс
* Проверка обновлений

## Карта

Основная карта поддерживает масштабирование, перемещение и работу с пользовательскими данными.

Маркеры, области, точки и маршруты можно создавать непосредственно на карте.

## Мини-карта

Мини-карта отображает позицию игрока во время игры.

**Отслеживание позиции доступно только на мини-карте.**

Позиция игрока определяется по координатам, скопированным в системный буфер обмена.

## Как это работает

TI-Evrima-Map работает как отдельное настольное приложение с HTML-интерфейсом карты.

Приложение:

* не читает память игры;
* не изменяет память игры;
* не внедряет код в процесс игры;
* не требует доступа к игровому процессу;
* использует только координаты, скопированные в системный буфер обмена.

Скопированные координаты используются приложением для определения позиции игрока на мини-карте.

## Пресеты

Пользовательские картографические данные можно сохранять в отдельные пресеты.

Доступны:

* Создание
* Загрузка
* Переименование
* Удаление
* Перезапись

Пресеты позволяют хранить разные наборы маркеров, областей и маршрутов отдельно.

## Координаты

Координаты отображаются при навигации по карте и могут использоваться для поиска нужных позиций.

Координаты игрока для мини-карты могут передаваться через системный буфер обмена.

## Маршруты и области

Можно создавать собственные маршруты и области для обозначения территорий, путей, ресурсов, опасных зон и других объектов.

Поддерживаются три типа областей:

* Свободное рисование
* Круг
* Полигон

## Локализация

Интерфейс доступен на русском и английском языках. Выбранный язык сохраняется между запусками.

## Обновления

Приложение автоматически проверяет наличие новой версии.

При обнаружении обновления пользователю предлагается установить последнюю версию.

## FAQ

### Это мод для The Isle: Evrima?

Нет. TI-Evrima-Map — отдельное настольное приложение, которое не изменяет игру.

### TI-Evrima-Map читает память игры?

Нет. Приложение не читает и не изменяет память игры.

### Как работает отслеживание игрока?

Позиция игрока определяется по координатам, скопированным в системный буфер обмена. Затем эти координаты используются для отображения позиции игрока на мини-карте.

### Приложение внедряет код в игру?

Нет. TI-Evrima-Map не внедряет код в процесс игры и не взаимодействует с её памятью.

### Используется ли OCR?

Нет. Координаты игрока получаются через системный буфер обмена, а не с помощью захвата экрана или OCR.

---

# TI-Evrima-Map

**TI-Evrima-Map** is a desktop mapping tool for **The Isle: Evrima** and the **Gateway** map.

It combines an interactive map with coordinate navigation, custom markers and areas, routes, map layers, presets, and a minimap with player position tracking.

[Download the latest release](ссылка/releases/latest)

## Features

* Gateway map
* Minimap with player position tracking
* Coordinate navigation and search
* Waypoints
* Routes and movement trajectories
* Custom markers with names and colors
* Custom areas:

  * Freehand
  * Circle
  * Polygon
* Map layers:

  * Migration
  * Patrol
  * Sanctuary
  * Water
  * Salt
* Custom color palette
* Map presets
* Persistent settings
* English and Russian interface
* Update checking

## Map

The main map supports zooming, panning, and editing custom map data.

Markers, areas, points, and routes can be created directly on the map.

## Minimap

The minimap displays the player's position while playing.

**Player position tracking is available on the minimap only.**

The player's position is determined using coordinates copied to the system clipboard.

## How It Works

TI-Evrima-Map is a standalone desktop application with an HTML-based map interface.

The application:

* does not read game memory;
* does not modify game memory;
* does not inject code into the game process;
* does not require access to the game process;
* only uses coordinates copied to the system clipboard.

Copied coordinates are used to determine and display the player's position on the minimap.

## Presets

Custom map data can be saved as separate presets.

Available operations:

* Create
* Load
* Rename
* Delete
* Overwrite

Presets keep different sets of markers, areas, and routes separate.

## Coordinates

Coordinates are displayed while navigating the map and can be used to find specific locations.

Player coordinates for the minimap can be provided through the system clipboard.

## Routes and Areas

Custom routes and areas can be created to mark territories, paths, resources, danger zones, and other locations.

Three area types are supported:

* Freehand
* Circle
* Polygon

## Localization

The interface is available in English and Russian. The selected language is saved between launches.

## Updates

The application automatically checks for new versions.

When an update is detected, the user is prompted to install the latest version.

## FAQ

### Is TI-Evrima-Map a mod?

No. TI-Evrima-Map is a standalone desktop application and does not modify the game.

### Does TI-Evrima-Map read game memory?

No. The application does not read or modify the game's memory.

### How does player tracking work?

Player position is determined using coordinates copied to the system clipboard. The coordinates are then used to update the player's position on the minimap.

### Does the application inject code into the game?

No. TI-Evrima-Map does not inject code into the game process or interact with its memory.

### Does the application use OCR?

No. Player coordinates are obtained from the system clipboard rather than screen capture or OCR.
