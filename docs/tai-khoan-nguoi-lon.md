# Tài khoản người lớn – Vietlim Bank

## Đối tượng
Công dân từ **14 tuổi trở lên** (theo mô phỏng dự án)

---

## Cách đăng ký tài khoản

### Bước 1: Nhập thông tin cá nhân
Người dùng nhập các thông tin sau:
- Họ và tên
- Ngày sinh
- Số giấy tờ tùy thân:
  - CCCD / CMND / Hộ chiếu (Passport)

---

### Bước 2: Chụp giấy tờ tùy thân
Người dùng chụp ảnh:
- Mặt trước CCCD / CMND / Passport  
- Mặt sau CCCD / CMND (nếu có)

📌 Lưu ý:
- Ảnh phải rõ nét
- Thông tin người sở hữu phải trùng với thông tin đã nhập

---

### Bước 3: Xác minh khuôn mặt (eKYC)
Người dùng thực hiện quét khuôn mặt:
- Chụp **mặt trước**
- Quay **mặt trái**
- Quay **mặt phải**

👉 Hệ thống đối chiếu:
- Khuôn mặt ↔ giấy tờ tùy thân

Nếu xác minh thành công → chuyển sang bước tiếp theo.

---

### Bước 4: Liên kết thẻ / tài khoản ngân hàng khác
- Người dùng có thể liên kết:
  - Thẻ ngân hàng khác
  - Tài khoản ngân hàng khác
- Cho phép liên kết **nhiều thẻ / nhiều ngân hàng**

📌 Việc liên kết giúp:
- Nạp tiền
- Chuyển tiền
- Sử dụng dịch vụ thuận tiện hơn

---

### Bước 5: Hoàn tất đăng ký
- Hệ thống thông báo: **Đăng ký thành công**
- Người dùng được phép:
  - Đăng nhập
  - Sử dụng các chức năng trong ứng dụng (mô phỏng)

---

## Trạng thái tài khoản
- Chưa xác minh: Giới hạn chức năng
- Đã xác minh đầy đủ: Sử dụng đầy đủ tính năng (mô phỏng)

---

## Lưu ý pháp lý
Tài khoản trong dự án Vietlim Bank chỉ mang tính mô phỏng.  
Không thực hiện giao dịch tài chính thật.
---

## Xác minh khuôn mặt (Face Verification)

Ngoài việc xác minh bằng giấy tờ (CCCD/hồ sơ), Vietlim Bank áp dụng
**xác minh khuôn mặt** nhằm tăng độ an toàn và uy tín.

### Mục đích
1. Ngăn chặn việc trẻ nhỏ sử dụng giấy tờ của cha/mẹ để đăng ký khi chưa được phép
2. Đảm bảo người đăng ký là đúng đối tượng
3. Tăng mức độ tin cậy và an toàn cho hệ thống

### Cách thức (mô phỏng)
- Người đăng ký thực hiện quét khuôn mặt trực tiếp trên ứng dụng
- Hệ thống đối chiếu khuôn mặt với hồ sơ đã cung cấp
- Nếu khớp → hồ sơ được chuyển sang trạng thái **Chờ duyệt**
- Nếu không khớp → yêu cầu xác minh lại

### Lưu ý
Tính năng xác minh khuôn mặt chỉ mang tính mô phỏng trong dự án ý tưởng,
không thu thập hoặc lưu trữ dữ liệu sinh trắc học thật.
