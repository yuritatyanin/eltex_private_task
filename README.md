# Необходимо реализовать многопоточное приложение на языке С. 
Первый поток - распасовщик. N потоков - обработчики.
Распасовщик в случайный момент времени генерирует сообщение (например, набор символов) и предает его одному из свободных потоков-обработчиков.
Поток-обработчик при получении сообщения выводит его на экран и инкрементирует счетчик обработанных сообщений.
После этого поток-обработчик засыпает на какое-то время, чтобы дать возможность поработать соседним потокам.
Приложение должно уметь обрабатывать сигнал USR1, при котором будет выводиться статистика.
Сколько сообщений обработал каждый поток-обработчик.
Работу выполнять с использованием системы контроля версий git.
Дедлайн 1 неделя.
