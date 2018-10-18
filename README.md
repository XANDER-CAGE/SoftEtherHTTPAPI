# SoftEtherHTTPAPI
SoftEther HTTP API
В заголовке отправляем:
    token: 76d2ed410c9d5dc55bcb305ddcc8f25e
    hubname: название хаба

Методы:
sessions - список сессий
    ПАРАМЕТРЫ:
        Headers:
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
        - hubname: название хаба
        GET
all_users - список всех пользователей
    ПАРАМЕТРЫ:
        Headers:
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
        - hubname: название хаба
        GET
new_user - создание пользователя
    ПАРАМЕТРЫ:
        Headers:
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
        POST:
        - hubname: хаб,
        - username: логин,
        - password: пароль,
        - description: описание,
        - group: группа
delete_user - удаление пользователя
    ПАРАМЕТРЫ:
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
        - hubname: хаб,
        - username: логин,
user_details - информация о пользователе
    ПАРАМЕТРЫ:
        Headers:
        - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
        GET:
        - hubname: хаб,
        - username: логин,
get_groups - список всех групп
    ПАРАМЕТРЫ:
        Headers:
            - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
            - hubname: название хаба
getDhcp - проверка параметров DHCP сервера
    ПАРАМЕТРЫ:
        Headers:
            - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
            - hubname: название хаба
getServerInfo - информация о сервере
    ПАРАМЕТРЫ:
        Headers:
            - token: 76d2ed410c9d5dc55bcb305ddcc8f25e
            - hubname: название хаба
