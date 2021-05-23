# R для тервера и матстата

Добро пожаловать на страничку курса "R для теории вероятностей и математической статистики". Чувствуй себя как дома.

> Нашёл на этой страничке ошибку? Нашёл какой-то ультраполезный ресурс? Придумал какое-то интересное задание для семинара? Есть конструктивная критика? Не молчи, напиши мне об этом на почту filfonul@gmail.com, в Telegram (@Ppilif) или [Vk](https://vk.com/ppilif).

* Актуальные материалы семинаров лежат в папках `./end_seminars_2021/sem*`
* В каждой папке есть свой небольшойx README с дополнительными материалами
* Если вы хотите скачать из репозитория конкретную папку, просто вставьте ссылку на неё [в сервис для скачки.](https://minhaskamal.github.io/DownGit/#/home)
* Если вы хотите скачать всё, жмите зелёную кнопку справа наверху, либо [выучите git](https://nbviewer.jupyter.org/github/FUlyankin/LaTeX/blob/master/Logi_2019/sem_8/Intro_git_ssh.ipynb) и просто сделайте `clone`, а потом при каждом онбновлении делайте `pull`
* [Видео 2021](https://www.youtube.com/playlist?list=PLNKXA-74YGLgug7l557PiN-hPNCPVmKsJ)
* [Cтарая страничка курса,](https://fulyankin.github.io/r_probability/) [видосы с курса 2020 года](https://www.youtube.com/playlist?list=PLNKXA-74YGLhv3CdwExDVxMa0DmA4ASg_)


## Идеология курса:

Поздравляю! Впервые ты оказался около опасной черты. Твоих математических навыков стало хватать для постижения жизни. Именно этим мы и займёмся. Курс идёт 8 недель. Каждую неделю по две пары. Занятия полупрактические. Смотрим презентации, код, решаем задачи у доски. Цель курса — прокачать интуитивное понимание тервера и матстата, составить картину мира в целом, посмотреть, как они используются на практике. Вспомнить, что вы проходили на лекциях и переосмыслить, а также увидеть что-то новое, на что времени на лекциях не хватило.


## Бюрократия

Домашки сдаём командами по три человка. Скорее всего, будет три домашки. Внутри команды вы сами решаете, кто какие задачи решает, потом собираете решения вместе и получаете баллы на команду. Домашние задания сдаются в виде ссылки на colab. __По этой ссылке у меня должны быть права на редактирование.__ Писать решение можно либо на R либо на python. Какой язык вы выбирете - абсолютно неважно. 

Ради всего святого, оформляйте домашки по-нормальному: 

- [Потратьте 10 минут,](http://www.markdowntutorial.com/) чтобы разобраться с Markdown
- [Ещё 10 минут,](https://colab.research.google.com/notebooks/intro.ipynb) чтобы разобраться с колабом
- [И ещё 10 минут,](https://ru.wikibooks.org/wiki/Математические_формулы_в_LaTeX) чтобы разобраться как вбивать теховские формулы
- [И ещё 10 минут](https://github.com/danlark1/hse_missing_cs_education/tree/master/layout_systems) почитайте про философию маркдауна и теха


У каждого, кто записался на курс, уже есть зачёт: 4 балла из 10. Для того, чтобы получить за курс 10, команда должна насобирать 100 баллов. Оценка ставиться на всю команду разом. Первые две команды в рейтинге свожу почилить на крышу Яндекса. Конечно же, если у этих команд больше 100 баллов. __(Про Яндекс неточно, в связи с пандемией и ограничениями, но я очень постараюсь).__

* [Форма для регистрации команд](https://docs.google.com/forms/d/e/1FAIpQLSfW1e5wSWF42xlYxjE-XpXusxd7BMKROrdaiz2lPPio_OPsqw/viewform)
* [Форма для сдачи домашек](https://docs.google.com/forms/d/e/1FAIpQLSdfUl5-LbWXVOlNDrx6bjvuqcFvw_8c51uBgzW3_QuOnMfWYA/viewform)


## Домашние задания

| Ссылка на колаб | дедлайн | решение | стоимость |
|:---------------:|:-------:|:-------:|:---------:|
| [Симуляции](https://drive.google.com/file/d/1_d_o9_UvVeErRstAZ6-OIi7p94q8y17w/view?usp=sharing)       | 10 мая | будет   | 100 баллов|
| [Гипотезы](https://drive.google.com/file/d/1rfKx3N7ckWlrOCaWWEVMWDqXw_sHwZIm/view?usp=sharing)        | 20 июня | будет   | 100 баллов|
| Правдоподобие   | июнь | будет   | 100 баллов|


* Турнирная таблица с баллами команд:

> появится тут после сдачи первого дз


## Большой план маленьких побед на 2021 год:

__Что я хочу:__ многие вещи из предыдущих итераций курса очень подробно рассказаны [в моих онлайн-курсах на coursera,](https://www.coursera.org/specializations/machine-learning-from-statistics-to-neural-networks#courses) хочется в рамках этого курса не повторяться с тем, что там было и рассказать что-то другое. При этом надо сделать так, чтобы люди понимали о чём идёт речь. Выходит, что какое-то пересечение в темах будет неизбежным :(


- [__sem01__](./end_seminars_2021/sem01) Зачем мы учили тервер? Критерий Фишера, знаков и рангов. Говорим про разные распределения. Выводим нормальное распределение из воздуха. Генерируем случайные величины на компьютере. 

- [__sem02__](./end_seminars_2021/sem02) Говорим про варку случайных величин. Обсуждаем квантильное преобразование. Выводим распределение Пуассона из воздуха. Геометрия случайных величин. Говорим про формализм и сигма-алгебры. Про то, что это простой способ моделировать знания. 

- [__sem03__](./end_seminars_2021/sem03) Говорим про разные виды сходимости на доске (по вероятности, по распределению, в среднем, почти наверное). Обсуждаем их союзников и зачем они нам сдались. Решаем задачки на сходимости. 

- [__sem04__](./end_seminars_2021/sem04) Вся статистика через призму средних и ЦПТ. Метод моментов. Мощь средних. Дельта-метод. Доверительные интервалы. Концептуально про гипотезы. Схема матстата. Стабилизация дисперсии. Преобразования выборок. Притащить сюда весы и мешок конфет для эксперимента. 

- [__sem05__](./end_seminars_2021/sem05) Точные доверительные интервалы и гипотезы для Exp, Bin или U. Решаем задачки на ошибки 1 и 2 рода. Мощность критерия. Какими бывают критерии? Про бутстрап на пальцах. 

- [__sem06__](./end_seminars_2021/sem06) Метод максимального правдоподобия. Информация Фишера. Доверительные интервалы. Многомерный дельта-метод. Многомерное нормальное распределение. 

- [__sem07__](./end_seminars_2021/sem07) Энтропия. KL-дивергенция. Информационные критерии. Возможно, про TSNE и UMAP. Возможно, про EM-алгоритм. Как душа ляжет :) 

- [__sem08__](./end_seminars_2021/sem08) Тут либо про Марковские цепи, либо про Байесовские методы и MCMC.


__Чего не хватает:__ экспоненциальное семейство, достаточные статистики. Распределения максимумов и финансовые рынки. Большая сила o-малых. Задачи на марковские цепи, метод 1 шага и тп для собесов и экзаменов. Куда-нибудь всунуть геометрию случайных величин и тп. 


## Почиташки и видосы:

Тут лежат всякие глобальные полезные ссылки на разные материалы. Ещё больше ссылок ищите в README к семинарам!

* Ещё больше полезных материалов [ищи в репозитории к курсеровскому курсу](https://github.com/FUlyankin/matstat_coursera)


__Книги по терверу и матстату:__

* [Учебник Черновой по терверу](https://github.com/FUlyankin/r_probability/raw/master/books/Хороший%20учебник%20по%20терверу.pdf)
* [Учебник Черновой по матстату](https://github.com/FUlyankin/r_probability/raw/master/books/Хороший%20учебник%20по%20матстату.pdf)
* [Книга про парадоксы в теорвере и матстате ](https://github.com/FUlyankin/r_probability/raw/master/books/Sekej%20G.%20_Paradoksy%20v%20teorii%20verojatnostej_.pdf)
* [Культурный код.](https://github.com/bdemeshev/probability_dna) Сборник красивых нетривиальных задач по терверу и матстату. Слабо решить их все?
* [Занимательная статистика Лагутина,](https://yadi.sk/i/UuWhEn_L4X_Rwg) как и Чёрнова выводит в понимании на более высокий уровень
* Целые [10 глав](http://personal.psu.edu/drh20/asymp/lectures/asymp.pdf) асимтотического тервера и статистики, очень хороший конспект для продвинутого изучения 
* [Coock boock](http://statistics.zone/) по терверу и матстату в 10 страницах


__Книги по R:__

* [Учебник Демешева по R для начинающих](https://github.com/bdemeshev/r_manual_book)
* Его же [страница по R с кучей учебников и ссылок](https://github.com/bdemeshev/em301/wiki/R)


__Другие крутые источники:__

* [Визуализации по терверу и матстату.](http://students.brown.edu/seeing-theory/) Можно посмотреть на условную вероятность и многое другое своими глазами.
* [Репозиторий по теории вероятностей](http://bdemeshev.github.io/pr201/) от Демешева Б.Б. Рекомендую посмотреть видеозаписи семинаров. Там решается много экстраординарных задач, которые встречаются на собеседованиях.
* [Тест по теории вероятностей для школьников из этого репозитория.](https://github.com/FUlyankin/r_probability/blob/master/books/intro_test.pdf) Слабо ответить на все вопросы верно?
* [Набор лекций по рискам от Ильи Езепова.](hhttps://rpubs.com/iezepov) Море теории вероятностей для финансов и не только. Кстати говорая, на [Rpubs](https://rpubs.com/) можно найти много других приятных тетрадок с кодом на R.


## Лицензия и благодарности

Весь контент, созданный для этого курса распространяются на правах лицензии [Creative Commons Attribution-Share Alike 4.0.](https://creativecommons.org/licenses/by-sa/4.0/deed.ru) Материалы публикуются как общественное достояние. При наличии технической возможности необходимо также указать активную гиперссылку на [страницу курса.](https://fulyankin.github.io/R_probability/)

Спасибо за помощь в создании этого курса Демешеву Борису Борисовичу! Его материалы по терверу и запал энтузиазма сделали его возможным. Спасибо за помощь в стенографировании домашек Белякову Юре (формулы). Спасибо огромной своре второкурсников за поиски ошибок и опечаток (Сороковниной Свете, Кидло Ире, Нуртудинову Камилю, Курилкиной Юле и Евстафьеву Серёже и многим-многим другим)


<br>

<br>
