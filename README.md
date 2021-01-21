# RISE - Электронное меню
описание и тд

# Список технологий на сайте
<img src="https://t.me/risekg/2" alt="logo" width="300" data-canonical-src="https://oss.redislabs.com/redisearch/img/logo.svg" style="max-width:100%;">

WEB (витрина и панель управления)

• Laravel - PHP-фреймворк

• База данных MySQL

• Bootstrap - на основе дизайна Argon от Creative Tim

• React JS

• Готовность к работе с мобильными устройствами - витрина и панель управления

# 

Версия программного обеспечения

PHP 7.x, MySQL 4.x,
MySQL 5.x
# 
Файлы включены

JavaScript JS, JavaScript JSON, HTML, CSS, Sass, PHP
# 
# Инструкции по установке

Это проект Laravel. Вы можете установить на VPS или на виртуальный хостинг. Инструкция по виртуальному хостингу.  (здесь ссылка)
# 

Установка на виртуальном хостинге
Узнайте, как установить RISE
# 
Требования

RISE - это автономное веб-приложение, написанное на PHP поверх платформы Laravel 5.8. Для установки RISE требуется следующее:

Версия PHP: 7.4 или 8.0

Версия MySQL:> = 5.x

Сервер приложений: Apache, Nginx

ВАЖНО: сценарий не может быть установлен во вложенную папку. Только непосредственно в домене или субдомене.
# 
Подготовьтесь к установке

Установить RISE очень просто, и вы сможете установить его без каких-либо знаний в области программирования. Процесс установки включал три основных этапа:
# 
1.Создание домена или субдомена

2.Создание базы данных

3.Выгрузка файлов сценария на хост
# 

Установка на виртуальном хостинге
Рекомендуются Plesk / cPanel и другие менеджеры хостинга. В этом руководстве мы будем использовать Plesk, но для других должно быть похоже.
# 
1. Создайте свой домен или субдомен на общем хостинге.

После того, как вы его создали, вы сможете получить доступ к файловому менеджеру для этого домена / поддомена.
Удалите все файлы по умолчанию, которые могут быть добавлены.
# 
2. Создайте базу данных

Создайте пустую базу данных на вашем виртуальном хостинге и запомните эти учетные данные
имя базы данных
имя пользователя db
пароль пользователя db

Процесс создания базы данных примерно такой
# 
Фото: https://t.me/risekg/2
# 
3. Загрузите исходный код, который вы получили от Разработчика, и распакуйте его.
# 
4. Теперь перейдите к веб-адресу, на котором расположен ваш проект.
# 
напр. mydomain.com или subdomain.mydomain.com
# 
Щелкните «Проверить требования». Если некоторые требования отсутствуют, они будут отмечены.
# 
Фото: https://t.me/risekg/3
# 
Теперь проверим права доступа к папке. Если какая-то папка отмечена как недоступная для записи, проверьте его разрешение. Должно быть 775 или 777

Фото: https://t.me/risekg/4
# 

Теперь нам нужно настроить среду. Это говорит Laravel, как работать

Фото: https://t.me/risekg/5
# 

Выберите классический текстовый редактор.

Фото: https://t.me/risekg/6
# 

5. Конфигурация среды

Примечание. Эта конфигурация требует много шагов, поэтому мы объясним это более подробно.
# 
Как мы уже упоминали, настройка среды требует много шагов, но для начала нам понадобится всего несколько
# 
Основы работы с приложениями Это первые переменные, которые вам нужно изменить.
# 
APP_NAME = здесь идет название приложения
APP_ENV = производство
APP_URL = URL вашего веб-сайта идет сюда
# 

Конфигурация базы данных

Когда вы закончите с этой конфигурацией, не забудьте сохранить файл.

Фото: https://t.me/risekg/6
# 


Нажмите на Сохранить и установить.
# 
Теперь начнется процесс установки
# 
Он установит все необходимые конфигурации. Если произойдет какая-то ошибка, следующий экран сообщит вам об этом. Сделайте с него скриншот. Отправьте мне на телеграмм @doznetkg
# 
Если все в порядке, вы можете нажать «Готово».
# 
Теперь у вас есть собственный экземпляр, но настройка еще не закончена. Теперь вам нужно продолжить настройку другой среды.
# 
Когда вы входите в систему как администратор, у вас будет возможность изменять и добавлять значения.
# 
