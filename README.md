# SoftEtherHTTPAPI
SoftEther HTTP API <br />
В заголовке отправляем:<br />
    <b>token</b>: 76d2ed410c9d5dc55bcb305ddcc8f25e<br />
    <b>hubname</b>: название хаба<br /><br />

Методы:
<b>sessions</b> - список сессий<br />
    ПАРАМЕТРЫ:<br />
        <b>Headers</b>:<br />
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e<br />
        - hubname: название хаба<br />
        <b>GET</b><br />
<b>all_users</b> - список всех пользователей<br />
    ПАРАМЕТРЫ:<br />
        <b>Headers</b>:<br />
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e<br />
        - hubname: название хаба<br />
        <b>GET</b><br />
<b>new_user</b> - создание пользователя<br />
    ПАРАМЕТРЫ:<br />
        <b>Header</b>s:<br />
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e<br />
        <b>POST</b>:<br />
        - hubname: хаб,<br />
        - username: логин,<br />
        - password: пароль,<br />
        - description: описание,<br />
        - group: группа<br />
<b>delete_user</b> - удаление пользователя<br />
    ПАРАМЕТРЫ:<br />
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e<br />
        - hubname: хаб,<br />
        - username: логин,<br />
    <b>DELETE</b><br />
<b>user_details</b> - информация о пользователе<br />
    ПАРАМЕТРЫ:<br />
        <b>Headers</b>:<br />
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e<br />
        <b>GET</b>:<br />
        - hubname: хаб,<br />
        - username: логин,<br />
<b>get_groups</b> - список всех групп<br />
    ПАРАМЕТРЫ:<br />
        <b>Headers</b>:<br />
            - token: 76d2ed410c9d5dc55bcb305ddcc8f25e<br />
            - hubname: название хаба<br />
<b>getDhcp</b> - проверка параметров DHCP сервера<br />
    ПАРАМЕТРЫ:<br />
        <b>Headers</b>:<br />
            - token: 76d2ed410c9d5dc55bcb305ddcc8f25e<br />
            - hubname: название хаба<br />
<b>getServerInfo</b> - информация о сервере<br />
    ПАРАМЕТРЫ:<br />
        <b>Headers</b>:<br />
            - token: 76d2ed410c9d5dc55bcb305ddcc8f25e<br />
            - hubname: название хаба<br />
