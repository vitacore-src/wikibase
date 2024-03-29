<!-- TITLE: Ведение межтериториальных расчетов (входящих от ТФОМС)-->
<!-- SUBTITLE: Руководство -->

# 	Работа ТФОМС территории страхования
## 	Входящие счета МТР от ТФОМС
Случаи оказания медпомощи и услуг лицам, застрахованным в СМО вне территории оказания услуг после раскассировки по территориям попадают в счёт-реестр для оплаты ТФОМС, на территории которого зарегистрирована СМО ЗЛ. Таким образом, ТФОМС по месту страхования получает счет-реестр от ТФОМС по месту оказания медицинской помощи. Счёт-реестр может быть **основным** (R-файл), и может иметь соответствующие **исправительные счета**(D-файл). В ответ на полученные счета ТФОМС по месту срахования формирует **файлы протоколов обработки счетов** (A-файл).

Начните работу с двойного нажатия левой кнопкой мыши на подпапке «Входящие счета МТР от ТФОМС». Будет открыто окно со счетами, загруженными за указанный период (текущий месяц по умолчанию) 

![1](/uploads/03/1.png "1")

### 	Загрузка нового счета-реестра в систему

Нажмите на кнопку «Загрузка счета МТР» на верхней панели основного окна системы .

![2](/uploads/03/2.png "2")

Будет открыто окно проводника для загрузки файла счета в систему 

![3](/uploads/03/3.png "3")

После успешной загрузки в систему и прохождения ФЛК будет открыто окно подтверждения 

![4](/uploads/03/4.png "4")

Следует указать папку, куда будет сохранён файл журнала **ФЛК (Y-файл)**

![5](/uploads/03/5.png "5")

Другой вариант загрузки счет-реестра через папку в автоматическом режиме, т.е. массово. Для того, чтобы узнать куда именно необходимо "кидать" счета-реестры на загрузку, нам необходимо зайти в настройки - настройки организации  в верхней строке панели инструментов в программе.

![6](/uploads/03/6.png "6")

В открывшемся окне нам необходимо зайти во вкладку "Загрузка" и по атрибуту "Процесс загрузки" найти необходимую нам очередь. и двойным кликом по очереди открыть окно.

![7](/uploads/03/7.png "7")

![8](/uploads/03/8.png "8")

Поле "Входящие" и указанная там папка отвечают за загрузку счетов, поля "Исходящие" и "Путь файлов ФЛК" соответствуют ошибка и результатам ФЛК.

### 	Работа с загруженными счетами-реестрами

Следует начать работу с двойного нажатия левой кнопки мыши по подпапке «Входящие счета МТР от ТФОМС» в левой части экрана .

![9](/uploads/03/9.png "9")

Список счетов-реестров содержит счета-реестры, которые соответствуют указанному периоду, а также удовлетворяют условиям фильтров.
Укажите период, когда был загружен счёт-реестр.

Если нужно отобразить счета-реестры только от определенного ТФОМС. Укажите ТФОМС источник с помощью поля справа  . Для удобства, в поле достаточно ввести часть названия фонда и выбрать его во всплывающем списке.

![10](/uploads/03/10.png "10")

После указания даты и нужных фильтров нажмите кнопку «Найти» 

![11](/uploads/03/11.png "11")

Будет отображен список счетов-реестров, которые были загружены в систему. Закрытые счета отмечены серым цветом. Светлым шрифтом выделяются счета-реестры имеющие вид счёта «Исправительный» .
При нажатии на необходимый счет правой кнопкой мыши откроется окно меню где можно будет выбрать необходимую операцию с выбранным счётом.

![12](/uploads/03/12.png "12")

### 	Окно работы со счётом-реестром от ТФОМС

Чтобы открыть основное окно счёта-реестра  выберите нужный счёт-реестр в списке и дважды щелкните левой кнопкой мыши по строке, либо выберите пункт «Свойства» в контекстном меню.

![13](/uploads/03/13.png "13")

