3.985 25.07.2024
~~~~~
- В звіті по роботі пошук сервіса за словами
- Історія введеного сервісу з наряду
- Анулювання!!! наряду з поверненням наряду в незакриті

В розробці на майбутнє:
=======================
	* Реалізація "Що нового?"
	* Звіти у валюті
	* Перекидка сервіса з одного наряду в другий
	* Модуль по заліку інструментів на сервісі
	* Карточка товара - друк історії реалізації, графік (разом усі замінники), 
	* Заблокировать установку прайсовой цены при приходе (когда в настройках выбрано ценообразование кооф)
	* Заміна валюти для прайсової ціни у всіх запчастин (приведення до однієї валюти)
	* Анулювання з переносом наряда в незакриті
	* Заміна коду виробника по шаблону CEI 255044 -> ???.??? -> 255.044
	* В запросі при закритті наряду Ітоги наряду показувати згідно Налаштуваня (наприклад: Запчастини=USD, Сервіс=UAH)
	* При друці документів - заміна активної фірми (список складів).
	* При друці документів - друк тільки запчастин чи тільки сервіс
	* Ціни послуги (комплексні роботи)
	* Прихідний касовий ордер (під питанням чи потрібно)
	* Реалізація Рем.к-тів і Застосування для запчастини

3.984 28.06.2024
~~~~~
- Верхній регістр в назві фірми
- Боржники з виписаними нарядами
- Сальдо відкритих нарядів в карточці контрагента
- Фільтр поточного контрагента в видачі

3.983 05.05.2024
~~~~~
- Розділення наріду з перенесенням вибраних позицій
- Контроль на друк зарплати
- Заробітна плата при розрахунку по одному слюсарю
- Глюк з приганням в наряді по рядкам
- Контроль додавання з історії авто в невідкритий наряд
- update https://drive.google.com/file/d/0ByEtdsJRtCDVR2p1YWJHajJTdXc/view?usp=sharing&resourcekey=0-zta5REOD0MFstc7SjvMFrQ

3.982 31.03.2024
~~~~~
- Добавлення аудиту до наряду

3.981 26.03.2024
~~~~~
- Баг с Приват24 (збільшив ліміт транзакцій запиті) 

3.980 10.03.2024
~~~~~
- Сума накладної надходження
- Сортування в наряді по видачі
- В наряді змінив кнопку "Дата накладної" на "Дата видачі" останньої в наряді
- Змінив принцип формуання аналогів і доп.аналогів. Переробив алгоритм.
- Баг пошуку по назві запчастини, коли в назві були спец.символи

3.979 20.02.2024
~~~~~
- Контроль на друк чи закриття нарядів з 0 ціною продажі
- Розширив висоту стартового екрана 
- Знищив QR код з карточки товару
- Історія авто з наряду
- Добавлення запчастини з історії ТОваром в поточний наряд правою кнопкою миші.
- Добавлення і зняття ПДВ з сервісу наряду можно зробити тільки раз. Контроль на подвійну накрутку.
- Добавлена нумерація рядків в Додаток до акту
- Добавлена нумерація рядків в Рахунку
- Помилка при відкритті картки Контрагента на малому екрані
- Приват24 API
- Переробка домашнього шляху Home() на CURDIR()

3.978 20.12.2023
~~~~~
- Баг з пошуком по коду запчастини з символом "
- Баг з пошуком по назві контрагента з символом "
- Добавлення відображення року автомобіля в списку нарядів 

3.977 01.12.2023
~~~~~
- баг з Друком реалізації товару
- Зменшення розрядності номера інвойсу в Карго API 
- Відображення типу двигуна в списку нарядів
- Оптимізація пошуку в карточці товару

3.976 30.10.2023
~~~~~
- API для IC
- API для Карго (файл lines_2023-10-01_-_2023-10-31.xlsx в \download)
- Сортування по шифру в звірці по контрагенту
- Фільтр неоплочених нарядів через клік на хеадер "Оплата" в гріді qSumar, з групуванням по шифру
- Оновити папку TOOLS конвертором xlsx

3.975 11.10.2023
~~~~~
- Друк сторонього сервісу через звіт по бригаді "Інші"
- Ітоги в авансовому звіті 
- Розширення суми звіту по зарплаті (більше мільйона)
- Адаптація друку з картки Контрагента

