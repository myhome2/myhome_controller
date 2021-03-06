**MyHome Controller v 1.1** предназначен для создания устройств [**MyHome**](https://myhome2.github.io/) с автономным и 
сетевым питанием и подключение к системе умного дома через радиомодуль NRF24L01+.

**MyHome Controller** разработан на базе сравнительно нового микроконтроллера
*[ATmega328PB](http://ww1.microchip.com/downloads/en/DeviceDoc/40001906A.pdf)*
разработанного - улучшенной версии *ATmega328*, применяемого в *Arduino UNO/ NANO/PRO MINI*.
Для работы от батарейных устройств **MyHome Controller** работает на пониженной тактовой частоте 
8.0 МГц, которой, в прочем, вполне достаточно для создания беспроводных сенсоров *MySensors*.
На обратной стороне платы установлен миниатюрный SMD радиомодуль на базе
*[NRF24L01+ от Nordic Semiconductor](https://www.nordicsemi.com/-/media/DocLib/Other/Product_Spec/nRF24L01PPSv10.pdf)*

![](/Img/c3.jpg)
![](/Img/c4.jpg)
![](/Img/101.jpg)
Характеристики MyHome Controller
--------------------------------
- Микроконтроллер: ATmega328PB-AU (TQFP32)
- Тактовая частота: 8.0 МГц (внутренний резонатор)
- Напряжение питания: 2.7В - 6.0В
- Радиомодуль: NRF24L01+ (SPI интерфейс)
- Программирование: UART протокол (RX/TX/DTR), загрузчик OPTIBOOT

Описание разъемов MyHome Controller
-------------------------------------------
![](/Img/pinout.jpg)