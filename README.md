# *Работа с удаленными репозиториями*

Раннее мы работали лишь с самим Git. Теперь же нам необходимо создать аккаунт на сервисе <https://github.com/>. Однако путать Git и Github не стоит. Если в первом случае речь идет о популярной системе для работы с репозиториями, то во втором мы имеем дело с огромным архивом различных репозиториев, который позволяет разработчикам и программистам обмениваться версиями проектов и оперативно вносить в них изменения. Но каков же алгоритм работы с удаленными репозиториями?

*Прежде всего, ознакомимся с некоторыми командами:*

* **git clone.** Данная команда позволяет склонировать внешний репозиторий на ПК. При этом необходимо указывать адрес (ссылку) репозитория после введения команды. 
* **git pull.** Команда позволяет скачать всю информацию из текущего репозитория и автоматически сделать merge с нашей версией.
* **git push.** Команда позволяет отправить нашу версию репозитория на внешний репозиторий. Требует авторизации на внешнем репозитории.

*Итак, когда мы знакомы с данными программами, можно приступить к выполнению определенного алгоритма:*

1. Регистрируемся на Github
2. Находим интересующий нас репозиторий и делаем его fork 
3. Затем вводим команду git clone для нашей новой версии этого репозитория 
4. Создаем ветку с предполагаемыми изменениями
5. Производим все изменения только в этой ветке
6. Отправляем все изменения в свой аккаунт при помощи команды  
7. В окне на Github появляется возможность отправить pull request 