Будет открыто окно, которое содержит основную информацию об этом счете-реестре, а так же информацию о случаях оказания медицинской помощи и услуг, которые были оказаны пациентам вне территории страхования. 

![14](/uploads/03/14.png "14")

Вкладка «Информация» содержит сведения о номере счёта-реестра и его версии взаимодействия  (на данный момент актуальна версия 3.1), а так же данные о датах выставления и загрузки счёта в систему 

![15](/uploads/03/15.png "15")

Во вкладке «Оплата» доступны сведения о сумме выставленной МО фонду ОМС на территории оказания МП, сведения о сумме, которая была принята к оплате ТФОМС, а так же санкции вторичной МЭК. Здесь же указан отчётный период.

![16](/uploads/03/16.png "16")

Во вкладке «Платёжные поручения» доступны платёжные поручения от ТФОМС территории оказания МП. Здесь заносятся сведения о платёжных поручениях 

![17](/uploads/03/17.png "17")

Записи счета-реестра от МО разделены «По людям», «По законченным случаям»,  «По случаям», «По услугам» 

![18](/uploads/03/18.png "18")

С списке отображена информация о застрахованных лицах, которым была оказана медицинская помощь вне региона страхования, на территории ТФОМС источника. 

**Форма сведений о пациенте**

Двойным щелчком мыши на записи в списке откройте форму с данными о пациенте и его страховой принадлежности. (Рис.19) Для удобства информация поделена на вкладки. 

1)	Вкладка **«Пациент»** содержит персональную информацию о пациенте (ЗЛ) 

![19](/uploads/03/19.png "19")

2)	Во вкладке **«Представитель»** доступна информация о преставителе застрахованного лица (пациента). 

![20](/uploads/03/20.png "20")

3)	Вкладка **«Случаи оказания медпомощи»** содержит список случаев оказания МП выбранному застрахованному лицу на территории ТФОМС-источника в рамках счёта-реестра за отчётный период 

![21](/uploads/03/21.png "21")

Двойным щелчком мыши на строке случая можно открыть форму сведений о случае.

4)	Вкладка **«Страховая принадлежность»** позволяет получить информацию о страховой принадлежности застрахованного лица (пациента), и его действующем полисе ОМС 

![22](/uploads/03/22.png "22")


![23](/uploads/03/23.png "23")

Список содержит все записи законченных случаев в данном счет-реестре.(рис.22.1).Дважды щелкните мышкой на необхотимой строке в списке «По законченным случаям» для того чтобы открыть форму законченного случая .

**Форма законченного случая**

Структура разделена на вкладки.

1) Вкладка **"Общее"**. В ней отоюражается основная инормация по законченному случаю, код МО, даты лечения, исход заболевания,результат обращения, условия и вид оказания МП

![24](/uploads/03/24.png "24")

2) Вкладка **"Оплата"**. В ней Вы сможете увидеть данные о санкциях, сумме выставленной к оплате за оказанную МП, а так же о способе оплате.

![25](/uploads/03/25.png "25")

3) Вкладка **"Случаи лечения"**. Во вкладке случаи лечения отображаются все случаи оказания МП,которые входят в данный законченный случай.Через двойной клик мыши можно открыть форму "случая лечения",о которой будет написано в следующем разделе ниже.

![26](/uploads/03/26.png "26")

4) Вкладка **"Санкции"**. В данной вкладке будут отображаны санкции по законченному случаю

![27](/uploads/03/27.png "27")

По случаю

![28](/uploads/03/28.png "28")

Список содержит записи о случаях оказания МП по МТР .

Дважды щелкните мышкой на необхотимой строке в списке «По случаям» для того чтобы открыть форму сведений о случае.

**Форма сведений о случае**

Для удобства информация разделена на вкладки.

1)	Вкладка **«Общее»** содерщит общие сведения о случае 

![29](/uploads/03/29.png "29")

2)	Вкладка **«Оплата»** содержит информацию о выставленной сумме по данному случаю и санкциях в следствие выявленных нарушений. 

