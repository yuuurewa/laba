Для компиляции модуля ядра необходимо ввести в консоль:
~$make
~$sudo insmod proc.ko

Для просмотра успешной компиляции:
~$dmesg | tail -5

Если отказано в доступе, ввести:
~$sudo su

Затем записываем:
#echo "Hello World!" > /proc/hello

Читаем:
#cat /proc/hello

Информация о модуле:
~$modinfo proc.ko

Чтобы извлечь модуль:
~$sudo rmmod proc.ko 
