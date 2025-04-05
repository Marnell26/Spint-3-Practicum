# Работа с Git

## Что такое Git

Система контроля версий, или VCS, — это программное обеспечение, которое помогает отслеживать изменения в программах, текстовых файлах, больших документах, веб-сайтах и так далее. 
Одно изменение или группу изменений в VCS называют ревизией или версией. Каждая такая ревизия содержит информацию о том, что изменилось, кто внёс изменения, когда это было и иногда комментарии к изменению.

Основные функции системы контроля версий:

* хранит историю изменений в виде отдельных ревизий;
* позволяет манипулировать историей: например, менять порядок ревизий, полностью удалять версии, возвращаться назад в истории;
* помогает анализировать изменения: например, кто и когда вносит изменения, кто чаще всего вносит изменения в определённый файл и так далее.

## Основные команды Git

### Основные операции в командной строке

| Команда                                     | Назначение команды                                |
| ------------------------------------------- |:------------------------------------------------: |
| **pwd**                                     | Выводит путь к текущей директории                 |
| **cd %Имя_папки%**                          | Сменить директорию                                |
| **cd /~**                                    | Перейти к домашней директории                     |
| **cd ..**                                   | Вернуться на уровень выше                         |
| **ls**                                      | Вывести содержимое директории                     |
| **ls -a**                                   | Вывести содержимое директории со скрытыми файлами |
| **touch %Имя_файла%**                       | Создать файл                                      |
| **mkdir %Имя_папки%**                       | Создать папку                                     |
| **mkdir -p %папка/вложенная папка/...%**    | Создать структуру директорий                      |
| **cp %что_копируем% %куда_копируем%**       | Копирование файлов и папок                        |
| **mv %что_копируем% %куда_копируем%**       | Перемещение файлов и папок                        |
| **cat %Имя_файла%**                         | Чтение файлов (только текстовые файлы)            |
| **rm %Имя_файла%**                          | Удалить файл                                      |
| **rmdir %Имя_папки%**                       | Удалить папку                                     |
| **rm -r %Имя_папки%**                       | Удалить папку вместе со её содержимым             |

