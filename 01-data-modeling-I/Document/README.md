# Instruction
1. เข้าไปที่ path ของ folder 01-data-modeling-i
```sh
$ cd 01-data-modeling-i/
```
2. รันคำสั่งเชื่อมต่อ Database
```sh
$ docker-compose up
``` 
3. เปิด Port 8080 เข้า Database ด้วยรหัสที่อยู่ในไฟล์ docker-compose.yml
4. รันคำสั่งสร้าง Table บน Database
```sh
$ python create_tables.py
``` 
5. รันคำสั่งโหลดข้อมูลจาก JSON File เข้า Table
```sh
$ python etl.py
``` 

