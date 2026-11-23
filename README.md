# Recycling Bin with Points System ♻️

مشروع سلة إعادة تدوير ذكية تمنح نقاطاً للمستخدمين مقابل إعادة التدوير، باستخدام ESP8266 وخادم محلي وقاعدة بيانات Firebase وتطبيق للمستخدم.

## هيكل المشروع (Project Structure)
- **`firmware/`**: كود وبرمجة شريحة ESP8266 (NodeMCU 1.0) والتعامل مع الحساسات.
- **`server/`**: الخادم المحلي (Node.js & Firebase Admin SDK) لحساب النقاط بأمان ومعالجة العمليات الحساسة.
- **`app/`**: واجهات وتطبيق المستخدم لعرض الرصيد والنقاط.
- **`docs/`**: التوثيق والمخططات ودليل التوصيل والتشغيل.

## المتطلبات الأساسية (Prerequisites)
- Node.js (v24+)
- Arduino IDE (v2.x) مع حزمة لوحات ESP8266
- Firebase CLI و Google Cloud CLI
- لوحة NodeMCU 1.0 (ESP-12E Module)
