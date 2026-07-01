# Linux

#### Показать структуру каталога

Команда
```shell
tree
```

Пример
```shell
$ tree ./Проект  
./Проект  
├── content  
│   └── 05aed662b64e6.nwd  
├── meta  
│   ├── builds.json  
│   ├── index.json  
│   ├── options.json  
│   └── sessions.jsonl  
├── nwProject.nwx  
└── ToC.txt
```

#### Посмотреть процессы на порту

Команда
```shell
sudo lsof -i :8080
```

Пример
```shell
$ sudo lsof -i :8080  
COMMAND   PID  USER  FD   TYPE DEVICE SIZE/OFF NODE NAME  
java    59559 aleks 145u  IPv4 695194      0t0  TCP *:http-alt (LISTEN)
```


#### Узнать имя приложения по его PID

Команда
```shell
ps -p 59559 -o comm=
```

Пример
```shell
$ ps -p 59559 -o comm=  
java
```
