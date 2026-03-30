# Лабораторная работа №3
## Homework

Как было сказано на занятии, я не буду приводить здесь содержимое файлов `CMakeLists.txt`, лишь объясню как вся конструкция работает.

Рассмотрим дерево этого репозитория:
```
.
├── CMakeLists.txt
├── formatter_ex_lib
│   ├── CMakeLists.txt
│   ├── formatter_ex.cpp
│   └── formatter_ex.h
├── formatter_lib
│   ├── CMakeLists.txt
│   ├── formatter.cpp
│   └── formatter.h
├── hello_world_application
│   ├── CMakeLists.txt
│   └── hello_world.cpp
├── solver_application
│   ├── CMakeLists.txt
│   └── equation.cpp
└── solver_lib
    ├── CMakeLists.txt
    ├── solver.cpp
    └── solver.h
```

В каждой из папок находится по файлу `CMakeLists.txt`, каждый из которых выполняет свою задачу. В папках `formatter_lib`, `formatter_ex_lib` и `solver_lib` собираются три библиотеки. В папках `solver_application` и `hello_world_application` собираются два исполняемых файла, а в главном `CMakeLists.txt` собирается совокупность из двух исполняемых файлов.

Для проверки запустим исполняемые файлы из задания три.
```
-------------------------
hello, world!
-------------------------
```

```
1 5 -6
-------------------------
x1 = -6.000000
-------------------------
-------------------------
x2 = 1.000000
-------------------------
```

Все работает.

**To be continued...**