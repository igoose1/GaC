# gacpp



## Начало работы

Этот файл поможет скомпилировать .cpp файлы, используя компилятор g++, в редакторе sublime-text на linux-дистрибутивах.
Файл отличается от других тем, что многие настройки представлены переменными, что помогает лучше визуализировать конфигурации.


### Подготовка

Пакеты, требующие для правильной компиляции файлов и установки данного build-пакета

```
g++
terminator
git
```


### Установка

Скачайте файлы

```
git clone https://github.com/igoose1/gacpp.git
```

Переместите gacpp.sublime-build в папку с пакетами sublime-text

```
cp gacpp/gacpp.sublime-build $HOME/.config/sublime-text-3/Packages/User/
```



## Использование


### Версия C++

Измените переменную `C++_VERSION` для [нужной вам версии](https://gcc.gnu.org/projects/cxx-status.html).

По умолчанию стоит `c++14`.


### Оптимизация

Измените переменную `OPTIMIZATION_PARAMS` для [нужного вам флага](https://gcc.gnu.org/onlinedocs/gcc/Optimize-Options.html).

По умолчанию стоит `-O2`.
