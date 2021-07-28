## mysql Basics
* Create table
```sql
CREATE TABLE Usuario(
  id int,
  email varchar(255),
  username varchar(50)
);
```
* SELECT
```sql
SELECT * FROM prueba.Usuario;
```
* ALTER TABLE
```sql
ALTER TABLE Usuario ADD edad INT;
```
```sql
ALTER TABLE Usuario DROP COLUMN edad;
```
```sql
ALTER TABLE Usuario MODIFY COLUMN email VARCHAR(50);
```
* INSER INTO
```sql
INSERT INTO Usuario (email, username)
  VALUES('correo@gmail.com', 'user');
```
* DELETE
```sql
DELETE FROM Usuario WHERE email = 'correo@gmail.com' LIMIT 1;
```
* ALTER TABLE
```sql
ALTER TABLE Usuario ADD PRIMARY KEY (id);
```
```sql
ALTER TABLE Usuario MODIFY COLUMN id INT AUTO_INCREMENT;
```
