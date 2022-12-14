Для компиляции модуля ядра необходимо ввести в консоль:
~$make
~$sudo insmod chd.ko

Для просмотра успешной компиляции:
~$dmesg | tail -5

Чтобы увидеть записанное модулем:
~$cd /dev
/dev$ sudo su
/dev# cat chardev

Информация о модуле:
~$modinfo chd.ko

Чтобы извлечь модуль:
~$sudo rmmod chd.ko 
