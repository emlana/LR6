# LR6

Лабораторная работа №6

## Цель лаболаторной работы

изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## Ход работы

* Клонируем репозиторий и настраиваем профиль
    ![(рис 0)](./images/0.png)
* Скачиваем вторую ветку
    ![(рис 1)](./images/1.png)
* Выводим всю историю
    ![(рис 2)](./images/2.png)
* Сливаем 2 ветки в одну
    ![(рис 3)](./images/3.png)
* Удаляем вторую ветку
    ![(рис 4)](./images/4.png)
* Создаем комит, который будем удалять
    ![(рис 5)](./images/5.png)
* Удаляем этот комит
    ![(рис 6)](./images/6.png)
* Создаем файл в удаленном репозитории и обновляем локальный
    ![(рис 7)](./images/7.png)
* Создаем ветку для отчета
    ![(рис 8)](./images/8.png)
* Финальная история изменений

``` sh
efb9e6b - 4116 Романцов А.А, 2 minutes ago : ~~alpha~~ omega
52621d3 - 4116 Романцов А.А, 35 minutes ago : file created
c781a3f - 4116 Романцов А.А, 47 minutes ago : merge conflict resolve
0221506 - 4116 Романцов А.А, 66 minutes ago : test commit
921f53b - Kurtyanik, 1 year, 11 months ago : Обновление информации
0f9f50d - Kurtyanik, 1 year, 11 months ago : Заполнил файл
c08a654 - Kurtyanik, 1 year, 11 months ago : Файл создан пустым
3c6e913 - Kurtyanik, 1 year, 11 months ago : Initial commit
```

В виде графа:

``` sh
* efb9e6b - 4116 Романцов А.А, 3 minutes ago : ~~alpha~~ omega
* 52621d3 - 4116 Романцов А.А, 37 minutes ago : file created
*   c781a3f - 4116 Романцов А.А, 49 minutes ago : merge conflict resolve
|\  
| * 0f9f50d - Kurtyanik, 1 year, 11 months ago : Заполнил файл
* | 0221506 - 4116 Романцов А.А, 67 minutes ago : test commit
* | 921f53b - Kurtyanik, 1 year, 11 months ago : Обновление информации
|/  
* c08a654 - Kurtyanik, 1 year, 11 months ago : Файл создан пустым
* 3c6e913 - Kurtyanik, 1 year, 11 months ago : Initial commit
```

> Лог терминала и команд в отдельных txt файлах

## Вывод

Мы изучили базовые возможности системы управления версиями, получили опыт работы с Git Api и опыт работы с локальным и удаленным репозиторием.