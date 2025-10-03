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
<img width="577" height="709" alt="image" src="https://github.com/user-attachments/assets/68d799fa-066b-4deb-b2a1-598bee1177ac" />

ตัวอย่างการทำงาน

### UPDATE(PUT/PATCH) - แก้ไขสินค้า
Method PUT/PATCH
/api/appliances/{id}
แก้ไขข้อมูลสินค้าตาม ID
<img width="777" height="737" alt="image" src="https://github.com/user-attachments/assets/83989ca9-9f79-4205-a08e-cf3f917b08cd" />

ตัวอย่างการทำงาน

### DELETE(DELETE) - ลบสินค้า
Method DELETE 
api/appliances/{id}
ลบสินค้าตาม ID
<img width="616" height="729" alt="image" src="https://github.com/user-attachments/assets/8f3b5dd1-0f88-4cfa-b633-d1ee63884227" />

ตัวอย่างการทำงาน เมื่อทำการลบแล้วจะได้ respond กลับมาเป็น data ซึ่งโดนลบไปแล้วเลยแสดงผลว่า null

