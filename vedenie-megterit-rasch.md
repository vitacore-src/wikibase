<!-- TITLE: Ведение межтериториальных расчетов -->
<!-- SUBTITLE: Руководство -->

# 	Введение и интерфейс

Межтерриториальные расчеты осуществляются за медицинскую помощь, оказанную гражданам в Российской Федерации вне территории страхования.

В документе будет описана работа с модулем межтерриториальных расчетов. Модуль предназначен для ведения накопительной базы счетов-реестров, проведения МЭК и составления актов. Руководство содержит приемы работы с программой, основные принципы и примеры её использования.

В левой части окна представлен список модулей, доступных пользователю.  Он отображается в древовидной структуре в виде подпапок. Правая часть представляет собой рабочее поле модуля и содержит специальные инструменты для работы. (Рис.1)

![1](/uploads/02/1.png "1")

# 	Работа ТФОМС по месту оказания медпомощи

## 	Входящие счета МТР от МО

Медицинская организация (далее МО), работающая в системе обязательного медицинского страхования и оказавшая медицинскую помощь лицу, застрахованному в страховой медицинской организации (СМО) стороннего субъекта РФ, формирует счет-реестр и направляет в территориальный фонд обязательного медицинского страхования (далее ТФОМС) по месту оказания медицинской помощи. 

### 	Загрузка нового счета-реестра в систему

Чтобы загрузить новый счёт-реестр следует щелкнуть правой кнопкой мыши в поле списка счетов и в выпадающем меню выбрать пункт «Новый», либо нажать на пиктограмму   в верхнем левом углу вкладки (Рис.2).

![2](/uploads/02/2.png "2")

Будет открыто окно проводника, где нужно будет выбрать файл счёта-реестра (Рис. 3).

![3](/uploads/02/3.png "3")

Загружаемый счёт-реестр проходит форматно-логический контроль (далее ФЛК) и процедуру МЭК (Рис. 4).

![4](/uploads/02/4.png "4")

После загрузки следует указать папку, куда будет сохранён отчет о процедуре ФЛК (Рис. 5).

![5](/uploads/02/5.png "5")

Другой вариант загрузки счет-реестра - через папку в автоматическом режиме, т.е. массово. Для того, чтобы узнать куда именно необходимо "кидать" счета-реестры на загрузку, нам необходимо зайти в настройки - настройки организации  в верхней строке панели инструментов в программе.(рис.6)

![6](/uploads/02/6.png "6")

В открывшемся окне нам необходимо зайти во вкладку "Загрузка" и по атрибуту "Процесс загрузки" найти необходимую нам очередь.(рис.7) и двойным кликом по очереди открыть окно.(рис.8)

![7](/uploads/02/7.png "7")

![8](/uploads/02/8.png "8")

Поле "Входящие" и указанная там папка отвечают за загрузку счетов, поля "Исходящие" и "Путь файлов ФЛК" соответствуют ошибка и результатам ФЛК.

**Счета, поступившие по МТР от МО и успешно прошедшие ФЛК, будут добавлены в список счетов-реестров во «Входящие счета МТР от МО» и автоматически раскассируются  в папку «Исходящие счета МТР».**


### 	Работа с загруженными счетами-реестрами

Следует начать работу с двойного нажатия левой кнопки мыши по подпапке «Входящие счета МТР от МО» в левой части экрана (Рис. 9).

![9](/uploads/02/9.png "9")

Список счетов-реестров содержит только счета-реестры, которые соответствуют указанному периоду, а так же удовлетворяют условиям фильтров.

Чтобы воспользоваться календарём нажмите кнопку ![22](/uploads/000001/--22.png "22")  (Рис. 10).

![10](/uploads/02/10.png "10")

Либо воспользуйтесь методом ввода с клавиатуры. Щелкнув  мышкой на нужной цифре даты, введите цифру с клавиатуры. (Рис. 11)

![11](/uploads/02/11.png "11")

Для того чтобы указываемый период обозначал дату, когда был закрыт счёт-реестр, установите отметку «дата окончания реестра».

Если нужно отобразить счета-реестры только от определенной медицинской организации, укажите её в поле справа (Рис. 12).

![12](/uploads/02/12.png "12")

Также есть возможность написания фильтра для отбора счетов-реестров. После указания необходимых условий для отбора нажмите кнопку **«Найти»**.(Рис.13)

