#VR Display for Google Cardboard (concept)
[![](https://github.com/r57zone/VR-Display/blob/master/2.png)](https://github.com/r57zone/VR-Display/blob/master/2.png)
[![](https://github.com/r57zone/VR-Display/blob/master/1.png)](https://github.com/r57zone/VR-Display/blob/master/1.png)
[![](https://github.com/r57zone/VR-Display/blob/master/3.png)](https://github.com/r57zone/VR-Display/blob/master/3.png)
<h2>RU:</h2>
VR Display - HDMI дисплей для шлема виртуальной реальности Google CardBoard или для любых других аналогичных шлемов 
(держателей смартфонов, без дисплея).<br>
**Основные компоненты:**<br>
1. Дисплей 5 дюймов, 1920 на 1080 пикселей, поддерживающий как минимум 60 кадров, можно взять любой дисплей, 
при наличии к нему документации (распиновки). Идеальным решением был бы дисплей от смартфона Samsung Galaxy S4 
(5 дюймов, amoled, 1080p). Также можно взять дисплей от Lenovo K910 (5,5 дюймов, IPS, 1080p) или любой другой дисплей, 
соответствующий критериям. Со временем можно будет взять за основу 4K дисплей Sharp, когда начнется массовое производство 
и упадет цена.<br> 
2. Контроллер, который позволяет преобразовать HDMI сигнал на этот дисплей. Идеальным вариантом бы было, чтобы этот
контроллер еще эмулировал USB устройство гироскоп или что-то другое, позволяющее получить данные гироскопа.
Возможно, для этой цели подойдет контроллер Rasberry PI.<br> 
3. Гироскоп, подойдет любой Arduino совместимый гироскоп.<br> 
4. Кнопка включения, с модульным подключением (подключение через разъем на плате).<br> 
5. Колесико регулирующее яркость, с модульным подключением.<br> 
**Технические детали:**<br>
Питание устройства и передача данных от гироскопа происходит через один или два USB 2.0, или USB 3.0.<br>
**Тесты и улучшения:**<br>
Проверить удобство правого расположения разъемов HDMI и USB в Google Cardboard, если недостаточно удобно, 
то добавить возможность повернуть контроллер разъемами вниз, с программным или аппаратным (2 джампера) переключением 
осей гироскопа.
**Примерная стоимость:**<br>
Дисплей - ~35$, контроллер - ~40$, гироскоп - ~2$, дополнительные расходы - ~10$. Цены с учетом доставки по всему миру. 
Конечная стоимость железной части прототипа составляет около 90$. 
**Обратная связь**<br>
Если вы знаете подходящие дисплеи, контроллеры или хотите как-то помочь в разработке, то пишите - r57zone[собака]gmail.com.

<h2>EN:</h2>
VR Display - HDMI display for head-mounted display Google CardBoard or any other similar helmets
(holders of smart phones, without display).<br>
**Main components:**<br>
1. Display 5 inch, 1920-by-1080 pixel resolution that supports at least 60 frames, you can choose any display,
in the presence of supporting documentation (pinouts). The ideal solution would be a display of the smartphone Samsung Galaxy S4
(5 inch, amoled, 1080p). You can also take the display from Lenovo K910 (5,5 inches, IPS, 1080p) or any other display,
the relevant criteria. Over time, it will be possible to base the 4K display Sharp, when to start mass production
and the price will fall.<br> 
2. The controller, which allows you to convert the HDMI signal to the display. The ideal situation would be that this
Controller has emulated USB device gyro or something else that allows you to retrieve data Gyro.
Perhaps for this purpose will approach the controller Rasberry PI.<br> 
3. Gyro, you can use any Arduino Compatible gyroscope.<br> 
4. The power button, with a modular connection (connection via connector on the board).<br> 
5. Wheel adjusts the brightness, modular connection.<br> 
**Technical details:**<br>
Power devices and data from the gyroscope occurs in one or two USB 2.0, or USB 3.0.<br>
**Tests and improve:**<br>
Check the convenience of location right HDMI and USB in Google Cardboard, if not enough convenient,
then add the ability to turn down the controller connectors, software or hardware (2 jumpers) switching
axis gyroscope.
**Estimated cost:**<br>
Display - ~ $ 35, the controller - ~ $ 40, the gyro - ~ $ 2, additional costs - ~ $ 10. Prices include shipping worldwide.
The final cost of the prototype rail is about $ 90.
**Feedback**<br>
If you know the appropriate displays, controllers, or want to do something to help in the development, write - r57zone[at]gmail.com.<br>
![](https://raw.githubusercontent.com/r57zone/VR-Display/master/VRDisplay.png)