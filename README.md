MSH/
│
├── data/
│   ├── raw/                 # Dữ liệu gốc chưa xử lý (nếu có)
│   └── cleaned/             # Dữ liệu đã làm sạch, sẵn sàng phân tích (file CSV)
│
├── notebooks/               # Các file Jupyter Notebook phân tích, xử lý, mô hình
│   └── analysis.ipynb
│
├── sql/                    # Các file truy vấn SQL (nếu có)
│
├── reports/                 # Báo cáo chi tiết (có thể file markdown hoặc pdf)
│
├── scripts/                 # Mã nguồn Python riêng (nếu tách thành script)
│
├── requirements.txt         # Thư viện Python cần thiết
│
└── README.md                # Giới thiệu project, hướng dẫn sử dụng
# Phân tích và Dự đoán Giá Cổ Phiếu MSH

## Mục đích dự án
Dự án nhằm thu thập, làm sạch, phân tích và dự đoán giá cổ phiếu MSH trong 5 năm gần nhất, sử dụng dữ liệu từ sàn chứng khoán Việt Nam.

## Cấu trúc thư mục

- `data/raw/`: Dữ liệu gốc tải về.
- `data/cleaned/`: Dữ liệu đã làm sạch, sẵn sàng phân tích.
- `notebooks/`: Các file Jupyter Notebook phân tích, mô hình hóa.
- `sql/`: Các truy vấn SQL dùng trong quá trình phân tích.
- `reports/`: Báo cáo kết quả phân tích và dự đoán.
- `scripts/`: Các đoạn script Python riêng biệt (nếu có).
- `requirements.txt`: Danh sách thư viện Python cần cài đặt.

## Hướng dẫn sử dụng

1. Clone repo về máy:
git clone https://github.com/trnganbytes/MSH.git
2. Cài đặt thư viện Python:
pip install -r requirements.txt
3. Mở notebook phân tích tại thư mục `notebooks/` bằng Jupyter.
4. Thực hiện chạy các bước từ làm sạch dữ liệu đến mô hình dự đoán.
5. Các truy vấn SQL có thể chạy trong phần mềm quản lý CSDL hoặc phần mềm SQL tương thích.

## Yêu cầu

- Python 3.x
- Jupyter Notebook
- Thư viện: pandas, numpy, matplotlib, seaborn, scikit-learn, ...

---

## Liên hệ

Nếu có thắc mắc vui lòng liên hệ: [email hoặc Github profile]


