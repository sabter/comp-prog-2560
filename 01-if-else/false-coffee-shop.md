# False Coffee Shop #

ร้านกาแฟแห่งหนึ่งได้ใช้วิธีดึงดูดลูกค้าโดยการให้ลูกค้าทำบัตรสมาชิกเพื่อที่จะได้รับส่วนลด โดยบัตรสมาชิกจะมีด้วยกัน 3 ประเภทคือ Red Card, Gold Card และ Black Card

- ผู้ใช้บัตร Red Card (บัตรประเภท 1) จะได้ส่วนลด 10% เฉพาะวันเทศกาล
- ผู้ใช้บัตร Gold Card (บัตรประเภท 2) จะได้ส่วนลด 10% ทุกครั้ง แต่ถ้าหากเป็นวันเทศกาลจะลด 15%
- ผู้ใช้บัตร Black Card (บัตรประเภท 3) จะได้ส่วนลด 15% ทุกครั้ง แต่ถ้าหากเป็นวันเทศกาลจะลด 20%

การที่ลูกค้าจะได้รับส่วนลดนั้น สำหรับผู้ใช้บัตร Red Card และ Gold Card จะต้องมียอดชำระเงินตั้งแต่ 150 บาทขึ้นไป ส่วนผู้ใช้บัตร Black Card จะต้องมียอดชำระเงินตั้งแต่ 200 บาทขึ้นไป

จงเขียนโปรแกรมเพื่อคำนวณจำนวนเงินที่ลูกค้าต้องจ่ายเมื่อคิดส่วนลดแล้ว โดยดูจากยอดชำระเงินที่ยังไม่ลด, ประเภทของบัตร และวันเทศกาล (โดยให้ข้อมูลเข้าของวันเทศกาลเป็น `1` เมื่อวันนี้คือวันเทศกาล และเป็น `0` เมื่อวันนี้ไม่ใช่วันเทศกาล) โดยให้แสดงข้อความว่าได้รับส่วนลดพร้อมจำนวนส่วนลด (เมื่อได้รับส่วนลด) และจำนวนเงินที่ลูกค้าต้องจ่าย ซึ่งถ้าหากข้อมูลเข้าของประเภทบัตรหรือวันเทศกาลไม่ถูกต้อง หรือยอดชำระเงินที่ยังไม่ลดเป็นค่าติดลบ ให้แสดงข้อความว่า `Invalid input.` เมื่อใส่ข้อมูลเข้าครบแล้ว

### ตัวอย่าง Input/Output
```
Subtotal amount: 330.00
Card type: 1
Is Festival day? (1=yes/0=no): 0
Total amount is 330.00 baht.
```
```
Subtotal amount: 230.00
Card type: 3
Is Festival day? (1=yes/0=no): 1
You've got 20% discount.
Total amount is 184.00 baht.
```
```
Subtotal amount: 352.50
Card type: 5
Is Festival day? (1=yes/0=no): 0
Invalid input.
```
