วิธีได้ไฟล์ .apk (ไม่ต้องลง Android Studio)
1. สร้าง repo ใหม่บน GitHub แล้วอัปโหลดทุกไฟล์ในโฟลเดอร์นี้ (รวมโฟลเดอร์ .github)
2. แท็บ Actions -> Build APK -> รอ ~5 นาที
3. ดาวน์โหลด SYSTEM-apk จากหน้า run -> แตก zip ได้ app-debug.apk
4. ส่งเข้ามือถือ Android เปิดติดตั้ง (อนุญาต "ติดตั้งจากแหล่งที่ไม่รู้จัก")
ทางเลือก: Android Studio -> Open โฟลเดอร์ android -> Build APK
หมายเหตุ: เป็น debug APK ใช้ส่วนตัวได้ ถ้าจะขึ้น Play Store ต้อง sign release
