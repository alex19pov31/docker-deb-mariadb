## Обратить внимание!!!

В строке mysql -e 'GRANT ALL PRIVILEGES ON *.* TO \"root\"@\"%\" WITH GRANT OPTION; заменить символ % на IP адрес.

Другой вариант mysql -e 'GRANT ALL PRIVILEGES ON *.* TO \"root\"@\"%\" IDENTIFIED BY 'пароль' WITH GRANT OPTION;