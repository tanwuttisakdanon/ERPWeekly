# IT Operation Summary Report -23 
##### 29 May - 3 June 2022
## **IT ERP**
## Executive summary
  
## Highlight / Important
- Go-Live Realtime Process (Sprint#1) โดย User ที่เกี่ยวข้องสามารถใช้งานได้ตามที่ออกแบบไว้ สามารถลดการรับส่งเอกสารผ่านระบบ Dynamics 365 ได้อย่างถูกต้อง
## Meeting 
- IA Meeting with HR เพื่อปิดการตรวจ Workflow
- Go-Live & Demo Realtime Process Meeting (Sprint#1)
- Requirement Discussion Realtime Process Meeting (Sprint#2)
- New Workflow Presentation Prepare
- Wrapup Credit Limit Project
- Wrapup Realtime Process (Sprint#2)
- ERP Weekly Summary Meeting
# Operation & Service #

## *Weekly Task*
**Control Version**	DEV Server (.204) ไม่สามารถเชื่อต่อ Azure ได้ แก้ไขโดยการ 	**กำหนดเสร็จ** 27/05/2022(Delay)

**Clear Advance Workflow**	ต้องการ Set Workflow ให้การ Clear Advance ในทุกๆกรณีผ่าน Flow ตามเงื่อนไขที่กำหนดไว้ โดยแจ้งผลการแก้ไขทุกเงื่อนไข โดยเงื่อนไขที่ 3 (ใช้เกิน) ให้ CEO อนุมัติทุกกรณี	**กำหนดเสร็จ** 27/05/2022(Delay)

**Credit Limit Approval**	เนื่องจากทีมการเงินได้ใช้ Approve Credit Limit ที่ทีมพัฒนาเสร็จเรียบร้อยแล้ว แต่มีความต้องการเพิ่มเติมเพื่อให้สามารถทำงานได้สะดวกมากยิ่งขึ้น จึงให้ทีมไอทีได้เพิ่มเติม	โดยแก้ไข Flow การ Approve ให้มี Sales Manager เป็น Review Level 1 และทีมการเงินจะทำการ Approve ตามลำดับขึ้นต่อไป โดยการ Approve Level 1 จะต้องแนบเอกสารสำคัญ 5 เอกสาร	**กำหนดเสร็จ** 17/06/2022(Delay)

**Credit Limit Mass Upload**	เนื่องจาก Credit Limit ของหลาย Customer ไม่ถูกต้อง ทำให้ต้องมีการปรับใหม่เพื่อให้ถูกต้อง 	Mass Update Credit Limit และ Export ข้อมูลลูกค้าที่ Credit Limit ค่าใหม่กระทบกับการเปิด Sales Order หรือ Invoice	**กำหนดเสร็จ** 04/06/2022

## *CO-Project*
**WH Location Project** ปรับการขนส่งทุก BU เข้าระบบ Dynamics 365 เพื่อนำส่งกับ Kerry Express ซึ่งรอสรุปแผนจากทีม Project Coordinator อีกครั้ง

**Delta Project** เนื่องจาก Delta Project จะ Develop ด้วย .NET Core แต่ d365lib มีบางฟังก์ชั่นไม่รองรับ .NET Core  	สรุปรายละเอียด Service ทั้งหมดที่เกี่ยวข้อง และทำคู่มือให้กับ user เรื่องการเปลี่ยนแปลง แก้ไข Route, Formula และการ clear Route, Formula ที่ไม่ได้ใช้ 
https://gofivegroup.sharepoint.com/:w:/s/ITERP/EZxAPab0vBRBmDqVgfEManMBfZ97IQ4NqdXulLz4FJs93Q?e=OohSrA

## *ERP Project*
Project Name|Weekly highlight|
|---|---|
Review Service|Merging Service เรียบร้อยแล้ว เตรียมทดสอบใน UAT แล้วขึ้น Production ปลายเดือน
Realtime Process|เตรียม Go-Live (Sprint 1)
Power BI & Dashboard|Planning Dashboard (Ham) ปรับ Query ภาพเครื่องจักร รันทุกๆ 10 นาที
Inter Company Automate|Go-Live
Auto Alert|Go-Live and Review in production server
Workflow Revise|ออกแบบเรียบร้อยแล้ว เตรียมสรุปผลนำเสนอสำหรับ Phase#1 โดยจะยังไม่มี O3 อยู่ใน Workflow แต่เป็นการ Remove Duplicated ของ Workflow และกลุ่มของการอนุมัติที่ซ้ำซ้อน (นำเสนอวันที่ 06/06/2022)
Cal Cost|ออกแบบ Flow การทำงานเรียบร้อยแล้ว เตรียมวางแผนโปรเจค

**ERP Team Project Timeline 2022** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EX2NZuAgIpBFpFTJvF23FsMBTZUm4_jgncWha8bjLxFwFg

**Review Service** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EVn-UljCkdBMvWhxSOmzcdQBNdmo7WOqchaCdsBVgk1kBQ

**Realtime Process** https://gofivegroup.sharepoint.com/:x:/s/ITERP/ER92mfFxQgFEtE5Pb2HfNYABEnvz972bLcVWGrl7gYsv0A

**Power BI & Dashboard** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EVFZ6sIZdaJOi4Wl2ZRSHyUBLCkU2QoWfNoSJGRbABBBpQ

**Inter Company Automate** https://gofivegroup.sharepoint.com/:x:/s/ITERP/ETpEWdMIVltApg-ucEUJus4BQlokOP-pURXqbI7dduBFTw?e=M8w9B6

**Auto Alert** https://gofivegroup.sharepoint.com/:x:/s/ITERP/Ea-lXjTjfmVOrgntNhFBG-cB6zqoTdplq4e5mLiCVaYLaQ?e=AmlrhB

**Workflow Revise** https://gofivegroup.sharepoint.com/:x:/s/ITERP/Ed3RDwkANWNApIWMXQpN3MgBA2dJJey6NYvNlUamXv7tLg?e=Opo0tu

**Cal Cost** https://gofivegroup.sharepoint.com/:x:/s/ITERP/EQP6swE-JjVJhVQFX9EUPfsBvvpu_B3PjsA9JcNAK17Zfg?e=6CfS4h