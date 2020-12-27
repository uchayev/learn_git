# Изучаю GIT по видеоурокам.

Точнее, изучал когда-то, но решил заново пройти по разным видеокурсам на youtube и обновить знания.

## [GIT+GitHub от ITDoctor][1]

### INFO

#### Что интересного узнал/усвоил/использовал/применил:

#### Использованные расширения для VS Code:

- Gist | kenhowardpdx.vscode-gist | Ken Howard
- Git Graph | mhutchie.git-graph | mhutchie
- Git History Diff | huizhou.githd | Hui Zhou

#### GIT hints:

- git reset --hard HEAD^1 - отменяет (удаляет) последний коммит со всеми изменениями в коде
- git reset --soft HEAD^1 - отменяет (удаляет) последний коммит, но оставляет изменения в коде (однако файлы считаются измененными - modified)
- git checkout -- .  - отменяет изменения в коде до состояния предыдущего коммита

Также получил ответ на вопрос о переносе всей структуры (со всеми коммитами) дерева гита в новую ветку на сайте [Stackoverflow.com][2]

За что огромное спасибо [AlexGlebe](https://ru.stackoverflow.com/users/288358/alexglebe)

#### Что сделано:

- git checkout master - становимся в последний коммит master
- git reset --hard df46d78 - перенос master назад – вырезаем весь master до первого коммита
- git checkout git+github_by_itdoctor - переходим в новую ветку
- git reset --hard 109335e - новую ветку вперёд - вставляем всю структуру
- git checkout master - "выходим" на чистый master

---

## [Git Полный курс от  WebDev. GromMax][3]

### INFO

Интересный курс, рассказывается про git, git flow.
Но меня в этом курсе не устроило:

- качество материала (постредактура видео- и аудиоряда) оставляет желать лучшего
- объяснение велось на базе PhpStorm IDE со встроенными командами работы с гитом, а хотелось бы объяснений работы через консоль
- показалось, будто за 10 уроков пробежались "галопом по Европам"
- пожалуй, если уж автор взялся за объяснение git flow, то мог бы позаботиться и сделать несколько аккаунтов в гитхабе и трелло, чтобы было нагляднее.
- автор конечно владеет материалом в общем, но сбивается в некоторых деталях (в работе в PhpStorm IDE и GitHub).
- в итоге получается, что не такой уж и полный курс

НО:

Для интересующихся gitflow на реальных проектах и работой с git в PhpStorm IDE - должен зайти!

[1]: https://www.youtube.com/watch?v=JdUzxh8miQw&list=PLuY6eeDuleIOMB2R_Kky05ZfiAx2_pbAH
[2]: https://ru.stackoverflow.com/questions/1222765/%d0%9f%d0%be%d0%b4%d1%81%d0%ba%d0%b0%d0%b6%d0%b8%d1%82%d0%b5-%d0%ba%d0%b0%d0%ba-%d0%bf%d0%b5%d1%80%d0%b5%d0%bd%d0%b5%d1%81%d1%82%d0%b8-%d0%b2%d1%81%d1%8e-%d1%81%d1%82%d1%80%d1%83%d0%ba%d1%82%d1%83%d1%80%d1%83-%d0%b4%d0%b5%d1%80%d0%b5%d0%b2%d0%b0-%d1%81%d0%be-%d0%b2%d1%81%d0%b5%d0%bc%d0%b8-%d0%ba%d0%be%d0%bc%d0%bc%d0%b8%d1%82%d0%b0%d0%bc%d0%b8-%d0%b2-%d0%bd%d0%be%d0%b2%d1%83%d1%8e-%d0%b2%d0%b5%d1%82%d0%ba%d1%83
[3]: https://www.youtube.com/watch?v=EJGL-_5B_nI&list=PL4rYLeYunVf3d_RChabguoaKRptGxKTOo