Для компиляции модуля ядра необходимо ввести в консоль:
~$make
~$sudo insmod netlink.ko

Для просмотра успешной компиляции:
~$dmesg | tail -5

Информация о модуле:
~$modinfo netlink.ko

Чтобы извлечь модуль:
~$sudo rmmod netlink.ko 
