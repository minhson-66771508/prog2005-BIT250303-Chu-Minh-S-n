# Bài 1

# Tạo các biến với kiểu dữ liệu khác nhau
integer_number = 10
float_number = 5.5
string_text = "Hello Python"

# In ra các biến
print("Số nguyên:", integer_number)
print("Số thực:", float_number)
print("Chuỗi:", string_text)


# Bài 2

# Tính chu vi hình tròn
PI = 3.14
r = 5

chu_vi = 2 * PI * r

print("Chu vi hình tròn là:", chu_vi)


# Bài 3

# Nhập hai số nguyên từ người dùng
a = int(input("Nhập số thứ nhất: "))
b = int(input("Nhập số thứ hai: "))

# Thực hiện các phép toán
tong = a + b
hieu = a - b
tich = a * b
thuong = a / b

# In kết quả
print("Tổng:", tong)
print("Hiệu:", hieu)
print("Tích:", tich)
print("Thương:", thuong)


# Bài 4

# Hàm tính tổng hai số
def sum_two_numbers(a, b):
    return a + b

# Gọi hàm
result = sum_two_numbers(3, 7)

# In kết quả
print("Tổng hai số là:", result)


# Bài 5

# Khai báo biến
name = "Sơn"
age = 19
average_score = 9

# Hiển thị kiểu dữ liệu
print("Kiểu dữ liệu của name:", type(name))
print("Kiểu dữ liệu của age:", type(age))
print("Kiểu dữ liệu của average_score:", type(average_score))

# Xử lý dữ liệu
age_next_year = age + 1
doubled_score = average_score * 2

# In thông tin
print("Tên:", name)
print("Tuổi hiện tại:", age)
print("Tuổi năm sau:", age_next_year)
print("Điểm trung bình:", average_score)
print("Điểm gấp đôi:", doubled_score)
