## symfony-products

По итогам реализации задания необходимо указать сколько времени у Вас ушло на его выполнение.

Реализовать на Symfony2 (версия 2.3+) следующий функционал:

1. Авторизация (емайл, пароль), восстановление пароля, регистрация (имя, емайл, пароль, капча), подтверждение адреса электронной почты после регистрации.

2. Регистрация/Авторизация через соцсеть Facebook.

3. Роль администратора. Аккаунт администратора предустановленный (admin@mail.com/123), администратор не может регистрироваться.

4. Profile page. Возможность изменить емайл (при изменении емайла необходимо отправлять письмо для подтверждения нового адреса и делать logout текущего пользователя), имя и пароль.

5. Меню для не авторизованного пользователя: Login. Меню для авторизованного пользователя: Products, Profile, Logout.

6. Products page.

    - Список продуктов текущего пользователя: Название продукта, описание, thumbnail изображение, цена. Пользователь с ролью администратора видит продукты всех пользователей и в таблице продуктов добавляется еще одна колонка: "<имя пользователя> (<емайл>)". Список должен сортироваться по любой из колонок. Также нужна возможность фильтрации списка по названию товара.

    - Форма добавления/редактирования продукта. (название, описание, изображение продукта (опциональное поле), цена)

    - Возможность удаления продукта. (пользователь может удалить только свой продукт, администратор может удалить продукт любого пользователя)
