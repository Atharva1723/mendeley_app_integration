Testing Mendeley Handler with my_mendeley
1. Testing CREATE DATABASE

```
CREATE DATABASE my_mendeley
WITH
  ENGINE = 'mendeley'
  PARAMETERS = {
    "client_id" : "the client id",
     "client_secret" : "the client secret"
  };
```
![mendley](https://github.com/Atharva1723/mindsdb/assets/87201444/dc72a92d-c11e-4bbc-abe6-1b887aed3214)

2. Testing SELECT DATABASE
```
SELECT *
FROM my_mendeley.catalog_search_data
WHERE title = "COVID-19 diagnosis and management: a comprehensive review"
LIMIT 10;
```
![image](https://github.com/Atharva1723/mindsdb/assets/87201444/dcd5a4b6-d169-41c3-bd40-9f96203c530e)

3. Testing SELECT DATABASE
```
SELECT *
FROM my_mendeley.catalog_search_data
WHERE doi = "10.1111/joim.13091"
```

![image](https://github.com/Atharva1723/mindsdb/assets/87201444/07e5a2a6-0a2c-48fc-8ee8-7b2979590ea3)

4. Testing SELECT DATABASE
```
SELECT *
FROM my_mendeley.catalog_search_data
WHERE id = "c3503ef8-26eb-3666-87db-03ccc422293a"
```
![image](https://github.com/Atharva1723/mindsdb/assets/87201444/bb495dcb-550a-486d-b200-35ada98bf533)


  
