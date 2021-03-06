Финансовый блок
---------------

Для перехода к финансовому разделу, на панели разделов нажимаем
Bookkeeping portable.

|image0|

Первоначально, для работы в финансовом разделе, необходимо заполнить
План счетов «Бухгалтерский учет», а также справочник Финансовые года.

Справочник финансовые года
~~~~~~~~~~~~~~~~~~~~~~~~~~

Справочник финансовые года предназначен для ввода информации о
финансовом годе. Переход к справочнику осуществляется нажатием кнопки
«Финансовые года» на панели навигации в разделе Bookkeeping portable.

|image1|

Добавление нового элемента справочника происходит по кнопке Создать.

|image2|

В появившемся окне необходимо заполнить Наименование, а также период
действия данного финансового года, который может быть произвольным:
полугодие, год, 18 месяцев и пр. Период финансового года зависит от
внутренней политики предприятия, а также от особенностей
законодательства. Поле код присваивается программой автоматически при
записи.

В случае, если финансовый год является закрытым периодом, проставляется
флаг Закрытый.

План счетов
-----------

Для перехода к плану счетов, на панели разделов нажимаем Bookkeeping
portable, затем Chart of accounts «Bookkeeping». Справочник План счетов
является периодическим: в поле «Year validity» указываем финансовый год,
для которого будет актуален данный набор счетов.

Ввод нового элемента справочника План счетов происходит при
использовании кнопки «Создать». На первом этапе необходимо указать
является ли вводимое значение счетом или субсчетом.

|image3|

Важно! При создании счетов и субсчетов необходимо выполнять следующие
условия:

1. Счета первого уровня должны иметь одинаковое количество символов;

2. Счета второго уровня (субсчета) должны иметь одинаковое количество
   символов. При этом количество символов второго уровня может быть
   отличен от количества символов первого уровня;

3. Счета второго уровня (субсчета) должны иметь первое субконто равное
   субконто счета Родителя.

Для примера введем счет 201 «Inventory» из международного плана счетов:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

|image4|
~~~~~~~~

Введем субсчет 201.01 «Inventory - Raw materials and supplies»:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

|image5|
~~~~~~~~

При вводе нового элемента справочника План счетов указываем, что вводимый элемент является субсчетом. В появившемся окне заполняем следующую информацию:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1. .. rubric:: Родитель - указываем счет, к которому относится вводимый
      элемент (в нашем примере это 201 «Inventory»);
      :name: родитель---указываем-счет-к-которому-относится-вводимый-элемент-в-нашем-примере-это-201-inventory

2. .. rubric:: Код - указываем номер субсчета: 201-01;
      :name: код---указываем-номер-субсчета-201-01

3. .. rubric:: Наименование – наименование счета;
      :name: наименование-наименование-счета

4. .. rubric:: в поле Year of Start of Validity указываем период
      действия данного счета, причем если счет действительный и
      используется в программе, то начало периода указывается первый
      введенный финансовый год (с которого начинается работа в
      программе), а конец периода действия счета будет неактивным.
      Ввести период, с которого счет больше не будет использован в
      программе, можно при установке радиоточки No valid;
      :name: в-поле-year-of-start-of-validity-указываем-период-действия-данного-счета-причем-если-счет-действительный-и-используется-в-программе-то-начало-периода-указывается-первый-введенный-финансовый-год-с-которого-начинается-работа-в-программе-а-конец-периода-действия-счета-будет-неактивным.-ввести-период-с-которого-счет-больше-не-будет-использован-в-программе-можно-при-установке-радиоточки-no-valid

5. .. rubric:: Balance type указывает на признак счета/субсчета:
      балансовый, забалансовый или результативный (управленческий).
      Суммы по результативным счетам закрываются в конце года и на их
      основании строится Отчет о прибылях и убытках;
      :name: balance-type-указывает-на-признак-счетасубсчета-балансовый-забалансовый-или-результативный-управленческий.-суммы-по-результативным-счетам-закрываются-в-конце-года-и-на-их-основании-строится-отчет-о-прибылях-и-убытках

