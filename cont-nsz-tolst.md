<!-- TITLE: Подсистема «Контроль НСЗ» (толстый клиент) -->
<!-- SUBTITLE: Рабочая инструкция пользователя-->

# Введение
Чтобы войти в систему, необходимо подключиться к серверу, на котором находится клиент.

В открытом клиенте для настроек мероприятий и их движения потребуется работа со следующими разделами:
* 	Стадия процесса
* Шаблон процесса оформления (жизненного цикла) мероприятия
* 	Виды мероприятий шаблона
* 	Этап процесса оформления
* 	Веб алиасы сущностей
* 	Модели объектов передачи данных

# Настройка стадий процесса
Для того, чтобы создать стадии, через которые может проходить мероприятие, следует через пункт меню **<Сервис> → <Просмотр произвольного списка> раскрыть сущность <Стадия процесса>:**

![1](/uploads/nsz/-1.png "1")

![2](/uploads/nsz/-2.png "2")

![3](/uploads/nsz/-3.png "3")

В открывшемся списке через функцию **<Новый>** создаем новую запись. 

На форме следует заполнить поля:

|  | |
| ------------- | ------------- |
|Наименование	|Наименование стадии|
|Роль	|Роль пользователя, который может производить движение на эту стадию|
|Вид документа	|Привязка к сущности.<br>Выбирать необходимо сущность со схемой NSZ.<br>Этапы, не требующие дополнительного утверждения при переходе на следующий этап, должны быть привязаны к базовой сущности <STAGE_DOCUMENT>.|
|Критерии (условия) отбора мероприятий для включения в этап	|Ввод критериев отбора при необходимости|
|Наименование положительного действия	|Наименование действия при подтверждении перехода мероприятия(й) на этап|
|Наименование действия при отказе	|Наименование действия при отказе в переходе мероприятия(й) на этап|
|Роль утверждения стадии	|Заполняется только если документ текущего этапа требует утверждения перед переходом на следующий этап. Утверждение производит определенный пользователь системы.|
|Веб-сущность	|Заполняется автоматически|
|Описание типа документа	|Ввод названия документа, отражающего данный этап|
|Цвет	|Настройка цвета этапа|

# 	Настройка шаблона процесса оформления (жизненного цикла) мероприятия

После настройки стадий необходимо создать шаблоны движения для каждого типа мероприятий.

В открывшемся на сущности списке создаем новый шаблон:

![4](/uploads/nsz/-4.png "4")

В шаблоне необходимо заполнить поля:

|  | |
| ------------- | ------------- |
|**Наименование**	|Наименование шаблона|
|**Дата начала**	|Дата начала действия шаблона|
|**Дата окончания**	|Дата окончания действия шаблона|
|**Виды мероприятий**	|Выбор мероприятий, движение которых будет происходить по создаваемому шаблону (можно оставить пустым и заполнить позже)|
|**Этапы процесса оформления**	|Выбор этапов процесса оформления с последовательностью (можно оставить пустым и заполнить позже)|

Добавление вида мероприятия и этапов осуществляется через функцию **Insert**.

При добавлении вида мероприятия предлагается выбрать существующую запись из списка сущностей. 

Один шаблон может быть актуален для разных типов мероприятий.

При добавлении этапа предлагается выбрать существующую запись на сущности **Этап процесса оформления**, либо создать новый.

# Настройка этапов процесса оформления

Для настройки этапов и их порядка, следует создать новую запись на сущности **Этап процесса оформления**

При создании нового этапа необходимо заполнить:

![5](/uploads/nsz/-5.png "5")

|  | |
| ------------- | ------------- |
|Шаблон процесса оформления	|Выбор к какому шаблону будет относиться этап|
|Порядковый номер	|Номер этапа по порядку|
|Следующий этап	|Заполняется автоматически|
|Стадия процесса	|Выбор соответствующей этапу стадии|

# 	Настройка видов мероприятий шаблона

