# 3SB04_Django

LAB DJANGO 
สิ่งที่เรียนรู้

- ทำการสร้าง virtual environment ของ python ขึ้นมา บน linux โดยการติดตั้ง PYTHON
จากนั้นใช้ commanf python3 -m venv myvenv เพื่อสร้างสภาพแวดล้อมจำลองขึ้นมาก จะได้แยกการทำงานในไฟล์ requirement.txt ออกจากกันได้

โดยเราจะใส่ Django ลงไปใน requirement.txt แล้ว install 

ก็จะได้ Django framwork มาให้ใช้งาน

เมื่อ install เรียบร้อย เราต้องทำการ สร้างโปรเจค ซึ่งโครงสร้างโปรเจคจะมีหลักๆดังนั้น

1. manage.py คือไฟล์ script สำหรับรันคำสั่งต่างๆ ที่เกี่ยวข้องกับ Django เช่น Run Server , Collectstatic , Model & Migration เป็นต้น
2. __init__.py คือ initial ไฟล์หรือไฟล์เปล่าๆมีไว้เก็บ Python Package เราสามารถเพิ่ม Script การทำงานเข้าไปในไฟล์นี้ได้
3. settings.py คือไฟล์ที่ใช้สำหรับการตั้งค่าโปรเจคเช่น การตั้งค่าแอพ , เวลา , Path,ฐานข้อมูลที่ใช้ เป็นต้น
4. urls.py คือไฟล์ที่ใช้เก็บการ routing ของ HTTP request หรือเรียกอีกอย่างว่าการกำหนด url pattern ของ django project
5. wsgi.py คือไฟล์ที่ใช้เก็บข้อมูลโปรเจคสำหรับการ Deployment (Production)


Model คือส่วนที่เก็บข้อมูลของ Application
View สำหรับประมวลผลคำสั่งหรือข้อมูลต่างๆ (เหมือนกับ Controller) แล้วโยนไปแสดงผลตรงส่วนของ Template
Template คือหน้าตา Application เป็นส่วนที่ไว้ใช้แสดงผลข้อมูลผลลัพธ์จากการประมวลผลใน View มาแสดงผลในหน้าเว็บร่วมกับ HTML


