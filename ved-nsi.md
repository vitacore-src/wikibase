<!-- TITLE: Ведение НСИ -->
<!-- SUBTITLE: Руководство пользователя -->

# Введение
Документ содержит инструкции по ведении Нормативно-справочной информации. Принцип ведения любого справочника в системе универсален. Каждый справочник  выгружается на актуальный для него период времени, но пожеланию пользователя его выгрузка может осуществляться полноценно с указанием сроков аннулирования того или иного поля. Рассмотрим на примере ведения справочника экспертов качества медицинской помощи (федеральный код-F004)

Для этого зайдем в систему Медэксперт-Тфомс в раздес Справочники-Нормативные справочники-F004

![204](/uploads/04/--204.png "204")

Отобразится перечень ранее добавленных экспертов качества в системе.

# 	Добавление эксперта
Добавление нового эксперта качества осуществляется через контекстное меню, вызываемое нажатием правой клавиши мыши в окне реестра. В контекстном меню выбирается пункт «Новый». Также через контекстное меню совершается удаление эксперта из реестра-если было ошибочное внесение данных(рисунок 2).

![205](/uploads/04/--205.png "205")

При добавлении эксперта необходимо ввести его уникальный номер- может быть любой комбинацией цифр.Реестровый номер остается неизменным для данного Эксперта, в том числе при перерегистрации в журнале регистрации при подаче нового уведомления об осуществлении деятельности в сфере ОМС

![206](/uploads/04/--206.png "206")

Затем открывается окно создания нового эксперта. Вверху формы находится введенный ранее код эксперта, далее заполняются поля с его данными. Пункты «Код ОКАТО территории», «Фамилия», «Имя», «СНИЛС»  являются обязательными.

![207](/uploads/04/--207.png "207")

Для заполнения полей с данными документа удостоверяющего личность необходимо нажать на пункт «добавить документ».

Для заполнения полей с данными адреса необходимо нажать на пункт «добавить адрес». Данные адреса заполняются в соответствии с пропиской.

Для того чтобы добавить данные о банковских реквизитах эксперта нужно выбрать пункт «банковские реквизиты эксперта» и ввести данные в открывшемся окне. 

![208](/uploads/04/--208.png "208")

После заполнения данных в этом окне необходимо сохранить введенные параметры перед закрытием окна. Для этого используется кнопка «сохранить».

![209](/uploads/04/--209.png "209")

Также совершается сохранение данных о новом эксперте перед закрытием окна создания нового эксперта.

# 	Выгрузка справочника
Выгрузка любого справочника может осуществляться в разных форматах данных – формат xml(настраивается индивидуально под требования пользователя) и формат dbf(см. Инстуркция администратора по настройке экспорта данных).

# 	Массовая редакция элементов справочника НСИ (региональные справочники)

Для того чтобы внести изменения одновременно в нескольких элементах справочника необходимо :
1)Зайти в справочник НСИ(региональный)(рис.1) пр.кл.мыши по любому элементу справочника-Редактировать

![210](/uploads/04/--210.png "210")

   Откроется форма (рис.2). Произвести фильтрацию необходимых элементов за счет встроенного фильтра ( рис.3 ) и нажать кл. ОК внизу формы. Откроется пустая форма ввода элемента справочника. На открывшейся форме прописать необходимые значения полей (не обязательно все - возможно внести изменения лишь в одном или нескольких атрибутах (рис.5)). Введённые изменения будут применены для ВСЕХ отсортированных фильтром элементов справочника.

![211](/uploads/04/--211.png "211")

![212](/uploads/04/--212.png "212")

![213](/uploads/04/--213.png "213")

![214](/uploads/04/--214.png "214")

# Обновление федеральных классификаторов
С 01.06.2017 некоторые федеральные класификаторы стали доступны для самостоятельного обновления пользователям системы АИС Медэксперт ТФОМС.

Для того чтобы обновить федеральный классификатор, необходимо зайти под учетной записью системы АИС Медэксперт-ТФОМИС с ролью Администратор. В блоке Администрирование зайти двойным кликом лв. кл мыши в  подпапку Обновление федеральных классификаторов (рис.1)

![215](/uploads/04/--215.png "215")

Откроется рабочее поле модуля с набор допустимых для обновления федеральных классификаторов 

![216](/uploads/04/--216.png "216")

Далее, кликаем пр. кл мыши по выбранному классификатору – выбираем подменю  «Обновить справочник» 

![217](/uploads/04/--217.png "217")

Откроется окно для выбора xml файла необходимого классификатора 

![218](/uploads/04/--218.png "218")

Выбираем необходимый файл и нажимаем Открыть. Процесс загрузки будет завершен уведомлением Об успешной загрузке либо будет выведено сообщение с ошибкой!