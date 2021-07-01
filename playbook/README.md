# Самоконтроль выполннения задания

1. Где расположен файл с `some_fact` из второго пункта задания?  
   __Result:__ 
2. Какая команда нужна для запуска вашего `playbook` на окружении `test.yml`?  
   __Result:__ `ansible-playbook site.yml -i inventory/test.yml`
3. Какой командой можно зашифровать файл?  
   __Result:__ `ansible-vault encrypt <filename>`
4. Какой командой можно расшифровать файл?  
   __Result:__ `ansible-vault decrypt <filename>`
5. Можно ли посмотреть содержимое зашифрованного файла без команды расшифровки файла? Если можно, то как?  
   __Result:__ да, `ansible-vault view <filename>`
6. Как выглядит команда запуска `playbook`, если переменные зашифрованы?  
   __Result:__ `ansible-playbook site.yml -i inventory/test.yml --ask-vault-password`
7. Как называется модуль подключения к host на windows?  
   __Result:__ WinRM - Windows Remote Management
8. Приведите полный текст команды для поиска информации в документации ansible для модуля подключений ssh  
   __Result:__ `ansible-doc -t connection -s ssh`
9. Какой параметр из модуля подключения `ssh` необходим для того, чтобы определить пользователя, под которым необходимо совершать подключение?  
   __Result:__ -remote_user  
   User name with which to login to the remote server, normally set by the remote_user keyword. 
   If no user is supplied, Ansible will let the ssh client binary choose the user as it normally
