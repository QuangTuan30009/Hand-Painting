# Hand-Painting

## Mô tả
Dự án **Recognise-handwritten-digits** là một ứng dụng nhận diện chữ số viết tay (0-9) sử dụng mạng nơ-ron tích chập (Convolutional Neural Network - CNN). Dự án được xây dựng dựa trên tập dữ liệu MNIST, một tập dữ liệu chuẩn trong lĩnh vực thị giác máy tính, bao gồm 60,000 hình ảnh huấn luyện và 10,000 hình ảnh kiểm tra, mỗi hình có kích thước 28x28 pixel ở định dạng thang độ xám.

Mô hình CNN được huấn luyện để phân loại các chữ số viết tay với độ chính xác cao, tận dụng các thư viện TensorFlow và Keras để xây dựng và huấn luyện mô hình.

## Tính năng
- Nhận diện chữ số viết tay (0-9) từ hình ảnh.
- Sử dụng mô hình CNN với độ chính xác cao (~99% trên tập kiểm tra MNIST).
- Dễ dàng huấn luyện lại mô hình hoặc sử dụng mô hình đã được huấn luyện trước.

## Công nghệ sử dụng
- **Ngôn ngữ lập trình**: Python
- **Thư viện**:
  - TensorFlow/Keras: Xây dựng và huấn luyện mô hình CNN.
  - NumPy: Xử lý mảng dữ liệu.
  - Matplotlib: Hiển thị hình ảnh và kết quả.
- **Tập dữ liệu**: MNIST (60,000 hình ảnh huấn luyện, 10,000 hình ảnh kiểm tra).

## Cài đặt
Để chạy dự án trên máy local, làm theo các bước sau:

1. **Clone repository**:
   ```bash
   git clone https://github.com/QuangTuan30009/Recognise-handwritten-digits.git
