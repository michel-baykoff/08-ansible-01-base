# 08-ansible-01-base
1. Запускаем playbook test.yml.
![playbook test.yml](img/01.png)

2. Изменили переменную some_fact на "all default fact".
![change some_fact](img/02.png)

3-4. Создали 2 контейнера с ubuntu и centos. Запустили playbook на окружении prod.yml. 
![playbook prod.yml](img/03.png)

5-6. Добавили факты в group_vars для каждой группы.
![groupvars](img/04.png)

7. Шифруем факты через ansible-vault.
![ansible-vault encrypt](img/05.png)

8. Исполняем playbook с зашифрованными фактами.
![encrypted facts](img/06.png)

9-11. Добавили группу хостов local. Запустили playbook на окружении prod.yml 
![local](img/07.png)
