# Multi-condition coverage

| แหล่งที่มา                              | คำอธิบาย                                                                                              |
|-----------------------------------------|-------------------------------------------------------------------------------------------------------|
| [CISPP Glossy - Student Guide](https://www.isc2.org/certifications/cissp/cissp-student-glossary) | These criteria require sufficient test cases to exercise all possible combinations of conditions in a program decision. |
| Chat GPT | เกณฑ์เหล่านี้ต้องการกรณีทดสอบที่เพียงพอเพื่อทดสอบทุกการผสมผสานที่เป็นไปได้ของเงื่อนไขในคำตัดสินของโปรแกรม |
| Gemini | เกณฑ์เหล่านี้กำหนดให้มีกรณีทดสอบเพียงพอเพื่อทดสอบทุก ๆ การรวมกันของเงื่อนไขที่เป็นไปได้ในคำตัดสินใจของโปรแกรม |
| [Qt Group](https://www.qt.io/product/quality-assurance/coco/feature-multiple-condition-coverage-mcc) | In the MCC coverage metric, all statements must be executed and all combinations of truth values in each decision must occur at least once to reach full coverage. The coverage of a program is the number of executed statement blocks and condition combinations divided by their total number in the program. |
| Chat GPT | ในเกณฑ์ Multiple Condition Coverage (MCC) ทุกคำสั่งในโปรแกรมต้องได้รับการดำเนินการ และการผสมผสานของค่าความจริงในแต่ละคำตัดสินต้องเกิดขึ้นอย่างน้อยหนึ่งครั้งเพื่อให้ครอบคลุมทั้งหมด การครอบคลุมของโปรแกรมจะคำนวณจากจำนวนบล็อกคำสั่งที่ดำเนินการและการผสมผสานของเงื่อนไขที่เกิดขึ้น แบ่งด้วยจำนวนทั้งหมดของคำสั่งและการผสมผสานในโปรแกรม |
| Gemini | ในเมตริกการครอบคลุม MCC (Modified Condition/Decision Coverage) คำสั่งทั้งหมดจะต้องถูกเรียกใช้งาน และการรวมกันของค่าความจริงในแต่ละเงื่อนไขจะต้องเกิดขึ้นอย่างน้อยหนึ่งครั้งเพื่อให้ครอบคลุมเต็มที่ การครอบคลุมของโปรแกรมคือจำนวนของบล็อกคำสั่งและการรวมกันของเงื่อนไขที่ถูกเรียกใช้งาน หารด้วยจำนวนทั้งหมดของบล็อกคำสั่งและการรวมกันของเงื่อนไขในโปรแกรม |
| MySelf                                  | เป็นหลักเกณฑ์ที่ใช้ในการทดสอบซอฟต์แวร์ โดยเน้นการตรวจสอบทุกเงื่อนไขที่สามารถทำได้ เพื่อให้มั่นใจว่าการทำงานของซอฟต์แวร์ครอบคลุมทุกการทำงาน ลดโอกาสเกิดข้อผิดพลาดให้ได้มากที่สุด |
| Sample in Daily Life                   | สามารถนําไปใช้ประยุกต์ในชีวิตประจําวันได้พวก การตัดสินใจ การแก้ปัญหา เช่น การตัดสินใจการลงทะเบียนเรียน การจองตั๋วหนัง การเลือกซื้อสินค้า การจัดการเวลา |

# [Pichanat](https://naieric.github.io/multi-condition-coverage)
