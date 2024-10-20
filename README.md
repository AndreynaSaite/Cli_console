# Конфигурационное управление дз №1
## Общее описание
Разработка эмулятора для языка оболочки ОС. Эмулятор запускается из реальной командной строки, 
а файл с виртуальной файловой системой не нужно распаковывать у пользователя. 
Эмулятор принимает образ виртуальной файловой системы в виде файла формата 
zip. Эмулятор работает в режиме CLI.
##  Описание всех функций и настроек

1. pwd
   - вывод текущей дирректории
2. history
     - вывод истории введенных команд
4. uptime
     - выводит в одну строку информацию о работе системы: текущее время, общее время, в течение которого система работала, количество пользователей (количество зарегистрированных пользователей)
5. tree
     - выводит дерево каталога 
6. tail
     - выводит 10 последних строк файла
7. cal
     - выводил календарь
8. date
     - выводит текущкю дату
##  Описание команд для сборки проекта.
1. Клонирование репозитория 

```git clone https://github.com/AndreynaSaite/Cli_console.git```

2. Переход в директорию Homework_config

```cd Cli_console/cli```

3. Запуск скрипта для демонстрации возможностей Cli

```python .\var37.py .\config.toml```

4. Запуск тестов
   
```pytest test.py```

## Примеры использования
![Screen](https://github.com/AndreynaSaite/Cli_console/blob/main/img.png)

## Результаты прогона тестов
![Screen](https://github.com/AndreynaSaite/Cli_console/blob/main/%D0%B8%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5.png)

<!--описание коммитов-->
## Описание коммитов
| Название | Описание                                                                             |
|------------------|----------------------------------------------------------------------------- |
| Clicommit	    | Готовый проект                                                               |
