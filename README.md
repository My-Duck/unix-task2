# Вторая задача в курсе UNIX

## Тестирование

Для проверки работы используется скрипт `runme.sh`. 
Этот скрипт запукает 10 экземпляров программы. Каждый экземпляр в вечном цикле блокирует файл на одну секунду, после снимает блокировку.
В результате работы будет сформирован файл result.txt, который содержит информацию о работе каждого экземпляра (PID процесса и количество успешных блокировок) по одному в строке.


## Компоненты

- `main.c` - программа для блокировки указанного файла
- `runme.sh` - скрипт для тестирования программы