# First seminar commands

> + __git init__ – инициализация локального репозитория
> + **git status** – получить информацию от git о его _**текущем**_ состоянии
> - __git add__ – добавить файл или файлы к следующему коммиту
> - __git commit -m “message”__ – создание коммита

# Second seminar commands

> 5. **git log** – вывод на экран истории всех коммитов с их хеш-кодами
> 6. **git branch** – посмотреть список веток в репозитории
> 7. **git branch <название ветки>** – создать новую ветку
> 8. __git checkout <название ветки>__ – переход к другой ветке
> 9. **git branch -d <название ветки>** – удалить ветку

# Play with images and links

> ___
>![Is_that_poop_image?](poop.png)
> — Oh nah, is that poop emoji? It's so uncivilized!
> 
> — Yeahhh, that's it! And take the [3D-model link](https://clck.ru/33JsAL) too.
> 
> — Oh Gosh, you are abnormal.


___

# New AMAZING git commands!

> __git add .__ — добавить __*все*__ файлы из репозитория к отслеживанию.

> __git commit -am "комментарий"__ - обьединение команд *"git add ..."* и *"git commit -m ..."*; т.е. файл одновременно добавляется к отслеживанию и коммитится.

> __git log --graph__ - лог в виде дерева, где *"--graph"* это параметр.

> __git checkout -b branch_name__ - создать и перейти в новую ветку, где *"-b"* это параметр *"branch"*.

> **git merge name_branch** - слияние двух веток и подстановка на место **_текущей_** ветки.

> **git merge --abort** - отмена слияния (при конфликте).

## Тест отмены слияния при конфликте

Тут, на 45-й строке в ветке master должен возникнуть конфликт и текстом из ветки test_aborting. Посмотрим к чему это приведёт.