3.974 01.10.2023
~~~~~
- Прайс сервісу, друк
- Переклад на PL акту виконаних робіт, опція в параметрах
- В настройках вибір друку номерів запчастин
- В параметрах вибір Польского акту
- Забрав автовиділеня тексту в картці асортименті при пошуку
- Змінив сортування в нарядах, тепер завжди разом одне авто, якщо різні наряди. Зручно при розділенні наряду.
- Токен для API IC для користувача
- Знищив API Нової Пошти
- Тепер всі звіти в одном місці


3.973 01.09.2023
~~~~~
- Зміна контрагента для закритого надходження
- Контроль на кількість знаків інвойса постачальника
- Сторонній сервіс (Інші) в наряді з підзвітною особою
- Список підзвітних в параметрах
- Контроль на б/у запчастини 09 рахунку при накрутці ПДВ, попередження для розділення
- Розділеня наряду на основний та з бу та стороннім сервісом
- Знімання ПДВ з сервісу в незакритому наряді 
- Авансовий звіт по підсвітній особі

3.972 16.06.2023
~~~~
- Друк суми оплати EQ
- Ctrl+C в надходженні
- Звіт по менеджерам
- Групування в звіті по реалізації товару (балансовий рахунок та шифр оплати)
- Розширення ціни в надходженні
- API Омеги прив'язане до користувача (зміна SETS)
- Обробка помилок за API Омеги

3.971 06.06.2023
~~~~
- +/- ПДВ з 20% на встановленні в системі
- Пробіг - 7 знаків
- Од.виміру - 5 знаків
- Пробіг в список нарядів
- Форма для друку наряду PL
- Еквівалент оплати (для кросс курсів валюти)

3.97 30.03.2023
~~~~
- В карточці клієнта в приходній накладній разрахунок реалізації товару
- Відкриття карточки товару з карточки клієнта також при надходженні товару
- Добавлення в налаштування префіксів і суфіксів кодів для Омеги (для API)
- Розширення поля номеру авто для фірм, які додають свій номер до державного номера. Наприклад: CE1200XH/1200
- Копіювання коду в асортименті в буфер обміну Ctrl+C
- Розширення розмітки при акті звірки для неоплачених нарядів

3.96 07.02.2023
~~~~
- API УкрГазБанка

3.95 05.02.2023
~~~~
- API МоноБанка

3.94 12.01.2023
~~~~
- Акт звірки по залишкам оплати контрагента
- Баг з валютою для бригади
- Друк актів і накладних при закритті в різних валютах (ГРН/USD)
- Знижка в додатку до Акту 3

3.93 05.01.2023
~~~~
- Помилка при закритті наряду в сумі при *44 рахунку (в параметрах перерахунок за період 2 міс)
- Друк в валюті акту, накладної і рахунку
- Виправив, щоб не друкувало Info з наряду
- Фіксування користувача, що закрив наряд (дата та час)
- Розрахунок заробітної плати не враховує знижку клієнту
- Бригаді задати валюту по-замовчуванню

3.92 14.11.2022
~~~~
- Перехід на облік фінансів в USD

3.91 04.11.2022
~~~~
- Відсотки прибутку в наряді (в грн і в валюті)

3.90 26.10.2022
~~~~
- Порядок позицій в надходженні оригінальний
- В реєстрі при експорті порядок позицій без сортування
- Копіювання номеру по бренду в буфер при виписці наряду

3.89 08.10.2022
~~~~
- Заміна одиниць виміру у групи товарів
- Друк днів сервісу в додатку до акту
- Колонка одиниці виміру в карточці товару
- В боржниках борг в валюті на момент закриття наряду

3.88 30.09.2022
~~~~
- Пошук по інвойсу в карточці клієнта
- Пошук по номеру оплати в карточці клієнта
- Зміна номеру авто в карточці клієнта змінює в історії автомобіля

3.87 16.09.2022
~~~~
- Історія надходження в накладній (з друком)
- Пошук в реєстрі по накладній (інвойсу)
- Переробка друку ассортименту (з ітогами)
- Перенос автомобіля з оплатою

3.86 18.08.2022
~~~~
- Реестр видатків з експортом в 1С
- Фільтр в кассі по контрагенту

3.85 04.07.2022
~~~~
- Баг з сумою в реестрі

3.84 29.06.2022
~~~~
- Добавлення в експорт одиниці виміру

