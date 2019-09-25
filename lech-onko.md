<!-- TITLE:ПОСТРОЕНИЕ ИСТОРИИ ЛЕЧЕНИЯ ПАЦИЕНТА ПО ОНКОЛОГИИ СИСТЕМЫ АИС «МЕДЭКСПЕРТ-ТФОМС»-->
<!-- SUBTITLE:РУКОВОДСТВО -->

# Введение
Данные документ описывает бизнес процесс построения истории лечения пациента по онкологии . Выборки данных при разработке данного модуля согласно приложению 1 к документу.

# 	Подключение модуля sp_UpdateOncologyMonitor

Для того, чтобы подключить модуль построения истории лечения пациента по онкологии, необходимо зайти в папку Администрирование- и выбрать раздел Клиентские модули (рис.1)
 
![317](/uploads/0000003/--317.png "317")

Далее пр.кл мыши по выбранному модулю – «Свойства» ( рис.2)
 
![318](/uploads/0000003/--318.png "318")

Установить права доступа ролям пользователям системы (рис.3)
 
![319](/uploads/0000003/--319.png "319")

В настройках роли проставить Признак доступности обновления мониторинга онкологии.

	Перезапустите программу АИС Медэксперт-ТФОМС.
После перезапуска клиентской части в папках системы отобразится модуль «Мониторинг онкологии» (рис.4)

![320](/uploads/0000003/--320.png "320")
# Запуск процедуры «Обновить мониторинг онкологии»

**Запуск процедуры «Обновить мониторинг онкологии» доступен только для администратора ТФОМС**

Для обновления данные в системе построения истории лечения пациента по онкологии, необходимо в меню инструментов «Сервис» - выбрать «Обновить монитор онкологии». Произойдет вычитка случаев лечения из реестров счетов в системе АИС Медэксперт-ТФОМС согласно условиям Приложения 1. (рис.5)
 
![321](/uploads/0000003/--321.png "321")

# Просмотр сведений истории лечения пациента по онкологии «мониторинг онкологии».
Для просмотра сведений по истории лечения пациента, необходимо зайти   в папку «Мониторинг онкологии» (рис.5)
 
![](/uploads/0000003/-.jpg "")

Отобразится список пациентов, соответствующих выборке согласно Приложению 1

Путем наложения «сохраненного фильтра» (рис.6) можно реализовать выборки по пациентам или осуществить поиск самого пациента по регистру.
 
![323](/uploads/0000003/--323.png "323")

Фильтры поиска могут задаваться любые по желанию пользователя