![13](/uploads/02/13.png "13")

Будет отображен список счетов-реестров, которые были загружены в систему и удолетворяют условиям фильтров и соответствуют указанному периоду. Счета- реестры, имеющие статус «закрыт», отмечены серым цветом (Рис.14).

![14](/uploads/02/14.png "14")

Предусмотрена возможность сортировать список по нужному атрибуту: например по дате. Так же можно добавить новые атрибуты (см. Руководство администратора).

### 	Окно работы со счётом-реестром от МО

Подменю «Свойства»

Нажмите правой кнопкой мыши по требуемому счёту и выберите пункт «Свойства» из выпадающего меню (Рис. 15).

![15](/uploads/02/15.png "15")


Будет открыто окно работы со счетом-реестром от МО. Это же можно проделать двойным щелчком мыши на выбранном в списке счёт-реестре.

Окно отображает основную информацию об этом счет-реестре, а так же сведения о всех случаях оказания медицинской помощи и услуг, которые были оказаны пациенту (застрахованному лицу) в данной медицинской организации за отчётный период (Рис. 16).

Основная информация отображена в верхней части окна и разделена на вкладки (Рис. 16).

![16](/uploads/02/16.png "16")

1.	Во вкладке **«основное»** содержится информация об медицинской организации, от которой поступил счет, и его отчётный период (Рис. 17).

![17](/uploads/02/17.png "17")

2.	Вкладка **«Оплата»** содержит информацию о сумме выставленной МО к оплате, о сумме принимаемой к оплате фондом ОМС на данный момент. Отображена суммы, которые не подлежат оплате из-за выявленных нарушений на этапе МЭК, МЭЭ и ЭКМП (Рис. 18).

![18](/uploads/02/18.png "18")

3.	Вкладка **«Платежные поручения»** содержит информацию о заненсеных платежных поручениях.. (Рис.19)

![19](/uploads/02/19.png "19")

Для того, чтобы занести информацию о платежных поручения, необходимовы зайти в счет реестр, выбрать вкладку «Платежное поручение» и нажать на гиперссылку **Добавить.**  Откроется форма для заполнения ( рис.19.1)

![20](/uploads/02/20.png "20")

После заполнения всех полей, необходимо нажать клавишу ОК для сохранения.

Записи счета-реестра разделены «По людям», «По законченому случаю», «По случаям», «По услугам» (Рис. 20) 

![21](/uploads/02/21.png "21")

![22](/uploads/02/22.png "22")

С списке отображена информация о застрахованных лицах, которым была оказана услуга в МО. Красным цветом отмечены пациенты (ЗЛ), у которых были выявлены ошибки МЭК в счёте-реестре (Рис. 21).

**Форма сведений о пациенте**

Двойным щелчком мыши на записи в списке «По людям» можно открыть форму с данными о пациенте и его страховой принадлежности. (Рис. 22) Для удобства информация поделена на вкладки. 

1)	Вкладка **«Пациент»** содержит персональную информацию о пациенте (ЗЛ) (Рис. 22)

![23](/uploads/02/23.png "23")

2)	Во вкладке **«Представитель»** доступна информация о преставителе застрахованного лица (пациента). (Рис. 23)

![24](/uploads/02/24.png "24")

3)	Вкладка **«Страховая принадлежность»** позволяет получить информацию о страховой принадлежности застрахованного лица (пациента), и его действующем полисе ОМС (Рис. 24).

![25](/uploads/02/25.png "25")

Для того чтобы произвести запрос о страховой принадлежности в ЦС (центральный сегмент) нажмите кнопку «Запрос СПЗЛ».

4)	Вкладка **«Случаи оказания медицинской помощи»**  не только отображает информацию о случаях оказания услуг в МО, но и предоставляет доступ к форме информации о каждом индивидуальном случае для данного пациента. Щелкните дважды мышкой на строке случая для того, чтобы открыть форму сведений о случае (Рис. 25). 

![26](/uploads/02/26.png "26")

5)	Вкладка **«Истории стаховых принадлежностей»** содержит информацию о истории страхования пациента. Также через кнопку "запрос истории страховых принадлежностей" можно узнать историю страхования (Рис. 26).

![27](/uploads/02/27.png "27")

![28](/uploads/02/28.png "28")

