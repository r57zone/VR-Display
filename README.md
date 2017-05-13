# VR Display for Google Cardboard (concept)
[![](https://github.com/r57zone/VR-Display/blob/master/2.png)](https://github.com/r57zone/VR-Display/blob/master/2.png)
[![](https://github.com/r57zone/VR-Display/blob/master/1.png)](https://github.com/r57zone/VR-Display/blob/master/1.png)
[![](https://github.com/r57zone/VR-Display/blob/master/3.png)](https://github.com/r57zone/VR-Display/blob/master/3.png)
<h2>RU:</h2>

VR Display - концепт HDMI дисплея для шлема виртуальной реальности Google CardBoard или для любых других vr гарнитур, без дисплея.<br>
**Готовые решения:**<br>
[BoboVR X1](http://ali.pub/1g7wh5) - 139$, 080p, Android, HDMI.<br>
[Deepoon-E2](http://ali.pub/1g7ww4) - 270$, 1080p и DK2 compatible.<br>
**Готовые компоненты**<br>
HDMI Дисплей 5.5 дюйма 2560 на 1440 128$ - http://ali.pub/1g7xle<br>
Oculus Rift DK1 USB трекер $43 - http://ali.pub/1g7xoi <br>
**VR гарнитуры:**<br>
Google Cardboard v2 - http://ali.pub/1g7xfd<br>
Bobo Z4 - http://ali.pub/1g7x77<br>

**Основные компоненты:**
1. Дисплей 5 дюймов, 1920 на 1080 пикселей или 2560 на 1440, поддерживающий как минимум 60 кадров. Можно взять следующие дисплеи: LG G3, Samsung Galaxy Note 3 N9005 (5,7 дюймов), Lenovo K910 (5,5 дюймов), LG Optimus Pro E980 (5,5 дюйма) или 4K дисплей Sharp.<br> 
2. Два контроллера. Первый преобразовывает входной видеосигнал интерфейса HDMI в потоковые видеоданные, соответствующие стандарту MIPI DSI - Toshiba TC358779XBG. Второй эмулирует USB устройство и позволяет получить данные гироскопа - STM32F100C4T6B.<br> 
3. Гироскоп GY-85 9DOF IMU.<br> 
4. Кнопка включения, с модульным подключением (подключение через разъем на плате).<br> 
5. Колесико регулирующее яркость, с модульным подключением.<br> 

**Технические детали:**<br>
Питание устройства и передача данных от гироскопа происходит через один или два USB 2.0, или один USB 3.0.<br>
**Тесты и улучшения:**<br>
Проверить удобство правого расположения разъемов HDMI и USB, если недостаточно удобно, то добавить возможность повернуть контроллер разъемами вниз, 
с программным или аппаратным (2 джампера) переключением осей гироскопа. Также можно попробовать оставить только один интерфейс, USB 3.0, по нему передавать изображение и данные.<br>
**Обратная связь:**<br>
r57zone[собака]gmail.com.<br>


<h2>EN:</h2>
VR Display - concept HDMI display for head-mounted display Google CardBoard or any other similar vr headsets without display.<br>
**Ready solutions:**<br>
[BoboVR X1](http://ali.pub/1g7wh5) - 139$, 080p, Android, HDMI.<br>
[Deepoon-E2](http://ali.pub/1g7ww4) - 270$, 1080p и DK2 compatible.<br>
**Ready components**<br>
HDMI display 5.5 inch 2560 x 1440 128$ - http://ali.pub/1g7xle<br>
Oculus Rift DK1 USB tracker $43 - http://ali.pub/1g7xoi<br>
**VR headsets:**<br>
Google Cardboard v2 - http://ali.pub/1g7xfd<br>
Bobo Z4 - http://ali.pub/1g7x77<br>
**Main components:**
1. 5-inch display, 1920 x 1080 or 2560 x 1440 pixel resolution that supports at least 60 shots. You can take the following displays: LG G3, Samsung Galaxy Note 3 N9005 (5,7 inches), Lenovo K910 (5,5 inches), LG Optimus Pro E980 (5,5 inches) or 4K display Sharp.<br>
2. Two controllers. The first converts the input video signal to an HDMI video stream corresponding to the standard MIPI DSI - Toshiba TC358779XBG. The second emulation USB device provides data gyro - STM32F100C4T6B.<br> 
3. Gyro GY-85 9DOF IMU.<br>
4. The power button, with a modular connection (connection via connector on the board).<br>
5. Wheel adjusts the brightness, modular connection.<br>

**Technical details:**<br>
Power devices and data from the gyroscope occurs in one or two USB 2.0, one or USB 3.0.<br>
**Tests and improvements:**<br>
Check the convenience of location right HDMI and USB, if insufficient convenient, then add the ability to turn down the controller connectors,
software or hardware (2 jumpers) switching axis gyroscope. You can also try to leave only one interface, USB 3.0, on it to transmit images and data.<br>
**Feedback:**<br>
r57zone[at]gmail.com.<br>

![](https://raw.githubusercontent.com/r57zone/VR-Display/master/VRDisplay.png)