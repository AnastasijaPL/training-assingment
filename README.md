Стратегия (план) тестирования

Дано: ссылка на страницу: https://wortex.by/catalog#shurupoverty 
Эта страница с продукцией электроинструмента WORTEX. 

Цель: Так как было сказано, что тестирование нужно проводить методом «чёрного ящика», то для этого нам нужно знать только требования и спецификацию, нам не надо знать внутреннюю структуру страницы. Поэтому, на мой взгля, нужнопротестировать функциональность элементов, внешний интерфейс, удобство использования данной страницы.
Что тестировать:
- вкладка «Продукция» и выбор товара;
- поиск нужной продукции;
- переход на карточку с выбранной продукцией;
- кнопка «Скачать каталог»;
- переход по ссылке info@wortex.by
- переход по нажатию на надпись WORTEX;
- кнопка «Совместима с Makita LXT»;
- переход на Инстаграм по клику на иконку.

Как тестировать:
Составить тестовые сценарии или чек-лист, что именно и как тестировать на странице. Будет описание вначале как позитивных проверок, так и негативных. Далее переход непосредственно к тестированию:
1. Вначале проверка дымовым тестированием, чтобы определить выполняет ли страница свою основную функциональность; Здесь минимальный набор тестов для того, чтобы понять продолжать ли тестировать далее сайт или вернуть его на доработку.
2. Функциональное тестирование всех основных элементов данной страницы (кнопки, ссылки, поле «Поиск», карточка товара). Это основной вид теста, при котором происходит проверка функциональности сайта при его стандартном использовании, а также при нестандартном. Основная цель функционального тестирования- это обеспечить максимально возможное покрытие тестами программного продукта (которые я указала в чек-листе).
3. Проверка пользовательского интерфейса: оценить простоту навигации и доступность важной информации; проверка наличия ошибок в дизайне.
4. Регрессионное тестирование: проводится каждый раз при внесении новых изменений, чтобы проверить как работает старая функциональность с новой, её совместимость. Проводится повторное прохождение всех тестовых сценариев, протестированных ранее.

Чек-лист проверок для страницы с продукцией электроинструмента WORTEX https://wortex.by/catalog#shurupoverty

ПРОВЕРКА (Результат)
1. Открыть страницу https://wortex.by/catalog#shurupoverty
2. При наведении на вкладку «Продукция» появляется выпадающий список с товарами	
3. Выбрать любой товар из выпадающего списка «Продукция» 	
4. Открыть любую карточку с продукцией при нажатии на название товара 	
5. Открыть любую карточку с продукцией при нажатии на картинку товара	
6. Переключить на следующую страницу с информацией о товаре при нажатии на кнопку «следующий»	
7. Вернуться на предыдущую страницу с информацией о товаре при нажатии на кнопку «предыдущий»	
8. Переключение картинок товара с помощью стрелок влево/вправо	
9. Переключение картинок товара с помощью стрелок на клавиатуре	
10. Увеличить любую картинку с товаром при нажатии на эту картинку	
11. Закрыть любую увеличенную картинку с товаром при нажатии на копку «X»	
12. Закрыть любую увеличенную картинку с товаром при нажатии на свободное место от картинки	
13. Вернуться на страницу со всей продукцией при нажатии на вкладку «Продукция»	
14. Вернуться на страницу с всей продукцией при нажатии на кнопку «Назад» в браузере	
15. Ввести в поле «Поиск» полное наименование любого товара и нажать иконку «Лупы»	
16. Ввести в поле «Поиск» полное наименование любого товара и нажать кнопку «Enter» на клавиатуре	
17. Ввести в поле «Поиск» неполное наименование любого товара 3 буквы 	
18. Ввести в поле «Поиск» неполное наименование любого товара 2 буквы	
19. Ввести в поле «Поиск» неполное наименование любого товара 4 буквы 	
20. Ввести в поле «Поиск» сочетание букв использующихся в середине наименования любого товара	
21. Ввести в поле «Поиск» цифры	
22. Ввести в поле «Поиск» полное наименование любого товара буквами верхнего и нижнего регистра 	
23. Ввести в поле «Поиск» латиницу	
24. Скачать каталог при нажатии кнопки «Скачать каталог»	
25. Сортировка товара с совместимостью Makita LXT при нажатии кнопки «Совместимо с Makita LXT»	
26. Открыть почту для связи WORTEX при нажатии на ссылку info@wortex.by
27. Переход на страницу в Instagram при нажатии на иконку Instagram	
28. Шрифты совпадают со шрифтами из макета	
29. Поведение элементов на страницах одинаково	
30. Появление сообщение при ненайденном товаре	
31. Вернуться на страницу со всей продукцией при нажатии на ссылку «Каталог»(когда товар на найден)	
32. Ввести в поле «Поиск» пустое поле	
33. Ввести в поле «Поиск» несколько пробелов	
34. Ввести в поле «Поиск» пробелы до и после текста 	
35. Ввести в поле «Поиск» спецсимволы

	Ошибка 1	Ошибка 2	Ошибка 3
Заголовок	Окрывается дубликат текущей странице при нажатии кнопки "Скачать каталог" 	Не полностью отображается выпадающийся список при наведении на вкладку "Продукция" на странице с результататом, что товар не найден	Не окрывается увеличенная картинка при нажатии на картинку в карточке товара
Описание			
Окружение	Google Chrome Версия 128.0.6613.114	Google Chrome Версия 128.0.6613.114	Google Chrome Версия 128.0.6613.114
Версия сайта	—	—	—
Стабильность воспроизведения	Стабильно	Стабильно	Стабильно
Предусловия	—	—	—
Шаги воспроизведения	"1. Открыть страницу https://wortex.by/catalog#shurupoverty
2. Нажать на кнопку ""Скачать каталог""
"	"1. Открыть страницу https://wortex.by/catalog#shurupoverty
2. Ввод в поле ""Поиск"" - 123
3. Нажать на иконку ""Лупа"" или клавишу ""Enter"" на клавиатуре
4. Навести мышку на вкладку ""Продукция""
"	"1. Открыть страницу https://wortex.by/catalog#shurupoverty
2. Ввод в поле ""Поиск"" - Аккумулятор CBL 1820-1
3. Нажать на иконку ""Лупа"" или клавишу ""Enter"" на клавиатуре
4. Нажать на карточку товара Аккумулятор CBL 1820-1
5. Нажать на картинку товара"
Фактический результат	Открывается дубликат текущей страницы	Не полностью отображается выпадающийся список	Не окрывается увеличенная картинка товара
Ожидаемый результат	Скачивается каталог с товарами и либо сохраняется в загрузках на компьютере, либо сразу открывается каталог с товарами	Полностью отображается выпадающий список	Открывается увеличенная картинка товара
Дополнительная информация			


	
	
	

	
	







	
	
	




 



