# Backup_taskTemplateMconnect_050620
Version ต้นแบบ ที่จะทำ Task แก้ ปัญหา update  OK ช้า 
เปิด Server database  บอร์ด อ่าน Ram มา ส่ง ทันที
ปิด Server database  บอร์ด write data ลง Ram เรื่อยๆ 
แก้ไข code เพิ่มเติม 
ตามนี้  
  เปลี่ยน data type ตัวแปร ใช้ volatile กับตัวแปรที่รับ OK มาจาก server
  คืออ่านจาก memory เพื่อให้ค่าที่รับ เป็นปัจจุบัน

![img](https://iotfmx.com/imgtest/MconTest050620/edit1.png)
![img](https://iotfmx.com/imgtest/MconTest050620/edit2.png)
![img](https://iotfmx.com/imgtest/MconTest050620/edit3.png)
![img](https://iotfmx.com/imgtest/MconTest050620/edit4.png)
![img](https://iotfmx.com/imgtest/MconTest050620/edit5.png)
![img](https://iotfmx.com/imgtest/MconTest050620/debug1.png)
![img](https://iotfmx.com/imgtest/MconTest050620/debug2.png)
![img](https://iotfmx.com/imgtest/MconTest050620/debug3.png)
