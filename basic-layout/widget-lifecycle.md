# Widget Lifecycle

## Stateless

จะต้องไม่มีการ change state ของ data ในนี้

build function จะ run เพียงครั้งเดียวเมื่อมันถูกสร้างขึ้นมา

จะไม่มีอะไรอัปเดตในนี้ ถ้าหาก state มีการเปลี่ยน

แต่ถ้าต้องการจะอัปเดตอะไรบางอย่าง

จะใช้วิธี destroy widget และ create instance ของมันใหม่

## Stateful

state สามารถเปลี่ยนแปลงได้ตลอดเวลา

ถ้าต้องการจะเปลี่ยนแปลงค่าอะไรบางอย่าง

จะทำด้วยวิธี set state

และเมื่อข้อมุลมีการเปลี่ยนแปลงแล้ว มันจะ trigger build function

เพื่อ rebuild widget ใหม่

