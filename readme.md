**1. Выбор базы данных**

    Реляционная SQL
    Выбор MySQL был изза того что это одна из самыз популярных и удобная в обработки запросов база данных, еще изза того что с ней работать более приятно лично для меня. 
    - **Плюсы**
        - Маштабируемость *(сам пока не сталкивался в так как опыта в проектах где понадобилось бы маштабировать базу как вертикально так и горзонтально не учавствовал, но в сообществе пишут об этом)* 
        - Производительность
        - Сообщество и поддержка
    - **Минусы**
        - Бывают проблемы с гибкостью схемы данных при необходимости внесния изменений

**2. Схема маркета**
    ![Схема маркета](https://i.ibb.co/ydg5mpq/sekrana.png)
    https://ibb.co/6rDbc8F
    так же схему можно посмотреть перейдя по [ссылке](https://lucid.app/lucidchart/6d315e80-c854-4075-85ee-6770bf00211b/edit?viewport_loc=-2571%2C-549%2C2560%2C1254%2C0_0&invitationId=inv_7f3550e0-2644-4a06-bf71-c36bbbb8285f)
    
    **Связи между таблицами**
        users->orders
        cities->warehouses
        categoeies->subcategories
        orders->order_elements
        product->order_elements
        subcategories->products
**3. Прототип API оформления заказа**
    Код прототипа находится [тут](market_proto.php)
