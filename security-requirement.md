# 5.1.3 Input Validation

**[Details](https://owasp.org/www-project-application-security-verification-standard)**
- Verify that all input (HTML form fields, REST requests, URL parameters, HTTPheaders, cookies, batch files, RSS feeds, etc) is validated using positivevalidation (allow lists). 



 **[Chat GPT](chatgpt.com)**
- ตรวจสอบให้แน่ใจว่าทุกการป้อนข้อมูล (ฟอร์ม HTML, คำขอ REST, พารามิเตอร์ URL, หัวข้อ HTTP, คุกกี้, ไฟล์ชุดคำสั่ง, ฟีด RSS, ฯลฯ) ได้รับการตรวจสอบโดยใช้การตรวจสอบเชิงบวก (allow lists) 



**[Gemini](gemini.google.com)**
- การตรวจสอบว่าข้อมูลป้อนเข้าทั้งหมด (ช่องแบบฟอร์ม HTML, คำขอ REST, พารามิเตอร์ URL, ส่วนหัว HTTP, คุกกี้, ไฟล์แบทช์, ฟีด RSS ฯลฯ) ได้รับการตรวจสอบโดยใช้การตรวจสอบเชิงบวก (รายการที่อนุญาต)


**Summary**
- การตรวจสอบข้อมูลที่เข้ามาทุกประเภท (เช่น จากฟอร์ม, การร้องขอ API, พารามิเตอร์ URL, คุกกี้ หรือไฟล์ต่างๆ) ควรตรวจสอบให้แน่ใจว่าอนุญาตเฉพาะข้อมูลที่ถูกต้องและปลอดภัย (โดยใช้รายการที่อนุญาตหรือ "allow list") แทนการแค่บล็อกรายการที่ไม่ถูกต้องหรืออันตราย (ที่เรียกว่า "block list")


**Example**
- การใช้รหัสผ่าน (Password):
- Allow list เมื่อคุณตั้งรหัสผ่าน คุณจะต้องสร้างรหัสผ่านที่มีตัวอักษร, ตัวเลข, และสัญลักษณ์บางตัวเท่านั้น เช่น "A1b#4D" ซึ่งเป็นการตั้งค่าที่อนุญาตเฉพาะการใช้คาแร็กเตอร์ที่ปลอดภัยตามที่ระบบกำหนด

 
**Members**

[6530250093 ธนพัฒน์ อุไรวงษ์]

[6530200835 สรสิช ปัญญางค์]
