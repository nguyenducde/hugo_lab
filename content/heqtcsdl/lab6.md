---
title: "Lab 6. Tải và cài đặt MySQL trên Docker"
date: 2020-11-10T07:30:20+07:00

---
### Tải và cài đặt Mysql trên docker
- Tải image mysql
```
docker pull mysql
```

- Chạy docker container
```
docker run — name=mysqldb -e MYSQL_ROOT_PASSWORD=123456 -e MYSQL_DATABASE=quanlysinhvien -p 3305:3306 -d mysql
```

- username: root
- password: 12345678
- database: quanlysinhvien
- port: 3305

- Thử kết nối với MysqlWordbench
