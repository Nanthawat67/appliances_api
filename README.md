# Lab10-Web-API

67543210037-7 ปวริศ​ คูณศรี
## การใช้งาน

### READ (GET) อ่าน/ค้นหาข้อมูลสินค้า
#### ดึงข้อมูลสินค้าทั้งหมด
Method GET
/api/appliances 
ดึงสินค้าทั้งหมด
<img width="850" height="892" alt="image" src="https://github.com/user-attachments/assets/bf100cb5-5017-49ff-b639-8374427d3a87" />

ตัวอย่างการทำงาน

#### ดึงข้อมูลสินค้าทีละรายการตาม ID
Method GET
/api/appliances/{id} 
ดึงข้อมูลสินค้าตาม ID 
<img width="617" height="579" alt="image" src="https://github.com/user-attachments/assets/e3b50474-331d-485b-b3f8-18d505320723" />

ตัวอย่างการทำงาน

### CREATE(POST) - สร้างสินค้าใหม่
Method POST
api/appliances 
สร้างสินค้าใหม่ โดยใส่ข้อมูล JSON ลงใน BODY
<img width="3600" height="2214" alt="image" src="https://github.com/user-attachments/assets/a317d756-515e-451b-ace1-46fe1eb68561" />
ตัวอย่างการทำงาน

### UPDATE(PUT/PATCH) - แก้ไขสินค้า
Method PUT/PATCH
/api/appliances/{id}
แก้ไขข้อมูลสินค้าตาม ID
<img width="3600" height="2214" alt="image" src="https://github.com/user-attachments/assets/9f80c8fc-07fc-4e05-a63c-023c068100b8" />
ตัวอย่างการทำงาน

### DELETE(DELETE) - ลบสินค้า
Method DELETE 
api/appliances/{id}
ลบสินค้าตาม ID
<img width="3600" height="2214" alt="image" src="https://github.com/user-attachments/assets/0a129631-1602-4d2f-a283-c6cb43ceb888" />
ตัวอย่างการทำงาน เมื่อทำการลบแล้วจะได้ respond กลับมาเป็น data ซึ่งโดนลบไปแล้วเลยแสดงผลว่า null

