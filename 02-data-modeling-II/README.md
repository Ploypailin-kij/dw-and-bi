# Instruction

1. เข้าไปที่ path ของ folder 02-data-modelling-ii
```sh
$ cd 02-data-modeling-II
```

2. สร้าง ENV เพื่อรองรับการการติดตั้ง Library 
```sh
$ python -m venv env 
```

3. run คำสั่ง Activate ENV
```sh
$ source env/bin/activate
```

4. Install Library ที่เกี่ยวข้องกับการใช้งาน
```sh
$ pip install -r requirements.txt
```

5. Run Docker เพื่อใช้งาน Cassandra
```sh
$ docker compose up
```

6. สามารถจัดการการ Create Table/ Insert/ Update Data ผ่าน script etl.py  
```sh
$ python ety.py
```


#Shutdown steps

7. stop Cassandra service by shutdown Docker:
```sh
$ docker-compose down
```

8. deactivate the visual environment:
```sh
$ deactivate
```