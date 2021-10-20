Необходимо один раз запустить VNC сервер для предварительной настройки.

touch /etc/init.d/vncserver

сохранить в файл содержимое vncserver указав пользоватея под которым будет запускаться VNC

chmod +x /etc/init.d/vncserver
update-rc.d vncserver defaults