# Liquidation Levels Indicator

🌍 **Language:** [🇬🇧 English](#english) | [🇷🇺 Русский](#русский)

---

## English

### Description
This indicator calculates liquidation levels based on a manually entered base price and leverage.  
It allows you to visualize:
- **Base Price** (Manual input)
- **Liquidation Levels** for long and short positions
- **Labels for each level** displayed on the chart

### Features
- Manual input for the base price
- Toggle visibility of liquidation levels
- Flexible leverage settings
- Customizable level colors
- Supports TradingView Pine Script v6

### Installation
1. Open TradingView.
2. Go to the "Pine Script" section.
3. Create a new script and paste the code from `liquidation_levels.pine`.
4. Click "Save" and add the indicator to your chart.

### Settings
| Parameter             | Description                                   |
|----------------------|---------------------------------------------|
| **Manual Base Price** | Base price for calculations                 |
| **Leverage Levels**   | Leverage values for liquidation calculations |
| **Show Long Levels**  | Display long liquidation levels             |
| **Show Short Levels** | Display short liquidation levels            |
| **Colors**           | Customize colors for each level             |

### Visualization
- **Base Price** is displayed in gray with a label and value.
- Liquidation levels:
  - Level 1 - Blue
  - Level 2 - Green
  - Level 3 - Yellow
  - Level 4 - Orange
  - Level 5 - Red

### Author
**mrgunkin**  
[GitHub Profile](https://github.com/mrgunkin)

### License
This code is provided "as is" without any warranties.

---

## Русский

### Описание
Этот индикатор рассчитывает уровни ликвидации на основе заданной базовой цены и плеча.  
Позволяет визуализировать:
- **Базовую цену** (ручной ввод)
- **Ликвидационные уровни** для лонгов и шортов
- **Подписи уровней** на графике

### Функционал
- Ввод базовой цены вручную
- Возможность включать/выключать отображение уровней
- Гибкая настройка плеч
- Настраиваемые цвета уровней
- Поддержка TradingView Pine Script v6

### Установка
1. Откройте TradingView.
2. Перейдите в раздел "Pine Script".
3. Создайте новый скрипт и вставьте код из `liquidation_levels.pine`.
4. Нажмите "Сохранить" и добавьте индикатор на график.

### Настройки
| Параметр            | Описание                          |
|----------------------|---------------------------------|
| **Manual Base Price** | Базовая цена, от которой идут расчёты |
| **Leverage Levels**  | Значения плеч для расчёта ликвидации |
| **Show Long Levels** | Отображать уровни ликвидации для лонгов |
| **Show Short Levels**| Отображать уровни ликвидации для шортов |
| **Colors**          | Настройка цвета для каждого уровня |

### Визуализация
- **Base Price** отображается серым цветом с подписью и значением.
- Ликвидационные уровни:
  - Level 1 - голубой
  - Level 2 - зелёный
  - Level 3 - жёлтый
  - Level 4 - оранжевый
  - Level 5 - красный

### Автор
**mrgunkin**  
[GitHub Profile](https://github.com/mrgunkin)

### Лицензия
Этот код предоставляется "как есть" без каких-либо гарантий.