Для настройки видов мероприятий к шаблонам, необходимо создать новые записи на сущности **Вид мероприятий шаблона**:

![6](/uploads/nsz/-6.png "6")

|  | |
| ------------- | ------------- |
|**Шаблон процесса оформления**|	Выбор к какому шаблону будет относиться мероприятие|
|**Сущность метаданных**	 |Выбор сущности мероприятия<br>Выбирать необходимо сущность со схемой NSZ.|

# 	Настройка веб алиасов сущностей

Для того чтобы настроить передачу данных сущности на WebApi, необходимо настроить веб алиасы сущностей. Их настройка производится в разделе **Администрирование** → **Веб алиасы сущностей**.
Создаем новую запись через действие **Новый**:

|  | |
| ------------- | ------------- |
|**Псевдоним справочника**	|Ввод названия сущности, для которой настраивается алиас.Аналогично названию самой сущности (с маленькой буквы)|
|**Наследует псевдоним**	|Указываем это поле, если данный алиас будет наследовать атрибуты от другого алиаса (необходимо для дальнейшей настройки модели объекта передачи данных)|
|**Сущность справочника**	|Выбор сущности, для которой создается веб алиас.Выбирать необходимо сущность со схемой **NSZ**.|
|**Описание**	|Описание алиаса|

Обязательно нужно указать ![8](/uploads/nsz/-8.png "8")  .

Если нужно настроить фильтры, можно воспользоваться настройкой фильтров внизу формы. Например, для мероприятий, которые должны попадать в архив, веб алиас настроен с фильтром ![9](/uploads/nsz/-9.png "9")

# 	Настройка моделей объектов передачи данных

Настройки отображения объекта на web-платформе следует производить в разделе **Администрирование** → **Модели объектов передачи данных**. 

При создании новой модели необходимо заполнить следующую форму:

![10](/uploads/nsz/-10.png "10")

|  | |
| ------------- | ------------- |
|Наименование	||
|Описание	||
|Сущность метаданных	|Выбор сущности.Выбирать необходимо сущность со схемой **NSZ**.|
|Тип шаблона	|Детализированная модель|

После выбора сущности можно добавлять элементы модели (атрибуты, которые будут отображены на форме) по одному ![11](/uploads/nsz/-11.png "11") , либо сразу все ![12](/uploads/nsz/-12.png "12") . Если добавить сразу все атрибуты, то в модель подтянутся все атрибуты из выбранной сущности.

Заполненная модель объекта передачи данных представлена ниже на рисунке :

![13](/uploads/nsz/-13.png "13")

Внутри каждого атрибута необходимо настроить данные:

![14](/uploads/nsz/-14.png "14")

|  | |
| ------------- | ------------- |
|Наименование	|Вводим только при создании нового атрибута|
|Тип данных	||
|Формат	||
|Описание	|Название атрибута, которое будет отображено на web-платформе|
|Модель объекта передачи данных	|Выбираем только если атрибут наследует отображение от другой модели.<br>Например, у модели мероприятий **«MEASURE»** настроен атрибут **«mo»**, который на  web-платформе представлен раскрывающимся списком, состоящим из атрибутов, настроенных у модели **«MO»**.|
|Множественность	|Обозначает обязательность атрибута:<br>0..1– необязательный<br>1..1 – обязательный<br>0..* - необязательное множество<br>1..* - обязательное множество|

Также, следует проставлять возможность изменения (Set) атрибута ![15](/uploads/nsz/-15.png "15") .

С помощью стандартных фильтров программы можно настроить лексему значения атрибута. 

После настройки всех требуемых атрибутов, пользователь может произвести, при необходимости, настройку колонок через функцию ![16](/uploads/0000000/-16.png "16") :
 
![17](/uploads/0000000/-17.png "17")

С помощью данной функции можно выбрать какие атрибуты будут отображены на форме, по каким атрибутам будет работать фильтр и т.д.

После настройки и сохранения всех требуемых разделов, пользователь может проверить произведенные изменения на web-платформе.
