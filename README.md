# MLOps Project

Một dự án MLOps (Machine Learning Operations) toàn diện, bao gồm quy trình xây dựng, huấn luyện, triển khai và giám sát các mô hình machine learning.

## 📋 Mục đích

Dự án này cung cấp một khung công tác hoàn chỉnh để:
- Xây dựng và huấn luyện mô hình ML
- Quản lý dữ liệu và pipeline
- Triển khai mô hình trong production
- Giám sát hiệu suất mô hình
- Tự động hóa quy trình CI/CD

## 🚀 Bắt đầu nhanh

### Yêu cầu
- Python 3.8+
- pip hoặc conda
- Git

### Cài đặt

1. Clone repository:
```bash
git clone <repository-url>
cd mlops-project
```

2. Tạo virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# hoặc
venv\Scripts\activate  # Windows
```

3. Cài đặt dependencies:
```bash
pip install -r requirements.txt
```

## 📁 Cấu trúc dự án

```
mlops-project/
├── data/                 # Dữ liệu (train, test, validation)
├── models/              # Mô hình đã huấn luyện
├── src/                 # Source code
│   ├── data/           # Data processing
│   ├── models/         # Model definitions
│   ├── training/       # Training scripts
│   └── inference/      # Inference scripts
├── tests/              # Unit tests
├── configs/            # Configuration files
├── notebooks/          # Jupyter notebooks
├── logs/               # Training logs
├── docker/             # Docker configuration
├── requirements.txt    # Dependencies
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## 🔧 Sử dụng

### Huấn luyện mô hình
```bash
python src/training/train.py --config configs/config.yaml
```

### Inference
```bash
python src/inference/predict.py --model models/model.pkl --input data/input.csv
```

### Chạy tests
```bash
pytest tests/
```

## 📊 Pipeline

Dự án sử dụng các bước chính:
1. **Data Preparation** - Tiền xử lý và chuẩn bị dữ liệu
2. **Model Training** - Huấn luyện mô hình
3. **Evaluation** - Đánh giá hiệu suất
4. **Deployment** - Triển khai mô hình
5. **Monitoring** - Giám sát và logging

## 🐳 Docker

Xây dựng và chạy với Docker:
```bash
docker build -t mlops-project .
docker run -it mlops-project
```

## 📦 Dependencies

Xem `requirements.txt` để danh sách đầy đủ các thư viện. Các thư viện chính:
- pandas
- scikit-learn
- tensorflow/pytorch
- mlflow (MLOps tracking)
- fastapi (API serving)

## 🤝 Đóng góp

Hướng dẫn đóng góp:
1. Fork dự án
2. Tạo branch cho feature (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Mở Pull Request

## 📝 License

Dự án này được cấp phép theo MIT License - xem file LICENSE để chi tiết.

## 📧 Liên hệ

Nếu có câu hỏi hoặc đề xuất, vui lòng tạo một issue hoặc liên hệ qua email.

---
**Cập nhật lần cuối:** May 3, 2026