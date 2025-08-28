# ESP32-DHT-Sensor-Real-time-Chart-ESPAsyncWebServer-
โปรเจกต์ตัวอย่างนี้ใช้  ESP32 + DHT11/DHT22 Sensor  เพื่ออ่านค่า  Temperature  และ  Humidity  และส่งข้อมูลไปแสดงผลเป็นกราฟแบบ Real-time ผ่าน  ESPAsyncWebServer + Chart.js
# ESP32 + DHT Sensor Real-time Chart (ESPAsyncWebServer)

โปรเจกต์ตัวอย่างนี้ใช้ **ESP32 + DHT11/DHT22 Sensor** เพื่ออ่านค่า **Temperature** และ **Humidity** และส่งข้อมูลไปแสดงผลเป็นกราฟแบบ Real-time ผ่าน **ESPAsyncWebServer + Chart.js**  

## 🔹 คุณสมบัติ
- อ่านค่าอุณหภูมิและความชื้นจาก DHT11 / DHT22
- แสดงผลบนหน้าเว็บเป็นกราฟแบบ Real-time
- ใช้ **WebSocket** สำหรับส่งข้อมูลสด ๆ
- ทำงานบน WiFi Local ไม่ต้องใช้ Cloud

## 🔹 อุปกรณ์ที่ใช้
- ESP32 DevKit V1
- DHT22 หรือ DHT11 Sensor
- Arduino IDE + Libraries:
  - ESPAsyncWebServer
  - AsyncTCP
  - DHT sensor library

## 🔹 การต่อวงจร
- VCC → 3.3V
- GND → GND
- DATA → GPIO 4 (แก้ไขได้ในโค้ด)

## 🔹 ตัวอย่างผลลัพธ์
เมื่อเปิด Browser จะเห็น Dashboard ที่แสดงค่า Temp/Hum อัปเดตทุก 2 วินาที 🎉  


## 🔹 วิธีใช้งาน
1. ติดตั้ง Arduino IDE และเพิ่มบอร์ด ESP32  
2. ติดตั้ง Libraries ที่จำเป็น  
3. แก้ไข `ssid` และ `password` ให้ตรงกับ WiFi ของคุณ  
4. Upload โค้ดไปยัง ESP32  
5. เปิด Browser ไปที่ IP ของ ESP32 → จะเห็นกราฟอัปเดตแบบ Real-time  

## 📖 อ่านบทความเต็ม
👉 [ESP32 + DHT Sensor แสดงผลกราฟ Real-time ด้วย ESPAsyncWebServer](https://devadiy.com/espasyncwebserverr-realtimecharts)  

---
✍️ Project by [DevaDIY.com](https://devadiy.com/)
