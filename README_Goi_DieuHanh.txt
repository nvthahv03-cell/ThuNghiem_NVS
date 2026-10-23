NVS-HVA – GÓI ĐIỀU HÀNH 15 CHỨC NĂNG (23/10/2026)

MỤC TIÊU: Đóng gói giao diện 5 nhóm x 3 ô = 15, không sửa nghiệp vụ đã PASS.
- CuocHop.html và NVS_BinhChon.html: sao chép nguyên bytes từ hai file người dùng gửi ngày 23/10. KHÔNG CHỈNH SỬA.
- TTPhatHanh.html, NVS_GiaoNhiemVu.html, NVS_LichCongTac.html, NVS_KhaoSat.html: bản người dùng gửi, giữ nguyên.
- NVS_PhanCongChuyenMon.html, NVS_DayThay.html, NVS_GiaoViec_TheoDoi.html: bản có sẵn từ bộ V22; CHƯA ĐƯỢC XÁC NHẬN PASS.
- NVS_BaoDamChatLuong.html: 8 mục placeholder, không Backend.
- HVA_Personnel.js: bản người dùng gửi, sao chép nguyên bytes để đảm bảo phụ thuộc của Cuộc họp; nguồn lõi thực tế thuộc GÓI DÙNG CHUNG. Khi triển khai chính thức, chỉ duy trì một bản chung.
- Các ô Nhân sự & Tài khoản, Phân quyền hệ thống, Quản lý nghiệp vụ, Thống kê – Báo cáo, Nhật ký hệ thống: HIỆN CHƯA CÓ TRANG ĐÍCH ĐƯỢC KIỂM CHỨNG, bấm sẽ hiện thông báo chờ triển khai.
- index.html, chuông thông báo, Kho VB, PWA: KHÔNG BAO GỒM, thuộc gói Dùng chung.
- Backend và hàm AI Cuộc họp: KHÔNG sửa, KHÔNG triển khai lại. Backend đang chạy cần tiếp tục giữ nguyên.

KIỂM TRA ĐÓNG GÓI: 5 nhóm, 3 ô/nhóm; không có Phân công khác; không có CSDL ngành; hai file PASS được so sánh SHA-256 với bản nguồn.
LƯU Ý: Chưa chạy thử end-to-end với backend, quyền truy cập, QR và dữ liệu thật. Không tự ghi đè hệ thống production khi chưa kiểm thử.
