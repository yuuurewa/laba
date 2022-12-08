Для компиляции модуля ядра необходимо ввести в консоль:
~$make
~$sudo insmod hello.ko

Для просмотра успешной компиляции:
~$dmesg | tail -5

Будет видно содержимое: Hello World!

Информация о модуле:
~$modinfo hello.ko

Чтобы извлечь модуль:
~$sudo rmmod hello.ko 
