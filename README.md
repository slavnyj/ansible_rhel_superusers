# ansible_rhel_superusers

Напишите Ansible-playbook, создающий группу пользователей superusers, куда входят пользователи user2 и user3, и которая, выполнив sudo -i, сможет повысить свои полномочия и стать root-пользователем. Можете использовать модуль lineinfile. У него есть параметр validate, позволяющий проверять сделанные изменения в файле. В документации есть пример валидации sudoers-файла.
