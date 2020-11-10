---
title: "Lab 5. Tải và cài đặt Mongo trên Docker"
date: 2020-11-10T07:30:17+07:00

---
### Tải và cài đặt Mongo trên docker
- Tải image mongo 
```
docker pull mongo
```

- Kiểm tra image có trong docker
```
docker image ls
``` 

- Chạy docker container
```
docker run --name mongo -p 27016:27017 -d mongo
```

- Để khởi động container đã được tạo
```
docker exec -it mongo bash
```


- Chú ý: lệnh trên để cổng 27016 để ko bị trùng với cổng mongo chính

- Kiểm tra kết nối với 3tmongo