3.83 23.06.2022
~~~~
- Добавлення в експорт ЗКПО

3.82 22.06.2022
~~~~
- Реестр надходження з експортом в 1С

3.81 04.05.2022
~~~~
- Вікриття картки товарів з накладної
- Баг з запуском коректора цін


3.80 10.04.2022
~~~~
- Заборона оплати в майбутньому
- Звіт Кредиторка: розмежування надходження і видатків
- Звіт Каса: розмежування надходження і видатків
- Округлення сальдо до 2 знаків
- Виконані роботи/послуги - info

3.79
~~~~
- Баг з виправленням ціни запчастини в наряді

3.78
~~~~
- Добавлення "Товару" через запчастину

3.77 01.02.2022
~~~~
- Баг з добавленням клієнта

3.76 30.12.2021
~~~~
- Ігнор фінасів для постачальника
- Інфо по авто (наприклад водій)
- Зміна шифра оплати в закритому наряді


3.75 14.12.2021
~~~~
- Баг з друком # в нарядах

3.74 01.12.2021
~~~~
- Блокіровка анулювання наряду з оплатою
- Права доступу на проведення оплати


3.73 13.11.2021
~~~~
- Розрахунок кредиторки на дату

3.72 15.10.2021
~~~~
- Сума в звіті про боржників
- Шифр оплати боржника
- Копія автомобіля для нового хозяїна

3.71 05.10.2021
~~~~
- Баг з пошуком по номеру

3.70 05.10.2021
~~~~
- Каса, банк
- Розділення фінансового обліку (на надходження і розхід)
- Автооплата на поточну дату

3.69 11.08.2021
~~~~
- Своє фото для кожного користуача в мережі MACHINEID_Userid
- Пошук и підвсічування в нарядах по запчастині
- Пошук в нарядах по клієнту
- Пощук і підсвічування в закритих нарядах
- Не друкувати Сервіс який починається на #
- Пдсвітка #

3.68 20.07.2021
~~~~
- Оптимізація роботи з аналогами (прискорення пошуку по мережі)
- Добавлення функції переносу/копіювання автомобіля між клієнтами
- Перенос історії ремонту автомобіля між клієнтами

3.67 08.06.2021
~~~~
- Можливість редагування прайса на послуги

3.66 05.06.2021
~~~~
- Друк накладної з карточки (друкована назва)
- Перевод на прайс лист виконаних робіт (сервіс)

3.65 28.05.2021
~~~~
- Друк накладної з карточки (баг)
- Нові обої

3.64 27.05.2021
~~~~
- Контроль на введення назви автомобіля
- Шифр нового наряду по замовчуванню (в параметрах)
- Шифр і валюта нового надходження по замовчуванню (в параметрах)
- Контроль на повтороення номеру надходження в поточному році
- Контроль на ціну надходження, щоб доларова ціна бла не нуль

3.63 20.02.2021
~~~~
- Збільшення знаків в адресі до 100
- Зховати усі закупні ціни в системі (модіфікатор доступу "z")
- Контроль завантаження виписки Приват24

3.62 12.02.2021
~~~~
- Добавлення в рахунок і накладну інформації по автомобілю

3.61 01.02.2021
~~~~
- Карточка клієнта друкується по всіх складах разом
- Контроль приведення суми наряду до 20% дозволених

3.60 29.01.2021
~~~~
- Реєстр нарядів (добавлена нова группіровка по назві контрагента після шифра)
- Реєстр надходження (добавлена нова группіровка по назві контрагента після шифра)
- Виконані роботи: Добавлена колонка з ціною

3.59 01.01.2021
~~~~
- Контроль на акт без запчастин, контроль на накладну з сервісом
- Баг, Накрутка клієнта на запчастини

3.58 29.12.2020
~~~~
- Баг за друком суми запчастин при *44 рахунку

3.57 28.12.2020
~~~~
- Горяча клавіша при виборі з списка по номеру запису в SETS
- Зміна Горверли на kurs.com.ua
- Фільтр по марці або кольору авто в нарядах

3.56 22.12.2020
~~~~
- Контроль інвойса на повтор при приходуванні (Попередження)
- Контроль на номер авто при відкритті наряду (Попередження)
- Довідник груп товара
- Формування бригади в наряді

