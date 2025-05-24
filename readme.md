# Python Jupyter Lesson - Hướng dẫn cài đặt và sử dụng

## 1. Giới thiệu

Đây là bộ bài học Python cơ bản đến nâng cao, sử dụng Jupyter Notebook, phù hợp cho người mới bắt đầu học lập trình và phân tích dữ liệu.

## 2. Yêu cầu môi trường

- Python 3.7 trở lên
- pip (trình quản lý gói Python)

## 3. Cài đặt thư viện cần thiết

### Cách 1: Sử dụng file requirements.txt

1. Mở **Command Prompt** hoặc **PowerShell** tại thư mục dự án này.
2. Chạy lệnh sau để cài đặt tất cả các thư viện cần thiết:
   ```
   pip install -r requirements.txt
   ```

### Cách 2: Cài đặt thủ công từng thư viện

Chạy lần lượt các lệnh sau:
```
pip install pandas
pip install matplotlib
pip install jupyter
pip install numpy
```

### Cách 3: Khuyên dùng cho người mới - Cài đặt Anaconda

1. Tải Anaconda tại: https://www.anaconda.com/products/distribution
2. Cài đặt theo hướng dẫn.
3. Mở **Anaconda Navigator** hoặc **Anaconda Prompt** và chạy:
   ```
   conda install pandas matplotlib jupyter numpy
   ```

## 4. Khởi động Jupyter Notebook

Tại thư mục chứa các file bài học, chạy:
```
jupyter notebook
```
Sau đó mở các file `.ipynb` để học và thực hành.

## 5. Một số lưu ý

- Nếu gặp lỗi thiếu thư viện, hãy kiểm tra lại bước cài đặt ở trên.
- Để tạo môi trường ảo (virtual environment), bạn có thể dùng:
  ```
  python -m venv venv
  .\venv\Scripts\activate
  pip install -r requirements.txt
  ```
- Nếu dùng PowerShell, hãy dùng lệnh tạo file requirements.txt như sau:
  ```
  "pandas`nmatplotlib`njupyter`nnumpy" | Out-File -Encoding utf8 requirements.txt
  ```

## 6. Nội dung các bài học

- Làm việc với biến, kiểu dữ liệu, hàm, vòng lặp, điều kiện
- Dictionary, Set, List, Tuple
- Đọc/ghi file, module, import
- Xử lý chuỗi, comprehension, lambda, map, filter, reduce
- Generator, iterator, decorator, context manager
- Thư viện chuẩn: datetime, os, sys
- Cài đặt thư viện mở rộng với pip
- Trực quan hoá dữ liệu với matplotlib
- Làm việc với dữ liệu bằng pandas

---

Chúc bạn học tốt Python!