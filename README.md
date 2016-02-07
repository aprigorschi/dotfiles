![Screenshot of my shell prompt](http://i.imgur.com/5NMkJfO.png?1)

## Установка
sh bootstrap.sh
sh brew.sh
sh .cask.sh


## Установка домена для виртуального сервера
1. Добавить имя сервера которое будет искаться на твоем компьютере а не в глобальной сети в файле /private/etc/hosts (можно открыть его через sublime плагин)
2. Добавить в файле /etc/apache2/extra/httpd-vhosts.conf настройки
3. перезагрузить apache server командой sudo apachectl restart либо алиас apacheRestart