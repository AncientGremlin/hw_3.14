# git config
Данная команда используется для настройки параметров GIT на глобальном и локальном уровнях проекта. 

### Использование

`git config [<options>]`

Посмотреть все возможные options:

`git config`
___
### Посмотреть текущие настройки GIT

`git config -l` 

или 

`git config --list` 
___
### Наиболее часто настраиваемые параметры
Установить имя пользователя (для User Name использовать только латинские буквы)

```bash
git config --global user.name "User Name"
```
___
Установить email. **Важно:** для последующей работы с GitHub email должен совпадать с той, на которую зарегестрирован аккаунт.

```bash
git config --global user.email "someemail@somedomdomain.something"
```
___
[Назад](./readme.md)