![30](/uploads/03/30.png "30")

3)	Информация о диагнозе, сроках лечения и его результате содержится во вкладке **«Лечение»**. Здесь же отображается информация об осложнениях и сопутствующих диагнозах. 

![31](/uploads/03/31.png "31")

4)	Вкладка **«Сведения об услугах»** отобразит список услуг, оказанных МО в рамках данного случая (Рис.27).
 
 ![32](/uploads/03/32.png "32")

5) Вкладка **«Законченный случай»** отображает информацию по срокам лечения законченного случая, МО направившей на лечение,сумме выставленной к оплате и санкциям 

![33](/uploads/03/33.png "33")

6) Вкладка **"КСГ-КПГ"** отображает сведения о номере КСГ или КПГ и соответствующих коэффициентах, если оплата данного случая была именно по КСГ, в противном случае, данная вкладка остается пустой.
 
![34](/uploads/03/34.png "34")

7) Во вкладках **"Онкология"**, **"Проведение консилиума"**, **"Направление по онкологии"** будут отображаться данные по онкологическим случаям, повод обращения, стадия заболевания, сведения об оказанной онкологической услуги,диагностический блок и т.д.

![35](/uploads/03/35.png "35")

**По услугам**
Вкладка в счет - реестре  "По услугам" отображает перечень всех услуг,которые были оказаны пациентам на другой территории.
 
 ![36](/uploads/03/36.png "36")
 
### 	Подменю «Открыть акт»

При приёме счёта-реестра некторые записи могут иметь ошибки и нарушения. Эти записи помечаются как имеющие нарушения и попадают в Акт.
Щелкните правой кнопкой мыши на счёте-реестре имеющем финансовые санкции и выберите пункт «Открыть акт» .

![37](/uploads/03/37.png "37")

Откроется окно содержащее иформацию о сумме не подлежащей оплате, а так же список случаев, имеющих нарушения .

![38](/uploads/03/38.png "38")

**Принять вручную**

В случае, когда необходимо принять случай к оплате в ручную, следует выбрать случай в окне «Акт» и щелкнуть правой кнопкой мыши. В контектном меню выберите пункт **«Принять в ручную»** . Случай который был принят к оплате будет выделен зеленым цветом.

![39](/uploads/03/39.png "39")

**Отказать в оплате**

При необходимости, случаи можно вручную добавить в акт. В основном окне счета необходимо переключится на вкладку «По случаям» и щелкнуть правой кнопкой мыши на строке случая . В контекстном меню выбрать «Отказать в оплате». Случаи, которые добавлены в акт, будут выделены красным светом.

![40](/uploads/03/40.png "40")

**Добавить причину отказа**

Причин отказа по одному случаю может быть несколько. Для того чтобы вручную добавить причину отказа выберите пункт «Добавить причину отказа» из контекстного меню.
 
 ![41](/uploads/03/41.png "41")
 
Причины отказа указывается согласно классификатору причин отказа в медицинской помощи .

![42](/uploads/03/42.png "42")

**Изменить причину отказа**

Для того чтобы вручную изменить причину отказа выберите пункт «Изменить причину отказа» из контекстного меню .

 ![43](/uploads/03/43.png "43")
 
Обратите внимание, выбор пункта удалит все причины отказа этого случая, выявленные на предыдущих этапах экспертиз .

![44](/uploads/03/44.png "44")

### 	Проведение повторной экспертизы

Чтобы провести дополнительную экспертизу (реМЭК) по счету принятому от ТФОМС, выполните последовательность действий описанных далее.

![45](/uploads/03/45.png "45")

Выберите счёт-реестр в списке главного окна «Входящие счета МТР от ТФОМС».  Нажмите пиктограмму  ![12355](/uploads/03/12355.png "12355") на главной панели системы «МэдЭксперт ТФОМС». Либо, воспользуйтесь контекстным меню вызываемым нажатием правой кнопкой мыши на строке счёта-реестра, и выберите пункт «Провести экспертизу». Будет открыто окно, в котором, пользуясь встроенным фильтром (Рис. 41), можно будет провести дополнительную экспертизу по принятому счету от ТФОМС. 