3.55 04.11.2020
~~~~
- В параметрах опція: Друкувати виконавців у документах
- SHIFT + 20% до запчастин при надходженні
- Історія пошуку в карточці товару
- В карточці товару відображати Користувача видачі
- В карточці контрагента відображати Користувача видачі
- Номер авто в зарезервованих запчастинах

3.54 02.11.2020
~~~~
- Нова форма друку акту виконаних робіт №2
- Виправив баг с Р/р в документах - замінив на IBAN
- Ввів поняття Директора фірми для друку в формі акту №2
- Для контрагента нове поле - договір
- Звіт: Виправив урахування за весь період відкритих нарядів при розрахунку з/п 

3.53 16.10.2020
~~~~
- Контроль при закритті наряду: Дата закриття більша за відкриття
- Знищення пробілів при вводі кода запчастини або кода аналога (кнопка)

3.52 06.10.2020
~~~~
- Контроль при друці наряду, на накрутку ПДВ на сервіс в рахунках 45~49 (нове поле)
- Нова опція в правах користувача, для влючення контролю ПДВ в сервісі - "E"
- Накрутка ПДВ в закритому наряді на сервіс (зхована функція)

3.51 26.09.2020
~~~~
- Звіт: Зарплата працівників по кожному в бригаді (новий бланк)
- Звіт: Історія затрат по автомобілю за період
- Виділення сервісу в наряді, який починається з "*"
- Звіт: Зарплата, зняти 20% з зарплати в рахунках 45~49

3.50 25.08.2020
~~~~
- Друк доповнення до акту з картки клієнта
- Можливість ховати закупні ціни в наряді
- Ітогові суми по бригаді в наряді

3.49 10.08.2020
~~~~
- Шассі в буфер для нового наряду
- Новий бланк: Доповнення до акту
- Коректировка бланків на тему збільшення шрифту марки авто і номера
- Друк на бланках назви контрагента з поля "Для друку"

3.48 25.07.2020
~~~~
- Шассі в буфер з нарядів

3.47 22.07.2020
~~~~ 
- Фільтр по назві послуги та запчастини в нарядах
- Звіт "Реєстр нарядів" по шифру
- Акт звірки по собівартості
- Збільшений шрифт в картці клієнта
- Назва клієнта для друку (повна) - нове поле в бд

3.46 13.07.2020
~~~~
- При пошуку в картці товару знімати "Поточний місяць" і "Залишки"
- Введення поняття "Бокса" - нове поле в бд
- Фільтр при видачі "На боксах" / "Всі"
- Інфо до наряду (Сумарне)
- Баг з пробігом

3.45 06.07.2020
~~~~
- Баг з друком актів

3.44 03.07.2020
~~~~
- Звіт по реалізації
- Доробка по фільтру в наряді
- Приведення суми наряду до заданої суми через зменшення суми продажу чи сервісу

3.43 27.06.2020
~~~~
- Фільтр по авто (при виписці наряду)
- IBAN для SETUP (34 цифри)
- Контроль закриття наряду без дати
- Друк наряду перенесений в вкладку "Закриття"
- Звіт: Зміна шапки "Реестру видатків"

3.42 20.06.2020
~~~~
- Звіт: Реєстр видаткових накладних з прибутками та розділенням сервісу і запчастин

3.41 02.06.2020
~~~~
- При сервісі змога розбити ціну із суми
- Друк звітів без Бренда виробника

3.40 31.05.2020
~~~~
- Баг: перевірка при закритті надходження на #00027 
- При надходженні змога розбити суму на ціну товара

3.39 08.04.2020
~~~~
- Перерахунок наряду по поточному курсу (запчастини)
- Ліцензія в буфер обміну
- Баг: пустий файл підпису ліцензії

3.38 25.03.2020
~~~~
- Виправлення багів
- Звіт по роботі по складам (розділити - поточний склад або разом)


3.37 26.02.2020
~~~~
- Функція надходження і видатків (Змінено зтворення)
- Мінорні виправлення

3.36 17.12.2019
~~~~
- Функція імпорта номенклатури з xl5

3.35 27.11.2019
~~~~
- Послуги по поточному складу
- Копіювати в буфер шассі в карточці клієнта
- Оповіщення при копіюванні в буфер кодів, шасі
- Історія по авто з переліка автомобілів клієнта

3.34 09.08.2019
~~~~
- Підготовка бази до введення IBAN

