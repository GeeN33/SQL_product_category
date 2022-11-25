# Вопрос №3:

## “Одному продукту может соответствовать много категорий, в одной категории может быть много продуктов.” Это связь many to many нужно добавить связующую таблицу допустим ## «SQL_product_category» тогда запрос будет такой:

## SELECT product.name, category.name 
## FROM product
## LEFT JOIN product_category ON product.id == product_category.product_id 
## LEFT JOIN category ON category.id == product_category.category_id;