Список содержит все случаи оказания медицинской помощи в  МО за отчётный период. Красным цветом выделены случаи, в которых выявлены нарушения по МЭК(Рис. 27). Случаи имеющие нарушения попадают в акт.

Дважды щелкните левой кнопкой мыши на требуемой строке в списке «По случаям» для того чтобы открыть форму информации о случае .

**Форма сведений о случае**

Для удобства информация разделена на вкладки.

1)	Вкладка «Общее» содерщит общие сведения о случае (Рис. 28).

![29](/uploads/02/29.png "29")

С помощью кнопки **«Сведения о пациенте»** можно получить доступ к форме сведений о пациенте.

2)	Вкладка **«Оплата»** содержит информацию о выставленной сумме по данному случаю и санкциях в случае нарушений. (Рис. 29)

![30](/uploads/02/30.png "30")

3)	Информация о диагнозе, процессе лечения и его результате содержится во вкладке **«Лечение»**. Здесь же отображается информация об осложнениях и сопутствующих диагнозах. (Рис. 30)

![31](/uploads/02/31.png "31")

4)	Вкладка **«Сведения об услугах»** отображает список услуг, оказанных МО в рамках данного случая  (Рис. 31).

![32](/uploads/02/32.png "32")

При нажатии двойным щелчком мыши на строке случая будет открыта форма сведений об услуге.

**По услуге**

Список содержит перечень сведений о всех услугах, которые были оказаны застрахованным лицам (пациентам) за отчётный период (Рис. 32).

![33](/uploads/02/33.png "33")

**Форма сведений об услуге**

Двойным щелчком мыши на строке сведений о требуемой услуге можно получить доступ к форме информации об услуге (Рис. 33).

![34](/uploads/02/34.png "34")

**Форма законченного случая**

Структура разделена на вкладки.

1) Вкладка **"Общее"**. В ней отоюражается основная инормация по законченному случаю, код МО, даты лечения, исход заболевания,результат обращения, условия и вид оказания МП(рис.34)

![35](/uploads/02/35.png "35")

2) Вкладка **"Оплата"**. В ней Вы сможете увидеть данные о санкциях, сумме выставленной к оплате за оказанную МП, а так же о способе оплате.(рис.35) 

![36](/uploads/02/36.png "36")

3) Вкладка**"Случаи лечения"**. Во вкладке случаи лечения отображаются все случаи оказания МП,которые входят в данный законченный случай. (рис.36).Через двойной клик мыши можно открыть форму "случая лечения",о которой будет написано в следующем разделе ниже.

![37](/uploads/02/37.png "37")

4) Вкладка **"Санкции"**. В данной вкладке будут отображаны санкции по законченному случаю(рис.37).

![38](/uploads/02/38.png "38")

### Подменю «Открыть акт»

При приёме счёт-реестра некторые записи о случаях могут иметь нарушения и несоответствия. На этапе прохождения МЭК эти записи помечаются как имеющие нарушения и попадают в Акт. На них накладаваются финансовые санкции МЭК.

Щелкните правой кнопкой мыши на счёт-реестре, имеющем санкции. Выберите пункт «Открыть акт» (Рис. 38) .

![39](/uploads/02/39.png "39")

Откроется окно содержащее иформацию о сумме не подлежащей оплате, а так же список случаев, имеющих нарушения, а так же случаи, попавшие в акт по иным причинам (Рис. 39).

![40](/uploads/02/40.png "40")

В случае, когда необходимо принять законченый случай к оплате в ручную, следует выбрать случай в окне «Акт» и щелкнуть правой кнопкой мыши. В контекстном меню выберите пункт **«Принять в ручную»**. Законченый случай который был принят к оплате будет выделен зеленым цветом, а его статус «добавлен в акт» примет значение «нет» (Рис. 40).

![41](/uploads/02/41.png "41")

![42](/uploads/02/42.png "42")

При необходимости, случаи можно вручную добавить в акт. В основном окне счета необходимо переключится на вкладку «По законченным случаям» и кликнуть правой кнопкой мыши на строке законченного случая (Рис. 41). В контекстном меню выбрать «Отказать в оплате». Случаи, которые добавлены в акт из принятых случаев, будут выделены красным светом.(Рис.42)

![43](/uploads/02/43.png "43")

Причин отказа по одному случаю может быть несколько. Для того чтобы вручную добавить причину отказа выберите пункт «Добавить причину отказа» из контекстного меню (Рис. 43).

