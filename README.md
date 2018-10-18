# SoftEtherHTTPAPI
SoftEther HTTP API <br />
В заголовке отправляем:<br />
    <b>token</b>: 76d2ed410c9d5dc55bcb305ddcc8f25e</p>
    <b>hubname</b>: название хаба<br /><br />

Методы:
<b>sessions</b> - список сессий
    ПАРАМЕТРЫ:
        <b>Headers</b>:
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
        - hubname: название хаба
        <b>GET</b>
<b>all_users</b> - список всех пользователей
    ПАРАМЕТРЫ:
        <b>Headers</b>:
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
        - hubname: название хаба
        <b>GET</b>
<b>new_user</b> - создание пользователя
    ПАРАМЕТРЫ:
        <b>Header</b>s:
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
        <b>POST</b>:
        - hubname: хаб,
        - username: логин,
        - password: пароль,
        - description: описание,
        - group: группа
<b>delete_user</b> - удаление пользователя
    ПАРАМЕТРЫ:
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
        - hubname: хаб,
        - username: логин,
    <b>DELETE</b>
<b>user_details</b> - информация о пользователе
    ПАРАМЕТРЫ:
        <b>Headers</b>:
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
        <b>GET</b>:
        - hubname: хаб,
        - username: логин,
<b>get_groups</b> - список всех групп
    ПАРАМЕТРЫ:
        <b>Headers</b>:
            - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
            - hubname: название хаба
<b>getDhcp</b> - проверка параметров DHCP сервера
    ПАРАМЕТРЫ:
        <b>Headers</b>:
            - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
            - hubname: название хаба
<b>getServerInfo</b> - информация о сервере
    ПАРАМЕТРЫ:
        <b>Headers</b>:
            - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
            - hubname: название хаба
