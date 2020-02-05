Nginx
=========

Роль для установки и настройки Nginx сервера.

Все значения на данный момент жестко вшиты, конфигурация находится в files. Планируется добаление шаблонов j2.
Создаёт vhost mywp.local, который слушается а портах HTTP:82 и HTTPS:444. Данная роль пока не открывает порты файерволла.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }
