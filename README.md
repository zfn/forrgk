# О проекте
Проект предстваляет из себя систему уведомлений, которые срабатывают по событиям:
* register
  * При регистрации пользователя
* login
  * Когда пользователь выполняет вход
* logout
  * Когда пользователь выходит из системы
* newarticle
  * На сайте появилась новая статья
  
# Инструкция по установке
Чтобы установить и развернуть приложение, Вам необходимо
- Скачать или клонировать проект командой `git clone https://github.com/zfn/forrgk.git`
- Установить параметры для базы данных в файле `basic/config/db.php`
- Выполнить миграцию `yii migrate`
- Перейти на страницу `http://<ваш_хост>/basic/web/`

После этого должна появиться страница входа.

## Панель администратора
Данные для входа в панель администратора:
Имя пользователя: `the_admin`
Пароль: `qwerty123`


## Остальные пользователи
Автоматически регистрируются 20 пользователей, имена имеют вид `testuser[1-20]`,
а пароль у всех одинаковый: `qwerty123`

# Система уведомлений
В админпанели можно без проблем добавить уведомление конкретному пользователю, всем пользователям 
(широковещательное уведомление).
На одно событие можно вешать несколько уведомлений. Верно и обратное, т.е на одно уведомление
можно вешать несколько событий. 

# Интерфейс
По поводу интерфейса, отмечу, что таблицы в админпанели можно сортировать кликнув на заголовок.


# Структура проекта
Проект делиться на 2 части, по сути это FrontEnd и Backend. Весь backend расположен в файле
`basic/modules/admin`. Админпанель здесь реализована в качестве модуля

# Плагины
Также, я написал 1 плагин, который добавляет поддержку e-mail в систему

# Мои контакты и резюме
Создавать крутое резюме у меня не было времени :), поэтому я оставлю ссылку на резюме в hh.kz
https://hh.kz/resume/d130f9f8ff033b85770039ed1f364630394549

Мой номер: +7 705 378 21 51 - зовут Малик.