6. .. rubric:: в поле Balance side выбираем каким является счет/субсчет:
      активным (Dr), пассивным (Cr) или активно-пассивным (Dr/Cr);
      :name: в-поле-balance-side-выбираем-каким-является-счетсубсчет-активным-dr-пассивным-cr-или-активно-пассивным-drcr

7. .. rubric:: в поле Purpose указываем назначение вводимого
      счета/субсчета. Выбранное значение данного поля влияет на набор
      аналитик (субконто), которые можно присвоить для вводимого
      счета/субсчета;
      :name: в-поле-purpose-указываем-назначение-вводимого-счетасубсчета.-выбранное-значение-данного-поля-влияет-на-набор-аналитик-субконто-которые-можно-присвоить-для-вводимого-счетасубсчета

8. .. rubric:: флаг Currency устанавливается в случае, если счет
      валютный;
      :name: флаг-currency-устанавливается-в-случае-если-счет-валютный

9. .. rubric:: поля Ext dimension 1, Ext dimension 2, Ext dimension 3 –
      аналитика счета/субсчета. Т.о. в программе для счета/субсчета
      можно указать три субконто.
      :name: поля-ext-dimension-1-ext-dimension-2-ext-dimension-3-аналитика-счетасубсчета.-т.о.-в-программе-для-счетасубсчета-можно-указать-три-субконто.

Справочник Контрагенты
----------------------

Рассмотрим заполнение справочника Контрагенты для дальнейшего
использования в финансовом блоке.

В карточке Контрагента на вкладке Additionally необходимо указать
бухгалтерскую группу. Бухгалтерские группы позволяют присваивать группе
контрагентов определенный набор счетов, которые будут в последствии
использоваться в бухгалтерских проводках.

|image6|

Для добавления новой бухгалтерской группы, необходимо создать новый
элемент в справочнике Financial counterparty groups:

|image7|

В поле наименование указывается наименование бухгалтерской группы
контрагентов. Записываем введенный элемент и нажимаем на пиктограмму
|image8| для указания набора бухгалтерских счетов:

|image9|

Данные бухгалтерских счетов вводятся в справочник Bookkeeping Settings
Common Form (Общие параметры списка счетов). Данный справочник является
периодическим, благодаря чему можно настраивать список счетов на
определенную дату.

Заполнение справочника следующее:

-  period – дата, с которй начинает действовать данный список счетов;

-  Ac. «Ac. Payable» - счет кредиторской задолженности (задолженности
   перед поставщиком);

-  Ac. «Prepayment for customer» - счет полученного аванса от
   покупателя;

-  Ac. «Prepayment for supplier» - счет выданного аванса поставщику;

-  Ac. «Ac. receivable» - счет дебиторской задолженности (задолженности
   покупателя).

   Для заполнения бухгалтерской группы Резиденты/Дебиторы (из
   вышеприведенного примера) достаточно заполнить счет дебиторской
   задолженности и счет полученных авансов от покупателя. Можно
   настроить данный список таким образом, что в одной бухгалтерской
   группе будут заполнены счета дебиторской и кредиторской задолженности
   одновременно, но в проводки программа будет использовать счета
   расчетов в зависимости от установленного флага у контрагента:
   покупатель, поставщик или прочие отношения.

   |image10|

Справочник Номенклатура
-----------------------

В справочнике Номенклатура необходимо так же как и в справочнике
Контрагенты внести информацию о бухгалтерской группе.

В карточке Номенклатуры на вкладке Main parameters необходимо указать
бухгалтерскую группу в поле «Financial group». Бухгалтерские группы
позволяют присваивать группе элементов номенклатуры определенный набор
счетов, которые будут в последствии использоваться в бухгалтерских
проводках:

|image11|

Список бухгалтерских групп хранится в справочнике Financial products and
services groups.

Для добавления нового элемента справочника, нажимаем на кнопку Создать
на панели инструментов:

