# AI Impact On Job 2030: Occupational Risk Assessment System
### Course: Machine Learning (2026)

**Instructor:** Dr. Somsawat Nindam (ดร.สมสวัสดิ์ นิลดำ)  
**Department:** Digital Science and Technology, Faculty of Science at Sriracha, Kasetsart University 

---

## Revision Summary (แก้ไขตามคำแนะนำของอาจารย์)
โปรเจกต์นี้ได้รับการปรับปรุงเนื้อหาและแบบจำลองตามข้อเสนอแนะ เพื่อความถูกต้องแม่นยำในระดับมาตรฐานวิชาการ:

* **Academic Threshold (0.30):** ปรับเกณฑ์การตัดสินใจ (Decision Threshold) มาที่ **0.30 (30%)** โดยอ้างอิงมาตรฐานจากงานวิจัยระดับโลกของ **Frey & Osborne (Oxford University, 2013)** ที่ระบุว่าอาชีพกลุ่มเสี่ยงต่ำ (Low Risk) ต้องมีโอกาสถูกแทนที่น้อยกว่า 0.3
* **Target Leakage Handling:** กำจัดปัญหาข้อมูลเฉลยรั่วไหล (Data Leakage) โดยการตัดฟีเจอร์ `Automation_Probability` ออกจากการฝึกสอน เพื่อให้แบบจำลองเรียนรู้จากพฤติกรรมจริง (Real-world Generalization)
* **Class Imbalance Mitigation:** ใช้เทคนิค **Balanced Random Forest (Cost-Sensitive Learning)** เพื่อแก้ปัญหาความไม่สมดุลของข้อมูล ทำให้แบบจำลองทำนายกลุ่มเสี่ยงสูง (High Risk) ได้อย่างยุติธรรม

---

## Project Structure
[cite_start]เพื่อให้ง่ายต่อการตรวจสอบและประเมินผล คณะผู้จัดทำได้จัดสัดส่วนไฟล์ดังนี้: 

| ส่วนงาน | ไฟล์อ้างอิง | คำอธิบาย |
| :--- | :--- | :--- |
| **Report** | [Ai_impact_On_Job_Report.pdf](./Ai_impact_On_Job_Report.pdf) | เล่มรายงานฉบับสมบูรณ์ที่ปรับปรุงเนื้อหาใหม่  |
| **Source Code** | [AI_Impact_On_Jobs.ipynb](./AI_Impact_On_Jobs.ipynb) |
| **Presentation** | [Ai_impact_on_job_presentation.pdf](./AI_impact_on_job_presentation.pdf) | สไลด์สรุปเนื้อหาประกอบการนำเสนอ  |
| **References** | [Paper_The_Future_of_Employment.pdf](./Paper_The_Future_of_Employment.pdf) | งานวิจัยอ้างอิงจาก Oxford |
| **References** | [Paper_rescale.pdf](./Paper_rescale.pdf) | งานวิจัยอ้างอิงจากทฤษฎี Cost-Sensitive Learning|


---

## Group Members (Team 4)
| รายชื่อสมาชิก | รหัสนิสิต |
| :--- | :--- |
| **นายสุทธิรักษ์ พิมสุข** | 6630202783 |
| **นายธนุส คำพิทักษ์** | 6630202325 |
| **นายพงศกร ดวงปัญญา** | 6630202538 |
| **นายธัชพล แก้ววิลัย** | 6630202341 |