![44](/uploads/02/44.png "44")

Причины отказа указывается согласно классификатору причин отказа в медицинской помощи (Рис.44).

![45](/uploads/02/45.png "45")

### 	Подменю «Закрыть счёт»

Поступивший счёт-реестр после загрузки в систему будет иметь статус **«Открыт»**. Для того чтобы закрыть счет необходимо кликнуть правой кнопкой мыши по выбранному счету и выбрать в контекстном меню пункт **«Закрыть счет»** (Рис. 45).

![46](/uploads/02/46.png "46")

Для того чтобы вновь сделать счёт-реестр открытым, необходимо щелкнуть правой кнопкой мыши по выбранному счету и в появившемся меню выбрать **«Открыть счет»** (Рис. 46). После этого счёт-реестр перейдет в статус «Открыт».

![47](/uploads/02/47.png "47")

Счет-реестр, который был загружен в систему и успешно раскассирован по территориям, открытию подлежать не должен.

### 	Выгрузка акта

Подменю «Сформировать акт»

Для того чтобы создать протокол обработки ( это может быть необходимо для уведомления МО), необходимо щелкнуть правой кнопкой мыши по выбранному счету и выбрать «Сформировать акт» в контекстном меню (Рис. 47). 

![48](/uploads/02/48.png "48")

Откроется окно проводника, с помощью которого будет необходимо указать папку выгрузки счёта-реестра в файл (Рис. 48). После того как будет выбрано место сохранения файла нажмите «Ok». Файл архив будет сохранен в выбранном пользователем месте (Рис. 49).

![49](/uploads/02/49.png "49")


## 	Исходящие счета МТР

Входящие счета-реестры содержат случаи оказания услуг и мед.помощи лицам, застрахованным в СМО на территории другого региона. Система позволяет раскассировать эти случаи по территориям страхования ЗЛ.

Исходящие счета-реестры формируются раздельно для различных ТФОМС –получателей, куда будут помещены соответствующие случаи. Таким образом, после проведения МЭК и оплаты для МО, в случае отсутствия нарушений, ТФОМС по месту оказания медицинской помощи выставляет счёт на оплату ТФОМС территории страхования. Счета, поступившие от МО, автоматически отображаются в папке **«Исходящие счета МТР».**

ТФОМС по месту оказания медицинской помощи направляет счет-реестр ТФОМС по месту страхования. Счёт-реестр может быть **основным** (R-файл), либо **исправительным** (D-файл). ТФОМС по месту оказания МП получает в ответ от ТФОМС по месту срахования **файлы протоколов обработки счетов** (A-файлы), называемые сторонними актами проверки.

### 	Работа с формированными счетами-реестрами в ТФОМС

Следует начать работу с двойного нажатия левой кнопки мыши по подпапке **«Исходящие счета МТР»** в левой части экрана (Рис. 50).

![50](/uploads/02/50.png "50")

Список счетов-реестров содержит счета-реестры, которые соответствуют указанному периоду, а так же удовлетворяют условиям фильтров.Укажите период, когда был загружен счёт-реестр (Рис. 50). 

Чтобы отобразить счета-реестры, направляемые только в определенный ТФОМС, укажите **ТФОМС получатель** с помощью поля справа.  (Рис. 51). Для удобства, в поле достаточно ввести часть названия фонда и выбрать его во всплывающем списке (Рис. 51) .

![51](/uploads/02/51.png "51")

После указания даты и нужных фильтров нажмите кнопку **«Найти»** (Рис.52).

![52](/uploads/02/52.png "52")

Будет отображен список счетов-реестров, которые были загружены в систему. Закрытые счета отмечены серым цветом. Светлым шрифтом выделяются счета-реестры имеющие вид счёта «Исправительный» (Рис. 52).

При нажатии правой кнопкой мыши на необходимом счёте откроется контекстное меню (Рис. 53), в котором можно будет выбрать необходимую операцию с нужным счётом-реестром.

![53](/uploads/02/53.png "53")

### 	Окно работы со счётом-реестром

**Подменю «Свойства»**

Чтобы открыть основное окно счёта-реестра  выберите нужный счёт-реестр в списке и дважды щелкните левой кнопкой мыши по строке, либо выберите пункт «Свойства» в контекстном меню (Рис. 54).

![54](/uploads/02/54.png "54")

