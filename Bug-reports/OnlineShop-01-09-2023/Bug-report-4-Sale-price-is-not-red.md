# #18016475 Цена со скидкой перестает быть красной в разделе "Корзина" после нажатия на кнопку "+" в таблице

**Метки:** Корзина, Оформление

**Предусловие:** открыть сайт http://prestashop.qatestlab.com.ua/en/ в Mozilla Firefox

**Шаги:**

1. Добавить товар со скидкой в корзину
2. Нажать на панель “Cart” и перейти в корзину
3. Напротив товара со скидкой в колонке “Qty” нажать “+”

**ФР:** Цена товара со скидкой перестает быть красной

**ОР:** В колонке “Unit price” отображается: цена товара со скидкой (красная), процент скидки (на красном фоне), и сумма без скидки (зачеркнутая).

**Серьезность:** Trivial

**Приоритет:** Low

![Bug screenshot](/Bug-reports/OnlineShop-01-09-2023/img/004.png "Bug screenshot")