|image12|

Заполнение элемента справочника следующее:

-  Код – присваивается программой автоматически, но может быть изменен
   при необходимости;

-  Наименование – заполняется наименование бухгалтерской группы товаров
   и услуг.

   После записи элемента справочника, необходимо присвоить список счетов
   для данной бухгалтерской группы. Для этого, на панели инструментов
   нажимаем на кнопку |image13|.

   Данные бухгалтерских счетов записываются в справочник Bookkeeping
   Settings Common Form (Общие параметры списка счетов). Справочник
   является периодическим, благодаря чему можно настраивать список
   счетов на определенную дату.

   |image14|

   Заполнение справочника следующее:

-  period – дата, с которй начинает действовать данный список счетов;

-  Ac. «Cost of goods» - счет учета товарно-материальных ценностей;

-  Ac. «Sales amount» - счет доходов от продаж;

-  Ac. «Sales costs» - счет затрат (себестоимости).

Шаблон типовых операций
-----------------------

Шаблон типовых операций представляет собой бухгалтерские проводки,
специфичные для определенной операции. Список шаблонов типовых операций
находится в разделе Bookkeeping portable. Данный справочник является
иерархическим, т.е. можно создавать группы и подгруппы для типовых
операций. К примеру, группа Расходные документы может быть разделена на
подгруппы: Дебиторы / Резиденты, Дебиторы / Нерезиденты и пр.

|image15|

Рассмотрим заполнение реквизитов шаблона типовой операции.

На вкладке General указываются основные реквизиты типовой операции:

|image16|

-  Наименование – указывается наименование шаблона бухгалтерской
   операции;

-  Document base – документ основания, который выбирается из выпадающего
   списка документов;

-  Set filter - позволяет устанавливать фильтр для выделения из списка
   документов только тех, в которых присутствует реквизит, по которому
   создается фильтр:

   |image17|

   К примеру, фильтр по Подразделению: будут отбираться документы
   Customer invoice, в которых подразделение равно значению Main
   department;

-  Description for bookkeeping operation - текстовое поле, в котором
   отражается краткое описание бухгалтерской операции;

-  Group records – установка флага позволяет группировать проводки, т.е.
   при наличии в одном документе одинаковых позиций, участвующих в
   бухгалтерской проводке, программа объединяет. К примеру, в документе
   указаны несколько номенклатурных позиций, которые входят в одну
   группу, а в бухгалтерской проводке аналитика ведется по группам. В
   таком случае, данные позиции в бухгалтерской проводке объединяться в
   одну. Установка флага обязательна;

-  Don’t generate zero records – при установке данного флага записи с
   нулевой суммой не формируются. Установка флага обязательна.

-  Lock/Unlock template – устанавливает блокировку бухгалтерской
   проводки в случае, если данный шаблон больше не будет использоваться
   в документах.

   На вкладке Bookkeeping records отражаются бухгалтерские проводки,
   присущие для данной бухгалтерской операции:

   |image18|

   Бухгалтерские проводки формируются на основании различных данных: на
   основании данных документа, табличных частей или регистров, по
   которым делается запись того документа, который выбран в качестве
   основания в поле Document base.

   Для добавления основания необходимо воспользоваться кнопкой
   |image19|, а для удаления - |image20|.

   После ввода хотя бы одного элемента, на основании которого будет
   создана бухгалтерская запись, становится доступной кнопка |image21|,
   с помощью которой можно создавать необходимое количество проводок,
   присущие одной бухгалтерской типовой операции.

   В поле Account отражается счет учета (выбирается из справочника
   Bookkeeping Settings Common Form: элементов списка бухгалтерских
   групп Номенклатуры или Контрагентов), а в полях Extra dimension –
   аналитика выбранного счета.

   В поле Amount Dr указываем какое значение будет попадать в сумму по
   дебету, а в поле Amount Cr –какое значение будет попадать в
   кредитовую сумму. В поле Description можно ввести стандартную фразу,
   которая будет кратко описывать данную проводку. В Поле Conditions
   можно указать условия, при которых будет срабатывать данная
   бухгалтерская запись.

   Автоматический расчет курсовых разниц при формировании проводки
   возможен при установке флага Use in exchange rate difference
   calculations.

   На вкладке Purchase VAT Records – отражается шаблон проводок для
   отражения НДС при покупках (принимаемый к зачету), а на вкладке Sales
   VAT Records – проводки по НДС от продаж (к уплате в бюджет).

   На вкладке Exchange rate differences – отражается счет и аналитика
   курсовых разниц.

