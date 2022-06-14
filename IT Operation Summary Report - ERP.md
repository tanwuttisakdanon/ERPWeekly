# IT Operation Summary Report - 25 
##### 13 June - 17 June 2022
## **IT ERP**
## Executive summary
  
## Highlight / Important
- Mass Upload Credit Limit
## Meeting 
- E-Purchase 2 Get Requirement with Isuzu(Tripetch) Customer
- E-Purchase 2 Isuzu(Tripetch) Preparation Meeting
- RTP Sprint Planning (Sprint#2)
- Service Catelog
- Warehouse with Kerry Plan Discussion
- Asset Management Design
- IT Operation and Service Projects Review Meeting

# Operation & Service #

## *Weekly Task*

**Clear Advance Workflow**	ต้องการ Set Workflow ให้การ Clear Advance ในทุกๆกรณีผ่าน Flow ตามเงื่อนไขที่กำหนดไว้ โดยแจ้งผลการแก้ไขทุกเงื่อนไข โดยเงื่อนไขที่ 3 (ใช้เกิน) ให้ CEO อนุมัติทุกกรณี นำเสนอพร้อมกันกับ Workflow Revise เพื่อดำเนินการแก้ไขพร้อมกัน ในวันที่ 14/06/2022	**กำหนดเสร็จ** 27/05/2022(Delay)

**Credit Limit Approval**	เนื่องจากทีมการเงินได้ใช้ Approve Credit Limit ที่ทีมพัฒนาเสร็จเรียบร้อยแล้ว แต่มีความต้องการเพิ่มเติมเพื่อให้สามารถทำงานได้สะดวกมากยิ่งขึ้น จึงให้ทีมไอทีได้เพิ่มเติม	โดยแก้ไข Flow การ Approve ให้มี Sales Manager เป็น Review Level 1 และทีมการเงินจะทำการ Approve ตามลำดับขึ้นต่อไป โดยการ Approve Level 1 จะต้องแนบเอกสารสำคัญ 5 เอกสาร (กำหนดเป็น ERP Project)	**กำหนดเสร็จ** 20/06/2022(Delay)

**Credit Limit Mass Upload**	เนื่องจาก Credit Limit ของหลาย Customer ไม่ถูกต้อง ทำให้ต้องมีการปรับใหม่เพื่อให้ถูกต้อง 	Mass Update Credit Limit และ Export ข้อมูลลูกค้าที่ Credit Limit ค่าใหม่กระทบกับการเปิด Sales Order หรือ Invoice	**กำหนดเสร็จ** 17/06/2022(Delay)

**Edit Signature TBDP Report**	เนื่องจากเจ้าของลายเซ็นต์ลาออก จึงจำเป็นต้องแก้ไขลายเซ็นใน Report ที่เกี่ยวข้องเช่น Invoice และ Receipt	**กำหนดเสร็จ** 17/06/2022(Delay)

**E-Purchase**	เตรียมประชุมกับทีม Sales เพื่อหาแนวทางในการตอบลูกค้า	**กำหนดเสร็จ** 15/06/2022(Delay)

**Sales Order Template**	ทศนิยมในส่วนของราคาต่อหน่วยมีจำนวนมาก ทำให้เกิด Error ในระบบที่ไม่ถูกต้อง ทำการ Validate ไม่ให้เกิน 4 Digits	**กำหนดเสร็จ** 17/06/2022

**ตัดเบิกกาวอัตโนมัติ(Ticket#5266)**	หน่วยงานเตรียมพิมพ์มีความต้องการตัดเบิก RM กาว ต้องคุยรายละเอียดอีกครั้ง **กำหนดเสร็จ** 17/06/2022

**Printing Report**	(High Priority) Packing Slip, Invoice แต่ละต้นทางการปริ้นแสดงผลไม่เหมือนกัน อาจจะต้องเก็บข้อมูล Report ที่มีปัยหาแล้วตรวจสอบในระบบอีกครั้ง **กำหนดเสร็จ** 17/06/2022

## *CO-Project*
**WH Location Project** เปลี่ยนความต้องการเป็นส่งข้อมูล Packing Slip เพื่อใช้ยริการขนส่งกับ Kerry โดยมีงานที่ทีม ERP ต้องรับผิดชอบดังนี้ 
- Warehouse Management ส่ง Kerry Template ให้ทีม Synnex Export ข้อมูลจากระบบได้ทันที (Phase#1)
- Offset Product ใช้ Process Flow ปกติในการทำงาน แต่ต้องทำ Export Function ตามข้อมูลใน Template เพื่อนำเข้าระบบ Kerry(Phase#2)
- Digital Product (Phase#3)
ต้องมี Report Support ทีมบัญชีในการเช็ค Diff ของการ Post Invoice ข้ามเดือนกับ Packing Slip รวมถึงการแก้ไข Report as Finished Auto เพื่อให้รับยอดผลิตจากระบบ TOne และ Picking and Packing Automatically 

Note:เตรียมจัดการในรูปแบบของ Project Management

**กำหนดเสร็จ** 01/07/2022

**Delta Project** เนื่องจาก Delta Project จะ Develop ด้วย .NET Core แต่ d365lib มีบางฟังก์ชั่นไม่รองรับ .NET Core  	สรุปรายละเอียด Service ทั้งหมดที่เกี่ยวข้อง และทำคู่มือให้กับ user เรื่องการเปลี่ยนแปลง แก้ไข Route, Formula และการ Clear Route, Formula ที่ไม่ได้ใช้ (เรียบร้อยแล้ว)
https://gofivegroup.sharepoint.com/:w:/s/ITERP/EZxAPab0vBRBmDqVgfEManMBfZ97IQ4NqdXulLz4FJs93Q?e=OohSrA

## *ERP Project*
Project Name|Weekly highlight|
|---|---|
Review Service|Merging Service เรียบร้อยแล้ว เตรียมขึ้น Production กลางเดือนมิถุนายม (หลังปาล์มรับปริญญา)
Realtime Process|Go-Live (Sprint 1) and Review, Sprint Planning (Sprint#2)
Power BI & Dashboard|Planning Dashboard แก้ไข Job Monitor Offset Web เพื่อให้สามารถผลเป็น TV ได้
Workflow Revise|ออกแบบเรียบร้อยแล้ว เตรียมสรุปผลนำเสนอสำหรับ Phase#1 และ Return Advance โดยจะยังไม่มี O3 อยู่ใน Workflow แต่เป็นการ Remove Duplicated ของ Workflow และกลุ่มของการอนุมัติที่ซ้ำซ้อน (นำเสนอวันที่ 14/06/2022)
Cal Cost|ออกแบบ Flow การทำงานเรียบร้อยแล้ว เตรียมวางแผนโปรเจค
Credit Limit|Task List เรียบร้อยแล้ว เตรียมทำ Sprint Planning
Auto PO After Re-Ordering Point|เริ่มต้นโดยการระบุค่า Minimum ใน Product ที่ต้องการให้เกิดการแจ้งเตือนผ่านทาง Email กรณี Inventory Balance ลดลงมากกว่า Minimum ที่ระบุไว้
Warehouse Kerry| เตรียมออกแบบ Project Phase, Pilot Project, Dry-Run Period และ Sprint Planning 
***

**ERP Team Project Timeline 2022** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EX2NZuAgIpBFpFTJvF23FsMBTZUm4_jgncWha8bjLxFwFg

**Review Service** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EVn-UljCkdBMvWhxSOmzcdQBNdmo7WOqchaCdsBVgk1kBQ

**Realtime Process** https://gofivegroup.sharepoint.com/:x:/s/ITERP/ER92mfFxQgFEtE5Pb2HfNYABEnvz972bLcVWGrl7gYsv0A

**Power BI & Dashboard** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EVFZ6sIZdaJOi4Wl2ZRSHyUBLCkU2QoWfNoSJGRbABBBpQ

**Inter Company Automate** https://gofivegroup.sharepoint.com/:x:/s/ITERP/ETpEWdMIVltApg-ucEUJus4BQlokOP-pURXqbI7dduBFTw?e=M8w9B6

**Auto Alert** https://gofivegroup.sharepoint.com/:x:/s/ITERP/Ea-lXjTjfmVOrgntNhFBG-cB6zqoTdplq4e5mLiCVaYLaQ?e=AmlrhB

**Workflow Revise** https://gofivegroup.sharepoint.com/:x:/s/ITERP/Ed3RDwkANWNApIWMXQpN3MgBA2dJJey6NYvNlUamXv7tLg?e=Opo0tu

**Cal Cost** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EQP6swE-JjVJhVQFX9EUPfsBvvpu_B3PjsA9JcNAK17Zfg?e=6CfS4h