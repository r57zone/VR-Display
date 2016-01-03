#VR Display for Google Cardboard (concept)
[![](https://github.com/r57zone/VR-Display/blob/master/2.png)](https://github.com/r57zone/VR-Display/blob/master/2.png)
[![](https://github.com/r57zone/VR-Display/blob/master/1.png)](https://github.com/r57zone/VR-Display/blob/master/1.png)
[![](https://github.com/r57zone/VR-Display/blob/master/3.png)](https://github.com/r57zone/VR-Display/blob/master/3.png)
<h2>RU:</h2>
VR Display - HDMI дисплей для шлема виртуальной реальности Google CardBoard или для любых других аналогичных шлемов (держателей смартфонов, без дисплея).<br>
**Основные компоненты:**<br>
1. Дисплей 5 дюймов, 1920 на 1080 пикселей, поддерживающий как минимум 60 кадров. Можно взять следующие дисплеи: Samsung Galaxy Note 3 N9005 (5,7 дюймов), Samsung Galaxy S4 GT-I9500 (5 дюймов), Lenovo K910 (5,5 дюймов), LG Optimus Pro E980 (5,5 дюйма). В следующих ревизиях можно будет взять за основу 4K дисплей Sharp, когда начнется массовое производство 
и упадет цена.<br> 
2. Два контроллера. Первый преобразовывает входной видеосигнал интерфейса HDMI в потоковые видеоданные, соответствующие стандарту MIPI DSI - Toshiba TC358779XBG. Второй эмулирует USB устройство и позволяет получить данные гироскопа - STM32F100C4T6B.
3. Гироскоп GY-85 9DOF IMU.<br> 
4. Кнопка включения, с модульным подключением (подключение через разъем на плате).<br> 
5. Колесико регулирующее яркость, с модульным подключением.<br> 
**Технические детали:**<br>
Питание устройства и передача данных от гироскопа происходит через один или два USB 2.0, или один USB 3.0.<br>
**Тесты и улучшения:**<br>
Проверить удобство правого расположения разъемов HDMI и USB, если недостаточно удобно, то добавить возможность повернуть контроллер разъемами вниз, 
с программным или аппаратным (2 джампера) переключением осей гироскопа. Также можно попробовать оставить только один интерфейс, USB 3.0, по нему передавать изображение и данные.<br>
**Примерная стоимость:**<br>
Дисплей E980 - 15$, контроллер 1 - 10$, котроллер 2 - 5$, гироскоп - 8$, дополнительные расходы - ~10$. Цены с учетом доставки по всему миру. 
Конечная стоимость железной части прототипа составляет около 50$.<br> 
**Обратная связь:**<br>
Если вы знаете подходящие дисплеи, контроллеры или хотите как-то помочь в разработке, то пишите - r57zone[собака]gmail.com.<br>
**Софт:**<br>
Arduino Headtracker - https://github.com/mdjarv/arduinoheadtracker<br>
**3D шлемы:**<br>
Google Cardboard - http://ali.pub/q152a<br>
VR Box - http://ali.pub/eocnj<br>
Shinecon VR - http://ali.pub/dc9ml<br>
**Дополнительно:**<br>
Дисплеи 5" 1080p и 6" 1440p - http://www.alibaba.com/products/F0/oculus_rift_2/CID400401.html<br>
TF60010A(2K) + HDMI плата 200$за комплект, TF60007A + HDMI плата 100$за комплект. Доставка 35-50$, отправкой DHL (lisa.he[собака]topfoison.com).<br>
Дисплеи 5" 1080p и 6" 1440p на Aliexpress - http://ali.pub/wsy8b<br>
Гироскоп USB Oculus DK1 - http://ali.pub/nfxr1<br>
Мелкосерийное производство несложной электроники - http://habrahabr.ru/post/241493/<br>
Проищводство - http://www.vzrt.ru/ или они http://promwad.ru/uslugi/izgotovlenie-opytnyh-obrazcov<br>
MIPI DSI Display Shield/HDMI Adapter - https://hackaday.io/post/6905<br>
Galaxy S4 AMOLED screen working - https://hackaday.io/project/364-mipi-dsi-display-shieldhdmi-adapter/log/16504-galaxy-s4-amoled-screen-working<br>


<h2>EN:</h2>
VR Display - HDMI display for head-mounted display Google CardBoard or any other similar helmets
(holders of smart phones, without display).<br>
**Main components:**<br>
1. 5-inch display, 1920-by-1080 pixel resolution that supports at least 60 shots. You can take the following displays: Samsung Galaxy Note 3 N9005 (5,7 inches), Samsung Galaxy S4 GT-I9500 (5 inches), Lenovo K910 (5,5 inches), LG Optimus Pro E980 (5,5 inches). The next audit will be used as a basis 4K display Sharp, when to start mass production
and the price will fall.<br>
2. Two controllers. The first converts the input video signal to an HDMI video stream corresponding to the standard MIPI DSI - Toshiba TC358779XBG. II emulates USB device provides data gyro - STM32F100C4T6B.
3. Gyro GY-85 9DOF IMU.<br>
4. The power button, with a modular connection (connection via connector on the board).<br>
5. Wheel adjusts the brightness, modular connection.<br>
**Technical details:**<br>
Power devices and data from the gyroscope occurs in one or two USB 2.0, one or USB 3.0.<br>
**Tests and improvements:**<br>
Check the convenience of location right HDMI and USB, if insufficient convenient, then add the ability to turn down the controller connectors,
software or hardware (2 jumpers) switching axis gyroscope. You can also try to leave only one interface, USB 3.0, on it to transmit images and data.<br>
**Estimated cost:**<br>
Display E980 - $15, the controller 1 - $10, the controller 2 - $5 gyro - $8, additional costs - ~$10. Prices include shipping worldwide.
The final cost of the prototype of the iron is about 50 $.<br>
**Feedback:**<br>
If you know the appropriate displays, controllers, or want to do something to help in the development, write - r57zone[at]gmail.com.<br>
**Software:**<br>
Arduino Headtracker - https://github.com/mdjarv/arduinoheadtracker<br>
**3D helmets:**<br>
Google Cardboard - http://ali.pub/q152a<br>
VR Box - http://ali.pub/eocnj<br>
Shinecon VR - http://ali.pub/dc9ml<br>
**Extras:**<br>
Displays 5 "1080p and 6" 1440p - http://www.alibaba.com/products/F0/oculus_rift_2/CID400401.html<br>
TF60010A (2K) + HDMI $200 fee per set, TF60007A + HDMI fee of $100 per set. Delivery $35-50, sending DHL (lisa.he[at]topfoison.com).<br>
Displays 5 "1080p and 6" 1440p on Aliexpress - http://ali.pub/wsy8b<br>
Gyro USB Oculus DK1 - http://ali.pub/nfxr1<br>
Small-scale production of simple electronics - http://habrahabr.ru/post/241493/<br>
Proischvodstvo - http://www.vzrt.ru/ or they http://promwad.ru/uslugi/izgotovlenie-opytnyh-obrazcov<br>
MIPI DSI Display Shield / HDMI Adapter - https://hackaday.io/post/6905<br>
Galaxy S4 AMOLED screen working - https://hackaday.io/project/364-mipi-dsi-display-shieldhdmi-adapter/log/16504-galaxy-s4-amoled-screen-working<br>

![](https://raw.githubusercontent.com/r57zone/VR-Display/master/VRDisplay.png)