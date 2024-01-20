# Проектирование больших систем на языке С++
# Задачи для самостоятельной работы


## 1. HTTP-SERVER (epoll/kqueue/boost::asio/libevent)

        ./wwwd  -d/--dir <path>  -h/--ip <IP>  -p/--port <int>  -w/--workers <int>  -h/--help  -v/--verbose

Запросы HEAD/GET/POST

        "GET /data/test.html HTTP/1.0\r\n\r\n"
        "HTTP/1.0 200 OK"        
        "HTTP/1.0 404 Not Found"

В каталоге dir лежат html и jpeg файлы

        CMND URI HTTP/1.0\r\n
        Header1: something\r\n
        ...
        HeaderN: something\r\n
        \r\n
        BODY html/text/jpeg

Написать нагрузочный тест для демонстрации работоспособности


## 2. SHELL	
Запоминать предыдущие команды по команде "стрелка вверх"

* long pipes |
* Каналов может быть несколько подряд
* Conditional expressions () && || ^ , 
* Background execution &
* Не забыть дождаться завершения и показать результаты выполнения всех фоновых задач
* Streams redirection < > >> 2>
* argc/argv уточнять для запускаемых программ


## 3. CHAT

**client** (select/poll)

Запуск:
        ./cli  -p/--port=<int>  -ip=<IP>  -m/--maxmsglen=<int>  -v/--verbose  -h/--help

**server** (epoll/kqueue)

Запуск:

        ./charsrv  -p/--port=<int>  -ip=<IP>  -u/--userlimit=<int>  -v/--verbose  -h/--help

Несколько клиентов, показывать «адрес-имя» отправителя сообщения

        «Welcome», «user <…> append», «user <…> leaved»


## 4. ThreadPool + TaskQueue
 (pthread/std::thread)
 
Запуск:

      ./tpool 
      -w/--workers <int> - число потоков
      -q/--quescap <int> - объем очереди задач
      -p/--priorities <int> - число приоритетов задач, если 1 – приоритетов нет, если >1, то есть – показать, что приоритеты учитываются
      -v/--verbose – показывать логирование - как выполняются операции с работниками/очередями
      -h/--help

Придумать задачи разной длительности, (3,5,9 … секунд и прочие)

Придумать «случайный» алгоритм генерации задач для демонстрации работоспособности модели

