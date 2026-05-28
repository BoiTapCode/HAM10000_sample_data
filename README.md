 HAM10000 Dataset - Phân loại Ung thư da

## Các cột dữ liệu chính
* `lesion_id`: Mã ca bệnh.
* `image_id`: Tên file ảnh tương ứng.
* `dx`: Nhãn bệnh (Loại bệnh da liễu - Xem chi tiết bên dưới).
* `dx_type`: Phương pháp chẩn đoán (Giải phẫu bệnh, nội soi da,...)
* `age`: Tuổi của bệnh nhân.
* `sex`: Giới tính (`male` / `female`).
* `localization`: Vị trí vết thương trên cơ thể (Ví dụ: `back`, `face`, `scalp`...).

## Ý nghĩa các nhãn bệnh (`dx`)
Tập dữ liệu gồm 7 loại tổn thương da chính:
1. `nv`: Nốt ruồi lành tính (Chiếm số lượng nhiều nhất).
2. `mel`: U hắc tố (Ung thư ác tính nguy hiểm).
3. `bcl`: Ung thư biểu mô tế bào đáy.
4. `akiec`: Dày sừng quang hóa (Tiền ung thư).
5. `vasc`: Tổn thương mạch máu.
6. `df`: U xơ da lành tính.
7. `misc`: Các bệnh da liễu khác.
