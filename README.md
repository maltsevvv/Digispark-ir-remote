# Digispark-ir-remote
Управление ПК при помощи пульта от ТВ. Без всякого сторонего софта.
Отлично подходит для управления HTPC. А самое главное, это цена!!!
В данном примере реализованно управление для KODI медиаплеер.

# Что понадобится
1. DIGISPARK attiny85 aliexpress.com цена 1шт. от 1.17$.
2. TSOP4838 38kHz aliexpress.com цена 2шт. от 0.94$.
3. Библиотека Adafruit-Trinket-USB-master\TrinketHidCombo
https://github.com/adafruit/Adafruit-Trinket-USB/archive/master.zip
4. Скетч для управления, взять отсуда SKETCH_KODI.
Оригинал взят от сюда 
http://arduino.ru/forum/proekty/ik-distantsionnoe-upravlenie-kompom-cherez-digispark

# 
Я задейстовал кнопки на пульте, неиспользуемые для управления ТВ. 
В своем роде получилось HDMI-CEC, один пульт управляет двумя устройствами. Только цена гораздо ниже.
Протестировал на пультах, что попались (LG AKB74915325, SAMSUNG AA59-00741A, SAMSUNG BN59-00685A, MYSTERY MTV-2622LW

# Пока есть одна пробломка. 
После перезагрузки необходимо физически передернуть USB кабель.
