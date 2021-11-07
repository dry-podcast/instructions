# Запись выпуска при помощи Mumble

Мы используем Mumble т.к. он позволяет записать всех участников стрима на отдельные аудиодорожки. 
Это позволяет более гибко работать с голосами на post production. 
Следующие шаги описывают как настроить Mumble у себя для участия в выпуске.

### 1. Установите клиент Mumble
[Скачайте][mumble-link] и установите Mumble на свое устройство.

![image][mumble-download-screen]

### 2. Запустите программу

![image][mumble-main-screen]

### 3. Добавьте сервер

Откройте список серверов

![image][add-server]

Нажмите **Add New**

![image][server-list]

#### Заполните все поля:

**Address** - mumble-ru.cleanvoice.ru

**Port** - 22126

**Username** - nick который будет отображаться в беседе(любой)

**Label** - отображаемое название в списке серверов(любой)

![image][server-data-filled]

Нажмите **OK**

Добавленный сервер появится в списке серверов.

![image][added-server]


### 4. Настройте звук

Перейдите в "Настройки" и выберите источник входящего звука.

![image][settings]

Если вы используете внешний микрофон/петличку, выберите его в настройках.

![image][audio-input]

**!!!ВАЖНО!!! Не используйте в качестве источника входящего сигнала микрофоны TWS наушников(AirPods и им подобные).**


### 5. Подключитесь к серверу

![image][connect-to-server]

### 6. Войдите в нужную "комнату"

После подключения к серверу, вы окажетесь в **Root** комнате. 

![image][root-room]

Если есть другая комната, просто перетащите в нее мышкой своего пользователя.

![image][podcast-room]

### На этом все.


[mumble-link]:https://www.mumble.info/
[mumble-download-screen]:asssets/mumble/mumble_download.png
[mumble-main-screen]:asssets/mumble/main_screen.png
[add-server]:asssets/mumble/add_server.png
[server-list]:asssets/mumble/server_list.png
[server-data-filled]:asssets/mumble/server_data_filled.png
[added-server]:asssets/mumble/added_server.png
[connect-to-server]:asssets/mumble/connect_to_server.png
[root-room]:asssets/mumble/root_room.png
[podcast-room]:asssets/mumble/podcast_room.png
[settings]:asssets/mumble/settings.png
[audio-input]:asssets/mumble/audio_input.png
