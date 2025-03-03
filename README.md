# FPTStudentCompare 🚀  

FPTStudentCompare là một hệ thống web giúp tự động **so sánh danh sách sinh viên** giữa Google Sheets và file PDF một cách chính xác và nhanh chóng.  

## ✨ Tính năng chính  
- 📄 Nhập **link Google Sheets** và tải lên **file PDF** chứa danh sách sinh viên.  
- 🔍 **So sánh mã sinh viên** giữa hai danh sách với độ chính xác 100%.  
- 📊 Hiển thị kết quả trực tiếp trên giao diện web.  
- 📥 **Xuất kết quả** ra file **Excel** để lưu trữ hoặc chia sẻ.  

## 🛠 Công nghệ sử dụng  
- **Python** (Flask hoặc Django).  
- **Google Sheets API** (lấy dữ liệu trực tiếp từ Google Sheets).  
- **pdfplumber / PyMuPDF / camelot** (trích xuất bảng từ PDF).  
- **Pandas** (xử lý và so sánh dữ liệu).  
- **React.js CSS** (giao diện web). 
- **PostgreSQL hoặc MongoDB** (Lưu lịch sử so sánh).
- **Excel (openpyxl / pandas)** (Xuất kết quả).

## 🚀 Cài đặt và chạy dự án  
### 1️⃣ Cài đặt môi trường  
Đảm bảo bạn đã cài đặt **Python 3.10+** và **pip**. Sau đó, chạy lệnh:  

```bash
git clone https://github.com/hieunqdev/FPTStudentCompare.git  
cd FPTStudentCompare  
pip install -r requirements.txt  
