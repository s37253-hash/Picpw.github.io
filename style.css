import turtle
import colorsys

# ตั้งค่าหน้าจอแสดงผล
screen = turtle.Screen()
screen.bgcolor("black")          # พื้นหลังสีดำช่วยให้สีนีออนเด่นขึ้น
screen.title("ภาพวาดกราฟิกสีรุ้งเรืองแสง")

# ตั้งค่าปากกา
pen = turtle.Turtle()
pen.speed(0)                    # ตั้งความเร็วสูงสุด
turtle.delay(0)                 # ปิดดีเลย์เพื่อให้วาดเร็วทันใจ
pen.pensize(2)                  # ขนาดเส้น

# กำหนดจำนวนรอบและตัวแปรสำหรับไล่เฉดสี
num_lines = 180
hue = 0.0

# ลูปสำหรับวาดภาพเรขาคณิต
for i in range(num_lines):
    # แปลงค่า HSV เป็น RGB เพื่อให้ได้สีรุ้งที่ไล่เฉดอย่างนุ่มนวล
    color = colorsys.hsv_to_rgb(hue, 1.0, 1.0)
    pen.color(color)
    hue += 1.0 / num_lines      # ขยับเฉดสีไปเรื่อยๆ ในแต่ละเส้น
    
    # วาดเส้นตรงและหมุนมุมเพื่อให้เกิดมิติเวียนขวา
    pen.forward(i * 3)          # ยิ่งวาด เส้นยิ่งยาวขึ้นออกไปด้านนอก
    pen.left(145)               # หมุนทำมุม 145 องศาเพื่อให้เกิดลวดลายขัดกันเป็นตาข่าย
    
# ซ่อนหัวปากกาเมื่อวาดเสร็จสิ้น
pen.hideturtle()

# เปิดหน้าจอค้างไว้
turtle.done()