Будет открыто окно, которое содержит основную информацию об этом счет-реестре, а так же информацию о случаях оказания медицинской помощи и услуг, которые были оказаны пациентам вне территории страхования. (Рис.55)

![55](/uploads/02/55.png "55")

Вкладка **«Информация»** содержит сведения о номере счёта-реестра и его версии взаимодействия  (на данный момент актуальна версия 3.1), а так же данные о датах выставления и загрузки счёта в систему (Рис. 56).

![56](/uploads/02/56.png "56")

Во вкладке **«Оплата»** доступны сведения о сумме выставленной МО фонду ОМС на территории оказания МП, сведения о сумме, которая была принята к оплате ТФОМС, а так же санкции вторичной МЭК (Рис. 57). Здесь же указан отчётный период.

![57](/uploads/02/57.png "57")

### 	Создание платёжного поручения

Во вкладке «Платёжные поручения» доступно добавление платёжного поручения для ТФОМС получателя счёта (Рис. 58).

![58](/uploads/02/58.png "58")

Все поля формы нового платёжного поручения обязательны для заполнения (Рис. 59).

![59](/uploads/02/59.png "59")

### Подменю «Отметить как (не)оплаченный для МО»

Существует возможность отметить счёт-реестр как оплаченный для МО. Выберите пункт «Отметить как (не)отмеченный для МО» в контекстном меню, доступном с помощью мыши (Рис. 60).
  
	![60](/uploads/02/60.png "60")
	
Аналогичным образом ставится отметка «Нет» (Рис. 61).

![61](/uploads/02/61.png "61")

### 	Закрыть счёт-реестр

Поступивший счёт-реестр после загрузки в систему будет иметь статус «Открыт». Для того чтобы закрыть счет необходимо кликнуть правой кнопкой мыши по выбранному счету и выбрать в контекстном меню пункт «Закрыть счет» (Рис. 62).
 
 ![62](/uploads/02/62.png "62")
 
После этого счёт-реестр получает статус «закрыт», он становится доступным для выгрузки.

Для того чтобы вновь сделать счёт открытым, необходимо щелкнуть правой кнопкой мыши по выбранному счету и в появившемся меню выбрать «Открыть счет» (Рис. 63). После этого счет перейдет в статус «Открыт».

![63](/uploads/02/63.png "63")

### 	Формирование исходящего файла счёт-реестра

**Подменю «Сформировать счёт»**

ТФОМС по месту оказания медицинской помощи направляет счет-реестр ТФОМС по месту страхования. Пункт «Сформировать счёт» позволяет сформировать основной счёт-реестр (R-файл) для отправки в ТФОМС по месту страхования ЗЛ. 

Выберите пункт «Сформировать счёт» в контестном меню, вызываемом нажатием правой клавиши мыши на требуемой строке списка исходящих счетов-реестров (Рис. 64).

![64](/uploads/02/64.png "64")

Будет открыто окно проводника, с помощью которого следует указать путь месту, где будет сохранён счёт-реестр для ТФОМС (R-файл) (Рис.65).

![65](/uploads/02/65.png "65")

При необходимости создайте новую папку, для завершения нажмите «Ok».

### 	Работа со сторонним актом

Если ТФОМС территории страхования (ТФОМС – получатель) после получения счёта-реестра выявляет дополнительные ошибки и нарушения, то в ответ на полученные счета-реестры ТФОМС по месту срахования формирует **файлы протоколов обработки счетов (A-файл).** 

Для того, чтобы загрузить сторонний акт проверки, необходимо выбрать на верхней строке меню программы **"Загрузить акт МТР"** (рис.66).

![66](/uploads/02/66.png "66")

Как только по счету поступит протокол обработки счёта-реестра (акт) от ТФОМС – получателя, его станет возможно просмотреть. Для этого следует выбрать счёт-реестр, на который поступил акт, в списке «Исходящие счета МТР». Потом необходимо выбрать пункт «Открыть Акт» из контекстного меню счёта-реестра (Рис. 67).

![67](/uploads/02/67.png "67")

Для того, чтобы узнать есть ли сторонний акт проверки у исходящего счета, необходимо вытащить атрибут "Информация о закрытии  ->  Счет-реестр -> Сторонний акт проверки" (рис.67.1)

![67 1](/uploads/02/67-1.png "67 1")

