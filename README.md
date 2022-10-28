# Функциональные тест кейсы
# Описание
Было проведено 2 тест-кейса App url: https://www.nashamoda.by 

Результат: Все тесты пройдены

# Тест 1:
1. перейти по ссылке;
2. на главной странице выбрать панель поиска;
3. ввести "Пальто";
![image](https://user-images.githubusercontent.com/70698710/193314709-aa891ff7-c4e5-40b7-94bd-e42d1e48137d.png)

Будет вывед католог модели верхней одежды "Пальто"

# Тест 2:
Предусловие: Найти товары из категории "пальто";
1. Перейти на любой товар из найденой категории "пальто";
![image](https://user-images.githubusercontent.com/70698710/193315234-83d4d95e-078d-4295-b412-e22d583b81c8.png)
2. Нажать кнопку "Добавить в корзину";
3. Для перехода в корзину нажать на иконку "Корзина";

Открывается окно корзины, в которой находится выбранный товар.


# Тест 3. **_Проверка возможности добавления в избранное_**

### Шаг:
1. Посетите каталог.
2. Нажмите на кнопку добавления товаров в избранное. ![button](screens/favorites.png)
3. Посетите страницу "Мои желания". 

### Ожидаемый результат:
Отобразились выбранные товары в разделе "Мои желания".

### Реальный результат:
Отобразились выбранные товары в разделе "Мои желания".

### Вердикт:
Тест пройден успешно.

![test search](screens/favorites2.png)

## 5. **_Проверка реализации локализации_**

### Шаг:
1. Посетите сайт.
2. Нажмите на кнопку необходимого языка.

### Ожидаемый результат:
Основные надписи на сайте стали отображаться на выбранном языке.

### Реальный результат:
Не все основные надписи на сайте отображаются корректно на выбранном языке.

### Вердикт:
Тест не пройден.

![test search](screens/lang.png)

## 6. **_Проверка возможности покупки оптом_**

### Шаг:
1. Посетите сайт.
2. Нажмите на кнопку "Заказать оптовый прайс".
3. Введите необходимые данные.
4. Нажмите кнопку "Отправить".

### Ожидаемый результат:
Подтверждение отправки заявки на заказ.

### Реальный результат:
Подтверждение отправки заявки на заказ.

### Вердикт:
Тест пройден успешно.

![test search](screens/buyopt.png)

## 7. **_Проверка невозможности выполнения пустого поиска_**

### Шаг:
1. Посетите сайт.
2. Выделите поле строки поиска, нажав на него.
3. Ничего не вводите и нажмите ввод или на значок поиска.

### Ожидаемый результат:
Отображение сообщения о том, что результатов по данному запросу не найдено.

### Реальный результат:
Отобразилось все товары, добавленные в каталог.

### Вердикт:
Тест не пройден.

![test search](screens/searchnull.png)

## 8. **_Проверка возможности 'Покупки в 1 клик'_**

### Шаг:
1. Посетите каталог.
2. Выберите необходимую категорию и товар или воспользуйтесь поиском в правом верхнем углу.
3. Нажмите кнопку "Купить в 1 клик"
4. Заполните форму для заказа и отправьте.

### Ожидаемый результат:
Подтверждение отправки заявки на заказ.

### Реальный результат:
Подтверждение отправки заявки на заказ.

### Вердикт:
Тест пройден успешно.

![test search](screens/buy.png)

## 9. **_Проверка отображения раздела 'Вы просматривали'_**

### Шаг:
1. Посетите каталог.
2. Просмотрите несколько товаров.

### Ожидаемый результат:
Отображение просмотренных недавно товаров в разделе "Вы просматривали".

### Реальный результат:
Отображение просмотренных недавно товаров в разделе "Вы просматривали".

### Вердикт:
Тест пройден успешно.

![test search](screens/see.png)

## 10. **_Проверка корректной работы фильтров (мин./макс. цена)_**

### Шаг:
1. Посетите каталог.
2. Поставьте нуль как значение минимальной и максимальной цены товаров.

### Ожидаемый результат:
Отображение сообщения о том, что подходящих результатов не найдено.

### Реальный результат:
Отображение товаров с значением цены "Не указана".

### Вердикт:
Тест не пройден.

![test search](screens/category.png)
