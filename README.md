# MY Git

**This is my school for GIT**

## comands
**базовые команды**

* init - инициализация папки
* added - добавить что либо
* сommit -m "сохраняем с коментарием"
* log - смотрим изменеия в файле
* checkout - переход на другое сохранение
* checkout master - возврат на самое актуальное состояние
* diff - разница между записываемыми файлами

**Работа с ветвями**

* branch - выводим список веток в репрозитории
* branch имя новой ветки - создадим новую ветку
* clear - очистка терминала пишем без (git)
* checkout - переходим на ветку
* merge - слияние веток
* branch -d имя ветки  -удаление ветки
* log --graph - графическое отоброжение веток
* q - выход

## Markdown first steps

1. *Italics.* - обрамляем текст звездочками
2. **bold** - обромляем текск двумя звездочками
3. ## subhead - двойной хэш тэг для позоголовка
4. ~strikeouts - не работает зачеркивания)

## Lists

чтобы добавить ненумерованные списки нужно ввести звездочку пробел(* ) например так
 * элемент один
 * элемент два
 * элемент три
 
 чтобы добавить нумерованный список нужно всго лишь ввести номер точка. например так
 1. первый элемент 
 2. второй элемент
 3. третий элемент

## images

чтобы ввести картинку в текст пишем:

* !(текст в случае не запуска картинки)[ссылка на картинку помещенную в отслеживаемой гитом папку]
учитываем что большие файлы в том числе картинки в написании кода не используются для этого в корневой ветви git создается папка .gitignor/ при помещении большого файла git перестает ругаться на неотслеживаемый файл.

# создаем конфликт и решаем его
