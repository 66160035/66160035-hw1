# 66160035-hw1
## git command used in this lab
หน้าแรก
git checkout -b development
git add .
git commit -m "สร้างโครงสร้างโปรเจคเริ่มต้น"
git checkout -b feature/home-page
git add index.html
git commit -m "หน้าหลัก" 
git add index.html
git commit -m "เพิ่มรูปและส่วนท้าย"
git add index.html
git commit -m "หน้าHomeที่แก้ไขแล้ว" 
git add css/style.css
git commit -m "เพิ่มcssพื้นฐาน"
git add css/style.css  
git commit -m "เพิ่ม animation"
git add css/style.css
git commit -m "Hover Effects"
git add index.html
git commit -m "เพิ่มไฮไลท์" 
git add css/style.css
git commit -m "แก้ไขเพื่อเพิ่มไฮไลท์ในหน้าหลัก"

หน้ารายละเอียด
git checkout development
git checkout -b feature/detail-page
git add detail.html
git commit -m "เพิ่มรายละเอียด1"
git add detail.html
git commit -m "เพิ่มรายละเอียด2"
git add detail.html
git commit -m "เพิ่มรายละเอียด3"
git add detail.html
git commit -m "เพิ่มรายละเอียด4"
git add detail.html
git commit -m "เพิ่มรายละเอียด5"
git add "Bamboo arch.jpg"
git add "khao.jpg"
git add "khundan.jpg"
git add "nangrong.jpg"
git add "watlek.jpg"
git add css/style.css
git add detail.html
git commit -m "หน้ารายละเอียด"
git checkout development

หน้าติดต่อ
git checkout -b feature/contact-page
git add contact.html 
git commit -m "สร้างโครงสร้างพื้นฐานหน้าติดต่อ"
git add contact.html
git commit -m "เพิ่มฟอร์ม"  
git add contact.html      
git commit -m "เพิ่ม validation"
git add contact.html
git commit -m "เพิ่ม ARIA labels ในฟอร์ม"
git add contact.html
git commit -m "เพิ่ม ARIA landmarks ในการนําทาง"
git add css/style.css
git commit -m "styleหน้าลายละเอียด" 
git add contact.html
git commit -m "หน้ารายละเอียด"  
git checkout development 
git merge feature/home-page
git merge feature/about-page
git merge feature/contact-page 
git push origin development