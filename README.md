Задание

1.Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного файла. Переименовать файл, дав ему новое имя (Друзья человека).

![Снимок экрана (26)](https://github.com/RUStAMERQ/qwerty/assets/131195804/9d7cc8ef-9fe2-4f62-890b-2125a2f4fdb8)

2.Создать директорию, переместить файл туда.

![Снимок экрана (26)](https://github.com/RUStAMERQ/qwerty/assets/131195804/cd76a3a3-bc7a-41de-9a9f-488654fa7687)

3.Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.

![Снимок экрана (27)](https://github.com/RUStAMERQ/qwerty/assets/131195804/de22da39-781d-4868-8418-c1de761f6526)
![Снимок экрана (28)](https://github.com/RUStAMERQ/qwerty/assets/131195804/be0d5866-5a1d-4cdd-b8ee-4458584c7b19)

4.Установить и удалить deb-пакет с помощью dpkg.

![Снимок экрана (29)](https://github.com/RUStAMERQ/qwerty/assets/131195804/d8aebbd3-9ee6-4f22-b62c-2e575f267e37)

5.История команд в терминале Ubuntu

mkdir VVSESUAL

cd ~/VVSESUAL

cat > home_animals

cat > pack_animals

cat home_animals pack_animals > animals

cat animals

mv animals human_friends

ls -ali

cd
mkdir VVSESUAL_system

cd ~/VVSESUAL

mv humans_friends ~/VVSESUAL_system

cd ~/VVSESUAL_system

ls -ali

sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb

sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb

sudo apt-get update

sudo apt-get install mysql-server

sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.1.0.13~3-0~ubuntu-jammy_amd64.deb

sudo dpkg -i doccker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb

sudo dpkg -r doccker-ce-cli

6.Нарисовать диаграмму

![Снимок экрана (30)](https://github.com/RUStAMERQ/qwerty/assets/131195804/1a9623a5-fb5b-4126-9f00-b788535ce9d6)

7.В подключенном MySQL репозитории создать базу данных “Друзья человека”

8.Создать таблицы с иерархией из диаграммы в БД

9.Заполнить низкоуровневые таблицы именами(животных), командами которые они выполняют и датами рождения

10.Удалив из таблицы верблюдов, т.к. верблюдов решили перевезти в другой питомник на зимовку. Объединить таблицы лошади, и ослы в одну таблицу. 11.Создать новую таблицу “молодые животные” в которую попадут все животные старше 1 года, но младше 3 лет и в отдельном столбце с точностью до месяца подсчитать возраст животных в новой таблице

11.Объединить все таблицы в одну, при этом сохраняя поля, указывающие на прошлую принадлежность к старым таблицам.

код 7-12
