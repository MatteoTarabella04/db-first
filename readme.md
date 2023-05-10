# DB-First

## Second-Hand Cars

## Entity name: Car
## Table Name: cars

## Table:

- id => NOTNULL, PRIMARY KEY, UNIQUE, AUTO-INCREMENT, BIGINT, INDEX
- brand => NOTNULL, INDEX, VARCHAR(100)
- model => NOTNULL, INDEX, VARCHAR(100)
- year => NULLABLE, INDEX, YEAR
- km => NOTNULL, MEDIUMINT
- color => NOTNULL, INDEX VARCHAR(50)
- fuel => NOTNULL, VARCHAR(50)
- kw => NOTNULL, VARCHAR(50)
- buy_price => NULLABLE, DECIMAL(9,2)
- sell_price => NOTNULL, INDEX DECIMAL(9,2)
- doors => TINYINT, DEFAULT(5)
- seats => TINYINT, DEFAULT(4)
- transmission => NOTNULL, INDEX, VARCHAR(20)
- optional => NULLABLE, TEXT
- owners => TINYINT, DEFAULT(1)
- image => NOTNULL, UNIQUE, VARCHAR(255)
- damage => NULLABLE, TEXT
- sold => TINYINT, DEFAULT(0) ---> BOOLEAN VALUE