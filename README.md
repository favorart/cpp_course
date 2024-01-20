# Курс лекций "Проектирование больших систем на языке программирования С++"

Создан: апрель 2019

Прочитан для магистров первого и второго года обучения
механико-математического факультета
филиала МГУ им. М.В. Ломоносова в городе Ташкенте.
* весна/2019
* осень/2021
* осень/2023

Кафедра МаТИС.

[Использованная литература](https://github.com/favorart/cpp_course/blob/main/bibliography.md)

## Благодарности:
* Автору блога http://scrutator.me
* [Алексееву Дмитрию Владимировичу](http://intsys.msu.ru/staff/alexeev/)
* [Алисейчику Павлу Александровичу](http://intsys.msu.ru/staff/aliseychik/)
* [Гасанову Эльяру Эльдаровичу](http://intsys.msu.ru/staff/gasanov/)
* [Калугину-Балашову Дмитрию Андреевичу](https://github.com/rvncerr)


## Лекция 1. Введение в проектирование ПО
(2021)
Содержание:
* Анализ требований
* Процесс разработки
* Борьба со сложностью
* Архитектура
* Создание ПО - человеческая деятельность
* Методология повторного использования
* Тестирование
* Документация

Видео-лекция:
[![Watch the video](https://img.youtube.com/vi/1w2YpJVnxRI/maxresdefault.jpg)](https://youtu.be/1w2YpJVnxRI)

[Лекция 1 — Проектирование.pdf](https://github.com/favorart/cpp_course/files/13997760/1.pdf)

[Тест для самопроверки 1](https://onlinetestpad.com/wmzxllsjj7ir2)



## Лекция 2. Нововведения стандарта языка С++ 2011 года
(2021)
Содержание:
* Новые регулярные слова
* Проверка инвариантов времени компиляции и времени выполнения
* Типизированные перечисления
* Тривиальный тип данных и тип со стандартным размещением
* RAII и утечки ресурсов
* Исправление шаблонов
* Константа нулевого указателя
* Нововведения в STL
* Управление потоками

Видео-лекция (Часть 1):
[![Watch the video](https://img.youtube.com/vi/0kotcuRDOc0/maxresdefault.jpg)](https://youtu.be/0kotcuRDOc0)

Видео-лекция (Часть 2):
[![Watch the video]()]()

[Лекция 2 — C++11.pdf](https://github.com/favorart/cpp_course/files/13997769/2.C%2B%2B11.pdf)

[Тест для самопроверки 2](https://onlinetestpad.com/iy7yf4tspvbrk)



## Лекция 3. Совмещение кодов на языках Си и С++
(2021)
Содержание:
* Обратно совместим ли С++ c ANSI/ISO Сu?
* Как вызвать Cu/C++ функцию из Cu/C++?
* Как включить Cи заголовок в коде на C++?
* Почему компоновщик (linker) выдаёт ошибки?
* Искажение имён
* Как передать объект класса Cu/C++ в/из Cu/C++?
* Различия C99 и современный С++

[Лекция 3 — C and C++.pdf](https://github.com/favorart/cpp_course/files/13997770/3.C.and.C%2B%2B.pdf)

[Тест для самопроверки 3](https://onlinetestpad.com/mn5rws2oiszso)

### Лекция 3.1. Полиморфизм
(2021)
Содержание:
* Полиморфизм динамический vs статический
* CRTP. Curiously Recurring Template Pattern
* MixIn вариации
* std::enable_shared_from_this

[Лекция 3.1 — polymorphisms.pdf](https://github.com/favorart/cpp_course/files/13997838/3.1.polymorphisms.pdf)

[Тест для самопроверки 3.1](https://onlinetestpad.com/fvdebsjsot5ng)



## Лекция 4. С++11. Семантика перемещения
(2021)
Содержание:
* Единообразная инициализация
* Запрет на “сужение” типа
* Конструирование
* Операторы выравнивания адресов в памяти
* Свойства выражений (lvalue и rvalue)
* Семантика перемещения (move-semantic)
* Специальные методы перемещения класса
* Совершенная передача (perfect-forwarding)
* Передача аргументов функций по ссылке или по значению
* std::decay

[Лекция 4 — move-semantics.pdf](https://github.com/favorart/cpp_course/files/13997877/4.move-semantics.pdf)

[Тест для самопроверки](https://onlinetestpad.com/yqdimxrimtnow)



## Лекция 5. Лямбда выражения
(2021)
Содержание:
* C++11 auto, decltype
* C++11 lambda-функции
* Списко захвата (capture list)
* Функторы
* std::function
* std::bind
* Обобщённая лямбда-функция

[Лекция 5 — lambda.pdf](https://github.com/favorart/cpp_course/files/13997883/5.lambda.pdf)

### Лекция 5.1 Нововведения стандарта языка С++ 2014 года
(2021)
Содержание:
* Авто-вывод типа возвращаемого значения функций
* Обобщённые (полиморфные) лямбда-выражения
* Нововведения в STL
* Обособленные строки и пользовательские литералы
* std::optional и std::exception_ptr
* std::complex

[Лекция 5.1 — C++14.pdf](https://github.com/favorart/cpp_course/files/13997882/5.1.C%2B%2B14.pdf)

[Тест для самопроверки для 5 и 5.1]( https://onlinetestpad.com/rvtmu2gwg6tx4)



## Лекция 6. Шаблоны с переменным числом параметров
(2021)
Содержание:
* Шаблоны языка С++
* Variadic Templates
* Пишем класс DiscriminatedPtr
* Применение в виде std::tuple

[Лекция 6 — variadic template.pdf](https://github.com/favorart/cpp_course/files/13997984/6.variadic.template.pdf)

### Лекция 6.1 Виды преобразований типов данных
(2021)

[![Watch the video](https://img.youtube.com/vi/5n39WzOYDPg/maxresdefault.jpg)](https://youtu.be/5n39WzOYDPg)

[Тест для самопроверки для 6 и 6.1](https://onlinetestpad.com/cmsuauoa2a6a6)

### Лекция 6*. Усложнённый вариант лекции 6
(2019)
Содержание:
* Продвинутые подходы мета-программирования
* Пишем вместе std::tuple правильно!

[6*. variadic_templates.pdf](https://github.com/favorart/cpp_course/files/13998019/6.variadic_templates.pdf)



## Лекция 7. Идиомы языка С++
(2021)
Содержание:
* SFINAE
* Lazy initialization
* PImpl
* TypeErasure
* std::any
* std::function

[Лекция 7 — sfinae.pdf](https://github.com/favorart/cpp_course/files/13997899/7.sfinae.pdf)

[Лекция 7.1 — type-erasure.pdf](https://github.com/favorart/cpp_course/files/13997900/7.1.type-erasure.pdf)

[Тест для самопроверки для 7 и 7.1](https://onlinetestpad.com/acp3vzdannj4o)



## Лекция 8. Нововведения стандарта языка С++ 2017 года
(2021)
Содержание:
* Свёртка variadic templates
* Вывод шаблонных аргументов
* Структурное связывание
* constexpr if
* Новый порядок выполнения инструкций
* Copy elision
* Атрибуты C++

[Лекция 8 — C++17.pdf](https://github.com/favorart/cpp_course/files/13997904/8.C%2B%2B17.pdf)

[Тест для самопроверки 8](https://onlinetestpad.com/rjubl65btmxtq)

## Лекция *. дополнительная
(2019)
Содержание:
* Заморозка нововведений (2019) для стандарта языка С++ 2020 г.
* Исчерпывающий список нововведений с объяснением некоторых новых механизмов

[Лекция * — C++20.pdf](https://github.com/favorart/cpp_course/files/13997910/C%2B%2B20.pdf)



## Лекция 9. Процессы, потоки и методы синхронизации
(2021)
Содержание:
* Процесс, его свойства и классификация
* Создание процессов, copy-on-write
* Иерархия и аттрибуты процессов unix
* Жизненный цикл процесса unix (fork + exec)
* Поток исполнения, его свойства и аттрибуты
* С++11: std::thread
* Мьютексы
* Условные переменные
* Барьеры
* Асинхронность (std::promise, std::future, std::async)

[Лекция 9 — Процесс и поток.pdf](https://github.com/favorart/cpp_course/files/13997928/13.pdf)

[Тест для самопроверки 9](https://onlinetestpad.com/exrp574h6lv5a)



## Лекция 10. Аллокаторы и управление памятью
(2019)
Содержание:
* Подходы управления памятью
* Ручное управление памятью
* Memory pool
* Garbage collection
* Ошибки памяти на языке С++
* Самая опасная функция в С/С++
* Область применения аллокаторов
* Как написать свой аллокатор?
* std::allocator
* Allocator С++03
* Allocator С++11
* Allocator С++17
* Polymorphic memory resource (PMR)
* Polymorphic Allocator

[Лекция 10 — allocator.pdf](https://github.com/favorart/cpp_course/files/13997919/14.allocator.pdf)

[Тест для самопроверки 10](https://onlinetestpad.com/tbilfvk334jam)

### Лекция 10.1. Умные указатели
(2021)
Содержание:
* Пишем свой умный указатель
* std::unique_ptr
* std::shared_ptr
* std::weak_ptr

[Лекция 10.1 — smart-pointers.pdf](https://github.com/favorart/cpp_course/files/13997839/3.2.smart-pointers.pdf)


## Лекция 11. Введение в библиотеку Boost
(2021)
Содержание:
* Boost
* Boost.Log
* Boost.Test
* Boost.Signals2
* Boost.Algorithm
* Boost.TypeTraits
* Boost.Filesystem
* Boost.Serialization
* Boost.Numeric
* Boost.Graph
* Boost.Regex
* Boost.MetaStateMachine
* Boost.Spirit
* Boost.PropertyTree
* Boost.Pool
* Boost.PointerContainer
* Boost.ScopeExit

[Лекция 11 — boost.pdf](https://github.com/favorart/cpp_course/files/13997911/9.boost.pdf)

[Тест для самопроверки 11](https://onlinetestpad.com/jd56s63xlgkmq)

### Лекция 11.1. Тестирование. Тесты покрытия кода

[Лекция 11.1 — Тесты, покрытие кода.pdf](https://github.com/favorart/cpp_course/files/13997914/9.1.pdf)

[Тест для самопроверки 11.1](https://onlinetestpad.com/4lbsxq7yroqmi)



## Лекция 12. Библиотека Boost.Geometry
(2019)
Содержание:
* Обзор
* Дизайнерские идеи
* Особенности
* Примеры
* Обоснование конструкции

[Лекция 12 — boost geometry.pdf](https://github.com/favorart/cpp_course/files/13997915/10.boost.geometry.pdf)

[Тест для самопроверки 12](https://onlinetestpad.com/sca4kdh5as3tw)



## Лекция 13. Сетевое взаимодействие
(2021)
Содержание:
* Сокеты Беркли
* IPv4, IPv6
* networking
* TCP, UDP, HTTP
* server-client
* Мультиплексирование
* select, poll, epoll, kqueue

[Лекция 13 — Сокеты.pdf](https://github.com/favorart/cpp_course/files/13997917/11.pdf)

[Тест для самопроверки 13](https://onlinetestpad.com/u36ygn7vngfz4)



## Лекция 14. Библиотеки сетевого взаимодействия
(2021)
Содержание:
* libevent
* libev
* boost.asio

[Лекция 14 — libevent-boost.asio.pdf](https://github.com/favorart/cpp_course/files/13997924/12.libevent-boost.asio.pdf)

[Тест для самопроверки 14](https://onlinetestpad.com/uvpknz2rwcn64)



## Рекомендованные видео-лекции для дальнейшего изучения
[список](https://github.com/favorart/cpp_course/blob/main/recommend-video-lections.md)

