1. Создать папку сервера. В нее скачать jar-файл сервера spigot последней версии. Сервер самого майнкрафта включен в него. Запусить jar-файл двойным кликом мыши.
https://getbukkit.org/download/spigot

2. bat-файл запуска сервера
@ECHO OFF
SET BINDIR=%~dp0
CD /D "%BINDIR%"
java -Xincgc -Xmx1G -Dfile.encoding=UTF-8 -jar spigot-1.16.3.jar nogui
PAUSE

3. Настройка сервера

4. Майнкрафт

5. Скачать последнюю версию библиотеки RaspberryJuice. jar-файл скопировать в папку plugin сервера.
https://github.com/zhuowei/RaspberryJuice

6. Установить API Python

pip3 install mcpi

https://github.com/martinohanlon/mcpi

7. Проверить работу mcpi.
Запустить сервер
Запустить майнкрафт
IDLE Python:

import mcpi.minecraft as minecraft
mc = minecraft.Minecraft.create()
mc.
