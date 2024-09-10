#Лабораторная работа 0 Ефимов Арслан Альбертович
## Эссе
Изучив некий материал по функциональным языкам программирования и посмотрев назначения языков программирования, которые к ним относятся, мой выбор упал на Erlang. Так как я в основном люблю заниматься бэкендом, а Erlang идеально подходит для работы с распределенными системами. Параллельные вычисления, работа на уровне процессов очень мощный инструмент в сфере программирования, также в отличие от Java, C# и так далее в Erlang каждый процесс изолирован и не имеет доступ к памяти других процессов, что дает огромные преимущества использования его в качестве отказоустойчивых систем реального времени. Интересный факт, один из самых популярных брокеров сообщений RabbitMQ написан на Erlang. Также мне всегда была интересна работа мессенджеров, а с помощью Erlang можно создавать достаточно хорошие и мощные чаты сервера или же P2P. По поводу 4 лабораторной работы я поискал в интернете некоторые интересные проекты, которые можно написать на Erlang: Мессенджер, дискорд-бот или телеграмм бот, P2P а также из интересного – простую реализацию блокчейн с параллельной обработкой блоков и валидацией транзакций. Пока что в планах стоит дискорд бот, который будет обрабатывать команды и исполнять взаимодействие с пользователем, а также поддерживать различные функции (например проигрывание музыки или игры). Очень интересно попробовать связать Erlang с Discord API.
Если говорить о инструментах, которые я буду интегрировать в работе с Erlang, то у Erlang есть встроенный интерпретатор в составе стандартного дистрибутива, система сборки – rebar3, автоматическое форматирование кода можно использовать с помощью erlfmt, инструменты тестирования – EUnit для модульного тестирования или тестирования отдельных функций и Common Test для функционального тестирования. Lint tools – dialyzer и elvis. Кстати Dialyzerуже встроен в дистрибутив Erlang и интегрирован с rebar3 (rebar3 dialyzer). Стиль кодирования: именование переменных с заглавной буквы, а функции с прописной в стиле snake case, для отступов 4 пробела. 
Список прочитанных статей или книг (начатых к прочтению): 
- https://habr.com/ru/articles/50028/ - немного о том, зачем нужен Erlang
- “Программирование в Erlang” - Франческо Чезарини
- “Изучай Erlang во имя добра!” - Фред Хеберт
