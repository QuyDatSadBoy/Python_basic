# Python Basic - Khóa học Python cơ bản

## 📋 Mô tả dự án

Repository này chứa các bài học Python cơ bản được tổ chức thành các notebook Jupyter, bao gồm các chủ đề từ cơ bản đến nâng cao về lập trình Python.

## 📁 Cấu trúc thư mục

```
Python_basic/
├── Basic_python_2/
│   ├── 2. pi_estimation.ipynb      # Ước tính số π bằng phương pháp Monte Carlo
│   ├── 4. File/
│   │   └── File_IO.ipynb           # Thao tác với file và I/O
│   └── 5. String.ipynb             # Xử lý chuỗi (String)
└── 3. Buit-in Functions.ipynb      # Các hàm built-in trong Python
```

## 🎯 Nội dung học tập

### 1. Built-in Functions (3. Buit-in Functions.ipynb)
- Các hàm tích hợp sẵn trong Python
- Sử dụng `input()` để nhận dữ liệu từ người dùng
- Ép kiểu dữ liệu với `float()`, `int()`, `str()`
- Ví dụ thực tế: Chuyển đổi độ sang radian

### 2. Ước tính số π (Basic_python_2/2. pi_estimation.ipynb)
- Phương pháp Monte Carlo để ước tính π
- Sử dụng vòng lặp `for`
- Câu lệnh điều kiện `if-else`
- Xử lý số ngẫu nhiên
- Đếm và thống kê

### 3. Xử lý File và I/O (Basic_python_2/4. File/File_IO.ipynb)
Bài học toàn diện về thao tác với file trong Python:

#### 3.1 Đọc file
- Sử dụng `open()` với mode 'r' (read)
- Đọc toàn bộ nội dung với `read()`
- Đọc từng dòng với `readlines()`
- Đóng file với `close()`

#### 3.2 Ghi file
- Mode 'w' (write) - ghi đè file
- Mode 'a' (append) - thêm vào cuối file
- Sử dụng `write()` để ghi dữ liệu

#### 3.3 Xử lý file CSV
- Đọc file Iris.csv
- Phân tích dữ liệu với `split(',')`
- Chuyển đổi kiểu dữ liệu với `float()`
- Xử lý header và dữ liệu

#### 3.4 Kiểm tra file
- Sử dụng `os.path.exists()` để kiểm tra file tồn tại
- Best practices với context manager (`with` statement)

### 4. Xử lý chuỗi (Basic_python_2/5. String.ipynb)
Hướng dẫn chi tiết về String trong Python:

#### 4.1 Tạo chuỗi
- Sử dụng dấu nháy đơn `'`, nháy kép `"`, ba nháy `'''` hoặc `"""`
- Xử lý ký tự đặc biệt với escape characters

#### 4.2 Định dạng chuỗi
- Formatting với `%` operator
- Sử dụng `format()` method
- F-strings (formatted string literals)

#### 4.3 Thao tác chuỗi
- Nối chuỗi với `+`
- Nhân chuỗi với `*`
- So sánh chuỗi

#### 4.4 Phương thức chuỗi
- Kiểm tra: `isdigit()`, `isalpha()`, `isupper()`, `islower()`, `istitle()`
- Chuyển đổi: `upper()`, `lower()`, `title()`, `capitalize()`, `swapcase()`
- Căn chỉnh: `center()`, `ljust()`, `rjust()`, `zfill()`
- Loại bỏ khoảng trắng: `strip()`, `lstrip()`, `rstrip()`
- Tìm kiếm: `find()`, `index()`, `startswith()`, `endswith()`
- Thay thế: `replace()`, `partition()`

## 🚀 Cách sử dụng

### Yêu cầu hệ thống
- Python 3.x
- Jupyter Notebook hoặc JupyterLab
- Các thư viện cơ bản: `os`, `random` (đã có sẵn trong Python)

### Chạy notebook
1. Clone repository:
```bash
git clone https://github.com/QuyDatSadBoy/Python_basic.git
cd Python_basic
```

2. Khởi động Jupyter Notebook:
```bash
jupyter notebook
```

3. Mở các file `.ipynb` và chạy từng cell để học tập

## 📊 Dữ liệu mẫu

Repository bao gồm các file dữ liệu mẫu:
- `Iris.csv` - Dataset Iris cho thực hành xử lý CSV
- `data.csv` - Dữ liệu mẫu về diện tích và giá
- `iris_demo.csv` - Dữ liệu Iris đã được xử lý
- Các file text mẫu cho thực hành I/O

## 🎓 Đối tượng học tập

- Người mới bắt đầu học Python
- Sinh viên muốn nắm vững cơ bản Python
- Lập trình viên chuyển từ ngôn ngữ khác sang Python

## 📝 Ghi chú quan trọng

- Tất cả code được viết bằng tiếng Việt để dễ hiểu
- Mỗi notebook có các ví dụ thực tế và bài tập
- Code được comment chi tiết
- Có xử lý lỗi và best practices

## 🤝 Đóng góp

Nếu bạn muốn đóng góp vào dự án:
1. Fork repository
2. Tạo branch mới cho feature
3. Commit changes
4. Push và tạo Pull Request

## 📧 Liên hệ

- GitHub: [@QuyDatSadBoy](https://github.com/QuyDatSadBoy)
- Email: [tranquydat2003@gmail.com]


---

*Chúc bạn học tập hiệu quả! 🐍💪*
