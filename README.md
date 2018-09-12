# 3SA03-React

ขั้นตอนเริ่มต้น การสร้างโฟลเดอร์ .git ใน local ของเรา

git init

การเชื่อมต่อ local กับ Repository โดยการใช้ remote

git remote add origin "yourRepo"

การเพิ่มไฟล์เข้าไปใน Repository | สามารถใช้ . แทนที่ชื่อไฟล์ จะเป็นการเพิ่มไฟล์ทั้งหมด

git add README.md

การเก็บข้อมูล

git commit -m "Your Comment"

การส่งข้อมูลจาก Local ไปยัง Repository | -u คือ จำ parameter origin master เอาไว้

git push -u origin master

การดึงข้อมูลจาก Repository มายัง Local

git pull 

#Basic Git Commands

ดึงข้อมูลจาก Server มายังเครื่อง

$ git clone "repo"

เชื่อมต่อ Local กับ Git Server

$ git remote add origin "repo" 

การตรวจสอบสถานะ

$ git status

การเพิ่มไฟล์ ถ้าใช้ . จะเพิ่มไฟล์ทั้งหมด จะได้สถานะ ติดตาม

$ git add file

การเก็บไฟล์

$ git commit -m "Comment"

ส่งไปยัง Server

$ git push -u origin master   | * ครั้งต่อไปใช้แค่ git push 
