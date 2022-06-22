# IT Operation Summary Report - 26 
##### 20 June - 24 June 2022
## **IT ERP**
## Executive summary
  
## Highlight / Important
- Credit Limit Approval 2 Task Launch
## Meeting 
- Cal Cost Meeting with related users
- ERP Knowledge Sharing
- ERP Weekly Summary Meeting

# Operation & Service #

## *Weekly Task*

**Clear Advance Workflow**	ต้องการ Set Workflow ให้การ Clear Advance ในทุกๆกรณีผ่าน Flow ตามเงื่อนไขที่กำหนดไว้ โดยหลังจากที่นำเสนอแล้วในส่วนของ Advance Clearing สามารถทำได้ทันทีตามที่ได้ออกแบบไว้
โดยต้องมีการแจ้งให้ User ทราบก่อนจะใช้งานจริง	**กำหนดเสร็จ** 01/07/2022

**E-Purchase**	เตรียมประชุมกับทีม Sales เพื่อหาแนวทางในการตอบลูกค้า โดยล่าสุดส่ง Demo ให้กับลูกค้า ซึ่งเป็นเวอร์ชั่นที่พัฒนาล่าสุดในปัจจุบันยังไม่สามารถ Approve ได้ และยังไม่มี Feedback จากลูกค้า	**กำหนดเสร็จ** 17/06/2022

**ตัดเบิกกาวอัตโนมัติ(Ticket#5266)** การเบิกวัตถุดิบกาว ไม่ได้ตัดเบิก 100% เนื่องจากไม่ได้ใช้ทั้งหมด หน่วยงานเตรียมพิมพ์มีความต้องการตัดเบิก Raw Material กาว โดยต้องคุยรายละเอียดอีกครั้ง **กำหนดเสร็จ** 24/06/2022

**Printing Report** Packing Slip, Invoice, Receipt แต่ละต้นทางการปริ้นแสดงผลไม่เหมือนกัน อาจจะต้องเก็บข้อมูล Report ที่มีปัยหาแล้วตรวจสอบในระบบอีกครั้ง **กำหนดเสร็จ** 24/06/2022

## *CO-Project*
**WH Location Project** เปลี่ยนความต้องการเป็นส่งข้อมูล Packing Slip เพื่อใช้ยริการขนส่งกับ Kerry โดยมีงานที่ทีม ERP ต้องรับผิดชอบดังนี้ 
- (Phase#1)Warehouse Management ส่ง Kerry Template ให้ทีม Synnex Export ข้อมูลจากระบบได้ทันที 
- (Phase#2)Offset Product ใช้ Process Flow ปกติในการทำงาน แต่ต้องทำ Export Function ตามข้อมูลใน Template เพื่อนำเข้าระบบ Kerry
- (Phase#3)Digital Product 
ต้องมี Report Support ทีมบัญชีในการเช็ค Diff ของการ Post Invoice ข้ามเดือนกับ Packing Slip รวมถึงการแก้ไข Report as Finished Auto เพื่อให้รับยอดผลิตจากระบบ TOne และ Picking and Packing Automatically 

**กำหนดเสร็จ** 01/07/2022

**Delta Project** เนื่องจาก Delta Project จะ Develop ด้วย .NET Core แต่ d365lib มีบางฟังก์ชั่นไม่รองรับ .NET Core  	สรุปรายละเอียด Service ทั้งหมดที่เกี่ยวข้อง และทำคู่มือให้กับ user เรื่องการเปลี่ยนแปลง แก้ไข Route, Formula และการ Clear Route, Formula ที่ไม่ได้ใช้ (เรียบร้อยแล้ว)
https://gofivegroup.sharepoint.com/:w:/s/ITERP/EZxAPab0vBRBmDqVgfEManMBfZ97IQ4NqdXulLz4FJs93Q?e=OohSrA

## *ERP Project*
Project Name|Weekly highlight|
|---|---|
Review Service|Merging Service เรียบร้อยแล้ว เตรียมขึ้น Production สิ้นเดือนมิถุนายน
Realtime Process|Sprint#1 - Closed, Sprint#2 - In Progress 
Power BI & Dashboard|Planning Dashboard ยังขาดรูปเครื่องจักร รอ Deploy กำหนดเสร็จ 24/06/2022
Workflow Revise| ดำเนินการสร้าง Return Advance Workflow และ ปรับเปลี่ยนการอนุมัติเป็นแบบขั้นบันไดและยุบรววม Workflow ในส่วนของ PR/PO
Cal Cost|ประชุมครั้งที่ 1(20/06/2022) กับทีมที่เกี่ยวข้องแล้ว พบว่าต้องสอนการใช้งานทั้งหมดใหม่ รวมถึงมีการแก้ไขบางส่วนเพื่อให้ใช้งานได้สะดวกมากยิ่งขึ้น ประชุมครั้งที่ 2(23/06/2022) เพิ่มเติมกับทีมบัญชี
Credit Limit|กำลังพัฒนาเรื่องวงเงินชั่วคราว กำหนดเสร็จ 27/06/2022
Warehouse Kerry| Phase 1 กำลังพัฒนาและตรวจสอบ Template กำหนดเสร็จ 27/06/2022
***

**ERP Team Project Timeline 2022** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EX2NZuAgIpBFpFTJvF23FsMBTZUm4_jgncWha8bjLxFwFg

**Review Service** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EVn-UljCkdBMvWhxSOmzcdQBNdmo7WOqchaCdsBVgk1kBQ

**Realtime Process** https://gofivegroup.sharepoint.com/:x:/s/ITERP/ER92mfFxQgFEtE5Pb2HfNYABEnvz972bLcVWGrl7gYsv0A

**Power BI & Dashboard** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EVFZ6sIZdaJOi4Wl2ZRSHyUBLCkU2QoWfNoSJGRbABBBpQ

**Inter Company Automate** https://gofivegroup.sharepoint.com/:x:/s/ITERP/ETpEWdMIVltApg-ucEUJus4BQlokOP-pURXqbI7dduBFTw?e=M8w9B6

**Auto Alert** https://gofivegroup.sharepoint.com/:x:/s/ITERP/Ea-lXjTjfmVOrgntNhFBG-cB6zqoTdplq4e5mLiCVaYLaQ?e=AmlrhB

**Workflow Revise** https://gofivegroup.sharepoint.com/:x:/s/ITERP/Ed3RDwkANWNApIWMXQpN3MgBA2dJJey6NYvNlUamXv7tLg?e=Opo0tu

**Cal Cost** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EQP6swE-JjVJhVQFX9EUPfsBvvpu_B3PjsA9JcNAK17Zfg?e=6CfS4h

**Warehouse** https://sharing.clickup.com/25655989/l/h/5-108838434-1/ad056f5b6c79f00


