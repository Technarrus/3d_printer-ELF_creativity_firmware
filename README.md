# Firmware Marlin for 3D Printer Elf Creativity and Two Trees Sapphire
Конфигурация <a href="https://github.com/MarlinFirmware/Marlin">официальной прошивки  Marlin</a> 2.0.7.2
для 3д принтера Elf Creativity, это аналог Two Trees Sapphire на базе прошивки от Сергея Панина (https://github.com/Sergey1560/Marlin_FB4S)

## ВНИМАНИЕ
Не тестировалась с Two Trees Sapphire, проверяйте версию платы и все остальное. Напишите мне если все будет работать.
Ускорения, рывки не калибровались. 
На моем эльфе только перенесен фидер на голову, остальное в стоке.

## ЧТО ВКЛЮЧЕНО
* Включен LA, возможность изменить ускорения, джерки, скорость и т.п.
* Включение выключение датчика филамента
* Включен и уже откалиброван PID стола и хотенда в стоке, поток
* Включен MESH BED LEVELING (сетка кривизны с ручной калибровкой)
* Включен LEVEL BED CORNERS (парковка по углам для настроки зазора сопло-стол)

## ВАЖНО !!!
Если вы меняли шкивы на другое кол-во зубов, винт оси Z, клеяли утеплитель на обратную поверхность стола, меняли экструдер, нужно окалибровать ПИД, откалибровать ИЛИ указать свои параметры шагов на миллиметр. 

## КАК УСТАНОВИТЬ
* ЕСЛИ НУЖЕН БИНАРНИК, ПИШИТЕ
* Скомпилировать в VSCode или в подобных платформах
* Скопировать Robin_nano35 (находится в папке прошивки в .pio\build\mks_robin_nano35) на microSD карту, вставить в слот, включить принтер. Процесс займет около 10 секунд. 
* Первым делом, перед настройками, сделать инициализацию ипрум.

### ВИДЕО
* Пока не делал

### Связь
Вопросы, обсуждения, предложения через следующие сообщества:
* [Telegram группа](https://t.me/technarr)
* [Группа в VK](https://vk.com/technarrus)

### 🍵 ПОДДЕРЖАТЬ АВТОРА ЗА ТРУДЫ: 
* https://boosty.to/technarru
* https://www.donationalerts.com/r/technarrus
* https://yoomoney.ru/to/41001171922875 
* https://www.paypal.me/technarrus
