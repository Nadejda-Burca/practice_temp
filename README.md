# practice_temp

## Соответствие групп и тем на практикум.

1. Что такое система контроля версий
2. Для чего нужна система контроля версий
3. Установка git на ваш ПК (в зависимости от системы)
4. Установка VSCode на ваш ПК
5. Что такое репозиторий и инструкция по созданию локальных репозиториев.
6. Базовая работа с локальным репозиторием
7. Что такое ветки и для чего они нужны при работе с системой контроля версий.
8. Базовая работа с ветками в git.
9. Что такое удаленный репозиторий и для чего он нужен
10. Базовая работа с удаленными репозиториями GitHub
11. Как строится и для чего нужна совместная работа в системах контроля версий
12. Инструкция по созданию pull request
13. Книги и полезные ссылки по изучению git.
14. Альтернативные системы контроля версий.


12. Инструкция по созданию pull request

 Сначала нам необходимо склонировать изначальный репозиторий. Для этого перейдем к нему и нажмем кнопку Fork.
  Далее склонированный репозиторий нужно скачать на свой компьютер.


 Локальный, скачанный, репозиторий имеет одну привязку к удалённому репозиторию, названную origin, которая указывает копию на GitHub, а не на оригинальный.

Downstream, то есть склонированный репозиторий, должен быть условно  курсе изменений происходящих в оригинальном репозитории, то есть в upstream. Так как разработка там продолжается. Таким образом, необходимо получить изменения (fetch) от upstream и применить к своему origin репозиторию, чтобы не было конфликтов.

Поэтому нужно создать привязку к изначальному репозиторию, чтобы проделать то, о чем сказано выше, и назвать ее любым именем, в этом примере она названа upstream, но это название обязательным не является:

 После этого рекомендуется создать новую ветку и вносить изменения туда.
  Далее нужно внести изменения в сам проект при помощи коммитов.
   После этого небходимо отправить изменения в копию репозитория на Github.
    Теперь изменения находятся в копии репозитория на GitHub в ветке feature.