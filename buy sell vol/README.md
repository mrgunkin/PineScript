# BuySell Volume Indicator

🌍 **Language:** [🇬🇧 English](#english) | [🇷🇺 Русский](#русский)

---

## English

### Description
The **BuySell Volume Indicator** is a TradingView Pine Script indicator that visually represents volume trends and price movement correlations.

### Features
- Analyzes volume changes over a defined lookback period
- Colors bars based on price movement and volume increase/decrease
- Includes an optional moving average of volume
- Works with multiple BTC tickers (INDEX:BTCUSD, BINANCE:BTCUSDT.P, BINANCE:BTCUSDT, MEXC:BTCUSDT.P)
- Provides a volume threshold filter for different timeframes

### Installation
1. Open TradingView.
2. Go to the "Pine Script" section.
3. Create a new script and paste the code from `buysell_volume.pine`.
4. Click "Save" and add the indicator to your chart.

### Settings
| Parameter       | Description                                       |
|---------------|-------------------------------------------------|
| **Lookback**  | Defines how many bars back the script checks |
| **Show MA**   | Enables/disables the moving average of volume |
| **MA Length** | Defines the length of the volume moving average |
| **Bar Coloring** | Enables/disables bar color changes based on volume and price |

### Visualization
- **Green bars** indicate a price decrease but increased volume.
- **Red bars** indicate a price increase with an increase in volume.
- **Gray bars** indicate mixed conditions.
- The volume moving average (if enabled) is shown in an orange overlay.

### Author
**mrgunkin**  
[GitHub Profile](https://github.com/mrgunkin)

### License
This code is provided "as is" without any warranties.

---

## Русский

### Описание
**BuySell Volume Indicator** — это индикатор Pine Script для TradingView, который визуально отображает динамику объемов и связь с движением цены.

### Функционал
- Анализ изменений объемов за указанный период
- Окрашивание свечей в зависимости от движения цены и объемов
- Добавление пользовательской SMA для объемов
- Поддерживает различные BTC-тикеры
- Фильтр объемов для разных таймфреймов

### Установка
1. Откройте TradingView.
2. Перейдите в раздел "Pine Script".
3. Создайте новый скрипт и вставьте код из `buysell_volume.pine`.
4. Нажмите "Сохранить" и добавьте индикатор на график.

### Автор
**mrgunkin**  
[GitHub Profile](https://github.com/mrgunkin)

### Лицензия
Этот код предоставлен "как есть" без каких-либо гарантий.
