# Hand Painting ✋🎨

Ứng dụng vẽ bằng cử chỉ tay, sử dụng OpenCV và MediaPipe để nhận diện tay qua webcam, cho phép bạn chọn màu và vẽ lên màn hình như một bảng vẽ ảo.

## 📌 Mô tả

- Nhận diện tay người dùng qua webcam.
- Dùng đầu ngón tay trỏ để vẽ.
- Khi ngón trỏ và ngón giữa đưa vào khu vực thanh màu ở đầu màn hình, bạn có thể chọn màu vẽ hoặc chế độ tẩy.
- Khi chỉ có ngón trỏ đưa ra (và ngón giữa co lại), ứng dụng chuyển sang chế độ vẽ hoặc xóa tuỳ theo màu đã chọn.

## 🖍️ Tính năng

- Vẽ bằng ngón tay trỏ (không cần chuột).
- Thanh công cụ lựa chọn màu nằm phía trên màn hình:
  - Red, Blue, Green, Purple, Cyan, Yellow
  - Erase (màu đen, nét lớn hơn)
- Nhấn **q** để thoát chương trình.

## 🛠️ Yêu cầu hệ thống

- Python 3.x
- Webcam

## 📦 Thư viện cần cài đặt

```bash
pip install opencv-python mediapipe numpy
```

## ▶️ Cách sử dụng

```bash
python hand_painting.py
```

- Đưa hai ngón tay (trỏ và giữa) lên khu vực thanh màu để chọn màu.
- Đưa một ngón tay (chỉ trỏ) để vẽ hoặc xoá trên màn hình.
- Cửa sổ “Painter” sẽ hiển thị khung hình có lớp vẽ.
- Cửa sổ “Canvas” hiển thị phần tranh riêng biệt.
- Nhấn `q` để thoát.

## 📁 Cấu trúc tệp

```
hand_painting.py      # Mã nguồn chính
README.md             # Mô tả dự án
```

## 💡 Ý tưởng mở rộng

- Thêm tính năng lưu ảnh đã vẽ.
- Nhận diện nhiều người cùng lúc.
- Thêm hiệu ứng cọ vẽ hoặc bảng chọn màu nâng cao.


