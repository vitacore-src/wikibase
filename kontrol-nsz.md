<!-- TITLE: Порядок настройки данных для работы в подсистеме «Контроль НСЗ» -->
<!-- SUBTITLE: Рабочая инструкция пользователя -->

# Введение

Данная инструкция описывает порядок работы в подсистеме «Контроль НСЗ» программного продукта «ОМС Финанс».
Подсистема предназначена для контроля процесса исполнения плана мероприятий по использованию средств НСЗ, предоставляемых ТФОМС МО медицинской организации.

Инструкция рассчитана на пользователей, имеющих навыки работы в ОС Windows и ознакомленных с базовым руководством пользователя по приложениям компании ЗАО «Витакор».

Следует иметь в виду, что скриншоты экранных форм приложения, приведенные в данной инструкции, могут в точности не совпадать с их фактическим внешним видом. Это связано с тем, что экранные формы в ряде случаев строятся на основании настроек приложения, которые могут быть различны в разных регионах и в разный период времени.

# Вход в систему

Для того, чтобы осуществить вход в подсистему «Контроль НСЗ», необходимо в строке браузера ввести: ```nsz.omsfinans.ru.```
По этой ссылке откроется страница, на которой нужно будет ввести логин и пароль пользователя как это показано на рисунке :

![1](/uploads/006/1.png "1")

Далее пользователь окажется на главной странице приложения, которая разделена на модули, как показано на рисунке :

![2](/uploads/006/2.png "2")

Чтобы перейти к работе с мероприятиями, пользователю необходимо перейти в модуль «НСЗ».
Далее будет раскрыт список мероприятий, который можно просмотреть по столбцам:
* 	Этапы
* 	Код МО
* 	Наименование МО
*  Тип мероприятия 
* 	Дата создания мероприятия
* 	Стоимость
* 	Количество единиц
* 	Наименование
* 	Цель мероприятия

![3](/uploads/006/3.png "3")

Отображение столбцов можно настроить через функцию на панели в верхнем левом углу <Выбор столбцов>. Затем, по желанию, настраивается порядок столбцов. Делается это перетаскиванием столбца в нужное место, удерживая левую кнопку мыши.

При необходимости сортировки информации по конкретному столбцу, пользователю следует щелкнуть по выбранному столбцу левой кнопкой мыши – тогда произойдет сортировка и появится значок около названия столбца <↓ / ↑>.

К информации в списке мероприятий можно применить фильтр. В системе фильтры настроены и у каждого столбца, в котором пользователь может искать нужные данные разными способами:

   ![4](/uploads/006/4.png "4")

# Создание мероприятий

Для создания нового мероприятия используется функция действия <Новый>, при нажатии на которое требуется выбрать тип создаваемого мероприятия как показано на рисунке ниже:

   ![5](/uploads/006/5.png "5")


**При выборе мероприятия типа «Обучение»**, открывается форма для заполнения, которая содержит строки для заполнения:
1.	ФИО мед. работника
2.	Дата рождения
3.	Специальность (выбор из справочника)
4.	Должность (выбор из справочника)
5.	Программа обучения 
6.	Длительность программы обучения
7.	Тип длительности программы обучения
8.	Стоимость в рублях

![6](/uploads/006/6.png "6")

**При выборе мероприятия типа «Закупка оборудования»**, открывается форма для заполнения, которая содержит строки для заполнения:
1.	Наименование оборудования (в произвольной форме)
2.	Количество
3.	Характеристика оборудования (текстовое поле)
    3.1.	Производитель
    3.2.	Марка
    3.3.	Модель
4.	Информация из справочника порядков:
    4.1.	Наименование порядка
    4.2.	№ и дата приказа, утверждающего порядок
    4.3.	№ приложения стандарта оснащения порядка
    4.4.	№ пункта стандарта оснащения (не обязательное к заполнению)
    4.5.	Наименование оборудования из порядка
5.	Отметка о готовности помещения
6.	Специальность мед. работника
7.	Должность мед. работника
8.	Стоимость в рублях

![7](/uploads/006/7.png "7")

**При выборе мероприятия типа «Ремонт оборудования»**, открывается форма для заполнения, которая содержит строки для заполнения:
1.	Наименование оборудования (в произвольной форме)
      1.1.	Производитель
      1.2.	Марка
      1.3.	Модель
2.	Год производства
3.	Дата постановки на баланс
4.	Дата акта ввода в эксплуатацию
5.	Дата выхода из эксплуатации
6.	Срок гарантийного обслуживания
7.	Информация из справочника порядков:
     7.1.	Наименование порядка
     7.2.	№ и дата приказа, утверждающего порядок
     7.3.	№ приложения стандарта оснащения порядка
     7.4.	№ пункта стандарта оснащения (не обязательное к заполнению)
     7.5.	Наименование оборудования из порядка
8.	Стоимость в рублях

![8](/uploads/006/8.png "8")

После ввода всех требуемых данных, можно сохранить мероприятие через панель действий: ![1234567](/uploads/000001/1234567.jpg "1234567") .
# Этапы прохождения мероприятий

После создания списка мероприятий, пользователь может производить и отслеживать движение своих мероприятий по ключевым точкам, которые в системе называются «Этапы». Просматривать это движение можно в разделе <Мероприятия> и <Этапы>.
В разделе <Этапы> представлен список документов со стадиями, на которых они находятся. При открытии любого этапа пользователь попадает на форму, в которой можно просмотреть реквизиты документа, связанного с данным этапом, и утвердить прохождение этого этапа (при необходимости утверждения) одним или группой мероприятий, которые относятся к утверждаемому этапу.

![9](/uploads/006/9.png "9")

В разделе <Мероприятия>, при открытии любого мероприятия можно увидеть в правом верхнем углу формы на какой стадии оно находится сейчас. Это изображено на рисунке:

![10](/uploads/006/10.png "10")

Также, этапы можно увидеть в общем списке мероприятий. Расшифровку цифрового обозначения можно открыть через функцию 
<Этапы мероприятий>: .![11](/uploads/006/11.png "11")  Ниже на рисунке представлено отображение этапов на списке:

![12](/uploads/006/12.png "12")

Однако, следует обратить внимание, что производить совместное движение на определенный этап могут только те мероприятия, которые находятся в данный момент на одном и том же этапе.
# Включение в план мероприятий

Для того чтобы включить одно или несколько мероприятий в план мероприятий, пользователю необходимо выделить в списке мероприятия, которые необходимо включить в план мероприятий, и выбрать появившееся действие <Включить в план>:

![13](/uploads/006/13.png "13")

При этом потребуется создать новый документ, либо выбрать из существующих:

![14](/uploads/006/14.png "14")

После этого пользователю необходимо подтвердить действие:

![15](/uploads/006/15.png "15")

# Список документов

Для просмотра и создания документов в подсистеме реализован раздел <Документы>.

В этом разделе можно создавать и просматривать документы, в которые затем будут включаться мероприятия.

Список документов представлен по столбцам:
* 	Тип документа
* 	Номер (не обязательно для всех типов документов)
* 	Дата создания
*  Дата утверждения
* 	Период – квартал/ год (не обязательно для всех типов документов)
* 	
Форма документа будет иметь соответствующие к заполнению поля и список мероприятий, включенных в данный документ.
