# 🛠️ Cài đặt và Thiết lập Dự án

Chào mừng bạn đến với **Group_1**, dự án này mang tên  **Child Mind Institute**. Dưới đây là hướng dẫn chi tiết để thiết lập môi trường và chạy dự án này trên máy cá nhân của bạn.

## 📋 Yêu cầu tiên quyết (Prerequisites)

Trước khi bắt đầu, hãy đảm bảo máy tính của bạn đã được cài đặt:

* **Python** (Phiên bản 3.8 trở lên): [Tải tại đây](https://www.python.org/downloads/)
* **Git**: [Tải tại đây](https://git-scm.com/downloads)
* Một trình biên tập code (VS Code, PyCharm,...)

## 🚀 Hướng dẫn cài đặt từng bước

Làm theo các bước sau để chạy dự án:

### 1. Clone dự án về máy

Mở Terminal (hoặc Git Bash) và chạy lệnh sau để tải mã nguồn về:

```bash
git clone [https://github.com/tungvoi38/Project_DataPreVisual_Group_1.git](https://github.com/tungvoi38/Project_DataPreVisual_Group_1.git)
```

Sau đó, di chuyển vào thư mục dự án:

```bash
cd Project_DataPreVisual_Group_1
```

### 2. Thiết lập môi trường ảo (Virtual Environment)

Khuyến khích sử dụng môi trường ảo để tránh xung đột thư viện:

```bash
# Tạo môi trường ảo tên là 'venv'
python -m venv venv
```

**Kích hoạt môi trường ảo:**

* **Trên Windows:**
    ```bash
    .\venv\Scripts\activate
    ```
* **Trên macOS / Linux:**
    ```bash
    source venv/bin/activate
    ```

### 3. Cài đặt các thư viện cần thiết

Sau khi kích hoạt môi trường ảo, hãy cài đặt các gói phụ thuộc từ file `requirements.txt`:

```bash
pip install -r requirements.txt
```

> **Lưu ý:** Nếu bạn gặp lỗi khi cài đặt, hãy thử nâng cấp `pip` trước bằng lệnh: `python -m pip install --upgrade pip`

### 4. Chạy dự án

Sau khi cài đặt xong, bạn có thể khởi chạy chương trình bằng lệnh:

```bash
# Nếu là chạy file Python thông thường
python main.py

# Nếu dự án sử dụng Streamlit (Ví dụ)
streamlit run app.py

# Nếu sử dụng Jupyter Notebook
jupyter notebook
```

*(Hãy thay `main.py` hoặc `app.py` bằng tên file chính xác của dự án nhóm bạn)*

---

## 🤝 Đóng góp (Contributing)

Nếu bạn là thành viên nhóm muốn cập nhật code:

1.  Tạo nhánh mới (`git checkout -b feature/Ten-Tinh-Nang`)
2.  Commit thay đổi (`git commit -m 'Thêm tính năng X'`)
3.  Push lên branch (`git push origin feature/Ten-Tinh-Nang`)
4.  Tạo một Pull Request.

---
