# [![Build status](https://ci.appveyor.com/api/projects/status/0q9a69i7x2e8imiv?svg=true)](https://ci.appveyor.com/project/LrdKefon/auto-5-1-patterns)
# Домашнее задание к занятию «2.3. Patterns»

В качестве результата пришлите ссылку на ваш GitHub-проект в личном кабинете студента на сайте [netology.ru](https://netology.ru).

[Шаблон для ДЗ](https://github.com/netology-code/aqa-code/tree/master/patterns).


## Задача №1: заказ доставки карты (изменение даты)

Вам необходимо автоматизировать тестирование новой функции формы заказа доставки карты:

![](pic/order.png)

Требования к содержимому полей, сообщения и другие элементы, по словам заказчика и разработчиков, такие же, они ничего не меняли.

Примечание: личный совет — не забудьте это перепроверить, никому нельзя доверять 😈

Тестируемая функциональность: если заполнить форму повторно теми же данными, за исключением «Даты встречи», то система предложит перепланировать время встречи:

![](pic/replan.png)

После нажатия кнопки «Перепланировать» произойдёт перепланирование встречи:

![](pic/success.png)

**Важно:** в этот раз вы не должны хардкодить данные прямо в тест. Используйте Faker, Lombok, data-классы для группировки нужных полей и утилитный класс-генератор данных — см. пример в презентации. 

Утилитными называют классы, у которых приватный конструктор и статичные методы.

Обратите внимание, что Faker может генерировать не совсем в нужном для вас формате.