3.33 26.07.2019
~~~~
- Друк видачі для комірника (з аналогами і залишками)

3.32 05.07.2019
~~~~
- Ручне добавлення в замовлення з карточки запчастини (добавити нову таблицю ZAKAZ)
- Новий код доступа U (обробка замовлення)
- Замовлення запчастин: Два режима - ручний(завантаження) і автоматичний(розрахунок)
- баг при пошуку послуги якщо її не існує, поле більше не знищується

3.31 12.04.2019
~~~~
- Добавлення виданих запчастин при розраховуванні замовлення

3.30 25.03.2019
~~~~
- Друк оборотної відомості з Виробником чи тільки з Артікулом (опція)

3.29 05.03.2019
~~~~
- Коофіцієнт націнки у контрагента, по якому рахувати ціну в наряді
- Неліквіди (звіт)

3.28 20.02.2019
~~~~
- Помилка при друці рахунку (реквізити), обновився NARIAD.xls, ACT.xls
- Редагування шифрів оплати (в параметрах)
- Акт звірки карточки клієнта (друк): групування по автомобілю за період
- Мінорні баги (друк накладної з карточки контрагента)

3.27 06.02.2019
~~~~
- Завантаження фото з папки PIC в базу даних (підготування до BANZAI4)
- Анулювання наряда (пока без перекидки в незакриті)

3.26 06.12.2018
~~~~
- Виправлений баг при розрахунку заказа
- В разі помилки системи, показувати саму помилку в діалоговому вікні
- В карточці клієнта в наряді показувати поле Info

3.25 11.09.2018
~~~~
- Звіт по видачі комірниками

3.24 10.09.2018
~~~~
- Видача зі складу (комірником)
- Статус запита: ВИДАНО = 1, ЗАПИТ = 2, ПОШУК = 3, ЗНАЙДЕНО = 4, АНАЛОГ = 5, НЕ ЗНАЙДЕНО = 6, ПОВЕРНЕННЯ = 7
- Видача з наряду менеджером або запит на видачу комірником
- Параметр в настройках (по замовчуванню): видача менеджером або запит на видачу

3.23 04.09.2018
~~~~
- Кнопка "Рефреш" при введенні наряда
- Друк накладної, рахунку в у.о.

3.22 13.08.2018
~~~~
- Звіт по сервісу по користувачу
- Інфо для аналога
- Ціна товара якщо прайсова, вивести в основний список
- Вивести UPLOAD з программи (зробити його більш автоматичним)
- В карточці клієнта данні по прибутках (сервіс+запчастини) за вказаний період або весь

3.21 25.06.2018
~~~~
- Перехід по даблкліку в карточці товара на прихідну накладну
- Пошук запчастини по назві в історії контрагента
- При пошуку по частині назви фірми і номеру товару з пробілами (наприклад LEM LE 306, або RID RD 44.58.85) знищити пробіли в коді товара (шукати по RID RD44.58.85)
- При пошуку по номеру з пробілами (наприклад RD 44.58.85), якщо нічого не знайдено, важати введене, як код товару (знищити всі знаки і провести пошук заново) 

3.20 11.05.2018
~~~~
- Добавлення номера ліцензії в Errors.log
- Заміна коду виробника (встановлення префіксу) 19544 -> FE19544, 7777 -> SEM7777
- Перевірка про нову версію раз в день, попередження про оновлення
- Перевірка на закінчення ліцензії за 10 днів, попередження про це червоним кольором в статусбарі

3.19 21.03.2018
~~~~
- Заміна даних авто по відкритих/закритих нарядах по номеру автомобіля
- Баг при закритті наряду (Refresh)
- Попередження, коли добавляєшь в "не свій" наряд запчастину або сервіс (для доступу "M")
- Данні в карточці Клієнта (email, ЗКПО)

3.18 20.02.2018
~~~~
- Фільтр списку нарядів: Поточний місяць, Весь період
- Звіт реалізації товару вибраного користувача

3.17 19.02.2018
~~~~
- При перегляді асортимента без "картки", правільне відображенння "Картки товару" і "Виписано" (баг)
- Права доступа користувачів для редагування/закриття тільки своїх нарядів 
- Анулювання надходжень з врахуванням нової системи доступа (доработка)
- Добавлення / Знищення користувача
- В карточці Клієнта відображати користувача Видатків/Надходжень
- Фільтр списку нарядів: по клієнту і користувачу

