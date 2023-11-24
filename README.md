# Это fork https://github.com/DanteOnline/lesson5-git-pull для разбора семинара https://www.youtube.com/watch?v=Oz0wLy4K91I
1. На видео 1:18 прописаны основные цели занятия:
- Создавать модули
- Делать импорт из своих и сторонних модулей
- Использовать if __name__ == "__main__"
- Создавать ветки и Pull Request (механизм, который позволяет отслеживать изменения в проекте)
2. На видео 14:22 говориться, что объяснение построено на примере рефакторинга кода следующих файлов:
- famous_info.py
- true_year.py
- victory.py
- 
все эти файлы требуют модуль random.py
(Рефакторинг (refactoring) — это процесс изменения внутренней структуры программы, не затрагивающий её внешнего поведения и имеющий целью облегчить понимание её работы.)
3. В результате рефакторинга создается новый модуль - famous_persons.py, который позволяет убрать дублирование кода (Рис. 1).
<image src="https://github.com/Pav9551/lesson5-git-pull/blob/master/refactoring.vpd.png" alt="Текст с описанием картинки">
## До работы с инструкцией рекомеендовано почитать про модули https://smartiqa.ru/courses/python/lesson-5 и посмотреть https://www.youtube.com/watch?v=1upalKiDeEI&t=1286s по Git:

- Сделать fork на своей учетке git https://github.com/DanteOnline/lesson5-git-pull:

- В pycharm создать новый проект с виртуальным окружением venv:

- Клонировать репозиторий со своей учетки (пример):
```
git clone https://github.com/Pav9551/lesson5-git-pull.git
```
- Перейти в папку:
```
cd .\lesson5-git-pull\
```

- Создать новую ветку - lesson4
```
git checkout lesson4
```





