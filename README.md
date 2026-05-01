# DATATHON 2026
## Thông tin nhóm
| Thành viên | Trường |
| :----: | :----: |
| Phan Thị Phương Chi | Trường Đại học Khoa học Tự nhiên - ĐHQG HCM |
| Trần Kim Ngân | Trường Đại học Khoa học Tự nhiên - ĐHQG HCM |
| Hồ Ngọc Mai Khanh | Trường Đại học Ngân hàng TP.HCM |

## Cấu trúc thư mục
```bash
├── data/
│   └── raw/              # Chứa dữ liệu thô từ ban tổ chức (.csv, .json, ...)
├── src/
│   ├── baseline.ipynb    # Code mẫu được cung cấp bởi cuộc thi
│   ├── EDA.ipynb         # Phân tích khám phá dữ liệu (Exploratory Data Analysis)
│   ├── mcqa.ipynb        # Xử lý logic cho bài toán câu hỏi trắc nghiệm
│   └── modeling.ipynb    # Xây dựng, huấn luyện và đánh giá mô hình dự đoán
├── requirements.txt      # Danh sách các thư viện cần thiết
└── README.md             # Hướng dẫn dự án
```

## Hướng dẫn cài đặt môi trường
1. Clone repository
```bash
git clone https://github.com/nganbee/datathon-gridbreakers.git
cd datathon-gridbreakers
```

2. Tạo môi trường ảo
```bash
python -m venv .venv
```

3. Cài đặt thư viện
```bash
pip install -r requirements.txt
```

## Hướng dẫn chạy
1. Khám phá dữ liệu (EDA)
- File: `src/EDA.ipynb`
- Cách chạy: MỞ file chọn `Kernel` -> `Restart & Run All`

2. Xử lý dữ liệu cho Multiple Choice
- File: `src/mcqa.ipynb`
- Cách chạy: MỞ file chọn `Kernel` -> `Restart & Run All`

3. Huấn luyện dữ liệu
- File: `src/modeling.ipynb`
- Cách chạy: MỞ file chọn `Kernel` -> `Restart & Run All`