3.16 07.02.2018
~~~~
- Обновлення API "Нової пошти"
- Попередження про закінчення ліцензії за 10 днів
- Перевірка обновлення системи при першому запуску в день
- Поле інфо в асортименті (для інфо по парі, наприклад: пара до накінечника - лівий, правий, пара до підшипника - якщо їх два)
- Інфо при вводі нової запчастини в наряд (баг)
- Зміна системи перевірки ліцензії (підпис md5)
- Оптимізація мережевого доступа при одночасному редагуванні наряду користувачами

3.15 15.09.2017
~~~~
- Мінорні баги (АвтоКлієнт Приват24)
- Інфо для позиції в наряді, карточці клієнта (Memo поле, не друкується в документах)

3.14 14.09.2017
~~~~
- Заміна API ПриватБанка на АвтоКлієнт
- Доступ до звітів (новий контроль доступу)
- Реалізація НЕПРЯМИХ аналогів

3.13 12.06.2017
~~~~
- Виправлення багу з доступом М (Менеджер)
- Зміна структури SETUP

3.12 09.05.2017
~~~~
- Пошук по коду з назвою виробника: FE 19544 - пошук по FEBI код 19544
- Нове відображення фото (миниатюри)
- При пустому наряді заборонити зміщуватися по спику відкритих нарядів.
- Оповіщення "Чекайте..." при тривалих операціях... (завантажування з Інтеренету)
- ТТН для Нової Пошти (відстеження)

3.11 28.04.2017
~~~~
- Приват24 в карточці контрагента (при наявності ЗКПО) за 3 місяці
- Пошук контрагента за його номером через #номер
- Пошук по частині Прізвища та Ім'я (контрагента)

3.10 10.02.2017
~~~~
- При збереженні назви Запчастини - галочка для запису назви всім аналогам.
- При зміні коду чи назви фірми виробника - рефреш аналогів в формі виправлення.

3.09 30.01.2017
~~~~
- Зміна відображення курсів Говерли
- Баг з полями оплати при закритті приходу (при умові відключених оплат в налаштуваннях)
- Зміна обоїв робочого стола (вибір)

3.08 15.12.2016
~~~~
- Мінорні баги

3.07 24.11.2016
~~~~
- Накрутка 20% на вартість послуги в наряді
- Експорт бази даних в 1С за розрахунковий місяць (опція в налаштуваннях)

3.06 06.11.2016
~~~~
- Зміна протоколу Приват24

3.05 01.07.2016
~~~~
- Мінорні баги

3.04 31.03.2016
~~~~
- Баг з транспорними витратами
- Зміна відображення курсів Говерли

3.03 24.07.2015
~~~~
- Опція "без ОПЛАТИ", очистка фінансів
- Лого фірми при друкі документів
- Новий фільтр в карточці товара по позиціях, що надійшли в поточному місяці
- Пошук по коду в TecDoc (вибірка аналогів і конструкційних номерів)
- Місце 4-го фото - інфа про товар з TecDoc

3.02 23.07.2015
~~~~
- Копія БД
- Копію на ГуглДрайв, ОнеДрайве (путь архіва)
- Посилання на сайт http://lordruss.wix.com/banzai
- Курси валют Говерли
- QR код (нова бібліотека OcvitaBarcode.ocx)
- Відправка рахунка на емейл клієнта (нове поле у Клієнта)
- Новий reg файл
- Параметри SMTP сервера для відправки пошти (в настройках)
- Нова біліотека SMTP (OSSMTP.dll)
- Нова система ліцензювання license.key
- Допомога через TeamViewer (нова кнопка)
- %% заробітної плати по фірмі та по бригадам
- Новий iconset

3.01 01.01.2015
~~~~
- Підтримка MD5 (новая бібліотека aamd532.dll)
- UPLOAD на автоматі (з програми)
- Індексація БД тепер в Update (після оновлення версії)
- Таблиця індексів
- Оновлення версії через інтернет (Google Drive)
- Підтримка ZIP архивів
- Перероблений дизайн головного вікна
- Курси валют Приват24, Говерла
- По три логіна банка на один склад
- Прогрес бар в тривалих операціях (друк)

3.00 12.12.2014
~~~~
- Реалізація Приват24
- Знижка в карточці товара
- Три фото на один товар
- Новий код товара (УКТ ЗЕД)