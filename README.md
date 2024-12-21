Ардуино проект компактной метеостанции.
Atmega328 считывает данные с BMP280, DHT11 и делает на их основе расчеты прогноза погоды.
Информация выводится на OLED 128*64 дисплей.
Питание в порт самой платы.
Управление одной сенсорной кнопкой: просыпание, переключение экранов, навигация в меню настройки.
Реализовано сохранение давления за последние 6 часов.

Прогноз рассчитывается на основе алгоритма Замбретти

Использовались библиотеки:
GyverBME280
GyverOLED
DHT


Arduino project of a compact weather station.
Atmega328 reads data from BMP280, DHT11 and makes weather forecast calculations based on them.
Information is displayed on OLED 128*64 display.
Power supply to the port of the board itself.
Control with one touch button: wake up, switch screens, navigate in the setup menu.
Implemented saving of pressure for the last 6 hours.

The forecast is calculated based on the Zambretti algorithm

Libraries used:
GyverBME280
GyverOLED
DHT
