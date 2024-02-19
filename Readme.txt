在麒麟系统下可以正常运行。
在同目录下，使用sudo g++ -I/usr/local/include/libusb-1.0 ./FUN_PrinterUSB.cpp ./PrintUSB3.cpp -o PrintUSB3 -lusb-1.0 -lpthread
进行编译
编译完成，生成PrintUSB3
执行 sudo ./PrintUSB3




但是在Windows下，无法开启USB，提示不支持。