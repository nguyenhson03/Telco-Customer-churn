# Telco Customer Churn Prediction with Deep Learning

Dự án này sử dụng mô hình Deep Learning để dự đoán khách hàng có khả năng rời bỏ (churn) của một công ty viễn thông. Mục tiêu là giúp doanh nghiệp chủ động giữ chân khách hàng, giảm thiểu thất thoát doanh thu.

---

## Giới thiệu

Bài toán churn (khách hàng rời đi) là một trong những vấn đề quan trọng đối với doanh nghiệp. Mô hình này được xây dựng nhằm:
- Phân loại khách hàng có khả năng rời đi (Yes/No)
- Hỗ trợ bộ phận chăm sóc khách hàng can thiệp kịp thời

---


## Tiền xử lý

- Mã hóa biến phân loại (`LabelEncoder`, `OneHotEncoder`)
- Chuyển dữ liệu về số
- Chuẩn hóa dữ liệu (`StandardScaler`)
- Tách tập huấn luyện và kiểm tra (train/test split, `stratify` để cân bằng lớp)
- Giải quyết mất cân bằng bằng cách giữ nguyên hoặc có thể dùng kỹ thuật nâng cao như SMOTE (tuỳ chọn)

---
##  Mô hình
Sử dụng **Keras (TensorFlow)** để xây dựng mô hình MLP (Multilayer Perceptron)

