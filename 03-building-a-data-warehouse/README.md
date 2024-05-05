## Instruction
1. เข้าไปที่ path ของ folder 03-building-a-data-warehouse
```sh
$ cd 03-building-a-data-warehouse

2. สร้าง ENV สำหรับติดตั้ง Library
```sh
$ python -m venv env 

3. run คำสั่ง Activate ENV
```sh
$ source env/bin/activate

4. Install Library ที่เกี่ยวข้องกับการใช้งาน
```sh
$ pip install -r requirements.txt

5. Create Key ใน Google query เพื่อใช้ในการสร้าง Scipt python เพื่อ Google bigquery ได้

6. หลังจากนั้นดาวน์โหลดไฟล์ JSON เก็บไว้ใน Local Storage

7. ใน Google query ให้สร้าง Folder จัดเก็บไฟล์ JSON ใน code space และใส่ project_id ที่มาจาก project name บน Bigquery 

8. สามารถจัดการการ Create Table/ Insert/ Update Data ผ่าน script etl.py โดยกำหนด file_path = github_detail.csv และ ใช้ข้อมูล github_events_01.json
```sh
$ python etl.py
