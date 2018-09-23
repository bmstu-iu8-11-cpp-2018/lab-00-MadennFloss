# Тестовый репозиторий
Этот репозиторий создан для тестирования средств разрабочтки и предоставляет возможность опробовать средства, которые требуются для выполнения лабораторных работ.

## Задание
1. Создайте собственную ветку `wp/lab`, отведенную от ветки с названием `master`.
1. Реализуйте приложение **hello world** в файле `main.cpp`.
1. Добавьте имя файла `main.cpp` в соответсвующую секцию в файле `CMakeLists.txt`.
1. Создайте pull request (сокращенно PR).
1. Убедитесь, что TravisCI проверил вашу работу и в ней нет ошибок.
1. Проверьте работу своего напартника в созданном им PR.
1. Исправьте замечания вашего напарника в вашем PR.
1. Убедитесь, что TravisCI проверил вашу работу и в ней нет ошибок.
1. Сообщите напарнику, что все замечания выполнены и дождитесь, когда напарник утвердит ваш PR.
1. Влейте свои изменения из ветки `wp/lab` в ветку `master`.
1. Повторите все шаги, пока не доведете эти действия до автоматизма.

#### Github
Git - это распределённая система управления версиями исходного кода. Git поддерживает быстрое разделение и слияние версий, включает инструменты для визуализации и навигации по нелинейной истории разработки.

Чтобы выполнить успешно выполнить лабораторную:
1. Необходимо создать разработческую ветку (назовем её `wp/lab`) отведенную от ветки с названием `master`. Это можно сделать с помощью клиентского приложения или прямо в веб-версии.
1. Всю дальнейшую работу необходимо вести в ветке `wp/lab`.
1. После выполнения работы, необходимо создать pull-request, запрос на изменений исходного кода в ветке `master`. Это удобно сделать в два клика в веб-версии github.com в вашем репозитории.
1. После этого запуститься автоматическая проверка работы.

#### TravisCI
Каждый учебный репозиторий содержит систему автоматической сборки TravisCI. Это позволяет автоматизировано проверить, что в коде нет синктактических ошибок, что исходный код компилируется и проходит ряд тестов.
1. Первый тест - это тест на форматирование кода. Специальный скрипт укажет на неточности соответствия принятому [codestyle](https://github.com/bmstu-iu8-cpp/cpp-beginner-2017/blob/master/styleguide.md)
1. Второй тест - это тест на то, что исходный код компилируется в исполняемый файл и этот файл работоспособный.
1. Третий тест - это тест на ошибки и предупрежедния компилятора.
Все эти проверки запускаются на созданный вами PR. Если все тесты прошли успешно, то TravisCI выставит "зеленую галочку", сообщающую об успешном прохождении тестов, если хотя бы одна проверка завершилась ошибкой, то появится "красный крестик". И это явное сообщение, что вы что-то сделали не так и необходимо эти ошибки исправить. О том какие именно ошибки вы совершили можно прочитать в лог-файле самого TravisCI, чтобы открывать этот файл - щелкните по "красному крестику".

#### Code review
Code review - это систематическая проверка исходного кода программы с целью обнаружения и исправления ошибок, которые остались незамеченными в начальной фазе разработки. Целью просмотра является улучшение качества программного продукта и совершенствование навыков разработчика. Эта техника принята во всех компаниях, которые занимаются программной разработкой. Мы же с помощью code review построим процесс обучения.

После того, как вы создали PR и система TravisCI сделала первичную проверку вашего кода и выставила "зеленую галочку", то настало время с гордостью отправить ваш PR на code review вашему преподавателю. Преподаватель проверит вашу работу, укажет на ошибки и неточности, попросит исправить ваш код. Лабораторная считается выполненной и зачтенной только после того, как преподаватель утвердил ваш PR.

### Самостоятельная работа
* ознакомтесь с графическим клиентом git.
* ознакомьтесь с утилитой clang-format. Она позволяет автоматически форматировать ваш код.
* ознакомнесь с консольным клиентов git.
