ansibleWordpress
================

На master-сервере необходим ansible и python.
На client-сервере python и ssh.
	# ssh-keygen
Генерируем ключи, передаем их на master-сервер и пробуем подключиться к нему через ssh.
	# ssh-copy-id "имя"@"ip"
	# ssh "имя"@"ip"
Если все прошло хорошо, то настраиваем hosts файл и запускаем playbook.
    	# ansible-playbook wordpress.yml

