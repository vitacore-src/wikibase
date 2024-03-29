<!-- TITLE: ИНСТАЛЦИЯ СЕРВЕРНОЙ И КЛИЕНСТКОЙ ЧАСТИ СИСТЕМЫ АИС «МЕДЭКСПЕРТ-ТФОМС» -->
<!-- SUBTITLE: Руководство администратора -->

# Установка программы АИС «МедЭкспер-ТФОМС»

## Установка сервера приложения программы АИС «МедЭкспер-ТФОМС»

Для установки программы необходимо запустить файл ServerInstaller.msi  из папки ServerInstaller.

![1](/uploads/05/1.png "1")

Выбираем папку для установки программы и нажимаем Далее

![2](/uploads/05/2.png "2")

![3](/uploads/05/3.jpg "3")

В окне Service logon settings выбираем LocalSystem 

![4](/uploads/05/4.png "4")

В окне IES Server Parameters указываем настройки сервера:

Primary server name -  имя сервера

Database name – имя базы данных

Authentication- выбираем Windows или  SQL Server аудентификацию, если выбрана SQL Server аудентификация, вводим логин и пароль

![5](/uploads/05/5.jpg "5")

![6](/uploads/05/6.png "6")

## Установка клиентской  части программы АИС «МедЭкспер-ТФОМС»

Для установки программы необходимо запустить файл ClientInstaller_V394, появится окно «Приветствия»- нажмите ДАЛЕЕ 

![7](/uploads/05/7.png "7")

Поставить галочку в поле «Я принимаю условия лицензионного соглашения» - нажмите ДАЛЕЕ

![8](/uploads/05/8.png "8")

По умолчанию программа **АИС «МедЭкспер-ТФОМС»** проинсталируется по пути 

![9](/uploads/05/9.png "9")

Если необходимо изменить путь, тогда  нажав на кнопку «Изменить…» выберите необходимую директорию- нажмите ОК

![10](/uploads/05/10.png "10")

В появившемся окне укажите 

Адрес сервера приложение: IP адрес сервера приложений

Адрес сервера обновлений: IP адрес сервера базы данных 

Код региона (рис.5) Нажмите ДАЛЕЕ

![11](/uploads/05/11.png "11")

В появившемся окне Нажмите- УСТАНОВИТЬ

![12](/uploads/05/12.png "12")

Дождаться установки программы **АИС «МедЭкспер-ТФОМС» **

![13](/uploads/05/13.png "13")

В появившемся окне Нажать кнопку ГОТОВО 

![14](/uploads/05/14.png "14")

## Установка сервера обновлений АИС «МедЭкспер-ТФОМС»

Для установки программы необходимо запустить файл UpdateServerInstaller.msi  на сервере приложений  АИС «МедЭкспер-ТФОМС»

![15](/uploads/05/15.jpg "15")

Поставить галочку в поле «Я принимаю условия лицензионного соглашения» - нажмите ДАЛЕЕ

![16](/uploads/05/16.png "16")

По умолчанию сервера обновлений АИС «МедЭкспер-ТФОМС» проинсталируется по пути Нажмите ДАЛЕЕ

![17](/uploads/05/17.png "17")

**ЗАПОЛНИТЬ!!**

каталог: рекомендуется записать путь: C:\IESUpdate\
                         порт:32768
 Аутентификация: tcp
(Рис.4) нажмите ДАЛЕЕ

![18](/uploads/05/18.png "18")

Выберите по умолчанию учетную запись  нажмите ДАЛЕЕ

![19](/uploads/05/19.png "19")

В появившемся окне нажмите УСТАНОВИТЬ 

![20](/uploads/05/20.png "20")

Дождитесь установки программы. В Появившемся окне нажмите «ГОТОВО»

![21](/uploads/05/21.png "21")

После установки программы необходимо в конфигурации сервера запустить службу IES Update Server 

![22](/uploads/05/22.png "22")

