# แบ่ง Thread ให้ทำงานเป็นลักษณะ Parallel , หรือ Asynchronous โดยการนำ Thread ที่แตกออกมานั้นคำนวน โดยจะแบ่งภาระการคำนวนของแต่ละ Thread อย่างเป็นเอกฉันฑ์ 

จากเดิมโปรแกรมจะมีการใช้ Global_Sumation แค่อันเดียว เมื่อเราต้องการที่จะทำเป็นลักษณะ Asynchronous ที่ต้องทำงานพร้อมๆ กัน ของทุกๆ  Thread เราจึงจำเป็นต้องสร้าง Global_Sumation เพื่อมารองรับ ค่าผลลัพธ์ที่ได้จากการคำนวนของ Thread แต่ละตัว และในท้ายที่สุดเมื่อทุก Thread ทำงานเสร็จสิ้น ก็นำ Global_Sumation  ทุกๆ ตัวมารวมกันให้เป็นผลลัพธ์เดียวที่ต้องการ

## หาก Clone ไปอย่าลืมเอา .dat มาใส่ใน Root Folder
