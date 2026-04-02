# CS372_MiniProject_2_Association_Rule_Mining

**จัดทำโดย**
* ธนภูมิ พลเมืองดี รหัสนักศึกษา 6609611972
* พฤกษ์ ฤกขะวุฒิกุล รหัสนักศึกษา 6609612137
* สุภนัย จิรกาลกุล รหัสนักศึกษา 6609612269

## **ตารางคำอธิบายตัวแปร (Data Dictionary)**

### 📊 Data Dictionary (ตารางคำอธิบายตัวแปร)

| ลำดับ | ชื่อคอลัมน์ | ประเภทข้อมูล | บทบาท | รายละเอียด / ความหมาย |
| :---: | :--- | :--- | :--- | :--- |
| 1 | **id** | Numeric (Integer) | Identifier | รหัสอ้างอิงของแต่ละรายการซื้อ (Transaction ID) ใช้สำหรับระบุแต่ละบิล |
| 2 | **Apple** | Categorical (Boolean) | Feature | ข้อมูลการซื้อแอปเปิล: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 3 | **Bread** | Categorical (Boolean) | Feature | ข้อมูลการซื้อขนมปัง: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 4 | **Butter** | Categorical (Boolean) | Feature | ข้อมูลการซื้อเนย: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 5 | **Cheese** | Categorical (Boolean) | Feature | ข้อมูลการซื้อชีส: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 6 | **Corn** | Categorical (Boolean) | Feature | ข้อมูลการซื้อข้าวโพด: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 7 | **Dill** | Categorical (Boolean) | Feature | ข้อมูลการซื้อผักชีลาว: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 8 | **Eggs** | Categorical (Boolean) | Feature | ข้อมูลการซื้อไข่ไก่: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 9 | **Ice cream** | Categorical (Boolean) | Feature | ข้อมูลการซื้อไอศกรีม: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 10 | **Kidney Beans** | Categorical (Boolean) | Feature | ข้อมูลการซื้อถั่วแดง: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 11 | **Milk** | Categorical (Boolean) | Feature | ข้อมูลการซื้อนม: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 12 | **Nutmeg** | Categorical (Boolean) | Feature | ข้อมูลการซื้อลูกจันทน์เทศ: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 13 | **Onion** | Categorical (Boolean) | Feature | ข้อมูลการซื้อหัวหอม: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 14 | **Sugar** | Categorical (Boolean) | Feature | ข้อมูลการซื้อน้ำตาล: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 15 | **Unicorn** | Categorical (Boolean) | Feature | ข้อมูลการซื้อยูนิคอร์น (สินค้าจำลอง/ของเล่น): `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 16 | **Yogurt** | Categorical (Boolean) | Feature | ข้อมูลการซื้อโยเกิร์ต: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
| 17 | **chocolate** | Categorical (Boolean) | Feature | ข้อมูลการซื้อช็อกโกแลต: `True` (ซื้อ) หรือ `False` (ไม่ซื้อ) |
