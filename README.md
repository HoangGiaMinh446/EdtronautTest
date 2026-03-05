# EdtronautTest


---

## Hướng Dẫn Sử Dụng

### 1. **Cài Đặt Môi Trường**

```bash
# Clone repository
git clone https://github.com/HoangGiaMinh446/EdtronautTest.git
cd EdtronautTest

# Cài đặt các thư viện cần thiết
pip install -r requirements.txt

### 2. **Chạy code chính ipynb**
Code chính được đặt trong file CHRO_AI_Co_Worker.ipynb - đây là nơi xây dựng AI Agent:
jupyter notebook CHRO_AI_Co_Worker.ipynb

### 3. **Demo Streamlit (Giới Hạn)**
Lưu ý quan trọng: Demo trên Streamlit chỉ hoạt động cho 1 request đầu tiên. Sau đó, sẽ gặp lỗi Rate Limit do giới hạn thời gian deploy cơ bản.
# Chạy ứng dụng Streamlit
streamlit run app.py

Hoặc truy cập demo online: 'https://edtronauttestgit-o52xd4mv5kbbesqonxyxsh.streamlit.app/'

File app.py chỉ là mục tiêu demo đơn giản - code chính của AI Agent được xây dựng và lưu trữ trong CHRO_AI_Co_Worker.ipynb

Xem file requirements.txt để xem yêu cầu cần tải để sử dụng:
streamlit
langchain
# Các thư viện khác...

Cài đặt bash: 'pip install -r requirements.txt'

Ngày cập nhật: 2026-03-05
Tác giả: HoangGiaMinh446
