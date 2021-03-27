## 3-1
```
INSERT INTO user (name, username, passward) VALUES ("Steven", "ply", "ply");
```
![alt text](./images/3-1.png)
## 3-2
```
SELECT * FROM user;
```
![alt text](./images/3-2.png)
## 3-3
```
SELECT COUNT(*) FROM user;
```
![alt text](./images/3-3.png)
## 3-4
```
SELECT * FROM user ORDER BY time DESC;
```
![alt text](./images/3-4.png)
## 3-5
```
Select * From user ORDER BY time DESC Limit 1,3;
```
![alt text](./images/3-5.png)
## 3-6
```
SELECT * FROM user WHERE username = 'ply';
```
![alt text](./images/3-6.png)
## 3-7
```
SELECT * FROM user WHERE username = 'ply' AND passward = 'ply';
```
![alt text](./images/3-7.png)
## 3-8
```
UPDATE user SET name = '丁滿' WHERE username = 'ply';
```
![alt text](./images/3-8.png)
## 3-9
```
DROP TABLE user;
```
## 4-1
```
SELECT message.content, user.name FROM message INNER JOIN user ON message.user_id = user.id;
```
![alt text](./images/4-1.png)
## 4-2
```
SELECT message.content, user.name FROM message INNER JOIN user ON message.user_id = user.id WHERE user.username = 'ply';
```
![alt text](./images/4-2.png)