AI Impact On Job 2030: Occupational Risk Assessment System (Revised)
Course: Machine Learning
Instructor: Dr. Somsawat Nindam (ดร.สมสวัสดิ์ นิลดำ) 
Department: Digital Science and Technology, Faculty of Science at Sriracha, Kasetsart University
---------------------------------------
 Revision Summary 
โปรเจกต์นี้ได้รับการปรับปรุงเนื้อหาและแบบจำลองตามคำแนะนำของอาจารย์ในหัวข้อหลักดังนี้:
Academic Threshold (0.30): ปรับเกณฑ์การแจ้งเตือน (Decision Threshold) มาที่ 0.30 (30%) โดยอ้างอิงมาตรฐานจากงานวิจัยของ Frey & Osborne (Oxford University, 2013) ที่ระบุว่าอาชีพกลุ่มเสี่ยงต่ำ (Low Risk) ต้องมีโอกาสถูกแทนที่น้อยกว่า 0.3 
Target Leakage Handling: กำจัดปัญหาข้อมูลเฉลยรั่วไหล (Data Leakage) โดยการตัดฟีเจอร์ Automation_Probability ออกจากการฝึกสอน เพื่อให้แบบจำลองเรียนรู้จากพฤติกรรมจริงและใช้งานกับข้อมูลใหม่ได้ (Real-world Generalization) 
Class Imbalance Mitigation: ใช้เทคนิค Balanced Random Forest (Cost-Sensitive Learning) เพื่อแก้ปัญหาความไม่สมดุลของข้อมูล ทำให้แบบจำลองสามารถทำนายกลุ่ม High Risk ได้อย่างยุติธรรมและแม่นยำขึ้น 
---------------------------------------
roject Structure
📂 Report/: Ai_impact_On_Job_Report.pdf - เล่มรายงานฉบับสมบูรณ์ที่ปรับปรุงแล้ว
📂 Code/: AI_Impact_On_Jobs.ipynb - Source Code แสดงขั้นตอนการทำ Preprocessing, Training และ Threshold Tuning
📂 Presentation/: Ai_impact_on_job_presentation.pdf - สไลด์ประกอบการนำเสนอ
📂 References/: รวบรวม Paper อ้างอิงระดับโลกที่ใช้ในโปรเจกต์ (Frey & Osborne, 2013 และ Elkan, 2001)
---------------------------------------
Group Members (Team 4)
Name                    Student ID
นายสุทธิรักษ์ พิมสุข        6630202783
นายธนุส คำพิทักษ์         6630202325
นายพงศกร ดวงปัญญา      6630202538
นายธัชพล แก้ววิลัย        6630202341
