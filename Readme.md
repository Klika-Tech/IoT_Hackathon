IoT Hackaton 2016
------

## Приветствуем вас!

Для вашего удобства представлен [образ Ubuntu 16.04](https://goo.gl/HOUjYr), который сразу позволит окунуться в мир Интернета вещей и STM Nucleo.
При желании, вы настроить подобную систему у себя на своём компьютере.

Пароль пользователя и по совместительству пароль для sudo: iot
В качестве IDE предлагается Eclipse + CDT + OpenSTM32 (System Workbench For STM32)

В домашнем каталоге Вы обнаружите папки с документацией и примерами кода как для центрального MCU (STM32Cube_FW_F4_V1.13.0 ) так и для плат расширения ( NucleoExpansions ).
Примеры можно прямо импортировать в IDE, для этого выберите импорт существующего проекта и выберите каталог примера с названием SW4STM32.

Для отладки необходимо создать новую Debug конфигурацию внутри Eclipse в разделе Ac6 STM32 Debugging. Убедитесь что выбран правильный исполняемый файл ( С/С++ Application ).

В Eclipse уже импортированы несколько проектов: IoTTest ( стандартный Hello World MCU - мигаем светодиодом ), STM32F4xx-Nucleo-Client_Socket ( пример от STM для работы с WiFi модулем )

Для удобства отладки на плате Nucleo в отладчик интегрирован последовательный порт позволяющий использовать стандартные printf и scanf. Для подключения можно использовать любой удобную для вас программу ( предустановлены moserial и gtkterm )

Для использования нестандартной раскладки периферии или реализации нестандартных идей, можно воспользоваться программой настройки MCU - stm32CubeMX. Программа позволяет экспортировать настройку в виде готового проекта для SysWorkbench ( SW4STM32 ).

Также присутствует ПО для простой загрузки прошивки в MCU - QStlink2. Также позволяет запустить удалённый GDB сервер и осуществлять отладку привычным инструментарием.

Краткий курс о том, что такое MCU и как он работает можно найти [здесь](http://easyelectronics.ru/category/arm-uchebnyj-kurs)

### Ссылки на документацию и примеры

* [Nucleo-64 Board](http://www.st.com/content/st_com/en/products/embedded-software/mcus-embedded-software/stm32-embedded-software/stm32cube-embedded-software/stm32cubef4.html)
* [MEMS Inertial and Environmental](http://www.st.com/content/st_com/en/products/embedded-software/mcus-embedded-software/stm32-embedded-software/stm32cube-expansion-software/x-cube-mems1.html)
* [WiFi module](http://www.st.com/content/st_com/en/products/embedded-software/mcus-embedded-software/stm32-embedded-software/stm32cube-expansion-software/x-cube-wifi1.html)
* [VL6180X (Proximity and Gestures)](http://www.st.com/content/st_com/en/products/embedded-software/mcus-embedded-software/stm32-embedded-software/stm32cube-expansion-software/x-cube-6180xa1.html)
* [Digital MEMS microphones](http://www.st.com/content/st_com/en/products/embedded-software/mcus-embedded-software/stm32-embedded-software/stm32cube-expansion-software/x-cube-memsmic1.html)
* [Dynamic NFC tag](http://www.st.com/content/st_com/en/products/embedded-software/mcus-embedded-software/stm32-embedded-software/stm32cube-expansion-software/x-cube-nfc1.html)

## Желаем Удачи!
