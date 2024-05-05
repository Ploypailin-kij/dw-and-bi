Instruction

1. เข้าไปที่ path ของ folder 02-data-modelling-ii
```
$ cd 02-data-modelling-II
```
2. สร้าง ENV เพื่อรองรับการการติดตั้ง Library ให้เหมาะสมกับงาน
```
$ python -m venv env 
```
3. run คำสั่ง ENV Activate
```
$ source env/bin/activate
```
4. Install Library ที่เกี่ยวข้องกับการใช้งาน
```
$ pip install -r requirements.txt
```
5. เริ่มการใช้งาน Cassandra ด้วย Docker
```
$ docker compose up
```
6. หากต้องการสร้าง table, เพิ่มข้อมูล, Query ข้อมูล สามารถทำได้ใน etl.py
```
$ python ety.py
```