![46](/uploads/03/46.png "46")

При необходимости созданный ранее фильтр можно сохранить для проведения экспертизы входящих счетов МТР от ТФОМС .

### 	Подменю «Закрыть счет»

Счёт-реестр, поступивший от ТФОМС, после загрузки в систему будет иметь статус «Открыт». Для того чтобы появилась возможность сформировать акт (файл протокола обработки счёта-реестра) счёт-реестр должен получить статус «Закрыт». Необходимо щелкнуть правой кнопкой мыши по выбранному счету и выбрать в контекстном меню пункт «Закрыть счет» .

Для удобства пользователя закрытые счета-реестры становятся выделенными серым цветом.

![47](/uploads/03/47.png "47")

Для того чтобы вновь сделать счёт открытым, необходимо щелкнуть правой кнопкой мыши по выбранному счету и в появившемся меню выбрать «Открыть счет» . После этого счет перейдет в статус «Открыт».

![48](/uploads/03/48.png "48")

### 	Формирование протокола обработки

ТФОМС территории страхования ЗЛ при выявлении дополнительных ошибок и нарушений после проведения повторной МЭК (МЭЭ и ЭКМП) направляет в ФОМС места оказания МП акт (А-файл протокола обработки). 
Для того чтобы выгрузить акт, необходимо щелкнуть правой кнопкой мыши по выбранному счету и на выбрать «Сформировать акт» в контекстном меню. 

![49](/uploads/03/49.png "49")

Откроется окно проводника для выбора места выгрузки файла на компьютер. 

![50](/uploads/03/50.png "50")

После того как будет выбрано место сохранения файла нажмите «Ok». Файл архив будет сохранен в выбранном пользователем месте.

# 	Ведение федеральных платежных поручений
## Выгрузка платежных поручений на территорию.

            Для того чтобы выгрузить платежное поручение по счетам от территорий необходимо занести сведения об оплате в систему. Для этого необходимо зайти во входящие счет от ТФОМС, двойным кликом левой клавишей мыши выбрать счет реестр, зайти на вкладку «Платежные поручения»
						
![51](/uploads/03/51.png "51")

Выбрать «Добавить», на появившейся форме занести сведения о платежном поручении.

Далее, на боковой панели рабочего окна в папке «Межтерриториальные расчеты» выбрать подпаку «Платежные поручения»-«Платежные поручения исходящие»

![52](/uploads/03/52.png "52")				

Двойным кликом левой клавишей мыши по папке «Платежные поручения исходящие».

Далее, правой клавишей мыши по рабочему полю окна добавить платежное поручения выгружаемое на территорию.

![53](/uploads/03/53.png "53")

Откроется форма для заполнения сведений о выгружаемом платежном поручении 

![54](/uploads/03/54.png "54")

Далее, выбрать «Добавить» -  и выбрать платежные поручения со счетов реестров относящиеся к выгружаемому.

Во вкладке «Данные о территории» - динамический справочник, редактируемый пользователями системы АИС МедЭксперт ТФОМС. Данные заносятся единожды и сохраняются для дальнейшего использования.

После того как данные о выгружаемом платежном поручении введены и сохранены, необходимо правой клавишей мыши выбрать «Выгрузить платежное поручение» - выпадет Обзор окно для сохранения файла.

## Загрузка платежных поручений от территорий

Для того чтобы загрузить платежное поручение от территории, необходимо выбрать на панели инструментов пиктограмму «Загрузка сведений об оплате (фед)»

![55](/uploads/03/55.png "55")

В случае успешной загрузки платежного поручения, оно будет отображено в папке «Платежные поручения входящие» в подпапках на боковой панели рабочего окна, а так же будет отражено в разделе «Платежные поручения» на реестре-счета.


						
