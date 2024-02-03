## Краткое описание программы Entire_Cluster_Checker
Программа проверяет подключение к кластерам СНГ сервера игры WoT:Blitz (Tanks Blitz).


##  Примечания
Если вы пользуетесь Брандмауэром Windows для блокировки кластеров,
эта программа поможет проверить работоспособность введённых вами диапазонов адресов
от кластеров серверов игры, не заходя в игру.
Или же если блокируете кластера с помощью WoTB CSM.

Если после выбора кластера, программа выдаёт:
Ответ от ...
Ответ от ...
Ответ от ...
Ответ от ...
То выбранный вами кластер не блокируется, или в брандмауэре введены неактульаные диапазоны адресов.

Если же после выбора кластера программа выдаёт:
Общий сбой.
Общий сбой.
Общий сбой.
Общий сбой.
Значит что кластер успешно блокируется, или он недоступен в связи с тех.работами на сервере.

Также если программа указывает на то что кластер не блокируется - вы можете использовать адрес,
который укажет программа, для блокировки кластера в брандмауэре Windows.
И желательно сообщить разработчику, в дискорд сервер - по поводу устаревших адресов в программе.


## В случае если вы хотите найти кластер с наименьшей задержкой:

### Пример:
```
Обмен пакетами с login3.tanksblitz.ru [92.38.156.189] с 32 байтами данных:
Ответ от 92.38.156.189: число байт=32 время=10мс TTL=54
Ответ от 92.38.156.189: число байт=32 время=10мс TTL=54
Ответ от 92.38.156.189: число байт=32 время=10мс TTL=54
Ответ от 92.38.156.189: число байт=32 время=10мс TTL=54

Статистика Ping для 92.38.156.189:
    Пакетов: отправлено = 4, получено = 4, потеряно = 0
    (0% потерь)
Приблизительное время приема-передачи в мс:
    Минимальное = 10мсек, Максимальное = 10 мсек, Среднее = 10 мсек
```
время=10мс - задержка до того самого кластера который вы проверяете.
Следовательно при проверке всех кластеров без блокирования можно увидеть тот - до которого у вас задержка наименьшая.


## Обратная связь
Если нашли баги - за помощью обратитесь к владельцу дискорд-сервера.
Чтобы попасть на наш дискорд сервер:
В консоли программы введите команду "dc" или "discord" без кавычек. Или по ссылке: https://discord.gg/2jJ3Qn4