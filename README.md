# task63
 mkdir libs - создаем каталог libs для библиотек .dll  
   
 gcc -shared -o libs/add.dll -fPIC add.c - компилируем динамические библиотеки в .dll 
 gcc -shared -o libs/subtract.dll -fPIC subtract.c 
 gcc -shared -o libs/root.dll -fPIC root.c  
 gcc -shared -o libs/multiply.dll -fPIC multiply.c

 gcc -o task63 task63.c - компиляция
 ./task63 — запуск программы
