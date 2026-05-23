#Bài 1
# Kiểm Tra 1 Số Trẵn

def is_even (x):

    if x % 2 == 0:
    
        return True
        
    else:
    
        return False
        
x = int(input("nhap so:"))

print(is_even(x))

<img width="1830" height="935" alt="Ảnh chụp màn hình 2026-05-23 191130" src="https://github.com/user-attachments/assets/65411486-5648-45d2-a925-012d3f1c1979" />

#Bài 2

a = int(input("a ="))

b = int(input("b ="))

c = int(input("c ="))

max_number = max(a,b,c)

print("Số lớn nhất là:", max_namber)

<img width="1832" height="988" alt="Ảnh chụp màn hình 2026-05-23 191750" src="https://github.com/user-attachments/assets/094f18b6-ea23-4ffd-9ecb-56658d15a19e" />

#Bài 3

def greet(name="Student!"):


greet()

<img width="1846" height="923" alt="Ảnh chụp màn hình 2026-05-23 191804" src="https://github.com/user-attachments/assets/836f1c70-ef94-4cc9-9193-53fc82ad0862" />

#Bài 4

age = int(input("Nhập số tuổi:"))

if 1<=age<=120:

     print("Tuổi hợp lệ")
     
else:

    print("Tuổi không hợp lệ")
    
<img width="1868" height="935" alt="Ảnh chụp màn hình 2026-05-23 191818" src="https://github.com/user-attachments/assets/83cfd453-c8b0-4a66-aee9-dd4654758b4c" />

#Bài 5

text = input("Nhập chuỗi:")

count = text.count('a')

print(count)

<img width="1822" height="938" alt="Ảnh chụp màn hình 2026-05-23 192044" src="https://github.com/user-attachments/assets/1f4da123-ca1b-4909-b835-ed81fafed5eb" />

#Bài 6

c = float(input('Nhập số C:'))

f = c*9/5+32

print(f"{c} độ C = {f} độ F")

<img width="1919" height="955" alt="Ảnh chụp màn hình 2026-05-23 192056" src="https://github.com/user-attachments/assets/d2b8ba40-a4b8-4586-9e40-6e085a4ba2fb" />

#Bài 7

kg = float(input("Nhập cân nặng:")

m = float(input("Nhập chiều cao:")

bmi = kg/(m*m)

print("BMI=", round(bmi, 2))

<img width="1843" height="940" alt="Ảnh chụp màn hình 2026-05-23 192123" src="https://github.com/user-attachments/assets/95c23e4a-bdca-4552-84ee-6ea14fe43cc0" />

#Bài 8

try:

a = int(input("Nhập số a:")

b = int(input("Nhập số b:")

if b==0:

     print("Không thể chia  cho 0")
     
else:

     print("Kết quả =:", a / b)
     
except:

print("Nhập sai dữ liệu")

<img width="1855" height="975" alt="Ảnh chụp màn hình 2026-05-23 192140" src="https://github.com/user-attachments/assets/44a7a0ff-69bf-427c-8e3e-1ee9e7459d60" />

#Bài 9

import math

n = float(input("Nhập số:")

if n < 0:

    print("Không tính được căn bậc hai")
    
else:

    print("Căn bậc hai =", math,sprt(n))
    
<img width="1862" height="894" alt="Ảnh chụp màn hình 2026-05-23 192155" src="https://github.com/user-attachments/assets/65c04676-2389-4d4b-ad6c-7ab0e06864bd" />

#Bài 10

for i in range(1, 4):

name = input("Nhập tên sinh viên:")

math_score = float(input("Nhập điểm môn toán:"))

physics_score = float(input("Nhập điểm môn vật lý:"))

chemistry_score = float(input("Nhập điểm môn hóa:"))

average = (math_score + physics_score + chemistry_score) / 3

print("Tên:", name)

print("Điểm trung bình :", round(average, 2))

<img width="1913" height="965" alt="Ảnh chụp màn hình 2026-05-23 192247" src="https://github.com/user-attachments/assets/decf85d6-ff0b-4795-a3f0-846c41c89f0b" />
