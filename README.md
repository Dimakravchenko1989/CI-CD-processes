**Процессы CI/CD**

***HomeWork 1. Основы CI/CD. Знакомство с gitlab***

Регистрация на GitLab:

1. Необходимо зарегистрироваться на GitHub: https://github.com/
Указать почту, пароль и пройти верификацию через указанную почту

2. Возможные причины/баги при регистрации, если просят номер телефона:
- удалить все расширения из браузера (при необходимости - установите их после)
- при создании аккаунта на Github:
- очистите кэш/куки браузера;
- отключите впн;
- укажите почту от яндекса;
- поставьте галки: использование для себя, что вы студент и в следующем шаге "collaborative coding";

3. Далее переходим на сайт GitLab: https://gitlab.com/
— нужно кликнуть на Get free trial, после чего откроется форма регистрации, там нужно выбрать пункт Register with: GitHub
— вводим логин и пароль от GitHub
— заполняем форму с данными (имя, фамилия, страна: Казахстан; место работы – можно указать любую компанию);
— проходим очередную верификацию по почте
— далее будет предложена возможность создать проект — создаем со своим названием

Домашнее задание:
1. Создать pipeline и runner
2. Попробовать сохранить артефакт одной из стадий + исключить из папки с артифактами любой файл
3. Попробовать сделать любую gitlab pages



***HomeWork 2. Continuous integration (непрерывная интеграция)***

Переписать test stage для тестирования docker-а. Достаточно проверить, что docker контейнер на базе нашего собранного образа в предыдущей job запускается.

Прислать ссылку на gitlab_ci.yaml либо скриншот gitlab_ci.yaml test stage и скриншот успешно отработанной job-ы test.