Формирование бухгалтерских проводок
-----------------------------------

После процедуры создания шаблона типовых операций, можно приступить к
формированию бухгалтерских проводок. Для этого необходимо в журнале
документов, для которого формируется бухгалтерская запись, выделить
необходимый элемент и нажать на кнопку |image22|. Если для данного
документа ранее не было создана бухгалтерская проводка, программа выдаст
соответствующее сообщение и предложит пользователю создать ее.

|image23|

Бухгалтерская проводка автоматически будет создана на основании данных
документа:

|image24|

Групповое проведение документов
-------------------------------

Для групповой обработки документов и автоматического создания
бухгалтерских проводок, предназначена обработка Bookkeeping posting
settings, которая находится в разделе Bookkeeping portable. При запуске
данной обработки, выводится список документов (определяемых
пользователем самостоятельно), с указанием признака: сформированы ли
бухгалтерские проводки или нет, а также для ввода шаблона бухгалтерских
операций в случае их отсутствия.

.. |image0| image:: media/image1.png
   :width: 4.04722in
   :height: 1.88542in
.. |image1| image:: media/image2.png
   :width: 3.59225in
   :height: 1.14215in
.. |image2| image:: media/image3.png
   :width: 3.65660in
   :height: 1.02820in
.. |image3| image:: media/image4.png
   :width: 1.92188in
   :height: 1.23149in
.. |image4| image:: media/image5.png
   :width: 3.60406in
   :height: 1.84800in
.. |image5| image:: media/image6.png
   :width: 3.69695in
   :height: 1.88174in
.. |image6| image:: media/image7.png
   :width: 3.79225in
   :height: 1.87762in
.. |image7| image:: media/image8.png
   :width: 3.72025in
   :height: 1.20314in
.. |image8| image:: media/image9.png
   :width: 0.30417in
   :height: 0.31181in
.. |image9| image:: media/image10.png
   :width: 3.73117in
   :height: 1.87676in
.. |image10| image:: media/image11.png
   :width: 3.89307in
   :height: 2.01566in
.. |image11| image:: media/image12.png
   :width: 4.00000in
   :height: 2.50000in
.. |image12| image:: media/image13.png
   :width: 4.05208in
   :height: 2.26944in
.. |image13| image:: media/image9.png
   :width: 0.30417in
   :height: 0.31181in
.. |image14| image:: media/image14.png
   :width: 4.05208in
   :height: 1.94792in
.. |image15| image:: media/image15.png
   :width: 4.05208in
   :height: 1.93056in
.. |image16| image:: media/image16.png
   :width: 4.05208in
   :height: 1.74792in
.. |image17| image:: media/image17.png
   :width: 3.69408in
   :height: 1.85783in
.. |image18| image:: media/image18.png
   :width: 4.05625in
   :height: 1.79167in
.. |image19| image:: media/image19.png
   :width: 0.26944in
   :height: 0.25208in
.. |image20| image:: media/image20.png
   :width: 0.27847in
   :height: 0.25208in
.. |image21| image:: media/image21.png
   :width: 1.04375in
   :height: 0.24375in
.. |image22| image:: media/image22.png
   :width: 0.30417in
   :height: 0.30417in
.. |image23| image:: media/image23.png
   :width: 4.04028in
   :height: 1.74375in
.. |image24| image:: media/image24.png
   :width: 4.04792in
   :height: 2.16806in