Будет открыто окно **«Сторонний акт проверки»**, содержащее информацию файла протокола обработки, поступившего от ТФОМС (Рис.68).

![68](/uploads/02/68.png "68")

Окно содержит сведения об общей сумме санкций МЭК (а так же МЭЭ и ЭКМП), проведённой ТФОМС территории страхования ЗЛ и сумме принятой к оплате. В списке указано общее количество позиций счёта-реестра, имеющих ошибки и непринятых к оплате.

На основе поступившего файла протокола становится доступно формирование **исправительного счёта-реестра**. Для этого нажмите кнопку **«Создать счет в работе»** в окне **«Сторонний акт проверки»**. Новый исправительный счёт-реестр будет добавлен в папку **«Счета в работе»** модуля межтерриториальных расчётов (Рис.69).

![69](/uploads/02/69.png "69")

## 	Формирование исправительного счета-реестра

В  подпапке «Счета в работе» находятся счета-реестры, которые нужно отредактировать для создания **исправительного счета-реестра**. 
Исправительный счет-реестр строится на основе акта (протокола обработки счёта-реестра), полученного от ТФОМС территории страхования, в ответ на исходящий счёт, и содержит только записи, которые не были приняты к оплате ТФОМС получателем.

### 	Редактирование счёта-реестра в работе
Главной особенностью формы «Счета в работе» является возможность редактировать информационные поля. 
 Следует начать работу с двойного нажатия левой кнопкой мыши на подпапке «Счета в работе». Укажите требуемый период и ТФОМС получатель аналогично процедуре заполнения полей в  исходящих счетах МТР. После того как требуемый счёт-реестр будет отображен в списке, откройте окно работы со счётом. Воспользуйтесь для этого контекстным меню, где выберите пункт «Свойства», либо двойным щелчком мыши на счёте-реестре в списке (Рис.70).

![70](/uploads/02/70.png "70")

Как и в исходящих счетах МТР окно счёта в работе содержит общие сведения о счёте-реестре во вкладках «Информация», «Оплата» и «Платёжные поручения» (Рис.71).

![71](/uploads/02/71.png "71")

Записи аналогично разделены на группы "По людям","По законченным случаям","По случаям" и "По услугам".

### 	Правка сведений о пациенте

Двойным щелчком мыши на строке списка «По людям» откройте форму редактирования сведений о пациенте (Рис.72).

![72](/uploads/02/72.png "72")

Во вкладке «Представитель» доступны поля данных о представителе ЗЛ (Рис.73).

![73](/uploads/02/73.png "73")

Из вкладки **«Случаи оказания медпомощи»** доступен доступ к списку случаев данного пациента, и к форме редактирования сведений о случае, аналогичной этой. Форму редактирования сведений о случае можно открыть двойным щелчком мыши по строке случая в списке (Рис.74).

![74](/uploads/02/74.png "74")

### Запрос страховой принадлежности ЗЛ в ЦС

Устранить несоответствия, связанные со страховой принадлежностью застрахованного лица можно с помощью кнопки «Запрос СПЗЛ» (Рис.75).

![75](/uploads/02/75.png "75")

### 	Исправление сведений о случаях

Двойным щелчком мыши на строке списка «По случаям» откройте форму редактирования сведений о случае (Рис. 76).

![76](/uploads/02/76.png "76")

Для удобства информация разделена на вкладки. Для того чтобы внести изменения в информацию о лечении и пациенте необходимо открыть список на выбор согласно рис.76 -  и двойным нажатием лв.кл.мыши откроется форма для редактировани. См.ниже (рис.77)

![77](/uploads/02/77.png "77")

**«По Людям- вкладка Случаи оказания мед.помощи»**

![78 1](/uploads/02/78-1.png "78 1")

**«По Людям- вкладка Страховая принадлежность»** 

![78 2](/uploads/02/78-2.png "78 2")

![78 3](/uploads/02/78-3.png "78 3")

![79](/uploads/02/79.png "79")

**По Услугам**
![80](/uploads/02/80.png "80")

После того, как все изменений будут внесены, необходимо сформировать исправительный счет - реестр. Для этого необходимо по счету в работу кликнуть пр.кл мыши – сформировать исправительный счет.( рис.81)

![81](/uploads/02/81.png "81")

Законченные случаи лечения, подвергшиеся изменению, будут сформированы в исправительный счет - реестр в папке «Исходящие счета -реестры».


