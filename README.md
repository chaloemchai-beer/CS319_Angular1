## README สำหรับการรันโปรเจกต์ Angular ในเครื่อง

README นี้แนะนำขั้นตอนการติดตั้งและรันโปรเจกต์ Angular บนเครื่องของคุณ

### ข้อกำหนดเบื้องต้น

1. **Node.js และ npm**: ตรวจสอบให้แน่ใจว่าเครื่องของคุณติดตั้ง Node.js และ npm เรียบร้อยแล้ว สามารถดาวน์โหลดได้จาก [Node.js](https://nodejs.org/)
2. **Angular CLI**: ติดตั้ง Angular CLI โดยใช้คำสั่งต่อไปนี้:
   ```bash
   npm install -g @angular/cli
   ```

### ขั้นตอนการรันโปรเจกต์ Angular

1. **โคลนโปรเจกต์**:
   ทำการโคลนโปรเจกต์ไปยังเครื่องของคุณด้วยคำสั่ง:
   ```bash
   git clone https://github.com/chaloemchai-beer/CS319_Angular1.git
   ```

2. **เข้าไปในโฟลเดอร์โปรเจกต์**:
   ```bash
   cd CS319_Angular1
   ```

3. **ติดตั้ง Dependencies**:
   ติดตั้ง dependencies ที่จำเป็นสำหรับโปรเจกต์ด้วยคำสั่ง:
   ```bash
   npm install
   ```

4. **รันโปรเจกต์**:
   รันโปรเจกต์ด้วยคำสั่ง:
   ```bash
   ng serve
   ```
   โปรเจกต์จะถูกรันที่ `http://localhost:4200` ตามค่าเริ่มต้น เปิดเบราว์เซอร์และเข้าไปยัง URL นี้เพื่อดูโปรเจกต์ที่รันอยู่

### ภาพหน้าจอ

ด้านล่างเป็นภาพหน้าจอของการรันโปรเจกต์ Angular ในเครื่อง:

![Run Angular Project](https://raw.githubusercontent.com/chaloemchai-beer/Image/refs/heads/main/RunAngular.png)

ภาพแสดงหน้าจอเบราว์เซอร์ที่โปรเจกต์ Angular ทำงานอยู่บน `http://localhost:4200` ซึ่งเป็นสัญญาณว่าโปรเจกต์รันสำเร็จแล้ว
