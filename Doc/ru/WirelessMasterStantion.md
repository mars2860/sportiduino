В системе реализована беспроводная станция сопряжения. Принципиальная схема и плата есть в [Upverter](https://upverter.com/AlexanderVolikov/55b140a993222192/Sportiduino-BTstantion/)

![](https://raw.githubusercontent.com/alexandervolikov/sportiduino/master/Master%20station/BTstation/BTstation.png)

В схеме задействован модули Arduino Pro mini, DS3231, RC522 и Bluettoth плата HC-05. Дополнительно есть место для SPI-flash памяти, в данном репоизитории она никак не используется и место можно оставить пустым, но если кто-то хочет реализовать дополнительный функционал, можно задействовать эту память. Аналогично, часы DS3231 не задействованы и их место можно оставить пустым.

Гербер для заказа платы находит в подпапке BTstantion. Выглядит плата следующим образом:

![](https://github.com/alexandervolikov/sportiduino/blob/master/Master%20station/BTstation/PCB_BTstation.PNG)

Принципиальная работа не отличается от простой станции сопряжения, но обмен данных осуществляется через Bluetooth, что позволяет реализовать работу с системой через Android устройства. Сборка осуществляется, в основном, навесным монтажом и не представляет сложности.