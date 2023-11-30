markdown_content = """
# PySide Coding Style

## Biến Số Nguyên:
```python
# numberOf hoặc Count
numberOf_tickets = 10
ticket_count = 20
Số Dấu Phẩy Động:
python
Copy code
# Amount
rainfall_amount = 25.5
money_amount = 100.75
Biến Boolean:
python
Copy code
# isSomething, hasSomething, doesSomething, didSomething, shouldDoSomething hoặc willDoSomething
is_active = True
has_data = False
should_update = True
Chuỗi:
python
Copy code
# String hoặc AsString
name_string = "John Doe"
description_as_string = "This is a description."
List:
python
Copy code
# s hoặc List
customers = ["Alice", "Bob", "Charlie"]
error_list = ["Error1", "Error2", "Error3"]
Object:
python
Copy code
# Danh từ
person_object = {"name": "John", "age": 30}
account_object = {"account_number": "12345", "balance": 1000.50}
Hàm:
python
Copy code
# handle
def handle_click_login():
    # Thực hiện các hành động khi nhấp vào nút đăng nhập
    pass
Tham Số:
python
Copy code
# Thêm tiền tố new để tránh shadow
def update_person(new_name, new_address):
    # Cập nhật thông tin người dùng với tên mới và địa chỉ mới
    pass
Hằng Số:
python
Copy code
# Chữ hoa và cách nhau bởi _
TOOLTIP_SHOW_DELAY_IN_MILLISECS = 2000
Lưu ý rằng trong Python, chuẩn PEP 8 là một hướng dẫn quy tắc đặt tên được chấp nhận rộng rãi.
"""

file_path = "pyside_coding_style.md"

with open(file_path, "w") as file:
file.write(markdown_content)

print(f"Markdown content has been written to {file_path}")
